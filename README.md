<img  src="https://github.com/NathanWu7/MimicJointPython/tree/main/assets/example_img.jpeg" />

1. Run the following code to install dependencies: </br>
   `pip install -r requirements.txt`

2. Place <strong>mimic_util.py</strong> into your project files.

3. Reference the <strong>find_joints_with_dof()</strong> function in <strong>mimic_util.py</strong> to obtain active and passive joints(mimic joints) for the specified joint.

4. Use the <strong>actuate()</strong> function to assign actuator control values(open-loop) to the specified original control matrix, in particular, the u_delta matrix obtained from the arm IK solver in Isaac Gym.

5. Use the <strong>position_check()</strong> function to apply closed-loop control signal to the specified control matrix
