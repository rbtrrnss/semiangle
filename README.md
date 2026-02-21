# Semiangle Calculator  
Browser based tool to calculate the semiangle for scanning transmission electron microscopy (STEM) experiments.  
[You can try it on GitHub pages.](https://rbtrrnss.github.io/semiangle/)  

## Usage  
Provide experimental BF disk and a Au Debye ring diameter (selectable d-spacing).  
The actual probe convergence semiangle is calculated.   
 
[<img src="screenshot.png" height="600"/>](screenshot.png "screenshot of the semiangle calculator, it includes input fields for high tension, BF disk diameter, Au (111) diameter, desired semiangle and the angle that the UI displays, there are also the results shown as well as a summary of desired aberration parameters")  
> [!Tip]
> - Hovering over the aberration parameters shows additional hints by alt texts/tooltips.  
> - The hidden section also contains simulated Debye rings (simulation was done in [ReciPro](https://github.com/seto77/ReciPro)).  
> - There is a marker that indicates the expected resolution in the Debye ring schematic based on the desired probe size.  

> [!Warning]
> Probe size estimation: There is no physical model included here. The used formula and parameters were manually fitted, so it matches the estimated D<sub>50</sub> of the C<sub>S</sub> corrector manufacturer.
