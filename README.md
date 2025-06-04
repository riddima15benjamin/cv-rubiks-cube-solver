# CV Rubik's Cube Solver

A computer vision-based Rubik's Cube solver that utilizes OpenCV for image processing and Kociemba's two-phase algorithm for solving the cube.

## Features

- Real-time cube face detection using OpenCV
- Integration with Kociemba's two-phase algorithm for efficient solving
- Web-based interface for user interaction

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/riddima15benjamin/cv-rubiks-cube-solver.git
cd cv-rubiks-cube-solver
```

### 2. Create and activate a virtual environment

```bash
python3 -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
```

### 3. Install the dependencies

```bash
pip install -r requirements.txt
```

## Usage

Run the application:

```bash
python main.py
```

Then, open your browser and go to:

```
http://127.0.0.1:5000
```

to access the web interface.

## Dependencies

- OpenCV
- Flask
- NumPy
- Kociemba’s Rubik's Cube solver (Python implementation)

For a complete list, see `requirements.txt`.

## Folder Structure

```
cv-rubiks-cube-solver/
├── static/
├── templates/
├── cube_scanner.py
├── main.py
├── requirements.txt
├── solver.py
└── README.md
```

## Contributing

Contributions are welcome! Please fork the repository and create a pull request for improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
