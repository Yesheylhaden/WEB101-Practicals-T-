# Reflection on RESTful API Weather Application Practical.

## Main Concepts Applied:

- **RESTful API Methods:** Implemented GET, POST, PUT, and DELETE HTTP requests to interact with external APIs.
- **Asynchronous JavaScript:** Used the Fetch API to handle asynchronous communication with APIs.
- **DOM Manipulation:** Dynamically updated the web page content based on API responses.
- **User Interface Design:** Created a tabbed interface to organize different API operations for better usability.
- **API Integration:** Combined data from OpenWeatherMap and JSONPlaceholder APIs to demonstrate real-world use cases.

---

## Things I Learned:

- How to structure a project that interacts with multiple APIs simultaneously.
- The importance of managing asynchronous requests and handling responses correctly.
- Practical use of HTTP methods beyond just GET, including creating, updating, and deleting resources.
- How to build an interactive and user-friendly interface that responds to user actions in real-time.
- Basics of error handling and user feedback in API-driven applications.

---

## Challenges and Solutions:

- **Challenge:** Handling asynchronous API requests and updating the UI without causing delays or inconsistent states.  
  **Solution:** I used `async/await` syntax to write cleaner asynchronous code and ensured the UI updates only after successful responses.

- **Challenge:** Managing the PUT and DELETE requests with a fake API (JSONPlaceholder) that doesn’t actually persist changes.  
  **Solution:** Implemented optimistic UI updates to reflect changes immediately, improving user experience despite backend limitations.

- **Challenge:** Coordinating multiple forms and event listeners in a single-page application without conflicts.  
  **Solution:** Organized the code with clear functions and event handlers tied to specific UI elements to maintain code clarity and functionality.

---

## Conclusion:

This practical project provided hands-on experience in working with RESTful APIs and deepened my understanding of client-server interactions. It reinforced key web development skills such as asynchronous programming, API consumption, and dynamic UI updates. Overall, the project was an invaluable exercise in building functional and interactive web applications that communicate effectively with external services.

