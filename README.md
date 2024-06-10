# DJS08 Project Brief: React Router 

**React Router**
🎥 Loom Presentation Link: [https://www.loom.com/share/62db750a3e0b4ddd81e568a530a35296?sid=c70c578d-4ed3-4136-90ed-b1ea3961eea0]

This project is a React application that demonstrates the use of React Router for implementing client-side routing and navigation. It was developed as part of a learning exercise to understand and apply the concepts of React Router.

## Getting Started

After cloning the repository, run the following command to install the required dependencies:

```
npm install
```

## Project Overview

For this project, I coded along with the lecturer from the "VanLife Project Bootstrapping" lesson on Scrimba. The lesson covered the basics of React Router, including setting up routes, defining nested routes, using route parameters, and implementing navigation controls.

The starter code provided all the necessary CSS styling, and the focus was on understanding routing and presenting the code through a recorded presentation.

## Presentation Talking Points

### Question 1: Explain the Setup and Basic Configuration of React Router

- **Purpose of React Router**: React Router is a library that enables client-side routing in React applications. It allows developers to create a single-page application (SPA) with multiple views and manage the application's state and URL history.

- **Setting up React Router with BrowserRouter**: React Router is set up by importing and rendering the `BrowserRouter` component from the `react-router-dom` library. This component provides the necessary context for the Router functionality and manages the browser's URL history.

- **Routes and Route Components**: The `<Routes>` component is used to define the navigation structure of the application. Inside `<Routes>`, multiple `<Route>` components are defined, each representing a specific URL path. Each `<Route>` component renders a particular component based on the current URL path.

### Question 2: Application of Route Parameters and Nested Routes

- **Route Parameters**: Route parameters are dynamic segments in the URL path that can be accessed and used within components. React Router provides the `useParams` hook to retrieve these parameters from the URL. Route parameters are useful for displaying or fetching data based on the URL path.

- **Nested Routes**: Nested routes allow for a hierarchical structure of routes within an application. This is achieved by rendering child routes inside a parent route. Nested routes help organize and group related views or components together, making the application structure more maintainable and scalable.

- **Example of Nested Routes**: In the VanLife project, nested routes were used to organize the different pages and components related to van rentals. For instance, the `/vans/:id` route could have nested routes like `/vans/:id/details` and `/vans/:id/pricing` to display specific information about a particular van.

### Question 3: Implementation of Navigation Controls and Dynamic Linking

- **Link Component**: The `<Link>` component from React Router is used for navigating between different routes within the application. It renders an accessible `<a>` element and updates the URL history when clicked, providing a seamless client-side navigation experience.

- **NavLink and Active Styling**: The `<NavLink>` component is a special type of `<Link>` that can apply active styles to the rendered element based on the current URL. This is useful for highlighting the active navigation link in a menu or navigation bar.

- **Search Parameters and useSearchParams Hook**: React Router provides the `useSearchParams` hook to access and manipulate the query string parameters in the URL. This hook returns an array with the current search parameters and a function to update them. In the VanLife project, search parameters were used to dynamically filter and display van rentals based on user input.

Throughout the presentation, I provided code snippets and real-world examples from the VanLife project to illustrate the concepts and implementations discussed.