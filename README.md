
# Study Circle Documentation

Welcome to the **Study Circle Documentation** repository! This repository contains all the essential information regarding the **Study Circle** project, including setup guides, usage instructions, and contributions for different user roles (User, Developer, Admin).

## Project Overview

**Study Circle** is a collaborative platform built using the **MERN (MongoDB, Express, React, Node)** stack. It aims to facilitate learning and collaboration between students, mentors, and enthusiasts by providing features like discussion forums, resource sharing, study groups, and live chat.

### Key Features:
- User registration and profile management
- Discussion forums and chat rooms
- Resource sharing (files, documents, links)
- Group formation and management
- Quiz and assignment tracking
- Event scheduling and notifications

---

## Table of Contents

1. [User Documentation](#user-documentation)
2. [Developer Documentation](#developer-documentation)
3. [Admin Documentation](#admin-documentation)
4. [Contributing](#contributing)
5. [License](#license)

---

## User Documentation

### Overview
As a user, you can:
- Register and log in to the platform.
- Join or create study groups.
- Participate in discussions and interact with group members.
- Share and access learning resources.
- Take quizzes and assignments.
- Schedule and attend study events.

### Registration & Login
1. Visit the homepage.
2. Click on **Sign Up** to create a new account or **Log In** if you already have an account.
3. Fill in the required information (username, email, password).
4. After successful login, you will be redirected to the dashboard.

### Joining/Creating Groups
1. Navigate to the **Study Groups** section.
2. Browse available groups and click **Join** to become a member.
3. To create a new group, click on **Create Group**, give it a name, and define its purpose and rules.

### Accessing Resources
- Access shared resources through the **Resources** tab.
- You can upload your own materials or download those shared by others.

### Notifications
- Stay updated with new discussions, events, and quizzes through the **Notifications** panel.

---

## Developer Documentation

### Project Setup

To get started with the Study Circle application locally, follow the instructions below:

#### Prerequisites
- Node.js (version 16 or later)
- MongoDB (local or cloud)

#### Clone the Repository
```bash
git clone https://github.com/your-organization/study-circle.git
cd study-circle
```

#### Backend Setup
1. Navigate to the backend directory.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Configure environment variables:
   - `.env` file: Add your database URL and other API keys (e.g., for JWT, MongoDB).
4. Run the backend server:
   ```bash
   npm start
   ```

#### Frontend Setup
1. Navigate to the frontend directory.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the frontend server:
   ```bash
   npm start
   ```

#### API Documentation
All the API endpoints are documented in the `backend/docs` directory. Key routes include:
- `GET /api/user/dashboard`: Fetch the user's dashboard data.
- `POST /api/groups/create`: Create a new study group.
- `GET /api/groups/:id`: Retrieve details of a specific group.

#### Code Structure
- **Backend (`/backend`)**:
  - `controllers/`: Contains logic for handling requests.
  - `models/`: Database schemas for MongoDB.
  - `routes/`: Defines the API endpoints.
- **Frontend (`/frontend`)**:
  - `components/`: Reusable UI components.
  - `pages/`: Pages of the application.
  - `services/`: API calls and external interactions.

---

## Admin Documentation

### Admin Dashboard
The admin dashboard allows you to manage users, groups, resources, and monitor activities within the platform.

#### Admin Features:
- **User Management**:
  - View all registered users.
  - Promote users to admins or remove them from groups.
  - Ban users or deactivate accounts.
- **Group Management**:
  - Approve or reject group creation requests.
  - Manage group members (add, remove, promote).
- **Event Management**:
  - Schedule and manage study events.
  - Notify users about upcoming events.
- **Content Moderation**:
  - Review flagged content (e.g., inappropriate messages or resources).

### Accessing the Admin Panel
1. Log in as an admin.
2. Navigate to the **Admin Dashboard**.
3. Use the sidebar to access different management sections.

---

## Contributing

We welcome contributions to the Study Circle project! Whether you’re fixing bugs, improving documentation, or adding new features, your help is appreciated.

### How to Contribute:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Open a pull request describing your changes.

Please follow the code style and ensure that all new code is well-tested.

---

