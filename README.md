# Phase 3 Physical Inventory

This is a separate, phone-friendly field-inventory app. It does not alter the existing Beach Asset Management application.

## Use

1. Open `index.html` in a browser (host it on a normal HTTPS site for camera scanning on a phone).
2. Import a department's original Phase 3 inventory workbook.
3. Scan a property-tag barcode or enter a tag number, Asset ID, or serial number.
4. Select **Mark Verified OK**, or edit the tag, serial, and field note.
5. Use **Export red-text workbook** when back at your desk.

The exported workbook retains the imported workbook's sheet structure. PMO COMMENTS receives `OK` when an item is verified. PMO comments, tag changes, and serial-number changes made in the app are emitted in red text.

## Validation

The app's import map was checked against the 46 supplied `Physical Inventory Listing` Phase 3 workbooks (2,236 inventory rows). They use one consistent header layout on row 5: `Asset ID`, `Tag #`, `Serial ID`, and `PMO COMMENTS` are all recognized.

## Important

The app keeps the original workbook and field changes in the browser on that device. Use the original file as the import source each time you set up another device, and export before clearing browser data. Camera access requires HTTPS when used on a phone.
