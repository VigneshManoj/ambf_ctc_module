# **How to run the code**
## Install AMBF simulator
To install the AMBF simulator, follow the instructions mentioned in the GitHub Repository: https://github.com/WPI-AIM/ambf

### Add the YAML file for 2 DOF, 3 DOF and 7 DOF robot to AMBF
- Copy the YAML files present in the YAML file folder to the home following directory (assuming ambf was installed in the home folder):
 /home/user_name/ambf/ambf_models/descriptions/multi-bodies

### To Run the Example Codes written in Python to understand
- Run roscore in one of the terminal windows
- Ensure the ambf simulator is sourced in the terminal you are launching the python terminal (I had used Pycharm)
- For running the example of CTC module implemented on a 3 DOF robot in python, Run the file named '3-DOF-CTC_set_point.py'
- For running 2 DOF CTC trajectory tracking code in python, Run the file named '2DOF-InverseDyamics.py'

### To Run the n DOF Robot code
- Run roscore in one of the terminal windows
- Ensure the ambf simulator is sourced in the terminal you are launching the python terminal (I had used Pycharm)
- For running the CTC module, Run the file named 'inversedynamiccontrol4.py'
- For running the PID module, Run the file named 'PID controller.py'
- When the computer prompts, enter the link you want to control (in the examples had used link 1)
- A GUI would pop up where you can provide the desired position and velocity
- Adjust the Gain values to reduce the error value being printed to a very small value

### How to run the 3 DOF trajectory tracking code 
- Run roscore in one of the terminal windows
- Ensure the ambf simulator is sourced in the terminal you are launching the python terminal (I had used Pycharm)
- Run the file named 'inversedynamiccontrol2.py'
- When the computer prompts, enter the link you want to control (in the examples had used link 1)
- A GUI would pop up where you can provide the desired position 
- Adjust the Gain values to reduce the error value being printed to a very small value


