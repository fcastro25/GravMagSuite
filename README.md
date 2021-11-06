# GRAV MAG SUITE

![Grav Mag Suite main GUI](https://github.com/fcastro25/GravMagSuite/blob/master/images/home.png)

## ABOUT THIS PROJECT

Grav Mag Suite is an open source MATLAB-based package for processing potential field geophysical data. The codes are written in MATLAB (version 9.4.0.813654 R2018a). This project partially represents the final product of the master degree programme of Federal University of Paraná [UFPR] in collaboration with Laboratory for Research in Applied Geophysics [LPGA]. 

## WHY?

Most geophysical software/suites are comercial or just simple open source command line programs. With Grav Mag Suite the user have in hand a variety of tools capable of perform several kinds of processing tasks over potential field geophysical data. To make it easier, every processing tool has a corresponding graphical user interface (GUI) which allows the user to perform processing tasks in few steps. In this way, Grav Mag Suite gathers the best of two worlds: be free of charge and easy to operate.

## AUTHOR

* Fabrício Rodrigues Castro [fcastrogeof@gmail.com].

Connect with me at [LinkedIn](https://www.linkedin.com/in/fabricio-castro-9a289792/).

## COLLABORATORS

* Saulo Pomponet Oliveira [saulopo@ufpr.br].
* Jeferson de Souza [jdesouza@ufpr.br].
* Francisco José Ferreira Fonseca [francisco.ferreira@ufpr.br].

## INSTALLATION

Grav Mag Suite may be installed by copying the content of the compressed file [Grav Mag Suite.rar] into a directory of your choice.

<p align="center">
IMPORTANT!<br/>
To work properly, Grav Mag Suite must be executed using the following version of MATLAB -> (version 9.4.0.813654 or R2018a). Older or newer MATLAB versions must trigger some issues and bugs.
</p>

## BUG REPORT

In order to maintain the program more stable your feedback is very important. Then, if you have any problem please report your bug sending me an E-mail at [fcastrogeof@gmail.com].

## FUNCTIONALITIES

### Profile and Grid Operations
<details>
  <summary> <i>(click to expand!)</i> </summary>
  <br>
  
  <details>
  <summary> <b> Profile Analysis </b> <i>(click to expand!)</i> </summary>
  <br>
  
  ![Profile Analysis](https://github.com/fcastro25/GravMagSuite/blob/master/images/Profile%20Analysis.png)
  This tool allows to load a profile [2 columns ASCII file] and apply some enhacement filters (ASA, THDR, TDX, TDR, among other) as well as derivative filters (both vertical and same profile direction).
  
  ---
  </details>
  
  <details>
  <summary> <b> Extract Profile From a Grid </b> <i>(click to expand!)</i> </summary>
  <br>
  
  ![Extract Profile From a Grid](https://github.com/fcastro25/GravMagSuite/blob/master/images/Extract%20profile%20from%20a%20grid.png)
  ![Extracted Profile](https://github.com/fcastro25/GravMagSuite/blob/master/images/extracted%20profile.png)
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
  
  ![Derivative Filter GUI](https://github.com/fcastro25/GravMagSuite/blob/master/images/Derivative%20filter%20GUI.png)
  ![Derivative Filter Products](https://github.com/fcastro25/GravMagSuite/blob/master/images/Derivative%20filter%20products.png)
  
  ---
  </details>
  
  <details>
  <summary> <b> Directional Derivative Filter </b> <i>(click to expand!)</i> </summary>
  <br>
  
  ![Directional Derivative Filter GUI](https://github.com/fcastro25/GravMagSuite/blob/master/images/Directional%20Derivative%20filter%20GUI.png)
  ![Directional Derivative Filter Products](https://github.com/fcastro25/GravMagSuite/blob/master/images/Directional%20Derivative%20filter%20products.png)
  
  ---
  </details>
  
  <details>
  <p> <summary> <b> Generalized Derivative Operator </b> <i>(click to expand!)</i> </summary> </p>
  <br>
  
  ![Generalized Derivative Operator GUI](https://github.com/fcastro25/GravMagSuite/blob/master/images/Generalized%20Derivative%20Operator%20GUI.png)
  ![Generalized Derivative Operator Products](https://github.com/fcastro25/GravMagSuite/blob/master/images/Generalized%20Derivative%20Operator%20products.png)
  
  ---
  </details>
  
  <details>
  <summary> <b> Vertical Derivative using Upward Continuation </b> <i>(click to expand!)</i> </summary>
  <br>
  
  ![Vertical Derivative using Upward Continuation GUI](https://github.com/fcastro25/GravMagSuite/blob/master/images/Vertical%20Derivative%20using%20Upward%20Continuation%20GUI.png)
  ![Vertical Derivative using Upward Continuation Products](https://github.com/fcastro25/GravMagSuite/blob/master/images/Vertical%20Derivative%20using%20Upward%20Continuation%20Products.png)
  
  ---
  </details>
  
  <details>
  <summary> <b> Field Continuation </b> <i>(click to expand!)</i> </summary>
  <br>
  
  ![Field Continuation GUI](https://github.com/fcastro25/GravMagSuite/blob/master/images/Field%20Continuation%20GUI.png)
  ![Field Continuation Products](https://github.com/fcastro25/GravMagSuite/blob/master/images/Field%20Continuation%20Products.png)
  
  ---
  </details>
  
  <details>
  <summary> <b> Directional Cosine </b> <i>(click to expand!)</i> </summary>
  <br>
  
  ![Directional Cosine Filter GUI](https://github.com/fcastro25/GravMagSuite/blob/master/images/Directional%20Cosine%20Filter%20GUI.png)
  ![Directional Cosine Filter Products](https://github.com/fcastro25/GravMagSuite/blob/master/images/Directional%20Cosine%20Filter%20Products.png)
  
  ---
  </details>
  
  <details>
  <summary> <b> Change Direction of Measurement </b> <i>(click to expand!)</i> </summary>
  <br>
  
  ![Change Direction of Measurement GUI](https://github.com/fcastro25/GravMagSuite/blob/master/images/Change%20Direction%20of%20Measurement%20GUI.png)
  ![Change Direction of Measurement Products](https://github.com/fcastro25/GravMagSuite/blob/master/images/Change%20Direction%20of%20Measurement%20Products.png)
  
  ---
  </details>
  
  <details>
  <summary> <b> Reduction to the Pole (RTP) </b> <i>(click to expand!)</i> </summary>
  <br>
	  
  The reduction to the pole GUI can reduce the input data under 3 different approaches, Pseudo-inclination ([MacLeod et al. 1993](https://www.tandfonline.com/doi/abs/10.1071/EG993679)), Azimuthal filtering ([Phillips, 1997](https://pubs.usgs.gov/of/1997/0725/report.pdf)), and Nonlinear thresholding ([Zhang et al. 2014](https://www.sciencedirect.com/science/article/abs/pii/S0926985114003048)). Once an approach is choosen, the GUI components related to the selected RTP method will be visible.
	  
  <p align="center">
	  <img src="https://github.com/fcastro25/GravMagSuite/blob/master/images/Reduction%20to%20the%20pole%20GUI.png?raw=true">
  </p>
	  
  - Pseudo Inclination Method.
  
	  The RTP wavenumber-domain operator is expressed by the following expression:  
	  <p align="center">
	  	<img src="https://render.githubusercontent.com/render/math?math=Q(k_{x},k_{y})=\frac{k_{x}^{2} %2B k_{y}^{2}}{(iLk_{x} %2B iMk_{y} %2B N\sqrt{k_{x}^{2} %2B k_{y}^{2}})^{2}}">  
	  </p>
	  or in polar coordinates (with r=1):
	  <p align="center">
	  	<img src="https://render.githubusercontent.com/render/math?math=Q(\theta)=\frac{1}{(sin(I) %2B icos(I)cos(D-\theta))^{2}}">  
	  </p>  
	  
  	  In the pseudo-inclination approach, the above RPT operator is used normally, but at unstable zones (D+90-beta<theta<D+90+beta and D+270-beta<theta<D+270+beta) the bellow expression is used instead:
	  <p align="center">
	  	<img src="https://render.githubusercontent.com/render/math?math=Q(\theta)=\frac{(sin(I)-icos(I)cos(D-\theta))^{2}}{(sin^{2}(I_{a}) %2B icos^{2}(I_{a})cos^{2}(D-\theta))(sin^{2}(I) %2B icos^{2}(I)cos^{2}(D-\theta))}">  
	  </p>
	  where (I_a) is an user-given parameter called pseudo-inclination. It must be larger than the actual magnetic inclination (I) and its absolute value may often be between 20 and 30 degrees. The following figures show an anomaly at I=90 and D=45 and its reduced to the pole product, and both real and imaginary parts of the RTP operator, showing that its amplitudes at unstable zones were fairly atenuated.
	  
  ![Reduction to the pole product 01](https://github.com/fcastro25/GravMagSuite/blob/master/images/Reduction%20to%20the%20pole%20product%2001.png?raw=true)
  ![Reduction to the pole product 01](https://github.com/fcastro25/GravMagSuite/blob/master/images/Reduction%20to%20the%20pole%20product%2002.png?raw=true)

  ---
  </details>
  
  <details>
  <summary> <b> Reduction to the Equator (RTE) </b> <i>(click to expand!)</i> </summary>
  <br>
  
  ![Reduction to the equator GUI](https://github.com/fcastro25/GravMagSuite/blob/master/images/Reduction%20to%20the%20equator%20GUI.png)
  ![Reduction to the equator Product](https://github.com/fcastro25/GravMagSuite/blob/master/images/Reduction%20to%20the%20equator%20products.png)
  
  ---
  </details>
  
  <details>
  <summary> <b> Vertical Integration </b> <i>(click to expand!)</i> </summary>
  <br>
  
  ![Vertical Integration GUI](https://github.com/fcastro25/GravMagSuite/blob/master/images/Vertical%20integration%20GUI.png)
  ![Vertical Integration Product](https://github.com/fcastro25/GravMagSuite/blob/master/images/Vertical%20integration%20product.png)
  
  ---
  </details>
  
  <details>
  <summary> <b> Hilbert Transform </b> <i>(click to expand!)</i> </summary>
  <br>
  
  ![Hilbert Transform GUI](https://github.com/fcastro25/GravMagSuite/blob/master/images/Hibert%20Transform%20GUI.png)
  ![Hilbert Transform Products](https://github.com/fcastro25/GravMagSuite/blob/master/images/Hibert%20Transform%20Products.png)
  
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
    
  ![Convolutional Filter GUI](https://github.com/fcastro25/GravMagSuite/blob/master/images/Convolutional%20Filters.png)
  ![Convolutional Products](https://github.com/fcastro25/GravMagSuite/blob/master/images/Convolutional%20Products.png)
  
  ---
  
  - Fourier Domain Filters:
    
  ![Butterworth Filter GUI](https://github.com/fcastro25/GravMagSuite/blob/master/images/Butterworth%20Filter%20GUI.png)
  ![Butterworth Products - BandPass](https://github.com/fcastro25/GravMagSuite/blob/master/images/Butterworth%20Filter%20product%20-%20band%20pass.png)
  
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
	
  ![Classical Enhancement Filters GUI](https://github.com/fcastro25/GravMagSuite/blob/master/images/Classical%20Enhancement%20Filters%20GUI.png)
  ![Classical Enhancement Filter Products](https://github.com/fcastro25/GravMagSuite/blob/master/images/Classical%20Enhancement%20Filter%20Products.png)
  
  ---
  </details>
  
  <details>
  <summary> <b> Balanced Horizontal Derivative [Edge Detector] </b> <i>(click to expand!)</i> </summary>
  <br>
	
  ![Balanced Horizontal Derivative GUI](https://github.com/fcastro25/GravMagSuite/blob/master/images/Balanced%20Horizontal%20Derivative%20GUI.png)
  ![Balanced Horizontal Derivative Products](https://github.com/fcastro25/GravMagSuite/blob/master/images/Balanced%20Horizontal%20Derivative%20Product.png)
  
  For more information visit -> [Ma and Li, 2014](https://www.sciencedirect.com/science/article/pii/S0926985114001682).
  
  ---
  </details>
  
  <details>
  <summary> <b> Monogenic Signal </b> <i>(click to expand!)</i> </summary>
  <br>
	
  ![Monogenic Signal GUI](https://github.com/fcastro25/GravMagSuite/blob/master/images/Monogenic%20Signal%20GUI.png)
  ![Monogenic Signal Products](https://github.com/fcastro25/GravMagSuite/blob/master/images/Monogenic%20Signal%20Products.png)
  
  For more information visit -> [Hidalgo Gato and Barbosa, 2015](https://library.seg.org/doi/abs/10.1190/GEO2015-0025.1) and [Hidalgo Gato and Barbosa, 2017](https://library.seg.org/doi/abs/10.1190/geo2016-0099.1).
  
  ---
  </details>
  
  <details>
  <summary> <b> Normalized Standard Deviation </b> <i>(click to expand!)</i> </summary>
  <br>
	
  ![Normalized Standard Deviation GUI](https://github.com/fcastro25/GravMagSuite/blob/master/images/Normalized%20Standard%20Deviation%20GUI.png)
  ![Normalized Standard Deviation Products](https://github.com/fcastro25/GravMagSuite/blob/master/images/Normalized%20Standard%20Deviation%20Products.png)
  
  For more information visit -> [Cooper and Cowan, 2005](https://library.seg.org/doi/abs/10.1190/1.2837309).
  
  ---
  </details>
  
  <details>
  <summary> <b> Vertical Integration of ASA </b> <i>(click to expand!)</i> </summary>
  <br>
	
  ![Vertical Integration of ASA GUI](https://github.com/fcastro25/GravMagSuite/blob/master/images/Vertical%20Integration%20of%20ASA%20GUI.png)
  ![Vertical Integration of ASA Products](https://github.com/fcastro25/GravMagSuite/blob/master/images/Vertical%20Integration%20of%20ASA%20Product.png)
  
  For more information visit -> [Paine and Haederle, 2001](https://www.tandfonline.com/doi/abs/10.1071/EG01238).
  
  ---
  </details>
  
  <details>
  <summary> <b> TDR+-TDX </b> <i>(click to expand!)</i> </summary>
  <br>
  
  ![Combination of TDR and TDX GUI](https://github.com/fcastro25/GravMagSuite/blob/master/images/Combination%20of%20TDR%20and%20TDX%20GUI.png)
  ![Combination of TDR and TDX Products](https://github.com/fcastro25/GravMagSuite/blob/master/images/Combination%20of%20TDR%20and%20TDX%20Products.png)
  
  ---
  </details>
  
</details>

---

### Semiquantitative Methods
<details>
  <summary> <i>(click to expand!)</i> </summary>
  <br>
  
  <details>
  <summary> <b> Source Distance </b> <i>(click to expand!)</i> </summary>
  <br>
	  
  ![Source Distance GUI](https://github.com/fcastro25/GravMagSuite/blob/master/images/Source%20Distance%20GUI.png?raw=true)
	  
  This semiquantitative method has two ways of represent the estimated depth, in a surface map or in a scattered plot.
  
  - Surface map;
  ![Source Distance product - surface map](https://github.com/fcastro25/GravMagSuite/blob/master/images/Source%20Distance%20product%20-%20surface%20map.png)
  - Scattered plot;
  ![Source Distance product - scattered plot](https://github.com/fcastro25/GravMagSuite/blob/master/images/Source%20Distance%20product%20-%20scattered%20plot.png)
  
  ---
  </details>
  
  <details>
  <summary> <b> Tilt-Depth </b> <i>(click to expand!)</i> </summary>
  <br>
  
  ![Tilt depth GUI](https://github.com/fcastro25/GravMagSuite/blob/master/images/Tilt%20depth%20GUI.png)
	  
  This semiquantitative method displays the following products: input data, TDR, depth estimates in scattered plot, and histogram of depth estimates.
  ![Tilt depth products - 01](https://github.com/fcastro25/GravMagSuite/blob/master/images/Tilt%20depth%20products%20-%2001.png)
  ![Tilt depth products - 02](https://github.com/fcastro25/GravMagSuite/blob/master/images/Tilt%20depth%20products%20-%2002.png)
  
  ---
  </details>
  
  <details>
  <summary> <b> Signum Transform </b> <i>(click to expand!)</i> </summary>
  <br>
  
  
  
  ---
  </details>
  
  <details>
  <summary> <b> Euler Deconvolution </b> <i>(click to expand!)</i> </summary>
  <br>
  
  
  
  ---
  </details>
  
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
  
  <details>
  <summary> <b> Spherical Body </b> <i>(click to expand!)</i> </summary>
  <br>
  
  
  
  ---
  </details>
  
  <details>
  <summary> <b> Dyke-Like Body </b> <i>(click to expand!)</i> </summary>
  <br>
  
  
  
  ---
  </details>
  
  <details>
  <summary> <b> Fault Model </b> <i>(click to expand!)</i> </summary>
  <br>
  
  
  
  ---
  </details>
  
  <details>
  <summary> <b> Irregular Cross-Section Body </b> <i>(click to expand!)</i> </summary>
  <br>
  
  
  
  ---
  </details>
  
  ---
  </details>
  
  <details>
  <summary> <b> 3D Modeling </b> <i>(click to expand!)</i> </summary>
  <br>
  
  - Prismatic Body:
    
  ![Prismatic Body GUI](https://github.com/fcastro25/GravMagSuite/blob/master/images/Forward%20Modeling%20of%20Prismatic%20Bodies%20GUI_01.png)
  ![Prismatic Body Model](https://github.com/fcastro25/GravMagSuite/blob/master/images/Forward%20Modeling%20of%20Prismatic%20Bodies%20GUI_02.png)
  
  ---
  
  - Spherical Body:
    
  ![Spherical Body GUI](https://github.com/fcastro25/GravMagSuite/blob/master/images/3D%20Forward%20Modeling%20of%20Spherical%20Body%20GUI_01.png)
  ![Spherical Body Model](https://github.com/fcastro25/GravMagSuite/blob/master/images/3D%20Forward%20Modeling%20of%20Spherical%20Body%20GUI_02.png)
  
  ---
  </details>
  
  ---
  
</details>

---
