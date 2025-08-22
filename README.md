# Chat App

A real-time chat application built with Node.js, Express, and Socket.io.

***

## Description

This is a simple real-time chat application that allows users to send and receive messages in a chat room. It is built with a Node.js and Express backend, and it uses Socket.io for real-time communication between the clients and the server.




***

## Features

* Real-time messaging
* User-friendly interface
* Multiple chat rooms
* Responsive design

***

## Technologies Used

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** Node.js, Express
* **Real-time Communication:** Socket.io

***

## Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/avinash2274/Chat_App_Guvi_2.git](https://github.com/avinash2274/Chat_App_Guvi_2.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd Chat_App_Guvi_2
    ```
3.  **Install the dependencies:**
    ```bash
    npm install
    ```

***

## .env File Setup

Before starting the server, you need to create a `.env` file in the root directory of the project. This file will store your environment variables.

1.  Create a new file named `.env` in the project's root folder.
2.  Copy and paste the following content into the file, replacing the `...` placeholders with your actual credentials.

    ```env
    MONGODB_URI=...
    PORT=5001
    JWT_SECRET=...

    CLOUDINARY_CLOUD_NAME=...
    CLOUDINARY_API_KEY=...
    CLOUDINARY_API_SECRET=...

    NODE_ENV=development
    ```

***

## Usage

1.  **Start the server:**
    ```bash
    npm start
    ```
2.  Once the server is running, **access the application by navigating to `http://localhost:5001`** (or the port you specified) in your web browser.

***

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

***

## License

[MIT](https://choosealicense.com/licenses/mit/)
