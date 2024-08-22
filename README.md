# Password Manager

![Screenshot](/public/screenshots/screenshot.png)

## Description

Password Manager is a web application that allows users to securely store and manage their passwords. Built with React and Vite, it offers a user-friendly interface and robust functionality.

## Features

- Add, edit, and delete passwords
- Copy passwords to clipboard
- Toggle password visibility
- Securely store and retrieve passwords using MongoDB
- Responsive design

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/HackesticMedusa/password-manager-mongo.git
    ```
    
2. Navigate to the project directory:
    ```sh
    cd password-manager-mongo
    ```
    
3. Install dependencies:
    ```sh
    npm install
    ```

## Usage

1. Start the development server:
    ```sh
    npm run dev
    ```
    
2. Open your browser and navigate to [http://localhost:5173/](http://localhost:5173/).

## Backend Setup

1. Navigate to the backend directory:
    ```sh
    cd backend
    ```

2. Install backend dependencies:
    ```sh
    npm install
    ```

3. Create a `.env` file in the backend directory and add your MongoDB URI and database name:
    ```env
    MONGO_URI=your_mongodb_uri
    DB_NAME=your_database_name
    ```

4. Start the backend server:
    ```sh
    node server.js
    ```

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)

## Contact

For any inquiries, please contact [HackesticMedusa](https://github.com/HackesticMedusa).