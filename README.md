# Drowsiness_detector

Nowadays drowsiness of drivers is one of the main reasons behind road accidents. Most people who travel long distances prefer to take night and early morning drives because that allows them to travel faster due to less traffic and helps to save a lot of time. It is natural for drivers who take long drives to doze off behind the steering wheel. A countless number of people drive on the highway day and night. Taxi drivers, bus drivers, truck drivers, and people traveling long-distance suffer from lack of sleep. Due to this, it becomes very dangerous to drive when feeling sleepy. The majority of accidents happen due to the drowsiness of drivers who travel during the night and early morning. This project intends to develop a computer vision system made with the help of OpenCV that can automatically detect driver drowsiness in a real-time video stream and then play an alarm if the driver appears to be drowsy.

Eye aspect ratio (EAR) is a metric that measures the level of openness of the eye, based on the ratio of the distance between two points on the eye to the distance between two points on the eyebrow and the distance between two points on the eye. The EAR calculation involves identifying specific facial landmarks, typically the inner and outer corners of the eye and the 37 highest and lowest points of the eyebrow, and computing the distances between them. The ratio of the horizontal distance between the inner and outer corners of the eye to the vertical distance between the highest point of the eyebrow and the lowest point of the eyelid gives the EAR value. 

 ![image](https://github.com/SubhashiniDB/Drowsiness_detector/assets/136738038/9c41b64f-a189-4c6d-9767-a4d3157c5917)


EAR is calculated using the below formula,

 ![image](https://github.com/SubhashiniDB/Drowsiness_detector/assets/136738038/0e57bc5e-cd34-4a51-9e9b-c80031ccd364)


A higher EAR value indicates that the eye is more open, while a lower value indicates that the eye is more closed. An EAR threshold is set to 2 to detect if the driver is getting drowsy or falling asleep based on the decrease in the EAR value over time. 

![image](https://github.com/SubhashiniDB/Drowsiness_detector/assets/136738038/f3aed96a-444b-4f98-abff-751a0e576eac)
 
