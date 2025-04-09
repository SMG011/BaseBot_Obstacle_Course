# Overview:

# Course Description and Obstacle Details
The obstacle course is a looped path that includes a variety of challenges designed to challenge the BaseBot’s navigation skills. Each obstacle tests the robot’s balance, turning, and object detection skills. The obstacles include:

 - Ramp = Located at the bottom right corner. The BaseBot must ascend and descend smoothly without tipping. It is the start and end part of our obstacle course.

- Cones = Placed inbetween the wall portion and the ramp. The BaseBot must weave between them carefully in order to wall and get to the next portion of the maze.

- Walls = Found on the bottom left side of the course. The BaseBot must maneuver through the  passage and not get stuck in the process when turning.

- Tunnel = Directly after the walls. The BaseBot must enter and exit while staying on course and avoiding the walls.

- Seesaw = Near the top right corner. The BaseBot must drive over it slowly to trigger the tilt and descend safely. Afterward it needs to ascend and descend the ramp yet again.


# How Your BaseBot Interacts with Each Obstacle
Ramp: Uses its motors to gently climb up and stabilize with its sensors to avoid flipping. It adjusts speed when descending.

Cones: Uses its front sensors to detect obstacles and steer between them using programmed turns.

Walls: Relies on side sensors or timing to navigate the tight path, avoiding collisions by making small adjustments.

Tunnel: Slows down slightly and follows a straight path, using sensors or timing to avoid straying.

Seesaw: Moves slowly onto the plank, waits for it to tilt, and proceeds forward once balanced.


# How to Run Your Python Script
1. Connect your BaseBot to the computer using USB.

2. Open the VEX program .

3. Upload the Python script to the BaseBot.

4. Place the BaseBot at the course’s starting line.

5. Click “Run” in the VEX program or press the play button on the BaseBot if it has one.


# Reflection: What Worked Well and Challenges Faced

# What Worked Well:

The building process went well. We were able to put together the BaseBot and the obstacles without any major issues.

We were able to code it with ease and get the basic functions working quickly.

Teamwork and communication were strong, which helped us stay organized and on task.

The BaseBot was able to handle simpler obstacles like the tunnel and ramp consistently.

# Challenges Faced:
Getting the code to be accurate was a challenge, especially when it came to turning angles and timing.

Fitting our obstacle course into the 4x3 build area was tough so we had to redesign parts of it to make everything fit.

Navigating the wall section was difficult for the BaseBot, and it sometimes got stuck or went off track.

Sometimes small changes in the code caused unexpected results, which meant we had to test and tweak multiple times.
