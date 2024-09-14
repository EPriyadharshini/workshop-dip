# workshop-dip
## NAME:PRIYADHARSHINI E
## REG:212223230159

PROGRAM:
```
import cv2
import matplotlib.pyplot as plt
image1 = cv2.imread('im1.jpg')
image2 = cv2.imread('im2.jpg')
image1.shape
image2.shape
image1_resized=cv2.resize(image1,(400,400))
image2_resized = cv2.resize(image2,(400,400))
image1_resized.shape 
image2_resized.shape 
R1 = image1_resized[0:200, 0:200]      
R2 = image1_resized[0:200, 200:400]  
R3 = image1_resized[200:400, 0:200] 
R4 = image1_resized[200:400, 200:400] 
R5 = image2_resized[0:200, 0:200]      
R6 = image2_resized[0:200, 200:400] 
R7 = image2_resized[200:400, 0:200] 
R8 = image2_resized[200:400, 200:400] 
image1_resized[0:200, 0:200]=R8
image2_resized[200:400, 200:400]=R3
plt.imshow(image1_resized)
plt.show()
plt.imshow(image2_resized)
plt.show()
```

## OUTPUT


![image](https://github.com/user-attachments/assets/7de5e7e0-01c7-474f-841c-2497a5550f56)


![image](https://github.com/user-attachments/assets/2ee5cb75-0bbb-46ae-825f-f48fc9193725)


## RESULT:
  The program executed successfully






         
