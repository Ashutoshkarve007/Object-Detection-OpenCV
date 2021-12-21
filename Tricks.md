    # Wait for 'a' key to stop the program  >> Break program from keyboard press
    
    if cv2.waitKey(1) & 0xFF == ord('a'):
        break
