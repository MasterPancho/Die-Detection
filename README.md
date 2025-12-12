# Die-Detection
A Python application that uses OpenCV and Tkinter to capture and process images of a six-sided die, and applies multiple recognition methods to identify the number on its top face.

The program captures an image using a webcam, applies a custom image-processing pipeline to isolate and clean the die’s top face, and then analyzes the processed image using three different approaches: an OCR-based method (PyTesseract), a CNN classifier trained with Google’s Teachable Machine, and a Vision-Language Model (GPT-4o). The detected number is then displayed to the user through a popup window.
