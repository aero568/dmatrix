# Aerodynamics Simulation Register

This project is a web application for registering and managing aerodynamics simulation runs. It provides a user-friendly interface to add, edit, and delete simulation records, with the data being stored in a SQL database.

## Table of Contents

1. [Features](#features)
2. [Technologies Used](#technologies-used)
3. [Installation](#installation)
4. [Usage](#usage)
5. [API Endpoints](#api-endpoints)
6. [Contributing](#contributing)
7. [License](#license)
8. [Contact](#contact)

## Features

- Add new simulation runs with specific parameters.
- Edit existing simulation records.
- Delete simulations from the database.
- View a table of all simulation records.
- Responsive design for desktop and mobile devices.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **Database**: SQLite

## Installation

Follow these steps to set up the project locally:

1. **Clone the repository**:

    ```bash
    git clone https://github.com/yourusername/aero-simulation-register.git
    cd aero-simulation-register
    ```

2. **Install dependencies**:

    Make sure you have [Node.js](https://nodejs.org/) installed. Then run:

    ```bash
    npm install
    ```

3. **Run the application**:

    ```bash
    node server/server.js
    ```

4. **Access the application**:

    Open your web browser and go to `http://localhost:3000`.

## Usage

- Navigate to the application in your web browser.
- Use the "Add New Run" button to add a new simulation.
- Use the "Edit" and "Delete" buttons to manage existing simulations.

## API Endpoints

### Get All Simulations

- **Endpoint**: `/api/simulations`
- **Method**: GET
- **Description**: Retrieves a list of all simulation runs.

### Add a New Simulation

- **Endpoint**: `/api/simulations`
- **Method**: POST
- **Description**: Adds a new simulation run.
- **Body Parameters**:
  - `name` (string): Name of the simulation.
  - `param1` (string): First parameter.
  - `param2` (string): Second parameter.

### Update a Simulation

- **Endpoint**: `/api/simulations/:id`
- **Method**: PUT
- **Description**: Updates an existing simulation run.
- **Body Parameters**:
  - `name` (string): Name of the simulation.
  - `param1` (string): First parameter.
  - `param2` (string): Second parameter.

### Delete a Simulation

- **Endpoint**: `/api/simulations/:id`
- **Method**: DELETE
- **Description**: Deletes a simulation run.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/YourFeature`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/YourFeature`.
5. Open a pull request.

Please make sure your code adheres to the project's coding standards and includes tests if applicable.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file

