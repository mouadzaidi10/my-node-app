# My Node.js Dockerized Application

This is a simple Node.js application dockerized for demonstration purposes.

## Prerequisites

Before running this application, make sure you have Docker installed on your system.

## Getting Started

1. Clone this repository:

```bash
git clone https://github.com/mouadzaidi10/my-node-app.git
```

2. Navigate to the project directory:

```bash
cd my-node-app
```

3. Build the Docker image:

```bash
docker build -t mouadzaidi/my-node-app:latest .
```

4. Run the Docker container:

```bash
docker run -d -p 3000:3000 mouadzaidi/my-node-app:latest
```

5. Access the application in your web browser at [http://localhost:3000](http://localhost:3000).

## Notes

- The application listens on port 3000 by default. You can change the port mapping in the `docker run` command if needed.
- You can customize the application by modifying the `index.js` file.

## Contributing

If you'd like to contribute to this project, feel free to open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
