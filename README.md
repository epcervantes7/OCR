# OCR

This OCR uses the pre-trained EAST model (frozen_east_text_detection.pb) to detect text regions in a image. Then we look for the smallest bounding box that contains all the previously detected bounding boxes, we crop the image using that large boundong box and finally the pytesseract is used to recognize the text in the cropped image.

# Requerimentos

OpenCV

Tesseract 4 

see the Simple OCR notebook using East and pytesseract.ipynb

this OCR was implemented based on https://www.pyimagesearch.com/2018/09/17/opencv-ocr-and-text-recognition-with-tesseract/


