# Hackathon


sudo modprobe bcm2835-v4l2

model --> /home/pi/Desktop/pi-object-detection/MobileNetSSD_deploy.caffemodel


txt --> /home/pi/Desktop/pi-object-detection/MobileNetSSD_deploy.prototxt.txt




python3 pi_object_detection.py \
	--prototxt MobileNetSSD_deploy.prototxt.txt \
	--model MobileNetSSD_deploy.caffemodel
