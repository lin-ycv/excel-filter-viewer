# Excel Filter Viewer

Native excel filter can only filter by one column, it's a bit complicated to filter by multiple columns.
This viewer allows filter to search multi-column instead of just one.

The viewer assumes the first row with data is the header row
The number input before the file selector is used if there are header cells in each row
Each row only displays the matched cells and and headers
Dropdown list contains all values that aren't headers

![](./demo.gif)

internet connection is required, as it uses [sheetjs](https://github.com/SheetJS/sheetjs)