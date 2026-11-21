# Magazine Editor

A simple browser editor for creating magazines, by TEAM a.r.g. Current version: **v0.3.0**.
Open `docs/index.html` in a browser. It works offline after the first load.

## Features
- Magazine settings: name, issue, date, page size (A4, US Letter, A5, A3, Tabloid, Digest, Square), grid size in mm, show grid.
- Pages: Blank, Cover, Backside, Article, Index; duplicate, delete, move, label, page number, background colour, cover image with crop.
- Blocks: Text, Title, Image, Table, Shape, Index, Rotated text. Drag, resize, snap to grid, layers list, inspector.
- Text editor: bold, italic, underline, strike, lists, alignment, system fonts (not embedded).
- Save JSON / Open (`.mag.json`), autosave in the browser.
- Export: PDF and EPUB (whole magazine), **PNG of the selected page**.
- `? Help` button in the header opens the built-in manual.

## Export PNG
Select a page, press **Export PNG**, pick a paper size (A6, A5, A4, A3, US Letter, same as magazine page, or custom pixel width) and a resolution (72, 150, 300, 600 dpi). A4 at 300 dpi gives 2480 x 3508 px. The height follows the shape of the magazine page. Grid and bleed line are not included. Handy for a website gallery.

## Changelog
- v0.3.0: Export PNG (current page, choose size and dpi), in-app Help, expanded README.
- v0.2.21: previous version.
