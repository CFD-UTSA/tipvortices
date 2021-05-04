# Final Project - Tip Vortices Schlieren Image Processing using GPU
Be aware this code might need the use of a NVIDIA GPU with CUDA capabilities.

Data Allocation: https://drive.google.com/drive/folders/1Fol3tnrV2WKfaaPOs4lknffI7Gg8uT-1?usp=sharing

Specific/Exotic/Special Packages:

1. ImageJ: a Java-based image processing program developed at the National Institutes of Health and the Laboratory for Optical and Computational Instrumentation (LOCI, University of Wisconsin).
2. Numba: a just-in-time compiler for Python that works best on code that uses NumPy arrays and functions, and loops.
3. CUDA: a parallel computing platform and programming model developed by NVIDIA for general computing on graphical processing units (GPUs).
4. PIL: a library provides extensive file format support, an efficient internal representation, and fairly powerful image processing capabilities.
5. GC: a module that includes functions for controlling how the collector operates and to examine the objects known to the system, either pending collection or stuck in reference cycles and unable to be freed.

NOTE: The use of Pandas in this project is limited or null due the characteristics of the data processed.

For this project, it has been proposed the implementation of GPU for image processing and matrix calculations and provide:

1. The use of big data sets that contains images with JPEG and TIFF format. The code will allow the handling of different type of collected Schlieren images, and the background substraction of them. The data sets containg 4 experiments with different subcases.
2. The process of the images to obtain the most optimal contrast between the fluids that are captured providing a clearer visualization of turbulent features, such as vortices, and decompose the frequency at which them start appearing.
3. The comparisson between the use of CPU calculations, following the same concept of background substraction, and GPU calculations as well as the comparisson between multiple packages: ImageJ vs Numba.

This script would be able to be used by any user who understands the Numba CUDA configuration and has the limitant of RAM memory and CPU cores/threads on the computer being used. With the main script the user woud have:

1. Image processing
2. RAM memory management
3. Image to array conversion
4. CPU vs GPU benchmark
5. ImageJ vs Numba/PIL benchmark

