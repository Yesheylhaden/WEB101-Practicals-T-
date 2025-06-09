# Practical_3: File Upload Application

## Overview:

- This is a simple React (Next.js) application that demonstrates how to implement a file upload form with the following key features: drag-and-drop interface, file type/size validation, upload progress tracking, and multipart form data handling.

---

## Table of Contents:

- [Installation](#installation)
- [Usages](#usages)
- [Features](#features)
- [Technologies](#technologies)
- [Conclusion](#conclusion)
- [Acknowledgments](#acknowledgments)

---

## Installation:

1. Clone or Download the Repository
- git clone https://github.com/Yesheylhaden/WEB101_Practicals_02240371.git

2. Install Dependencies
- npm install

3. Run the Application
- npm run dev

4. Access the App
- Open your browser and go to: http://localhost:3000

## Usages:

- **Drag & Drop:** Upload files easily by dragging them into the drop zone.
- **Validation:** Accept only specific file types (e.g., images) and limit file sizes.
- **Progress Tracking:** Monitor the real-time upload progress with a progress bar.
- **API Integration:** Files are uploaded using a custom Next.js API route (/api/upload) with multipart/form-data.
- **Form Handling:** Uses react-hook-form for managing file input and validations efficiently.

## Features:

- Drag-and-drop file upload area
- Client-side file validation (type and size)
- Upload progress indicator
- Backend API route using formidable for handling uploads
- Clean and responsive user interface
- No database setup required

## Technologies:

- **Next.js:** React framework for building the app and backend API route
- **React Hook Form:** For easy form handling and validation
- **React Dropzone:** For drag-and-drop file upload UX
- **Axios:** To send file data with progress tracking
- **Formidable:** – For parsing multipart/form-data in API route
- **JavaScript (ES6+):**  Core logic and form interaction
- **CSS/Modules:** Styling components

## Conclusion:

This practical demonstrates how to implement an end-to-end file upload system in a React/Next.js application. Through this task, I learned how to manage form input, perform client-side validations, and track file upload progress using modern JavaScript libraries and frameworks. It provided a solid foundation in handling real-world file uploads, including both frontend UI/UX and backend handling with form data.

## Acknowledgments:

I would like to thank my instructor for the clear guidance and structured objectives provided for this practical. Special thanks to the developers of React Hook Form, React Dropzone, Axios, and Formidable for creating tools that made this implementation much more manageable and insightful. Their documentation and open-source contributions were extremely helpful.

