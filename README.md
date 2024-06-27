# MERN Estate

## Introduction

MERN Estate is a web application built with the MERN stack (MongoDB, Express.js, React.js, Node.js) to manage and list real estate properties. This application allows users to view, add, edit, and delete property listings.

## Features

- User Authentication
- Property Listings
- Add New Property
- Edit Existing Property
- Delete Property
- Search and Filter Properties
- Responsive Design

## Technologies Used

- **Frontend**: React.js, HTML, CSS, Bootstrap/Tailwind
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Other Tools**: Git, GitHub, Postman

## Installation

### Prerequisites

- Node.js
- npm or yarn
- MongoDB

### Steps

1. **Clone the repository:**

    ```bash
    git clone https://github.com/payal1001/Estate-repo.git
    cd mern-estate-main
    ```

2. **Install dependencies for both client and server:**

    ```bash
    cd client
    npm install
    cd ../server
    npm install
    ```

3. **Set up environment variables:**

    Create a `.env` file in the `server` directory and add the following:

    ```env
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_secret_key
    ```

4. **Run the application:**

    Open two terminal windows/tabs.

    In the first terminal, start the backend server:

    ```bash
    cd server
    npm start
    ```

    In the second terminal, start the frontend client:

    ```bash
    cd client
    npm start
    ```

5. **Access the application:**

    Open your browser and go to `http://localhost:3000`.

## Usage

- Register or log in to your account.
- Browse the list of available properties.
- Add new properties if you are an authenticated user.
- Edit or delete properties that you have added.
- Use the search and filter functionalities to find specific properties.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

For any inquiries or issues, please contact `your_email@example.com`.

