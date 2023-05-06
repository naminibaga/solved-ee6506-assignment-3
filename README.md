Download Link: https://assignmentchef.com/product/solved-ee6506-assignment-3
<br>



In this exercise, you will use integral equation methods to compute the radar cross-section of an object. The objective is to give you a feel for the sort of design choices that need to be made to solve real world problems. Proceed in these steps:

<ol>

 <li>Consider a object whose shape is that of a regular pentagon, with the length of one sidebeing 3<em>λ</em>.</li>

 <li>Assume that the entire body of this can be modelled as a PEC or a homogeneous dielectric, so that the interior of the aircraft need not be modelled. For the PEC or dielectric scattering code, you may use the codes here as a starting point: <a href="https://bitbucket.org/udaykdk/cem_uday_iitm">http://bitbucket.org/udaykdk/cem_ </a><a href="https://bitbucket.org/udaykdk/cem_uday_iitm">uday_iitm</a></li>

 <li>Now, discretize the outline into segments of length ≈<em>λ</em>/15 and compute the 2D RCS of the object for <em>E<sub>z </sub></em> Be sure to write down the problem formulation properly starting from the operator viewpoint, then the matrix elements, and finally the expression for the radar cross-section.</li>

 <li>Assume the object is illuminated by a S-band radar wave (3 GHz) at 45<sup>◦ </sup>from the <em>x</em>-axis, and that the object is level with the ground and heading in the direction of the radar. Plot the RCS at all angles, and mention what the radar would measure assuming the object is:</li>

</ol>

<ul>

 <li>all PEC (metal), OR</li>

 <li>all carbon fibre. Look up and find the permittivity at this radar wavelength, reporting thesource. 1</li>

</ul>