# Change-Image-Effect
This project demonstrates a dynamic image transition effect using HTML, CSS, and JavaScript. The user can interact with an image by hovering over it, revealing a smooth sliding transition between two images.

## Features
Hover Effect: As the user moves their mouse over the image, a second image is gradually revealed from left to right.
Seamless Transition: The JavaScript script adjusts the width of the second image based on the mouse position, providing a smooth transition effect.
Responsive Design: The effect adapts to the screen size using percentages for dimensions, making it responsive for different devices.

## How it Works
The project includes an image container (img-box) that holds two images:
A base image (transparent placeholder).
An overlay image that changes width as the mouse moves over it.
A slider (line) is positioned between the images, visually indicating the split between the two images.
JavaScript handles the mouse move event, calculating the position of the cursor and adjusting the width of the second image (img-wrap) and the slider (line) in real time.
