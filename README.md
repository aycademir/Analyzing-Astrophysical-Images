# Analyzing-Astrophysical-Images

## INTRODUCTION
One of the most heavily researched topics in the field of astronomy are black holes. Although the detection of black holes is quite difficult as they do not emit any electromagnetic waves, astoronomers still manage to detect black holes when black holes happen to exist under special conditions, like in black hole-star binary systems. In such systems, matter from the companion star falls towards the black hole, creating an accretion disk. The friction between the accreting matter causes the temperature to rise to billions of degrees, resulting in X-ray emissions. X-ray telescopes are used in space to capture these X-rays since Earth's atmosphere absorbs X-rays (Chandra X-Ray Observatory, 2019). Structures of X-ray telescopes are different than optical telescopes: Instead of using optical lenses, they use nested grazing incidence mirrors to capture X-rays (NASA, 2018). X-ray telescopes (XMM-Newton, Chandra, Swift XRT and so forth) differ from each other mainly by their energy, angular and timing resolution; making them more suitable for different types of observations.

## OBJECTIVE
The project aims to study the dust scattering halo of 4U-1630 47 binary by calculating the radial distribution of brightness of the image and ploting it as a function of radius.

## METHODOLOGY
In this project's initial stage, research was conducted on black holes, X-ray emissions from black holes, and X-ray observatories using academic resources. 
In the second stage, the astrophysical image in FITS file format is filtered into arrays as sublists that contain data of photon energies and coordinates. Then, based on the filtered arrays,  an algorithm that calculates the radial distribution of photon intensity (photon count per arcsecond^2) is designed and the findings are plotted to analyze the dust scattering halo of the black hole. For this second coding phase of the project, the Python programming language is used.

## FINDINGS
The analysis of the photon intensity distribution as a function of radius, along with the utilization of DS9 software showed a dust scattering halo extending from 70" to 250". Relatively high emissions being received from such distances away from the source indicates the existence of a photon scattering medium, possibly a large gas cloud between the Earth and the source. The photons that were supposed to go in other directions could be scattered by the large gas cloud in between and redirected towards the Earth, enabling the detection of such extended emission region. The much clearer ring structure in the Chandra image may be due to Chandra's higher angular and energy resolution, as well as it's better sensitivity allowing Chandra to reveal structures in dust scattering halo to a better extent.

## ANALYSIS
To eliminate as much as possible the possibility of reduced quantum efficiency at the lower and higher end of detector's energy range affecting the results (Chandra X-Ray Observatory, n.d.), the images were analysed using only the photons within 1.5-6 keV energy range.
After the photon intensity distribution data of Chandra image was plotted, a region with relatively high photon intensity extending from 75" to 250" could be observed. To assist the analysis of the black hole source even further, DS9 software was utilized. After applying energy and coloring filters, an image of the emission region of the outer halo of the source was created. A ring-like structure was seen between 110" - 175" angular area, supporting the previous photon intensity graph.
The outer halo of the same black hole source was analysed using a different image, which was taken by Swift XRT.  The photon intensity distribution graph shows a region extending from 70" to 290", where the photon intensities are relatively higher. The visualisation of the outer halo of the source using DS9 enabled the structure of the previously detected region to be observed in more detail: A relatively high emission region was observed within 250" radius. Although not as detailed as in Figure 3, a ring-like structure around the center was also detected.

## RELATED LITERATURE
Chandra X-Ray Observatory. (2019, September 11). History of X-ray Astronomy. Retrieved from https://chandra.harvard.edu/xray_astro/history.html
Chandra X-Ray Observatory. (n.d.). Chapter 6 ACIS: Advanced CCD Imaging Spectrometer. Retrieved from https://cxc.harvard.edu/proposer/POG/html/chap6.html#tth_chAp6
European Southern Observatory. (2008, October 15). A binary black hole. Retrieved from https://www.eso.org/public/images/eso0836a/
NASA. (2018, September). X-ray Telescopes Introduction. Retrieved from https://imagine.gsfc.nasa.gov/observatories/technology/xray_telescopes1.html

