# Enhanced CSV Editor

This repository contains a web-based CSV editor built with HTML, CSS, and JavaScript. It allows you to upload, edit, and export CSV files with a range of useful features.

## Features

- **CSV Upload & Parsing**  
  Upload a CSV file and automatically parse its content for editing.

- **Editable Table**  
  Directly modify cells. The first row is protected as a header.

- **Row and Column Operations**  
  Add or delete rows and columns easily. You can also remove columns by clicking the remove button next to the header.

- **Drag & Drop Reordering**  
  Reorder rows using an enhanced drag-and-drop interface with visual feedback.

- **Sorting**  
  Double-click on a header cell to sort the rows for that column (numeric or alphanumeric).

- **Undo/Redo Functionality**  
  Revert or reapply changes using undo and redo buttons.

- **Search & Filter**  
  Quickly search and filter table rows based on text input.

- **CSV Export**  
  Save your changes by exporting the table back to CSV format.

## Demo

_You can view a live demo of this project [here](https://yapweijun1996.github.io/CSV-Editor/)._  
*(Replace `#` with the actual demo URL.)*



## Usage

1. **Upload a CSV File:**  
   Use the file input to select and upload your CSV file.

2. **Edit the Table:**  
   - Click any cell to edit its content.
   - Use the "Add Row" and "Add Column" buttons to modify the table structure.
   - Delete rows with the "Delete" buttons; note that the header row is protected.

3. **Reorder Rows:**  
   Drag and drop rows to change their order. Visual indicators show where the row will be inserted.

4. **Sort Columns:**  
   Double-click on any header cell (except action cells) to sort the table by that column.  
   The sort order toggles between ascending and descending.

5. **Undo/Redo:**  
   Use the Undo and Redo buttons to manage your edits.

6. **Export CSV:**  
   Click the "Save CSV" button to download the modified CSV file.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
