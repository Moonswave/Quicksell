# Interactive Kanban Board with React

This is an interactive Kanban board application built using **React JS**. The app allows users to dynamically group and sort tasks (tickets) using data fetched from a remote API. Users can group tasks by status, user, or priority, and also sort them by priority or title. The app ensures persistence of the selected view state even after a page reload.

## Features

- **Group By Options:**
  - Group tickets by their status.
  - Group tickets by the assigned user.
  - Group tickets by priority (Urgent, High, Medium, Low, No Priority).
  
- **Sort By Options:**
  - Sort tickets in descending order of priority.
  - Sort tickets in ascending order of their title.

- **Responsive Design:**
  - The application adjusts the layout to display properly on different screen sizes.
  
- **Persistent State:**
  - User's selected view state (grouping) is saved and remains even after a page reload using `localStorage`.

- **API Integration:**
  - Fetches task (ticket) data from the provided API endpoint.


### Grouping by User
![Grouping by User](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/de6f9ade-433a-4185-a6df-4d396ea8be2d/Untitled.png)

### Grouping by Priority
![Grouping by Priority](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2f8e52ba-2b96-40e8-be6a-34e25dd240eb/Untitled.png)

