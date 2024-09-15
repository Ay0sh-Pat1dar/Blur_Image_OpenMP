# Blur_Image_OpenMP
This project demonstrates how to apply a blur effect to an image using a parallelized approach with OpenMP and OpenCV. The blurring is applied using a large kernel (45x45) for a more intense blur effect.

Requirements:-
-> OpenCV (>=4.0)
-> OpenMP (>=2.0)
-> C++ compiler (with OpenMP support, e.g., GCC or Clang)

Installation:-
-> Install OpenCV: Follow the OpenCV installation guide for your platform.
-> Compile the Program:
    Make sure you have a C++ compiler with OpenMP support. For example, on Linux or macOS, you can use GCC:
    g++ -fopenmp -o blur_image blur_image.cpp `pkg-config --cflags --libs opencv4`

Usage:-
-> Prepare an input image: Ensure you have an image named input.jpg in the same directory as the executable or change the input file name in the code accordingly.
-> Run the Program:
    ./blur_image
-> The program will process the image and save the output as output_more_blurred.jpg in the current directory.
