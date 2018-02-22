![Alt text](circuit.png?raw=true "Title")
# Digital Circuit Simulation
Simluation of digital circuit using python and web browser

## Getting Started
The test cases are in the tests/ directory. tests/README.txt explains the syntax of the simulator input files. You can use the following command to run all the tests.
```
python circuit test.py
```

To work on a single test case, run the simulator on the test case with the following
command:
```
python circuit.py < tests/1gate.in > out
```

To use the visualizer, first produce a simulation trace.
```
TRACE=jsonp python circuit.py < tests/1gate.in > circuit.jsonp
```
Then use Google Chrome to open visualizer/bin/visualizer.html

### Prerequisites
None

## Citation

Erik Demaine, and Srinivas Devadas. 6.006 Introduction to Algorithms. Fall 2011. Massachusetts Institute of Technology: MIT OpenCourseWare, https://ocw.mit.edu. License: Creative Commons BY-NC-SA.
