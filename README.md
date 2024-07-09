# UAV-Pedestrian-Detection-for-Social-Distancing-Monitoring

# Dataset:
https://github.com/Akshathakrbhat/Manipal-UAV-Person-Dataset

13462 sampled images and 153112 object instances with their annotations.
Images captured from various heights

CBAM is applied as a layer in every convolutional block of a convolutional neural network model. It takes in a tensor containing the feature maps from the previous convolutional layer

![image](https://github.com/TejavardhanReddy03/UAV-Pedestrian-Detection-for-Social-Distancing-Monitoring/assets/108484910/8e57c600-c942-4287-b572-a5001f89c534)

# Homography matrix :
![image](https://github.com/TejavardhanReddy03/UAV-Pedestrian-Detection-for-Social-Distancing-Monitoring/assets/108484910/374bf288-aa18-4b22-a2e0-edf2bf20a2d5)

All we need is coordinates of    4 points  in original image and vertical image.Then use this matrix for rest of the images captured from same height
Since our target detection are roughly in the same plane here, z2=1 ,z1=1 and h33=1

# Tilted image: 
![image](https://github.com/TejavardhanReddy03/UAV-Pedestrian-Detection-for-Social-Distancing-Monitoring/assets/108484910/19cc51c3-4f93-44f5-8e91-786cae9d1fba)
# Vertical or bird view image : 
![image](https://github.com/TejavardhanReddy03/UAV-Pedestrian-Detection-for-Social-Distancing-Monitoring/assets/108484910/21c988c5-9dcd-44e6-8793-18e7102ffe49)

# Test image :
![image](https://github.com/TejavardhanReddy03/UAV-Pedestrian-Detection-for-Social-Distancing-Monitoring/assets/108484910/378c3e68-281e-40ba-b389-10a0d58eec7a)


# Test Results:
![image](https://github.com/TejavardhanReddy03/UAV-Pedestrian-Detection-for-Social-Distancing-Monitoring/assets/108484910/9e10a4df-e17a-4929-9be3-64b1c3f9877f)

# SAMPLE OUTPUTS:

![image](https://github.com/TejavardhanReddy03/UAV-Pedestrian-Detection-for-Social-Distancing-Monitoring/assets/108484910/db0a986d-9169-4221-bda4-84339959cddb)
![image](https://github.com/TejavardhanReddy03/UAV-Pedestrian-Detection-for-Social-Distancing-Monitoring/assets/108484910/2cb2202a-d0c6-4cc6-8ffa-028ef798b35c)



