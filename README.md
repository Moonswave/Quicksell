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
![QS1](https://github.com/user-attachments/assets/d2d96d94-d06c-4c94-b506-8c8bf658c8ca)
### Grouping by Priority
![priority](https://github.com/user-attachments/assets/d724fb8f-dd29-406a-9413-e13678e8e7b1)
### Grouping by Status
![status](https://github.com/user-attachments/assets/b6755e5a-58fb-4f44-a4ac-6c8f95da70b0)

