# AirPainter

AirPainter is a virtual painting application using OpenCV and MediaPipe that allows you to draw in the air using hand gestures.

## Features

- Draw lines, rectangles, circles, and freehand shapes using hand gestures.
- Erase parts of the drawing.
- Simple tool selection using gestures.

## Requirements

- Python 3.7 or higher
- OpenCV
- MediaPipe
- NumPy

## Installation

### Setting up a virtual environment

It is recommended to use a virtual environment to manage dependencies. Here’s how you can set up a virtual environment:

1. **Create a virtual environment:**

    ```bash
    python3 -m venv venv
    ```

2. **Activate the virtual environment:**

    - On Windows:

        ```bash
        .\venv\Scripts\activate
        ```

    - On macOS and Linux:

        ```bash
        source venv/bin/activate
        ```

3. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

## Running the Application

1. **Activate the virtual environment (if not already activated):**

    - On Windows:

        ```bash
        .\venv\Scripts\activate
        ```

    - On macOS and Linux:

        ```bash
        source venv/bin/activate
        ```

2. **Run the application:**

    ```bash
    python virtual_paint_app.py
    ```

## Repository Structure

AirPainter/
│
├── virtual_paint_app.py # Main application code
├── requirements.txt # Project dependencies
├── README.md # Project documentation
├── tools.png # Tool icons
└── venv/ # Virtual environment directory (not included in the repo)


## Contributing

Feel free to fork this repository and make pull requests. Contributions are welcome!




