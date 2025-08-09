# Simple Web App

This is a simple web application built using Node.js. It demonstrates how to set up a basic HTTP server and handle requests.

## Project Structure

```
simple-web-app
├── src
│   └── app.js          # Main entry point of the web application
├── Dockerfile           # Dockerfile to build the application image
├── package.json         # npm configuration file
└── README.md            # Project documentation
```

## Getting Started

To build and run this application using Docker, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone <repository-url>
   cd simple-web-app
   ```

2. **Build the Docker image:**

   ```bash
   docker build -t simple-web-app .
   ```

3. **Run the Docker container:**

   ```bash
   docker run -p 3000:3000 simple-web-app
   ```

4. **Access the application:**

   Open your web browser and navigate to `http://localhost:3000` to see the application in action.

## Dependencies

This project uses the following dependencies:

- Express: A web framework for Node.js.

## License

This project is licensed under the MIT License.