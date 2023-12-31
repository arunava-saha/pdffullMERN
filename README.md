# pdffullMERN - git repo name

code link:https://github.com/arunava-saha/pdffullMERN

# PDF Viewer

#### Description:

The PDF Viewer is a web-based application designed to manage and manipulate PDF documents. It provides various features for creating, editing, storing PDF files. The primary functionalities of the system include:

PDF Editing: The system allows users to modify existing PDFs, including adding or updating content, as well as annotating PDFs with comments and highlights.

PDF Storage: PDFs can be stored securely on the server. Users can upload, download, and organize their PDFs into folders for easy access.

API Integration: The system provides an API for external applications to interact with PDFs programmatically, enabling automation and integration with other systems.

#### Technology Stack:

1. Frontend: HTML, CSS, JavaScript, React.
2. Backend: Node.js, Express.js.
3. Database: MongoDB.
4. PDF Manipulation: pdf-lib, react-pdf.
5. Storage (for PDF storage): fs, multer.
6. API Development: RESTful API
7. Version Control: Git
8. Cors

#### Project Goals:- [Task given]

Provide a user-friendly interface for uploading and editing PDF documents. A web application that allows users to upload a PDF file and extract certain pages from the PDF to create a new PDF. The user should be able to select which pages they want to include in the new PDF.

#### Frontend (Any React framework):

- Implement a simple form to upload a PDF file. The form should include validation to ensure that only PDF files are uploaded.
- Once the file is uploaded, display a visual representation of all pages in the PDF.
- Allow users to select which pages they want to extract from the original PDF. This can be achieved through checkboxes or a similar UI element associated with each page.
- Include a button or functionality to create the new PDF based on the selected pages. Once completed, offer a download link to the user for the newly created PDF.
- All pages should be responsive and should work from mobile devices.

#### Backend (Any Node.js framework):

- Create a REST API to handle the upload of the PDF file and store it on the server.
- Create a REST API to retrieve the stored PDF file for display.
- Implement a REST API to extract the selected pages from the original PDF and create a new PDF. You can use any PDF library to achieve this in the Node.js framework you use.
- Ensure all APIs work correctly and handle potential errors.

## For more details see client [readme](https://github.com/arunava-saha/pdffullMERN/blob/main/client/README.md)
