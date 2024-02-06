# Group Study Planner

Group Study Planner is a collaborative study planning tool designed to help groups of students coordinate their study sessions effectively.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
  - [Technical Stack](#technical-stack)
  - [Cloning the Repository](#cloning-the-repository)
  - [Setting Up the Client](#setting-up-the-client)
  - [Setting Up the Server](#setting-up-the-server)
- [Project Structure](#project-structure)
- [Happy Coding](#happy-coding)

## Introduction

Group Study Planner consists of both a client and a server component. This repository serves as the parent repository containing submodules for each component.

- **Client**: The client component provides the user interface and interaction for the study planning tool.
- **Server**: The server component handles the backend logic and data storage.

For detailed information about each component, please refer to the respective submodule documentation:

- [Client Documentation](./Client/README.md)
- [Server Documentation](./Server/README.md)

## Getting Started

Follow these steps to set up and run the Group Study Planner on your local machine.

### Cloning the Repository

1. **Parent Repository:**

   - "GroupStudyPlanner-Hackathon" serves as the main Git repository, orchestrating collaboration for a study planning tool.

2. **Client Submodule (with origin):**

   - The "Client" submodule, linked with `https://github.com/maheshoz/study-planner`, enhances the main repository's functionality by managing the user interface and interaction features.

3. **Server Submodule (with origin):**
   - The "Server" submodule, with its origin set to `https://github.com/breathecode6365/Group-Study-Planner-Hackathon.git`, empowers the parent repository by governing backend logic and data storage.

```bash
git clone --recursive https://github.com/breathecode6365/Group-Study-Planner-Hackathon.git
```

## Technology Stack

| Area       | Technologies                              |
| ---------- | ----------------------------------------- |
| Frontend   | Redux, React.js, Tailwind CSS             |
| Backend    | Spring Boot with Maven, Java              |
| Database   | PostgreSQL                                |
| Deployment | Docker (for working with local databases) |

### Setting Up Group Study Planner

Follow the steps below to set up the Group Study Planner client and backend components. Detailed documentation for each component can be found in their respective directories.

#### Setting Up the Client

1. Navigate to the `Client` directory:

   ```bash
   cd Client
   ```

2. Follow the instructions in the [Client Documentation](./Client/README.md) to set up and run the client. Ensure that you meet all the requirements mentioned in the documentation.

#### Setting Up the Backend

1. Navigate to the `Server` directory:

   ```bash
   cd Server
   ```

2. Review the [Server Documentation](./Server/README.md) for detailed instructions on setting up and running the backend. Make sure to fulfill any prerequisites specified in the documentation.

#### Additional Notes

- For the complete project setup, ensure that both the client and backend components are configured according to their respective documentation.

### Project Structure

The Group Study Planner project follows a modular structure to separate concerns and facilitate ease of development. Below is an outline of the main directories and their purposes:

#### GroupStudyPlanner

```bash
|-- Client/
| |-- public/
| |-- src/
| | |-- components/
| | |-- containers/
| | |-- styles/
| | |-- App.js
| | |-- index.js
| |-- README.md
|-- Server/
| |-- src/
| | |-- controllers/
| | |-- DTO/
| | |     |-- Request/
| | |     |-- Response/
| | |-- DAO/
| | |     |-- Repository/
| | |-- services/
| | |-- utility
| | |-- GroupStudyPlannerApplication.java
| | |-- application.properties
| | |-- README.md
|-- README.md
|-- CONTRIBUTING.md
|-- LICENSE
|-- .gitignore
```

- **Client:** Contains the client-side code for the Group Study Planner.

  - **public:** Static assets and HTML templates.
  - **src:** Source code for React components, containers, and styles.
  - **README.md:** Client-specific documentation.

- **Server:** Contains the server-side code for the Group Study Planner.
  - **src:** Source code for controllers, models, routes, and services.
  - **README.md:** Server-specific documentation.

### Happy Coding!

For any queries or help, please contact maitainer.

**Frontend-Developer** : [Mahesh](https://github.com/maheshoz)

**Backend-Developer** : [Punith](https://github.com/breathecode6365)
