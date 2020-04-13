Monsoon Asia Drought Atlas (MADA) 
-----------------------------------------------------------------------
               World Data Center for Paleoclimatology, Boulder
                                  and
                     NOAA Paleoclimatology Program
-----------------------------------------------------------------------
NOTE: PLEASE CITE ORIGINAL REFERENCE WHEN USING THIS DATA!!!!!


NAME OF DATA SET: Monsoon Asia Drought Atlas (MADA) 
LAST UPDATE: 4/2010 (Original receipt by WDC Paleo) 
CONTRIBUTORS: Cook, E.R., K.J. Anchukaitis, B.M. Buckley, 
R.D. D'Arrigo, G.C. Jacoby, and W.E. Wright.  

IGBP PAGES/WDCA CONTRIBUTION SERIES NUMBER: 2010-037  

WDC PALEO CONTRIBUTION SERIES CITATION: 
Cook, E.R., et al. 2010. 
Monsoon Asia Drought Atlas (MADA).
IGBP PAGES/World Data Center for Paleoclimatology 
Data Contribution Series # 2010-037. 
NOAA/NCDC Paleoclimatology Program, Boulder CO, USA. 


ORIGINAL REFERENCE: 
Cook, E.R., K.J. Anchukaitis, B.M. Buckley, R.D. D'Arrigo, 
G.C. Jacoby, and W.E. Wright. 2010. 
Asian Monsoon Failure and Megadrought During the Last Millennium. 
Science, Vol. 328, Issue 5977, pp.486-489, 23 April 2010.  
DOI: 10.1126/science.1185188

ABSTRACT: 
The Asian monsoon system affects more than half of humanity worldwide, 
yet the dynamical processes that govern its complex spatiotemporal 
variability are not sufficiently understood to model and predict 
its behavior, due in part to inadequate long-term climate observations. 
Here we present the Monsoon Asia Drought Atlas (MADA), a seasonally 
resolved gridded spatial reconstruction of Asian monsoon drought 
and pluvials over the past millennium, derived from a network of 
tree-ring chronologies. MADA provides the spatiotemporal details 
of known historic monsoon failures and reveals the occurrence, 
severity, and fingerprint of previously unknown monsoon megadroughts 
and their close linkages to large-scale patterns of tropical 
Indo-Pacific sea surface temperatures. MADA thus provides a long-term 
context for recent monsoon variability that is critically needed for 
climate modeling, prediction, and attribution.


GEOGRAPHIC REGION: Southeast Asia
PERIOD OF RECORD: 1300 - 2005 AD 
  
FUNDING SOURCE:
U.S. National Science Foundation Paleoclimate Program, 
award ATM 04-02474.


DESCRIPTION: 
Monsoon Asia Drought Atlas (MADA). Palmer Drought Severity Index 
reconstructions based on a network of Asian Tree ring data. 
Data files and their contents are as follows: 

1) jja-mada.txt - 534 grid point reconstructions of JJA PDSI 
   for the Asian monsoon region.

These are the "Monsoon Asia Drought Atlas" (MADA) reconstructions 
from tree rings that are published in Cook et al. Science 2010. 
There are 534 grid point reconstructions on a 2.5x2.5° grid. 
The data are in column-ASCII form, one reconstruction per column 
and the grid point number is at the top of each column. 
Column 1 has the years and the total time period covered is 
AD 1300-2005. Missing values are indicated by -99.999. 
These reconstructions are actually ensemble averages of 24 
separate reconstructions based on four search radii 
(500, 1000, 2000, and 3000 km) and six correlation weightings. 
See the Cook et al. 2010 Science paper SOM for details.
	
The tree-ring estimates of JJA PDSI actually end in 1989 and the 
instrumental data from 1990 to 2005 have been appended to the ends 
of the reconstructions to bring them up to date. To do this in as 
seamless a manner as possible, the reconstructions have been scaled
to have the same means and standard deviations as the actual data 
over the 1951-1989 calibration period.
	

	
2) jja-mada-xy.txt - 534 longitude-latitude pairs that locate 
   the grid point reconstructions. The lon-lat pairs are ordered 
   to agree with the column number above each reconstruction.



3) JJA_PDSI_Act.txt - 534 actual JJA PDSI series used for 
   calibration and verification.

These series are organized columnwise in exactly the same way 
as the reconstructions and each column number heading matches 
the number of the reconstruction. The data cover the 1870-2005 
period of available data from the Dai-Trenberth-Qian. 
The original data are available at 
http://www.cgd.ucar.edu/cas/catalog/climind/pdsi.html. 
However, the data provided here have been modified to fill in 
missing values with weighted estimates from immediately adjacent 
grid points using a 9-point "Queen's Case" adjacency model. 
This has also resulted in a small degree of local spatial smoothing 
to the data. So there is not one-to-one agreement between what is 
provided here and what is directly available from the 
Dai-Trenberth-Qian website. See the Science paper SOM for details.



4) jja-mada-calver.txt - calibration and verification statistics 
   for each of the 534 JJA PDSI reconstructions, with longitude-
   latitude coordinates for their locations.

Five statistics are reported for each reconstruction: 
CRSQ (calibration period R2), 
CVRE (calibration period leave-one-out cross-validation 
reduction of error - essentially the same as Allen's PRESS), 
VRSQ (verification period square of the Pearson correlation 
coefficient), VRE (verification period reduction of error), 
and VCE (verification period coefficient of efficiency). 
The calibration period is 1951-1989 and the verification 
period is 1920-1950.
	
See the Science paper SOM for why these periods were chosen 
and also why regions of weak verification may be as much due 
to poor instrumental data quality as due to poor estimation 
by the tree rings.
	

