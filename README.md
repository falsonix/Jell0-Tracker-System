# Jell0-Tracker-System
Homemade version of the SlimeVR open-source designs.

Hey there! I made these designs as a low-cost way of getting nice-looking SlimeVR trackers; the system includes:
  - Extension PCB file for EasyEDA
  - Copy of the SlimeVR PCB for EasyEDA
  - 3D-printable case for main tracker
  - 3D-printable case for extension

# How to use
Step 1. Order just the case **OR** both of the PCB files from https://www.jlcpcb.com/ and make sure to get the boards with their assembly service

Step 2. Order batteries, ESP8266 chips, and IMU sensors (more on those below)

Step 2. Print out as many cases as you need for your trackers and extensions

Step 3. Solder everything together and visit https://slimevr-firmware-tool.futurabeast.com/ to flash your trackers with firmware. **Make sure that your trackers are OFF when flashing, this can cause your trackers to have issues otherwise.**

Step 4. Install the SlimeVR server software from https://github.com/SlimeVR/SlimeVR-Installer/releases/latest/download/slimevr_web_installer.exe and follow the instructions to set up your new trackers.

Step 5. Enjoy your new trackers! If you need any additional assistance please visit https://www.discord.com/invite/slimevr.

# What's an IMU?
You probably heard me mention an IMU earlier. They are the sensors that measure the movements you make, and send that data through the PCB to the server software.

# What IMU should I buy?
If you're new to SlimeVR or if you are on a budget, I would recommend buying the MPU-6050 IMU, as it is affordable and a good way to get into DIY trackers. However, if you have a larger budget, I would go with either the BMI180 or the BNO085 as they provide better tracking at the cost of, well, cost.

# I'm still stuck. Can I have some help?
If you need any assistance at all you can visit the SlimeVR Discord server at https://www.discord.com/invite/slimevr/. There are plenty of helpful people there willing to assist any newcomers to the hobby.
The DIY docs may also be of use, you can find them at https://www.docs.slimevr.dev/.

# Photo Gallery
These are renders taken in Microsoft's 3D Builder software to show off the (awesome) design of the tracker cases.

![Tracker Case (X-Ray)](/repository/assets/employee.png?raw=true "Employee Data title")

![Tracker Case (Assembled)](/repository/assets/employee.png?raw=true "Employee Data title")

![Extension Case (X-Ray)](/repository/assets/employee.png?raw=true "Employee Data title")

![Extension Case (Assembled)](/repository/assets/employee.png?raw=true "Employee Data title")
