 # NIT Hamirpur College Event Management

## Overview

The **NIT Hamirpur College Event Management** project is a MERN stack-based platform designed to streamline the organization, management, and promotion of events at NIT Hamirpur. This system provides an efficient way for students, faculty, and organizers to manage events, registrations, schedules, and communication.

---

## Features

- **Event Creation & Management**: Create, update, and delete events.
- **User Registration & Authentication**: Secure user registration and login using JWT.
- **Event Registration**: Students and faculty can register for events.
- **Event Scheduling**: View and manage event schedules.
- **Notifications**: Send reminders and updates to participants.
- **Admin Dashboard**: Manage users, events, and permissions.
- **Responsive Design**: Access the platform on any device.

---

## Technologies Used

- **Frontend**: React.js, HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Deployment**: Netlify

---

## Getting Started

Follow these steps to set up the project locally:

### Prerequisites

- Node.js (v16 or higher)
- npm (Node Package Manager)
- MongoDB (local or cloud-based)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/JAYVIJAYCHAUHAN/NIT-Event.git
   cd NIT-Event
  
  # NIT-Event

## Install Dependencies for Both Frontend and Backend

```bash
cd Backend
npm install
cd ../Frontend
npm install
```

## Set Up Environment Variables

### Backend `.env` File
Create a `.env` file in the `backend` directory and add the following:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
```

### Frontend `.env` File
Create a `.env` file in the `frontend` directory and add the following (if needed):

```env
REACT_APP_API_URL=http://localhost:5000
```

## Run the Backend Server

```bash
cd Backend
node index.js
```

## Run the Frontend Development Server

```bash
cd Frontend
npm start
```

## Access the Application
Open your browser and go to: [http://localhost:3000](http://localhost:3000)

## Available Scripts

In the project directory, you can run:

### `npm start`
Runs the app in development mode. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

### `npm test`
Launches the test runner in interactive watch mode.

### `npm run build`
Builds the app for production to the `build` folder. It correctly bundles React in production mode and optimizes the build for the best performance.

### `npm run eject`
**Note:** This is a one-way operation. If you aren’t satisfied with the build tool and configuration choices, you can eject at any time. This command will remove the single build dependency from your project.

## GitHub Repository
The source code for this project is available on GitHub:
**[JAYVIJAYCHAUHAN/NIT-Event](https://github.com/JAYVIJAYCHAUHAN/NIT-Event)**

## Contributing
We welcome contributions! If you'd like to contribute, please follow these steps:

1. **Fork** the repository.
2. **Create a new branch** (`git checkout -b feature/YourFeatureName`).
3. **Commit your changes** (`git commit -m 'Add some feature'`).
4. **Push to the branch** (`git push origin feature/YourFeatureName`).
5. **Open a pull request**.

## License
This project is licensed under the **MIT License**. See the `LICENSE` file for details.

## Contact
For any questions or suggestions, feel free to reach out:

 
