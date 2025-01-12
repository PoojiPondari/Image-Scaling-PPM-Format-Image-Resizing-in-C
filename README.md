# Image-Scaling-PPM-Format-Image-Resizing-in-C
A C program that reads a PPM image, creates smaller and larger versions by scaling down and up, and saves the resized images. The program supports both shrinking the image to half its original size and enlarging it to twice its original size.

Features
Resize images: Shrinks and enlarges PPM images.
Support for PPM format: Works with .ppm image files.
Customizable: Easily adaptable for other image transformations.
Technologies Used
C programming language
PPM image format handling
How It Works
The program loads a .ppm image file.
It creates two new images:
A smaller image, reduced to half of the original dimensions.
A larger image, enlarged to double the original dimensions.
The images are saved as pooj_small_image.ppm and pooj_large_image.ppm.
Requirements
A C compiler (e.g., GCC, Visual Studio).
PPM image handling functions (like ReadPPM, WritePPM, and pixel manipulation functions) which are assumed to be implemented in a separate header (PPMTools.h).
How to Use
Clone the repository to your local machine:
bash
Copy code
git clone https://github.com/yourusername/ppm-image-resizer.git
Compile the program:
bash
Copy code
gcc -o image_resizer image_resizer.c
Run the program:
bash
Copy code
./image_resizer
Enter the name of the .ppm file when prompted. The program will create and save the resized images in the same directory.
Example
bash
Copy code
Enter the image filename (.ppm format): example.ppm
This will generate two new files:

pooj_small_image.ppm: The smaller, reduced image.
pooj_large_image.ppm: The larger, enlarged image.
Contributing
Feel free to fork this repository and create a pull request with any improvements, bug fixes, or additional features. Contributions are always welcome!

License
This project is open source and available under the MIT License.

