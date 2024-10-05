# Affinity Frontend

Welcome to the Affinity Frontend repository! This project is part of the broader Affinity platform, focusing exclusively on frontend development. 
<h3><b>Goal:</b></h3><br>
Affinity aims to help people find and engage with others of similar intellectual levels through various interactive features.
<h3><b>Key Features:</b></h3><br>
<ul>
<li><b>AI powered chatbot:</b> Helps in user matchmaking </li>
<li><b>Interactive Games:</b> Includes various interactive games, such as coding rounds, to match users based on their skillset. </li>
<li><b>Real time conversations:</b>Once matched, users can engage in meaningful conversations with one another, fostering intellectual connections.</li>
</ul>

<h3>Want to contribute to the backend?</h3><br>
If you're interested in working on the backend of our project, feel free to explore the [Affinity Backend](https://github.com/Sidharth-Singh10/Affinity-backend) repository for more details.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation) 
- [Usage](#usage)
- [Contributing](#contributing)
- [Contact](#contact)

## Introduction

The Affinity Frontend is a React-based application designed to deliver a smooth and seamless user experience. This repository houses all the code related to the frontend portion of the Affinity project, and all contributions should be focused on this area. The frontend interacts with the backend through API calls to provide matchmaking services, games, and chat functionality for users.

## Features

- User-friendly interface
- Responsive design
- Integration with backend APIs
- Routing with React Router

## Technologies Used

- React
- React Router
- Axios
- CSS Modules

## Installation

To get started with the project, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/rishyym0927/Affinity_frontend.git
    cd Affinity_frontend
    ```

2. Install dependencies:

    ```bash
    npm install
    ```
3. Even after running npm install, it may give an error while running that "dotenv is not defined".
Simply run :

   ```bash
   npm install dotenv
   ```
   Now you can re-run the server and this time it will run without any error.
   
   >*Please note that you don’t need environment variables to run the project since no environment variables are currently being used in the codebase. The project contains only the frontend code and all the data has been hardcoaded. However, the requirement to install `dotenv` exists due to the boilerplate code present in the `vite.config.js`, which includes the `dotenv` configuration. Aside from this boilerplate setup, there is no practical need for `dotenv` in the project at the moment.*


## Usage

To run the application locally, use the following command:

```bash
npm start
```

This will start the development server and you can view the application in your browser at `http://localhost:5173`.



- **public/**: Contains the static files.
- **src/**: Contains the source code for the application.
  - **assets/**: Contains images, fonts, and other static assets.
  - **components/**: Contains reusable React components.
  - **pages/**: Contains React components for different pages.
  - **App.js**: The main App component.
  - **index.js**: The entry point of the application.


> **Note**: Users are informed that they have the complete right to manipulate the sample data present in *sampleData.js*, as it is hardcoded. Any changes made will affect only your own codebase and will not impact others.

### Routing

**Affinity** is still under development so the platform currently lacks connectivity between its various pages. This means there are no buttons or links to navigate between pages. But you can access them by using a */* followed by *page-route*.

<table align="center">
  <tr>
    <th> Page Name </th>
    <th>Route</th>
  </tr>
  <tr>
    <td>Landing</td>
    <td>/</td>
  </tr>
  <tr>
    <td>Login</td>
    <td>/login</td>
  </tr>
  <tr>
    <td>Register</td>
    <td>/register</td>
  </tr>
  <tr>
    <td>Room Page</td>
    <td>/room/:roomId</td>
  </tr>
  <tr>
    <td>Code Run</td>
    <td>/coderun</td>
  </tr>
  <tr>
    <td>Dashboard</td>
    <td>/dashboard</td>
  </tr>
  <tr>
    <td>Matches</td>
    <td>/matches</td>
  </tr>
  <tr>
    <td>Requests</td>
    <td>/request</td>
  </tr>
  <tr>
    <td>Queue</td>
    <td>/queue</td>
  </tr>
  <tr>
    <td>Chatbot</td>
    <td>/chatbot</td>
  </tr>
  <tr>
    <td>Denied</td>
    <td>/denied</td>
  </tr>
</table>


## Contributing

We welcome contributions from the community! Please read our [`CONTRIBUTING.md`](https://github.com/rishyym0927/Affinity_frontend/blob/main/CONTRIBUTING.md) file for detailed guidelines on how to contribute to this project.

### Hacktoberfest and GSSoC 24

This repository is actively participating in Hacktoberfest and GSSoC 24. We welcome contributions, but please note that only frontend-related tasks are open for contribution. Any modifications or changes to the backend will not be considered. Feel free to raise issues and start working on assigned tasks.


## Contact

If you have any questions or need further assistance, feel free to open an issue or contact the maintainers.

Thank you for your contributions!


