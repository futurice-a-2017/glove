Repo for controlling InMoov using the prototype glove.

Usage:
- Upload arduino_glove_pub.ino to arduino
- Run 'rosrun rosserial_python serial_node /dev/ttyACM0'
- Run 'rosrun glove joint_state_publisher.py'
- Run 'roslaunch inmoov_description display_nogui.launch'
