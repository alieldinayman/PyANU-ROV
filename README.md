# PyANU
• PyANU is a data science software application, packed with features for co-piloting and calculating various outcomes for remotelyoperated
underwater vehicles.
• Features include: estimating and plotting a plane’s crash site on a map, calculating distances using coordinate pixel conversion, color
and shape recognition, and various other tools.

# Changelog
v2.0.0:
*Implemented the GUI using PyQt4.
*Changed the wind equation to be variable in plotting the Crashmap.

v2.2.1:
*Added functionanility to the Seismo tab.

v2.2.2:
*Fixed the Seismo tabs switching in a random fashion.

v2.3.0:
*Changed the Horizontal function to measure on the mooring line.
*Added automatic screenshotting using PyScreenshot.
*Combined both functions above into the Horizontal tab.

v2.3.1:
*Added the NewCapture flag to know if the horizontal should make a new capture or use the last taken photo.
*Fixed the CSR by adding green, orange and yellow to be displayed as yellow.
*Added showing big letters instead of descriptive text on the screen.
*Removed the RES from the CSR.

v2.3.2:
*Adjusted CSR HSV color ranges to fit darker places via the Color Picker algorithm.
*Changed the wind equation to integrate over time using SciPy instead of updated incrementing to increase the accuracy.
*Changed many of the output printing methods in the Crashmap function.

v2.4.0:
*Added Real-Time OCR using Tesseract, OpenCV and PyScreenshot

v2.4.1:
*Added conditional aircraft type output to the OCR function.
*Improved OCR accuracy using multiple data pre-processing techniques.


