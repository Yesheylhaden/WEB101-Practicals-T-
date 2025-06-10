#  Practical_5: Infinite Scroll with TanStack Query

## Objective:
Implement an infinite scroll feature using TanStack Query in a React application.

---

## Table of Contents:
- [Objective](#objective)
- [Installation](#installation)
- [Instructions](#instructions)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Conclusion](#conclusion)
- [Acknowledgments](#acknowledgments)

---

## Installation:

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd Practical5_InfiniteScroll
2. **Install Dependencies:**
npm install

## Instructions:

1. **Setup TanStack Query:**
- npm install @tanstack/react-query
- Create QueryClient instance and wrap your app with QueryClientProvider.

2. **API Integration:**
- Create an API service to fetch paginated data.
- Use TanStack Query's useInfiniteQuery hook to manage data fetching.

3. **Infinite Scroll Implementation:**
- Add a scroll listener to detect when the user reaches the bottom of the page.
- Trigger the next page fetch using fetchNextPage from useInfiniteQuery.

4. **UI Components:**
- Build components to display the fetched data.
- Show a loading spinner while fetching new pages.

5. **Error Handling:**
- Handle API errors gracefully and display appropriate messages.

## Features:

1. **Infinite Scroll:**
- Automatically fetch and display more data as the user scrolls down.

2. **Optimized Data Fetching:**
- Efficiently manage paginated data using TanStack Query.

3. **Error Handling:**
- Display error messages for failed API requests.

4. **Loading Indicators:**
- Show loading spinners during data fetching.

## Technologies Used:
- **React:* Frontend framework
- **TanStack Query:** Data fetching and caching
- **Axios:** HTTP client for API requests

## Conclusion:
- This project demonstrates how to implement an infinite scroll feature using TanStack Query. It provides hands-on experience in managing paginated data efficiently and creating a seamless user experience.

## Acknowledgments:
- Special thanks to the developers of TanStack Query for their excellent documentation and tools. 