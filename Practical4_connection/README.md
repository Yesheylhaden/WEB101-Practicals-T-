# Practical_4: Connecting TikTok Frontend to Backend

## Objective
to Integrate Next.js frontend with an Express.js backend.

---

## Table of Contents:

- [Objective](#objective)
- [Installation](#installation)
- [Instructions](#instructions)
- [Features](#features)
- [Technologies Used](#technologies)
- [Conclusion](#conclusion)
- [Acknowledgments](#acknowledgments)

---

## Installation:

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd Practical4_connection
2. **Install Dependencies**
npm install 

## Instructions:
### Part 1: API & Auth Setup

1. Install required packages:
npm install axios jwt-decode react-hot-toast
2. Create src/lib/api-config.js with an Axios instance.
3. Add .env.local:
4. Create authContext.jsx and wrap it in layout.js.
5. Build UI components:
- Modal.jsx
- AuthForms.jsx
- AuthModal.jsx
6. Add login/logout functionality in MainLayout.jsx.

### Part 2: Video features

1. **Create:**
- videoService.js for API calls.
- userService.js for user-related operations.
2. **Update:**
- VideoCard.jsx and VideoFeed.jsx to fetch real data.
3. **Add pages:**
- following/page.jsx
- explore-users/page.jsx
- profile/[userId]/page.jsx
4. Update upload/page.jsx to allow video uploads.

## Features:

1. **Authentication System:**
- Secure login and logout functionality using JWT.
- Persistent user sessions with token-based authentication.

2. **Video Upload and Management:**
- Users can upload videos directly from the frontend.
- Backend handles video storage and metadata processing.

3. **User Profiles:**
- Dynamic user profile pages displaying uploaded videos and user details.
- Follow/unfollow functionality for user connections.

4. **Video Feed:**
- Real-time video feed displaying content from followed users.
- Explore page for discovering new users and trending videos.

5. **Global State Management:**
- Zustand for managing application-wide state efficiently.
- Lightweight and scalable solution for handling user data and video feed.

6. **Notifications:**
- React Hot Toast for displaying success, error, and info messages.
- Instant feedback for user actions like uploads and authentication.

7. **API Integration:**
- Axios for seamless communication between frontend and backend.
- Modular API services for handling user and video-related requests.

8. **Efficient Rendering:**
- Optimized rendering to ensure smooth user experience.
- Components re-render only when necessary, improving performance.

## Technologies Used:

- **Next.js:** Frontend framework
- **Express.js:** Backend framework
- **Axios:** HTTP client
- **JWT:** Authentication
- **React Hot Toast:** Notifications

## Conclusion:

- This project demonstrates how to connect a Next.js frontend to an Express.js backend, implement authentication, and manage video-related features. It provides hands-on experience in building full-stack applications.

## Acknowledgments:

- I would like to thank my instructor for their guidance and support throughout this practical. Special thanks to the developers of Axios, JWT, and React Hot Toast for their excellent tools and documentation.
