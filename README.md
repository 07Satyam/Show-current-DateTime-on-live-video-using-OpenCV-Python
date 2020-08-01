# Show-current-DateTime-on-live-video-using-OpenCV-Python

In this project, we will see how to show the current Date and Time on live Video. Firstly, we import important libraries then we define cap function for live video capture. Inside an infinite while loop, Display the image and use cv2.waitKey()  for a keypress. Specify the font and show the current date and time using cv2.putText()       cv2.putText(img, position, font, fontScale, color, thickness, lineType, bottomLeftOrigin)
Next,  provide the termination condition where key ‘q’ breaks the loop. Then we call cap.release()  function to release the camera device resource. Lastly, we call cv2.destroyAllWindows() function for destroys all the windows we created.

