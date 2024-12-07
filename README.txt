Frontend Assignment: Dynamic Table with Dropdown Selection

Welcome to Columsprout Frontend Take-Home Assignment. In this exercise, you will build a React application that displays data in a table, allowing users to switch between different data sources using a dropdown menu. The focus is on creating a clean and simple user experience.

Key Features you need to work on:
  A dropdown to select between "Posts" and "Comments" data sources.
  A reusable and nested table component that dynamically displays the data.
  Efficient state management for dynamic updates.
  This assignment tests your skills in React, TypeScript, modular components, and state management.

A note from us:
  You can check the submission deadline on your Internshala dashboard. 
  However, we value your time. If the assignment takes more than 10 hours, we recommend you submit whatever you have at that point.
  The functionality is simple, but we’re looking for attention to detail, clean design, and thoughtful execution. While the code doesn’t need to be production   ready, it should reflect quality and care.
  Feel free to go beyond the requirements and include a README outlining any bonus features or ideas for improvement.

2. Getting Started
Clone the repository:

bash
Copy code
git clone <your-repository-link>
cd <repository-folder>
Install dependencies:

bash
Copy code
npm install
Start the development server:

bash
Copy code
npm start
The app should now be running on http://localhost:3000.

Recommended Tools:

Node.js v16+
A modern browser with developer tools (e.g., Chrome or Edge)
3. Design Reference
Refer to the Figma design file for visual and layout guidance.

4. Backend API
The application will fetch data from the following endpoints:

Posts:
https://jsonplaceholder.typicode.com/posts
Columns to display: ID, Title

Comments:
https://jsonplaceholder.typicode.com/comments
Columns to display: ID, Name

API calls should be dynamically triggered based on the dropdown selection.

5. Tasks / Deliverables
Tasks:
Dropdown

Create a dropdown with two options: Posts and Comments.
Fetch data from the selected API endpoint.
Dynamically update the displayed table without page reloads.
Table (Reusable Component)

Create a nested TableComponent to handle table rendering.
Pass fetched data and column configurations as props.
Ensure appropriate columns are displayed:
For "Posts": ID and Title
For "Comments": ID and Name
Dynamic Updates

Use React's useState and useEffect for state and side effects.
Ensure data updates dynamically when the dropdown selection changes.
Pagination

Implement pagination to display 10 rows per page.
Include navigation controls (Previous, Next, Page Numbers) below the table.
Download Button

Add a "Download" button below the table to export the currently displayed data.

6. Submission Guidelines
Repository:

Push your solution to a public GitHub repository.
Documentation:

Include a README.md file explaining:
How to run the project locally.
Any assumptions or design decisions.
Any bonus features implemented.
Submission:

Share the GitHub repository link.
Ensure the app runs without issues and is easy to set up.
7. Evaluation Criteria
Your submission will be evaluated on the following criteria:

Functionality

The app meets the core requirements (dropdown, table, dynamic updates).
Code Quality

Clean, modular, and reusable components.
Best practices in TypeScript and React.
Design & Responsiveness

Follows the provided Figma design.
Responsive updates to the table data.
Performance

Efficient API calls and state management.
Bonus Points

Loading spinner implementation.
