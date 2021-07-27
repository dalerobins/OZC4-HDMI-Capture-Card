# OCZ4-HDMI-Capture-Card
OZC4 (2021-03-1) MS2109/MS9333 Based HDMI USB Capture Device With 4K Loopthrough


# image in readme
![](Images/20210727_133419.jpg)



I picked up this cheap HDMI USB Capture Device from Amazon, I needed one that had HDMI Passthrough as I want to use it with my HDMI Microscope.

Taken some pictures of the device externally and internally, pictures taken of the PCB and IC's with my microscope. 
I've dumped the 24C32 EEPROM and put the files on here.

Although this has a USB 3.0 Type A port, it appears to only have the USB 2.0 data lines connected to the PCB.



# Supported Formats:
	[video4linux2,v4l2 @ 0x55d9ff4dcf00] Compressed : mjpeg : Motion-JPEG : 
	1920x1080 1600x1200 1360x768 1280x1024 1280x960 1280x720 1024x768 800x600 720x576 720x480 640x480
	[video4linux2,v4l2 @ 0x55d9ff4dcf00] Raw : yuyv422 : YUYV 4:2:2 : 
	1920x1080 1600x1200 1360x768 1280x1024 1280x960 1280x720 1024x768 800x600 720x576 720x480 640x480



	Index       : 0
	Type        : Video Capture
	Pixel Format: 'MJPG' (compressed)
	Name        : Motion-JPEG
		Size: Discrete 1920x1080
			Interval: Discrete 0.017s (60.000 fps)
			Interval: Discrete 0.033s (30.000 fps)
			Interval: Discrete 0.040s (25.000 fps)
			Interval: Discrete 0.050s (20.000 fps)
			Interval: Discrete 0.100s (10.000 fps)
		Size: Discrete 1600x1200
			Interval: Discrete 0.017s (60.000 fps)
			Interval: Discrete 0.033s (30.000 fps)
			Interval: Discrete 0.040s (25.000 fps)
			Interval: Discrete 0.050s (20.000 fps)
			Interval: Discrete 0.100s (10.000 fps)
		Size: Discrete 1360x768
			Interval: Discrete 0.017s (60.000 fps)
			Interval: Discrete 0.033s (30.000 fps)
			Interval: Discrete 0.040s (25.000 fps)
			Interval: Discrete 0.050s (20.000 fps)
			Interval: Discrete 0.100s (10.000 fps)
		Size: Discrete 1280x1024
			Interval: Discrete 0.017s (60.000 fps)
			Interval: Discrete 0.033s (30.000 fps)
			Interval: Discrete 0.040s (25.000 fps)
			Interval: Discrete 0.050s (20.000 fps)
			Interval: Discrete 0.100s (10.000 fps)
		Size: Discrete 1280x960
			Interval: Discrete 0.017s (60.000 fps)
			Interval: Discrete 0.033s (30.000 fps)
			Interval: Discrete 0.040s (25.000 fps)
			Interval: Discrete 0.050s (20.000 fps)
			Interval: Discrete 0.100s (10.000 fps)
		Size: Discrete 1280x720
			Interval: Discrete 0.017s (60.000 fps)
			Interval: Discrete 0.020s (50.000 fps)
			Interval: Discrete 0.033s (30.000 fps)
			Interval: Discrete 0.050s (20.000 fps)
			Interval: Discrete 0.100s (10.000 fps)
		Size: Discrete 1024x768
			Interval: Discrete 0.017s (60.000 fps)
			Interval: Discrete 0.020s (50.000 fps)
			Interval: Discrete 0.033s (30.000 fps)
			Interval: Discrete 0.050s (20.000 fps)
			Interval: Discrete 0.100s (10.000 fps)
		Size: Discrete 800x600
			Interval: Discrete 0.017s (60.000 fps)
			Interval: Discrete 0.020s (50.000 fps)
			Interval: Discrete 0.033s (30.000 fps)
			Interval: Discrete 0.050s (20.000 fps)
			Interval: Discrete 0.100s (10.000 fps)
		Size: Discrete 720x576
			Interval: Discrete 0.017s (60.000 fps)
			Interval: Discrete 0.020s (50.000 fps)
			Interval: Discrete 0.033s (30.000 fps)
			Interval: Discrete 0.050s (20.000 fps)
			Interval: Discrete 0.100s (10.000 fps)
		Size: Discrete 720x480
			Interval: Discrete 0.017s (60.000 fps)
			Interval: Discrete 0.020s (50.000 fps)
			Interval: Discrete 0.033s (30.000 fps)
			Interval: Discrete 0.050s (20.000 fps)
			Interval: Discrete 0.100s (10.000 fps)
		Size: Discrete 640x480
			Interval: Discrete 0.017s (60.000 fps)
			Interval: Discrete 0.020s (50.000 fps)
			Interval: Discrete 0.033s (30.000 fps)
			Interval: Discrete 0.050s (20.000 fps)
			Interval: Discrete 0.100s (10.000 fps)

	Index       : 1
	Type        : Video Capture
	Pixel Format: 'YUYV'
	Name        : YUYV 4:2:2
		Size: Discrete 1920x1080
			Interval: Discrete 0.200s (5.000 fps)
		Size: Discrete 1600x1200
			Interval: Discrete 0.200s (5.000 fps)
		Size: Discrete 1360x768
			Interval: Discrete 0.125s (8.000 fps)
		Size: Discrete 1280x1024
			Interval: Discrete 0.125s (8.000 fps)
		Size: Discrete 1280x960
			Interval: Discrete 0.125s (8.000 fps)
		Size: Discrete 1280x720
			Interval: Discrete 0.100s (10.000 fps)
		Size: Discrete 1024x768
			Interval: Discrete 0.100s (10.000 fps)
		Size: Discrete 800x600
			Interval: Discrete 0.050s (20.000 fps)
			Interval: Discrete 0.100s (10.000 fps)
			Interval: Discrete 0.200s (5.000 fps)
		Size: Discrete 720x576
			Interval: Discrete 0.040s (25.000 fps)
			Interval: Discrete 0.050s (20.000 fps)
			Interval: Discrete 0.100s (10.000 fps)
			Interval: Discrete 0.200s (5.000 fps)
		Size: Discrete 720x480
			Interval: Discrete 0.033s (30.000 fps)
			Interval: Discrete 0.050s (20.000 fps)
			Interval: Discrete 0.100s (10.000 fps)
			Interval: Discrete 0.200s (5.000 fps)
		Size: Discrete 640x480
			Interval: Discrete 0.033s (30.000 fps)
			Interval: Discrete 0.050s (20.000 fps)
			Interval: Discrete 0.100s (10.000 fps)
			Interval: Discrete 0.200s (5.000 fps)



