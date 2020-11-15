# GRAV MAG SUITE

![Grav Mag Suite main GUI](https://github.com/fcastro25/GravMagSuite/blob/master/home.png)

## ABOUT THIS PROJECT

Grav Mag Suite is an open source MATLAB-based package for processing potential field geophysical data. The codes are written in MATLAB (version 9.4.0.813654 R2018a). This project partially represents the final product of the master degree programme of Federal University of Paraná [UFPR] in collaboration with Laboratory for Research in Applied Geophysics [LPGA]. 

## WHY?

Major geophysical software/suites are comercial ones or just simple open source scripts without a friendly graphical user interface (GUI). With Grav Mag Suite the user have in hand a variety of tools capable of do all kinds of processing tasks over potential field geophysical data. To make it easier, every processing tool has a corresponding GUI which allows the user to perform processing tasks in few steps. In this way, Grav Mag Suite unites the best of two worlds: be free of charge and easy to opperate.

## AUTHOR

* Fabrício Rodrigues Castro [fcastrogeof@gmail.com].

Connect with me at [LinkedIn](https://www.linkedin.com/in/fabricio-castro-9a289792/).

## COLLABORATORS

* Saulo Pomponet Oliveira [saulopo@ufpr.br].
* Jeferson de Souza [jdesouza@ufpr.br].
* Francisco José Ferreira Fonseca [francisco.ferreira@ufpr.br].

## INSTALLATION

Grav Mag Suite may be installed by copying the content of the compressed file [Grav Mag Suite.rar] into a directory of your choice.

## BUG REPORT

In order to mantain the program up to date your feedback is very important. Then, if you have any problem please report your bug sending me an E-mail at [fcastrogeof@gmail.com].

## FUNCTIONALITIES

- Profile and Grid opperations:
	- Profile Analysis:
  ![Profile Analysis](https://github.com/fcastro25/GravMagSuite/blob/master/Profile%20Analysis.png)
  This tool allows to load a profile [2 columns ASCII file] and apply some enhacement filters (ASA, THDR, TDX, TDR, among other) as well as derivative filters (both vertical and same profile direction).
  - Extract Profile From a Grid:
  ![Extract Profile From a Grid](https://github.com/fcastro25/GravMagSuite/blob/master/Extract%20profile%20from%20a%20grid.png)
  ![Extracted Profile](https://github.com/fcastro25/GravMagSuite/blob/master/extracted%20profile.png)
  In this tool a regularly spaced xyz file (scattered data may not work) can be loaded and a 2D profile can be extracted.
- Field Transformations:
  - Derivative Filters:
  - Directional Derivative Filter:
  - Generalized Derivative Operator:
  - Vertical Derivative using Upward Continuation:
  - Field Continuation:
  - Directional Cosine:
  - Change Direction of Measurement:
  - Reduction to the Pole:
    - Classical Equation.
    - Pseudo Inclination Method.
  - Reduction to the Equator:
  - Vertical Integration:
  - Hilbert Transform:
  - Anisotropic Diffusion Filter:
  - Other Filters:
    - Convolutional Filters:
    
    ![Convolutional Filter GUI](https://github.com/fcastro25/GravMagSuite/blob/master/Convolutional%20Filters.png)
    ![Convolutional Products](https://github.com/fcastro25/GravMagSuite/blob/master/Convolutional%20Products.png)
    
    - Fourier Domain Filters:
    
    ![Butterworth Filter GUI](https://github.com/fcastro25/GravMagSuite/blob/master/Butterworth%20Filter%20GUI.png)
    ![Butterworth Products - BandPass](https://github.com/fcastro25/GravMagSuite/blob/master/Butterworth%20Filter%20product%20-%20band%20pass.png)
    
- Enhancement Filters:
  - Classical Enhancement Filters:
  - TDR+-TDX:
- Semiquantitative Methods:
  - Source Distance:
  - Tilt Depth:
  - Signum Transform:
  - Euler Deconvolution:
- Modeling:
 - 2D Modeling:
 - 3D Modeling:
