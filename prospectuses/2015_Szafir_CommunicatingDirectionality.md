# Communicating Directionality in Flying Robots

*by Daniel Szafir, Bilge Mutlu, and Terrence Fong, in  HRI '15* - [10.1145/2696454.2696475](https://doi.org/10.1145/2696454.2696475)

### 1) What are the core research questions investigated through empirical studies?

How might we design explicit communication mechanisms that convey robot flight intentions at a glance?

### 2) What empirical methods have been used to study the research questions?

1. Indoor Live Study with 16 participants.

### 3) What kind of drone and/or other apparatus was used?

- Parrot AR.Drone 2.0
- An Arduino microcontroller
- Circular array of 64 individually-controllable, multi-color LEDs


### 4) What results have been obtained from the studies?

- Users differentiated the signal designs from baseline behavior in terms of telegraphing intent and believed that the use of gaze, thruster, blinker, and beacon behaviors improved robot predictability over baseline flight behaviors.
- There was an overall main effect of signal design on our objective composite measure, gaze, blinker, and thruster (but not beacon), significantly outperformed the baseline.
- There was a main effect of task on performance, with performance significantly higher in Task 1.
- For the performance of each design across task, the thruster performed significantly worse, while the beacon performed marginally worse in Task 2.
- In terms of clarity, post-hoc tests found all individual designs to be rated significantly higher than the baseline
- There was a significant difference between the blinker design, rated as highly intuitive, and the thruster design, which participants found to be less intuitive.
- While gaze, thruster, and blinker significantly improved participant confidence in understanding robot communication over the baseline, participants felt only marginally more confident when the robot used the beacon signals.
- Participants rated gaze, thruster, beacon, and blinker, as significantly improving perceptions of the robot as a work partner over the baseline.
- Participants felt that only the robot demonstrating gaze and blinker behaviors significantly made their task easier than the baseline, while the thruster design was rated as only marginally helpful and the beacon not at all.

### 5) How do the results inform design?

- Users preferred signal specificity at the cost of generalizability and overall found gaze behaviors to be highly useful in improving flyer abilities to communicate and collaborate effectively.
- User responses support the notion that visual cues should convey high level aspects of flight intentions rather than low level corrections to flight paths.
