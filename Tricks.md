# Wait for 'a' key to stop the program  >> Break program from keyboard press
    
    if cv2.waitKey(1) & 0xFF == ord('a'):
        break

# Take Video Frame By Frame

    import cv2
    import numpy as np

    cap = cv2.VideoCapture(0)

    while True:
         _, frame = cap.read()
         cv2.imshow("Frame", frame)
         cv2.waitKey(0)
