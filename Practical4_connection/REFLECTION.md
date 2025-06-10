# Reflection on Connecting TikTok Frontend to Backend

## Main Concepts Applied:
- **Frontend-Backend Integration:** Learned how to connect a Next.js frontend with an Express.js backend using RESTful APIs.
- **Authentication:** Implemented JWT-based authentication for secure login/logout and persistent user sessions.
- **State Management:** Utilized Zustand for efficient global state management across the application.
- **Video Upload and Management:** Developed functionality for video uploads and metadata processing on the backend.
- **Dynamic Routing:** Created dynamic user profile pages and implemented routing for video feeds and user exploration.

---

## Things I Learned:
1. **API Communication:** Gained hands-on experience with Axios for making HTTP requests and handling responses efficiently.
2. **Environment Variables:** Learned how to use `.env.local` files to securely store sensitive data like API URLs and keys.
3. **Context API:** Understood how to use React's Context API for managing authentication state across components.
4. **UI/UX Design:** Improved skills in building reusable UI components like modals and forms for better user experience.
5. **Backend Logic:** Learned how to handle video uploads, storage, and metadata processing in the backend.

---

## Challenges and Solutions:
1. **Challenge:** Managing authentication state across multiple components.
   - **Solution:** Used React Context API to create a global `authContext` and wrapped it around the main layout.

2. **Challenge:** Handling video uploads and ensuring proper metadata processing.
   - **Solution:** Implemented a backend service to handle video storage and metadata extraction, ensuring smooth uploads.

3. **Challenge:** Efficient state management for user data and video feeds.
   - **Solution:** Adopted Zustand for lightweight and scalable state management, reducing unnecessary re-renders.

4. **Challenge:** Dynamic routing for user profiles and video feeds.
   - **Solution:** Used Next.js dynamic routing to create pages like `profile/[userId]/page.jsx` and `following/page.jsx`.

---

## Conclusion:
This practical provided valuable insights into building a full-stack application by integrating a Next.js frontend with an Express.js backend. It enhanced my understanding of authentication, state management, and API communication while tackling real-world challenges like video uploads and dynamic routing. The experience has strengthened my skills in both frontend and backend development, preparing me for more complex projects in the future.