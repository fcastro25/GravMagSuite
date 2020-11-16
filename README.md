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

### Profile and Grid Operations
<details>
  <summary> <i>(click to expand!)</i> </summary>
  <br>
  
  <details>
  <summary> <b> Profile Analysis </b> <i>(click to expand!)</i> </summary>
  <br>
  
  ![Profile Analysis](https://github.com/fcastro25/GravMagSuite/blob/master/Profile%20Analysis.png)
  This tool allows to load a profile [2 columns ASCII file] and apply some enhacement filters (ASA, THDR, TDX, TDR, among other) as well as derivative filters (both vertical and same profile direction).
  
  ---
  </details>
  
  <details>
  <summary> <b> Extract Profile From a Grid </b> <i>(click to expand!)</i> </summary>
  <br>
  
  ![Extract Profile From a Grid](https://github.com/fcastro25/GravMagSuite/blob/master/Extract%20profile%20from%20a%20grid.png)
  ![Extracted Profile](https://github.com/fcastro25/GravMagSuite/blob/master/extracted%20profile.png)
  In this tool a regularly spaced xyz file (scattered data may not work) can be loaded and a 2D profile can be extracted.
  
  ---
  </details>
  
</details>

---

### Field Transformations
<details>
  <summary> <i>(click to expand!)</i> </summary>
  <br>

  <details>
  <summary> <b> Derivative Filters </b> <i>(click to expand!)</i> </summary>
  <br>
  
  ![Derivative Filter GUI](https://github.com/fcastro25/GravMagSuite/blob/master/Derivative%20filter%20GUI.png)
  ![Derivative Filter Products](https://github.com/fcastro25/GravMagSuite/blob/master/Derivative%20filter%20products.png)
  
  ---
  </details>
  
  <details>
  <summary> <b> Directional Derivative Filter </b> <i>(click to expand!)</i> </summary>
  <br>
  
  ![Directional Derivative Filter GUI](https://github.com/fcastro25/GravMagSuite/blob/master/Directional%20Derivative%20filter%20GUI.png)
  ![Directional Derivative Filter Products](https://github.com/fcastro25/GravMagSuite/blob/master/Directional%20Derivative%20filter%20products.png)
  
  ---
  </details>
  
  <details>
  <p> <summary> <b> Generalized Derivative Operator </b> <i>(click to expand!)</i> </summary> </p>
  <br>
  
  ![Generalized Derivative Operator GUI](https://github.com/fcastro25/GravMagSuite/blob/master/Generalized%20Derivative%20Operator%20GUI.png)
  ![Generalized Derivative Operator Products](https://github.com/fcastro25/GravMagSuite/blob/master/Generalized%20Derivative%20Operator%20products.png)
  
  ---
  </details>
  
  <details>
  <summary> <b> Vertical Derivative using Upward Continuation </b> <i>(click to expand!)</i> </summary>
  <br>
  
  ![Vertical Derivative using Upward Continuation GUI](https://github.com/fcastro25/GravMagSuite/blob/master/Vertical%20Derivative%20using%20Upward%20Continuation%20GUI.png)
  ![Vertical Derivative using Upward Continuation Products](https://github.com/fcastro25/GravMagSuite/blob/master/Vertical%20Derivative%20using%20Upward%20Continuation%20Products.png)
  
  ---
  </details>
  
  <details>
  <summary> <b> Field Continuation </b> <i>(click to expand!)</i> </summary>
  <br>
  
  ![Field Continuation GUI](https://github.com/fcastro25/GravMagSuite/blob/master/Field%20Continuation%20GUI.png)
  ![Field Continuation Products](https://github.com/fcastro25/GravMagSuite/blob/master/Field%20Continuation%20Products.png)
  
  ---
  </details>
  
  <details>
  <summary> <b> Directional Cosine </b> <i>(click to expand!)</i> </summary>
  <br>
  
  ![Directional Cosine Filter GUI](https://github.com/fcastro25/GravMagSuite/blob/master/Directional%20Cosine%20Filter%20GUI.png)
  ![Directional Cosine Filter Products](https://github.com/fcastro25/GravMagSuite/blob/master/Directional%20Cosine%20Filter%20Products.png)
  
  ---
  </details>
  
  <details>
  <summary> <b> Change Direction of Measurement </b> <i>(click to expand!)</i> </summary>
  <br>
  
  ![Change Direction of Measurement GUI](https://github.com/fcastro25/GravMagSuite/blob/master/Change%20Direction%20of%20Measurement%20GUI.png)
  ![Change Direction of Measurement Products](https://github.com/fcastro25/GravMagSuite/blob/master/Change%20Direction%20of%20Measurement%20Products.png)
  
  ---
  </details>
  
  <details>
  <summary> <b> Reduction to the Pole </b> <i>(click to expand!)</i> </summary>
  <br>
  
  - Classical Equation.
  
  ---
  
  - Pseudo Inclination Method.
  
  ---
  </details>
  
  <details>
  <summary> <b> Reduction to the Equator </b> <i>(click to expand!)</i> </summary>
  <br>
  
  
  
  ---
  </details>
  
  <details>
  <summary> <b> Vertical Integration </b> <i>(click to expand!)</i> </summary>
  <br>
  
  
  
  ---
  </details>
  
  <details>
  <summary> <b> Hilbert Transform </b> <i>(click to expand!)</i> </summary>
  <br>
  
  ![Hilbert Transform GUI](https://github.com/fcastro25/GravMagSuite/blob/master/Hibert%20Transform%20GUI.png)
  ![Hilbert Transform Products](https://github.com/fcastro25/GravMagSuite/blob/master/Hibert%20Transform%20Products.png)
  
  ---
  </details>
  
  <details>
  <summary> <b> Anisotropic Diffusion Filter </b> <i>(click to expand!)</i> </summary>
  <br>
  
  
  
  ---
  </details>
  
  <details>
  <summary> <b> Other Filters </b> <i>(click to expand!)</i> </summary>
  <br>
  
  - Convolutional Filters:
    
  ![Convolutional Filter GUI](https://github.com/fcastro25/GravMagSuite/blob/master/Convolutional%20Filters.png)
  ![Convolutional Products](https://github.com/fcastro25/GravMagSuite/blob/master/Convolutional%20Products.png)
  
  ---
  
  - Fourier Domain Filters:
    
  ![Butterworth Filter GUI](https://github.com/fcastro25/GravMagSuite/blob/master/Butterworth%20Filter%20GUI.png)
  ![Butterworth Products - BandPass](https://github.com/fcastro25/GravMagSuite/blob/master/Butterworth%20Filter%20product%20-%20band%20pass.png)
  
  ---
  </details>
  
</details>

---

### Enhancement Filters
<details>
  <summary> <i>(click to expand!)</i> </summary>
  <br>

  <details>
  <summary> <b> Classical Enhancement Filters </b> <i>(click to expand!)</i> </summary>
  <br>
	
  ![Classical Enhancement Filters GUI](https://github.com/fcastro25/GravMagSuite/blob/master/Classical%20Enhancement%20Filters%20GUI.png)
  ![Classical Enhancement Filter Products](https://github.com/fcastro25/GravMagSuite/blob/master/Classical%20Enhancement%20Filter%20Products.png)
  
  ---
  </details>
  
  <details>
  <summary> <b> TDR+-TDX </b> <i>(click to expand!)</i> </summary>
  <br>
  
  ![Combination of TDR and TDX GUI](https://github.com/fcastro25/GravMagSuite/blob/master/Combination%20of%20TDR%20and%20TDX%20GUI.png)
  ![Combination of TDR and TDX Products](https://github.com/fcastro25/GravMagSuite/blob/master/Combination%20of%20TDR%20and%20TDX%20Products.png)
  
  ---
  </details>
  
</details>

---

### Semiquantitative Methods
<details>
  <summary> <i>(click to expand!)</i> </summary>
  <br>
  
  - Source Distance:
  - Tilt Depth:
  - Signum Transform:
  - Euler Deconvolution:
  
  ---
  
</details>

---

### Modeling
<details>
  <summary> <i>(click to expand!)</i> </summary>
  <br>
  
  <details>
  <summary> <b> 2D Modeling </b> <i>(click to expand!)</i> </summary>
  <br>
  
  - Spherical Body:
    
  ![Prismatic Body GUI](https://github.com/fcastro25/GravMagSuite/blob/master/Forward%20Modeling%20of%20Prismatic%20Bodies%20GUI_01.png)
  ![Prismatic Body Model](https://github.com/fcastro25/GravMagSuite/blob/master/Forward%20Modeling%20of%20Prismatic%20Bodies%20GUI_02.png)
  
  ---
  
  - Dyke-Like Body:
    
  ![Prismatic Body GUI](https://github.com/fcastro25/GravMagSuite/blob/master/Forward%20Modeling%20of%20Prismatic%20Bodies%20GUI_01.png)
  ![Prismatic Body Model](https://github.com/fcastro25/GravMagSuite/blob/master/Forward%20Modeling%20of%20Prismatic%20Bodies%20GUI_02.png)
  
  ---
  
  - Fault Model:
    
  ![Prismatic Body GUI](https://github.com/fcastro25/GravMagSuite/blob/master/Forward%20Modeling%20of%20Prismatic%20Bodies%20GUI_01.png)
  ![Prismatic Body Model](https://github.com/fcastro25/GravMagSuite/blob/master/Forward%20Modeling%20of%20Prismatic%20Bodies%20GUI_02.png)
  
  ---
  
  - Irregular Cross-Section Body:
    
  ![Prismatic Body GUI](https://github.com/fcastro25/GravMagSuite/blob/master/Forward%20Modeling%20of%20Prismatic%20Bodies%20GUI_01.png)
  ![Prismatic Body Model](https://github.com/fcastro25/GravMagSuite/blob/master/Forward%20Modeling%20of%20Prismatic%20Bodies%20GUI_02.png)
  
  ---
  </details>
  
  <details>
  <summary> <b> 3D Modeling </b> <i>(click to expand!)</i> </summary>
  <br>
  
  - Prismatic Body:
    
  ![Prismatic Body GUI](https://github.com/fcastro25/GravMagSuite/blob/master/Forward%20Modeling%20of%20Prismatic%20Bodies%20GUI_01.png)
  ![Prismatic Body Model](https://github.com/fcastro25/GravMagSuite/blob/master/Forward%20Modeling%20of%20Prismatic%20Bodies%20GUI_02.png)
  
  ---
  
  - Spherical Body:
    
  ![Spherical Body GUI](https://github.com/fcastro25/GravMagSuite/blob/master/3D%20Forward%20Modeling%20of%20Spherical%20Body%20GUI_01.png)
  ![Spherical Body Model](https://github.com/fcastro25/GravMagSuite/blob/master/3D%20Forward%20Modeling%20of%20Spherical%20Body%20GUI_02.png)
  
  ---
  </details>
  
  ---
  
</details>

---
