# Unsupervised-HAR
Human Activity Recognition is a field in computer science and artificial intelligence that focuses on the development of algorithms and models to identify and classify human activities based on sensor data.  
Traditional approaches to Human Activity Recognition often involve supervised learning, where the model is trained on labeled datasets, and it learns to recognize activities based on the provided labels. However, unsupervised learning is an alternative approach where the algorithm tries to identify patterns and groupings in the data without predefined labels.

## Dataset Description
• Each of the 19 activities is performed by eight subjects (4 female, 4 male, between the ages 20 and 30) for 5 minutes. Total signal duration is 5 minutes for each activity of each subject. The subjects are asked to perform the activities in their own style and were not restricted on how the activities should be performed. For this reason, there are inter-subject variations in the speeds and amplitudes of some activities. The activities are performed at the Bilkent University Sports Hall, in the Electrical and Electronics Engineering Building, and in a flat outdoor area on campus. Sensor units are calibrated to acquire data at 25 Hz sampling frequency.  
The 19 activities are:  
1. Sitting (a01)
2. Standing (a02)
3. Lying on back (a03)
4. Lying on right side (a04)
5. Ascending Stairs (a05)
6. Descending stairs (a06)
7. Standing in an elevator still (a07)
8. Moving around in an elevator (a08)
9. Walking in a parking lot (a09)
10. Walking on a treadmill with a speed of 4 km/h in flat position) (a10)
11. Walking on a treadmill with a speed of 4 km/h in 15 deg position)(a11)
12. Running on a treadmill with a speed of 8 km/h (a12)
13. Exercising on a stepper (a13)
14. Exercising on a cross trainer (a14)
15. Cycling on an exercise bike in horizontal position (a15)
16. Cycling on an exercise bike in horizontal position (a16)
17. Rowing (a17)
18. Jumping (a18)
19. Playing basketball (a19)  
   
There are 5 sensory units on torso (T), right arm (RA), left arm (LA), right leg (RL), left leg (LL) and 9 sensors on each unit (x,y,z accelerometers; x,y,z gyroscopes; x,y,z magnetometers). Each row of CSV is the data recorded by the sensor while subject is performing the activity. Sensor column tell the type of sensor used to record the data and its position, Action Person column tells the activity and person seperated by, (a01 p1) where a01 is activity and p1 is person. All unique entries in Action Person column are respective classes and indexing starts from 0.  

**Sensors:**  
T-xacc, T-yacc, T-zacc, T-xgyro, T-ygyro, T-zgyro, T-xmag, T-ymag, T-zmag, RA-xacc, RA-yacc, RA-zacc, RA-xgyro, RA-ygyro, RA-zgyro, RA-xmag, RA-ymag, RA-zmag, LA-xacc, LA-yacc, LA-zacc, LA-xgyro, LA-ygyro, LA-zgyro, LA-xmag, LA-ymag, LA-zmag, RL-xacc, RL-yacc, RL-zacc, RL-xgyro, RL-ygyro, RL-zgyro, RL-xmag, RL-ymag, RL- zmag, LL-xacc, LL-yacc, LL-zacc, LL-xgyro, LL-ygyro, LL-zgyro, LL-xmag, LL-ymag, LL-zmag.

## Task Performed

Applied KNN on this transformed data.

## Data

Training data: [Link]()  
Testing data: [Link]()  
