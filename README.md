# Email-app

**Live Demo :** https://email-client-app-by-chandra-mohan.netlify.app/

**Project Overview:**

Name of the Application: Email Client App
Technologies Used: React, Redux, Axios, CSS
Project Duration: [Mention the duration]
Development Process:

**Project Setup:**

Created a new React app using create-react-app.
Installed necessary dependencies including Redux and Axios.
Set up the project structure with folders for components, actions, reducers, and containers.

**UI Design:**

Designed the user interface following the provided mockups and color codes.
Used semantic HTML tags for structure.
Styled the UI elements with CSS to match the design guidelines.

**State Management with Redux:**

Established a Redux store for centralized state management.
Created actions to fetch email data from the provided APIs.
Implemented reducers to update the application state.

**Email List:**

Developed an EmailList component to display a list of emails.
Populated the list using Redux state, displaying sender, subject, description, date, and time.
Generated circular avatars based on sender's first name.

**Master-Slave Layout:**

Enabled a master-slave layout to show the email list and email body.
The master section highlights the selected email.
Fetched the email body data via API when an email is clicked.

**Email Body View:**

Created an EmailBody component to display email subject, body, date, and time.
Added a "Mark as Favorite" button with Redux action dispatch.

**Email Management:**

Implemented functionality to mark emails as favorites.
Styled read and unread emails differently using CSS.
Allowed filtering of emails by "favorites," "read," and "unread."

**Pagination:**

Implemented pagination to handle long email lists.
Fetched emails for different pages using provided paginated APIs.
Persistent Storage (Good to Have):

Used localStorage to persist favorited and read emails across sessions.

**Code Refinement:**

Ensured modular and well-organized code.
Leveraged ES6/7 features and avoided mixing with ES5.
Focused on performance optimization.

**Visual Design:**

Paid attention to visual design and layout to match the provided mockups.

**Testing and Deployment:**

Thoroughly tested the application to ensure it functions without errors.
Deployed the React app to netlify.com
