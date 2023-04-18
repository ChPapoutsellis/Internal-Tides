# Internal Tides CMS

Calculation of Internal Tides (IT) using a Coupled-Mode System (CMS) obtained
by the body-forcing formulation describing the internal-tide generation process

The function ITCMS calculates the IT generated by a Gaussian ridge.
It returns the energy conversion rate and visualises several flow fields.

Details of the mathematical formulation and the numerical scheme are given in the paper:

Ch. Papoutsellis, M. Mercier, N. Grisouard, Internal tide generation from non-uniform barotropic body forcing

Any comments and questions are welcome!


# MWE
For a minimum working example example corresponding to a Gaussian ridge with criticality 0.8 and relative height 0.5, write ITCMS in the Matlab command prompt
window and press enter.  




# Remarks
For the colormaps we use the function cmocean.m (also provided here) written by Chad A. Greene of the Institute for Geophysics at the 
University of Texas at Austin (UTIG), June 2016, using colormaps created by Kristen
Thyng of Texas A&M University, Department of Oceanography.

Thyng, K.M., C.A. Greene, R.D. Hetland, H.M. Zimmerle, and S.F. DiMarco. 2016. True 
colors of oceanography: Guidelines for effective and accurate colormap selection. 
Oceanography 29(3):9?13, http://dx.doi.org/10.5670/oceanog.2016.66.

