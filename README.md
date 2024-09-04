# Fetch Data Lab

## Project Overview

In this lab, I created a React component named `FetchData` that renders data fetched from an API onto the user interface. This component uses the `UseFetch` custom hook to retrieve data from a specified URL.

The `UseFetch` custom hook encapsulates the data-fetching logic, utilizing React’s `useState` and `useEffect` hooks to manage the asynchronous data retrieval process and store the data in the component’s state.

## Completed Parts

- Implemented the `UseFetch` custom hook for fetching data from a specified URL.
- Created the `FetchData` component to display the fetched data using JSX.
- Styled the component with `FetchData.css` to enhance the presentation of the data.

## Challenges and Solutions

- **Challenge:** Handling asynchronous data fetching and managing the component state.
  **Solution:** Used the `useEffect` hook in `UseFetch` to fetch data and update the state, ensuring the component re-renders with the fetched data.

- **Challenge:** Rendering data dynamically in the `FetchData` component.
  **Solution:** Utilized the `map` method to iterate through the data array and display each item’s attributes in the UI.

## Remaining Tasks

- None at the moment. The component is complete and working as intended.
