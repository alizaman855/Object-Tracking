# Object-Tracking
It is a project of object tracking using YOLO object detection.In this project we
learn how we can take an object same  which is detected in different frames. For 
that purpose we have used OpenCv library of python. 
In this Project first of all we have to load video and also detect the objects in 
different frames of the video. After that we have to track the object. It means that
when one object change its location then it will detect the object as different object
but we have to detect it as same object. We have to do that by checking the distance of object
in different frames and if it is less than some spacific point then it is detected as same object.
