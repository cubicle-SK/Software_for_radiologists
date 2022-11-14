# Software_for_radiologists
An application where radiologist can manully segment and Dicom liver image (CT scan) by selecting the slid they want to work on. after segmentation tehy can add notes by either using speech to text feature or by typing and save the notes along with the Dicom image as a jpg for further sharing and comparison.
They can also run the automated version where segmentation is done using a region growing function of OpenCV library and contouring to find the area of the segmented liver.

## Implementations

1. Open command prompt
2. pip install pyinstaller
3. pyinstaller --onefile FILENAME. (in this case LIVER_GUI.ipynb)
4. Your .exe file will be in dist folder

You can share it to anyone irrespective of whether that person have Python on their system or not.

# First look
![r] (First Page.png)

## Choose slide number
![r] (CT slide.png)

## Manual segmentation
![r] (manual segmentation.png)

## Automated segmentation process
![r] (Automated process flow chart.png)

## Automated segmentation with area
![r] (Automated segmentation.png)

## Notes
![r] (speech to text notes.png)
![r] (re-editing fo notes and save as jpg.png)
