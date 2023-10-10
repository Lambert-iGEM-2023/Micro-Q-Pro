# Micro-Q-Pro

## Description
This is the GitHub repository associated with Micro-Q Pro from https://2023.igem.wiki/lambert-ga/measurement/. Read the link to learn more about the project. 

Micro-Q Pro is a camera-based fluorescence viewer under $10 capable of quantifying up to 8 PCR tubes simultaneously across the full visible wavelength spectrum. Since this detection uses camera imaging rather than photodiodes, users can record fluorescence videos and create real-time curves by snipping images at certain time points with 95.37% accuracy. This open-sourced fluorometer enables accurate and rapid sample quantification for diverse applications.

## Assembly
1. 3D print the STL file provided for the shell of Micro-Q Pro
2. Attach 4 inches of the 5000K LED strip onto the ramp on the inside of the Micro-Q Pro. Plug the LED into a battery or power bank to turn it on.
3. Upload the code for the ESP-32 Camera to create a local server to take images with the camera. On this portal set the contrast to 2 for the best results when imaging samples.
4. Add samples to the PCR tube holder, run the server, and begin imaging your samples.
5. After cropping the images upload them to the images folder in the GitHub clone and enter your file name into the second block of the Python Jupyter notebook where indicated.
6. Then run all the cells and view your results!
