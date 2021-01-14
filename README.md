# ocr_pan_card


1.After inputting image converted it to gray scale because it helps in noise reduction and reduces time for mathematical computation on images(colour is of no use for our task).

2.Detected horizontal lines/edges in the image to know whether image is tilted by any angle or not.

3.After detecting horizontal lines I calculated angle of that lines and calculated median of the lines so as to get average of all the lines detected.

4.Rotated the image if median angle of the obtained lines is not equal to zero .

5.Applied pytesseract library to detect text from the image.

6.Processed the text obtained.

7.Applied regex to detect date and PAN card number from the text .
