# mBot-Maze-Race-Project

## Introduction
This is a robotic project whereby the mBot needs to find its way through a maze in the shortest time. The mBot will be facing a number of challenges at intermediate waypoints while attempting to complete the race. The mBot must not bump into any wall by relying on a front ultrasonic sensor, and two side IR proximity sensors to accomplish this. Additionally, the mBot will have to sense colours and detect different frequency of tones.

## Features of the mBot
- Move according to the commands (forward, backward, left or right)
- Ability to detect walls and avoid them using Infrared (IR) sensors
- Ability to detect colour of regularly shaped coloured objects (e.g. cube, cylinder) and change direction with respect to the colour (as per the code)
- Ability to detect frequency of sound waves and change direction with respect to the frequency(as per the code)
- Play celebratory tune upon finishing a maze

## Overall Pseudocode
1. If there is a challenge:
    - Check the colour of the board above.
    - If the colour is not black:
      - Perform colour challenge.
    - Else:
      - Check if there is an audio input.
      - If there is an audio input, perform the audio challenge.
      - Else, play victory tune and terminate the program.
2. Else:
    - Align the robot and repeat from step #1

##### For more details, please refer to the `Final Report.pdf` document. 
