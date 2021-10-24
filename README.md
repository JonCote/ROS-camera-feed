# ROS-camera-feed

How to Run:

  1) start ros core: roscore
  2) start video_stream_opencv: rosrun video_stream_opencv video_stream 0 (if video device is at video0)
     - also can use the usb_cam interface: rosrun usb_cam usb_cam_node _pixel_format:=yuyv
  4) start web_video_server: rosrun web_video_server web_video_server  (send video stream to localhost:8080)


  usb_cam is also included incase problems with video_stream_opencv
  
  
  Dependancies:
    OpenSSL
    OpenCV
