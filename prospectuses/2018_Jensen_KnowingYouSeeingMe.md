# Knowing You, Seeing Me: Investigating User Preferences in Drone-Human Acknowledgement

*by Walther Jensen, Simon Hansen, Hendrik Knoche, in CHI '18* - [10.1145/3173574.3173939](https://doi.org/10.1145/3173574.3173939)

### 1) What are the core research questions investigated through empirical studies?

- What are the suitable drone gestures to acknowledge human presence?
- What is the suitable distance between human and drone when drone acknowledges human? 

### 2) What empirical methods have been used to study the research questions?

1. Live Study 1 with 16 participants to understand preferred acknowledgment distance.
2. Live Study 2  with 16 participants to understand preferred gestures.
3. An online survey with 129 participants. 

### 3) What kind of drone and/or other apparatus was used?

- Parrot Bebop 2 drone  
- IndoTraq™1  tracking system

### 4) What results have been obtained from the studies?

1. Live Study 1:
- On average, the participants’ preferred acknowledgment distance (pad) was 1.8m. 
- The linear correlation between the participants’ pad when approaching and being approached was high.
- The room ventilation system had effects on the experiment, it caused the drone to approach the participants more randomly when approaching from the right side.
- Participants approaching the drone at higher speeds preferred smaller acknowledgment distances.
- Only two participants felt uncomfortable when approaching the drone, feeling uncomfortable had no significant effect on the preferred acknowledging distance.
2. Live Study 2:
- There is a significant difference for the gesture with large effect size, on the feeling of being acknowledged.
- Participants had little difficulty describing and ascribing the meanings of the waggle as wobbling bobbing or winking, nod as greeting and orienting as trying to communicate. Participants struggled with the toss gesture.
3. Online Survey
- On average the online participants (66.4%) felt that the drone had acknowledged them.
- All salutations significantly increased the participants’ feeling of acknowledgment.
- Participants with no or low experience with robots felt more acknowledged than participants with medium experience. Previous drone experience did not moderate the feeling of being acknowledged.
- The respondents had no problem describing and ascribing meaning to toss compared to nod.

### 5) How do the results inform design?

- Physical designs of drones should visually emphasize the front of the drone so that users can recognize an orienting gesture.
- Gestures have to be sufficiently different from an approach or hovering posture.
- Due to external factors such as wind and sensor noise drones need to use corrective maneuvers to maintain their desired speed and orientation in terms of roll, pitch, and yaw. Gestures should be sufficiently different from such maneuvers
- Designers need to consider both the available space and the drone speed to use gestures in flight. 
- Drones need to adapt the gestures they use and how to perform them according to wind strength and direction.
- High rotational (yaw) speeds (200°/sec) appeared as uncontrolled behavior and slow speeds (50°/sec) resulted in unresponsive flights in our implementation. We found 100°/sec suitable for orienting and employed 66°/sec for nods and tosses and 133°/sec for waggles. 
- Changes in drone speeds were perceived as potentially threatening, aggressive, or erratic behavior.
- Designers should tap into other modalities for cues that can help communicate acknowledgment to make gestures more robust under adverse conditions and address the number of participants who did not feel acknowledged. Making eye contact and verbal salutations or other audible feedback all represent promising candidates. 
