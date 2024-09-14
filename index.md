## Contract Image Processing Software Engineer @ Optical Research Associates, Inc<br> (July 2005 to Aug 2006)

Principal developer of new algorithms and software for accurate simulation of images for lens systems designed with CodeV software developed by ORA. This new software subsystem is released since October 2006 as IMS option for ORA’s flagship CodeV product. CodeV is one of the most comprehensive optical design and analysis systems in the world. It is used by many lens designers at major lens manufacturing companies of the world, to design, analyze and perfect their new lens systems. With this new IMS option for CodeV, lens designers using CodeV can also get to simulate and analyze images of objects much before the lens prototypes are manufactured, so that they get to see the effect of their lens system and hence fine tune their lens more effectively. 

<details>
<summary>New algorithm and implementation for IMS option for CodeV software</summary>
                                         
1. Prototype algorithm development in MATLAB (with image processing package) to demonstrate proof-of-concept for the proposed image simulation subsystem (IMS).

2. Developed accurate methods to reduce the high-resolution lens point spread functions (PSFs) to image pixel resolution, for both rotationally symmetric and non-rotationally symmetric lens systems, for efficient image simulation without loss of any information. Designed appropriate data structures to represent a spatially varying system of PSFs for use during image simulation (for effecting spatially variant diffraction blur and relative illumination over the field of view). 

3. Developed a new approach to simulate lens introduced geometric distortion mapping from object space to image space. Implemented an efficient algorithm to map image points to object points for luminance and color information during image simulation.

4. Employed Intel Performance Primitives to accelerate steps of methods used in (2) and (3) mentioned above. Designed algorithms for accuracy versus computational time trade-off issues.

5. Developed a custom MFC GUI front end for visual analysis of IMS results during the core algorithm development phase.

6. Developed an algorithm to measure the ‘gamma’ of monitors and printers

7. Implemented rich command syntax for using the image simulation subsystem in CodeV under the new IMS option, according to the functional specification for the IMS option. Integrated the IMS subsystem with CodeV product.

8. Produced UML class diagrams for major C++ classes and participated in code-reviews. 

9. Participated in specification of an exhaustive list of tests for IMS Unit Test Plan that covered many optics related issues like measurement of lateral color, geometric distortion, spatially variant blur, etc., as well as, command syntax issues.

10. Performed several of the unit tests myself and produced the regression test scripts.

11. Participated in testing functional performance and fixed found bugs in IMS software.

12. All the software for IMS subsystem was developed in C++ under Visual Studio 6.0.

</details>

---
## Senior Vision Software Engineer @ Adept Technology, Inc<br> (May 1998 to July 2005)

Significantly contributed and lead embedded software development for new machine vision software product for vision guidance to robot controllers. Was awarded by the company in Dec. 2000 for the leading software development role for this product. Lead machine vision software development for many functionality enhancements for this product.

<details>
<summary>List of major projects</summary>
                                

1. Porting/re-writing a large base of legacy 16-bit versions of the C and Motorola assembly machine vision tools to highly portable 32-bit ANSI C code. This involved a large rewrite of many tools, functional unit testing, debugging, optimizing, retesting and checking-in to RCS archive. This new 32-bit ANSI C code is used in the current controller software as part of the machine vision subsystem. Most new 32-bit ANSI C code was developed on either (1) a Unix platform using gcc compiler or (2) Windows NT platform using VisualStudio IDE, and finally produced for the target processor of the embedded vision system board (Texas Instruments TMS320C80 processor). The specific tools ported/re-written are:
   * Line-finder tool   (Unix/gcc)
   * Linear ruler tool (Unix/gcc)
   * Arc ruler tool (Unix/gcc)
   * Arc finder tool (Unix/gcc)
   * Histogram tool (Windows NT/VisualStudio)
   * Auto-thresholding tool (Windows NT/VisualStudio)
   * Window statistics tool (Windows NT/VisualStudio)
   * Timing tests and analysis (perl scripts on Unix)
   * ObjectFinder tool feature analysis code (Unix/gcc)
   * New line-arc segmentation algorithm and implementation (Windows NT/VisualStudio)
   * Edge detection code (Windows NT/VisualStudio)
   * Correlation tool (Windows NT/VisualStudio)

