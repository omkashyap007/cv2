import cv2 
import numpy as n 

camera = cv2.VideoCapture(0) 

while True : 
    val , frame = camera.read() 
    cv2.imshow("frame" , frame) 

    if cv2.waitKey(1) == ord("e") :
        break 

camera.release()
cv2.destroyAllWindows()
