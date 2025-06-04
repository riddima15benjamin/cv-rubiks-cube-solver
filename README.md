# CV Cube Solver

## About
A computer vision Rubik's cube solver implementing Kociemba's two-phase algorithm.

Created as a Python web application utilizing the OpenCV library for image recognition, the [TwistySim](http://cube.crider.co.uk/twistysim.html) JavaScript API for puzzle visualizations, and [Maxim Tsoy's Python port of Kociemba's algorithm](https://github.com/muodov/kociemba).

## Dependencies
(see [requirements.txt](/requirements.txt))

## Usage
```
$ git clone https://github.com/raymondtruong/cv-cube-solver.git
$ cd cv-cube-solver
$ python3 -m venv env && . env/bin/activate
(env) $ pip3 install -r requirements.txt
(env) $ python3 main.py
```
The app can then be accessed at 127.0.0.1:5000.
