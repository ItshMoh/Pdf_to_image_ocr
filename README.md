# Pdf_to_image_ocr
It is the code for converting the pdf into image then recognising the scanned document with the help of Pytesseract. It will work on both hindi and english text. You can choose the languages as you want. Visit the tesseract docs.
The tech stack used here. 
1. Pytesseract
2. Pymupdf
Here first you have to download tesseract ocr. You have to specify the path of tesseract ocr.
I have opened the pdf with the help of Pymupdf and converting each page into image with the help of pixmap.
Then reading the image with the help of tesseract ocr.