2. Camera-interface project for the embedded machine vision sub-system – This was a major project that I solely completed. It involved development of (i) new image frame-buffer data-structures, (ii) AOI data-structures, (iii) code for supporting several varied and intricate picture acquisition modes depending on software trigger and external hardware trigger as well as controlling synchronized strobe outputs, (iv) camera model data-structures to support multiple differently capable cameras, etc. As part of this project, I developed a deep understanding of how machine vision CCD cameras work as well as of their intricacies (was called in-house “camera guru”), and applied the same to optimize the camera interface code to effect full frame-rate image processing to cater demanding machine vision applications using the product. All the code is 32-bit ANSI C code developed for Texas Instruments C80 processor target on a Windows NT/VisualStudio development platform.

3. Principally responsible for “Qualification Tests” of the final embedded machine vision prototype board. Devised systematic procedures for the same and solely completed the same. Worked directly with the vision board vendor to transparently resolve several issues to ensure expected quality of delivery.

4. Developed a blob-hole computation algorithm quickly within the time constraints taking a new approach leveraging some existing functions to ensure the needed functionality for the new product, against a pressing demand to release the new product due to sudden sourcing problems of hardware for legacy product

5. Lead benchmarking of the new machine vision system against the old one to provide accurate performance comparisons.

6. Detected and fixed a very difficult problem in a C80 library code for Canny edge detection operator – this bug was buried deep in the C80 parallel processor’s algebraic assembly language implementation portion of the Canny algorithm and was incorrectly computing edge-orientation for one quadrant during non-maximum suppression stage of edge detection process.

7. Developed new Convolution and Morphology tools (Windows NT/VisualStudio)

8. Lead several improvements to performance of the embedded machine vision product over the years

9. Developed a dynamically loadable camera model representation for a product that helps utilize a new camera easily with the product. Solely developed C++/MFC GUI Windows application for generating the dynamically loadable camera models (Win2K/VisualC++/MFC)

10. Developed a Image Viewer application to view custom TIFF format images stored when using the embedded machine vision product (Win2K/VisualC++/MFC)

11. Developed new facility for using non-rectangular templates with existing correlation-matching tool. The development was done on a Windows 2000 in VisualStudio. The final code was produced for the C80 target.

12. Developed a new histogram equalization tool for image quality enhancement in certain difficult lighting conditions. The development was done in Win2K/VisualStudio with the final code produced for C80 target

13. Developed a new focus measurement algorithm to enable “auto focusing” ability for robot controllers. Using this algorithm, it is possible to provide a visual image sharpness feedback to the robot motion control algorithms to effect auto focus control. (Development in Win2K/VisualStudio, final code for C80.)

14. Developed a machine vision camera image quality evaluation method to compare the CMOS cameras to more traditionally accepted CCD cameras for machine vision purpose. Based on this method, recommended cameras with select CMOS sensors for machine vision products. (Win2K/VisualStudio/perl)

15. Supervised development of specialized machine vision tools for semiconductor wafer center finder and notch finder algorithms – originated solution approach, provided help in procedures, algorithms, lighting, calibration, etc.

16. Worked with several Firewire camera vendors to address a crucial lack of feature in the Firewire Digital Camera (DCAM) Specification in addressing the needs of vision guided robots – this is the time-stamping feature for digital cameras to precisely know when an image is acquired (this is required to accurately register the camera coordinate system to robot world coordinate system). Convinced one vendor about the merits of such feature in the tightly integrated robotics and machine vision world to the extent that they added the feature without any NRE charges for the company. In fact, many more firewire camera vendors are now adding similar features on top of their DCAM specification compliancy.

17. Contributed to the software design and system architecture of a next generation machine vision product.

18. In charge of Version Control, System Release and Documentation Update process for embedded machine vision software subsystem, for over 5 years. Automated the whole process for RCS revision control using my own perl5 scripts.

</details>