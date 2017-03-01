# README

Please feel free to use these packages in future labs as long as you report which nodes you used were provided by the TAs.
 
For future labs, TA examples will be released to this repo using wstool after the due date of the labs.
 
## Installation Steps
```bash
cd ~/racecar-ws/
wstool set src/ta_examples_public --git "https://github.com/mit-racecar/TA_example_labs.git"
wstool update
catkin_make
```

## Using the example packages
```bash
roslaunch ta_lab3 example.launch
``` 