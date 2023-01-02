# MeasureML
Person Measurement system
# MEASURAI USER MANUAL
###### DISCLAIMER (THIS SYSTEM ONLY WORKS WITH GOOGLE COLAB AND RESULTS ARE ONLY FROM GOOGLE COLAB)
### The System works by running an image through Google's Body Position Detection model API to estimate where on the image each part of the body is. Then we take the pixel distance, and using the height of the person as a metric, we calculate the measurement of each part of the body, then using a distortion correction algorithm. Then using a custom correction algorthim created from 30 sample images of different people using the afformentioned Google calculation and their actual relavent measurements. we make the system more accurate. 
## Limitations
### The current program is intended to retrieve all relavent metrics for the bike fitter program. With a bit of fine tuning on which landmarks are being calculated from, the system will work
## Features
### Input a properly Cropped image and your height and it will retrieve all metrics for the bike system. It currently has an accuracy of within 3/4 of an inch.
### We reccomend using straight photos and making it so that the heels of the person are at the bottom, and the top of the head is at the top. The farther off, the smaller the estimates will be
