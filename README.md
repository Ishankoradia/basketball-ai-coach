## Basketball shooting posture detection and feedback

### Why

Basketball is rapidly growing in India, with increasing grassroots participation, professional leagues, and a rising presence in international competitions. However, access to quality coaching remains limited, especially outside major cities. A free, `AI-powered shooting form analysis tool` can bridge this gap by helping aspiring players refine their technique without needing expensive training sessions. By making such technology widely accessible, more players can develop fundamental skills, elevating the overall standard of basketball in the country and fostering a stronger, more competitive basketball culture.

Why only shooting ? Shooting is the most fundamental skill in basketball—no matter how good a player is at dribbling or defense, the ability to put the ball in the basket ultimately determines success. A great shooting form improves accuracy, consistency, and confidence, making it a key area for player development.

### What

Users will be able to either upload their shooting clips or record in real time to get feedback from the tool. The feedback will include
1. A score to determine how close you are to an `ideal shot`
2. Text based comments on how to further improve your shot

### How

The `AI-powered shooting form analysis tool` will use computer vision & pose estimation models under the hood to figure out how good your shot is.


## Milestones

### 1: Segmentation 

1.1 From an image, how to pick the area (or bounding box) of a human ? 

1.2 How to augment the above, to pick/select/localize the bounding box of a human in shooting position with basketball in hand ?

### 2: Key point detection

2.1 What is key point detection ?

2.2 How do you run key point detection on an image ? (Explore various models)

2.3 How does the output of a key point detection model look like ? Can you apply a logic to test if a pose if what you expect

### 2: Train on an ideal/correct pose


### 3: Run the model on a shooting clip


### 4: Ability to score user input


### 5: Textual feedback on user input


### 6: Package it as a app