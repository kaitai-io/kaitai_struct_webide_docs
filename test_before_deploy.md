- Editor
  - ksy saved after modification
- File system operations
  - files are visible (file list is not empty)
  - default kaitai.io samples and formats are there
  - new file, upload, download works
  - drag and drop works
  - right click context menu works
  - generating parser works
  - creating folder works
- Sample parsing works (zip)
- Converter panel works (every value is filled)
- Error panel works (open .ksy w/ other binary file) / it's closable
  - ksy parsing errors
  - file parsing errors
- Import works
  - relative import to a subfolder works
- About webide works / remember closing it for ever
- Hex viewer operations
  - mouse range selection works
  - deselect works
  - Two-way sync works between object tree and hex view
- Info panel works
  - selection shown, can modify
  - disable lazy parsing works
  - unparsed & byte array steppers work
  - selected path shown
  - export to JSON works
- Works in incognito mode (w/ empty storage)
- Proper warning without JS
- Works in supported browsers
  - Proper warning for unsupported browser
- Object tree
  - Can handle big files
    - Instances loaded lazily
    - Big arrays are split into smaller chunks (max 100 items in a level)
  - Two-way sync works between object tree and hex view
  - Open nodes are reopened after modifying source .ksy / reloading IDE
