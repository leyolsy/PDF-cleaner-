# PDF Cleaner

A client-side tool to quickly clean PDF files by removing links, annotations, and metadata directly in your browser.

## License

This project is licensed under the **GNU General Public License v3.0 (GPLv3)**.
See the [LICENSE](https://www.gnu.org/licenses/gpl-3.0.en.html) file for details.

## What am I?

PDF Cleaner is a simple, fast, and private way to sanitize your PDF documents. It processes files locally in your web browser, meaning your files are never uploaded to a server. The tool features a modern, visually appealing interface with a starry night theme and glass morphism effects.

## Key Features

* **Remove Annotations:** Strips all annotations, including embedded links and comments, from PDF pages.
* **Clear Metadata:** Resets common metadata fields like title, author, subject, creator, and producer.
* **Remove Form Fields:** Deletes AcroForm (form field) data from the PDF.
* **Client-Side Processing:** All operations happen directly in your browser for privacy and speed.
* **File Input:** Supports drag-and-drop or click-to-browse for PDF file uploads.
* **File Validation:** Checks for PDF file type and enforces a 10MB size limit.
* **User Interface:**
    * Visual feedback during processing, including a progress bar.
    * Clear download option for the cleaned PDF.
    * Easy reset to process new files.
    * Responsive design for various screen sizes.

## How to Use

1.  Access the PDF Cleaner tool.
2.  Drag and drop your PDF file onto the designated area, or click to browse and select your file.
3.  Wait for the processing to complete (a progress bar will indicate progress).
4.  Once cleaned, click the "Download Clean PDF" button to save your modified file.
5.  To process another file, click "Process Another File".

## Technologies Used

* **HTML5**
* **CSS3:** Animations, Flexbox, Grid, Glassmorphism
* **JavaScript (ES6+)**
* **pdf-lib.js:** For client-side PDF manipulation.
