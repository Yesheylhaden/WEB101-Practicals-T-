## Reflection on File Upload Implementation

## Main Concepts Applied:

- **File Upload Mechanism in React/Next.js:** Implemented file uploads using a combination of client-side React and server-side Next.js API routes.
- **Multipart Form Data Handling:** Used `formidable` to parse and handle file data in the backend.
- **Form Handling with Validation:** Applied `react-hook-form` for efficient form input management and validations.
- **Drag and Drop Interface:** Integrated `react-dropzone` to enhance UX with a modern drag-and-drop file selection area.
- **Upload Progress Tracking:** Leveraged `axios` to track and display real-time file upload progress.

---

## Things I Learned:

- How to structure file upload workflows using React and Next.js.
- How to validate files on the client side by checking file type and size before uploading.
- How to configure and use `formidable` in a Next.js API route to receive and handle file uploads.
- How to track file upload progress using Axios and show it in the UI.
- How to enhance form usability using `react-hook-form` and `react-dropzone`.

---

## Challenges and Solutions:

- **Challenge:** Struggled with configuring the Next.js API route to handle multipart form data.  
  **Solution:** Researched how `formidable` works and ensured the API route was set to disable the default body parser.

- **Challenge:** Drag-and-drop wasn’t working correctly with validation at first.  
  **Solution:** Integrated `react-dropzone` properly with `react-hook-form` using custom handlers.

- **Challenge:** Upload progress wasn’t displaying due to incorrect Axios config.  
  **Solution:** Implemented `onUploadProgress` correctly and added a state handler to reflect progress on the UI.

---

## Conclusion:

- This practical helped me gain a deeper understanding of how to build a robust file upload system in a full-stack React/Next.js application. I learned how to handle both frontend and backend aspects of file uploads, from user interaction to backend data parsing. Overcoming real-world challenges like file validation and upload tracking has boosted my confidence in working with form-based data and server-side processing.
