DocScanner
DocScanner is a Python-based document scanning application that allows users to convert images of documents into clear, high-quality scanned copies. The application leverages OpenCV , imultis ,numpy and other image processing libraries to detect document edges, apply perspective transformations, and enhance the document's readability.

Features
Automatic Document Detection: Automatically detects and highlights the document edges in an image.
Perspective Transformation: Corrects the perspective of the document to produce a flat, top-down view.
Image Enhancement: Enhances the document's clarity using various image processing techniques.
Save & Export: Save the scanned document as a high-quality image file or PDF.


##The basic idea on which the is implemented is:

Step 1: Detect edges.
Step 2: Use the edges in the image to find the contour (outline) representing the piece of paper being scanned.
Step 3: Apply a perspective transform to obtain the top-down view of the document.
