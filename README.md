## Install and Run

```bash

# Download
git clone https://github.com/vt-hri/HW12.git
cd GameTheory

# Create and source virtual environment
# If you are using Mac or Conda, modify these two lines as shown in [HW0](https://github.com/vt-hri/HW0)
# If you have previously created a virtual environment with torch, you can just source that environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
# If you are using Mac or Conda, modify this line as shown in [HW0](https://github.com/vt-hri/HW0)
pip install numpy torch matplotlib

# Run the script
python main.py
```

## Goal

Code for a mobile robot that is learning to reach a goal.
The robot is a point moving in an x-y plane, and the goal is static.
We will leave the learning algorithm fixed: our goal is to design a minimal dataset that teaches the robot the task.
