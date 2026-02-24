# PythonWebserver

A lightweight HTTP web server built with Python, designed for simplicity and ease of use.

## Features

- Serve static files (HTML, CSS, JavaScript, images)
- Handle HTTP GET and POST requests
- Simple routing support
- Configurable host and port
- Minimal dependencies — runs on the Python standard library

## Requirements

- Python 3.7 or higher

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Heyyam0855/PythonWebserver.git
   cd PythonWebserver
   ```

2. (Optional) Create and activate a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

## Usage

Start the server with the default settings (host `localhost`, port `8080`):

```bash
python server.py
```

To specify a custom host and port:

```bash
python server.py --host 0.0.0.0 --port 9000
```

Once running, open your browser and navigate to:

```
http://localhost:8080
```

## Project Structure

```
PythonWebserver/
├── server.py        # Main server entry point
├── handlers/        # Request handler modules
├── static/          # Static files served by the server
└── README.md        # Project documentation
```

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m "Add your feature"`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a pull request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
