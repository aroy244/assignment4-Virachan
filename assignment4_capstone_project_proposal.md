# A9501: Assignment 4 - Capstone Project Proposal  

## Simulating Emission-Line Behaviour in Active Galactic Nuclei  

### Principal Investigator: Viraja Khatu  

In the era of emerging astronomical observing facilities, the _Cosmological Advanced Survey Telescope for Optical and ultraviolet Research_[1] (CASTOR; Capak et al. 2019) is a Canadian-flagship ultraviolet (UV) space mission proposed to the Canadian Space Agency.  CASTOR successfully completed its initial science planning in early 2019 and continues to support its academic and industry partners in developing the telescope instruments.  One of the key science goals of CASTOR is to study the growth of supermassive black holes (SMBHs; black holes[2] millions to several billion times more massive than our Sun) residing at the centres of massive galaxies[3] up to billions of light years[4] away.  As part of the Active Galactic Nuclei[5] (AGN) science team for CASTOR, I have been involved in designing a survey simulation to optimize AGN variability surveys with the telescope.  The simulation is divided into several modules that coordinate with each other to deliver the end result -- AGN black hole masses over a wide range of cosmic times (billions of light years) using two promiment UV emission lines, Lyα λ1215 and CIV λ1549, in AGN.  For my Astronomy 9501Q Capstone Project, I aim to complete one of the simulation modules that generates light curves (brightness varying over a peiod of time) for emission lines of interest.

Despite decades of research on SMBHs, how they grow and evolve still remains unexplained.  Every massive galaxy in the local universe hosts an SMBH at its centre, but such black holes do not form in the present day universe.  Thus, there is a missing link of how SMBHs grow and evolve from the past to the present that is yet to be established.  In AGN, the inflow of gas through the accretion disk onto the central black hole releases tremendous amount of energy (from X-rays to the radio).  Some fraction of this energy drives energetic winds and the rest contributes to the growth of the black hole; hence, AGN are ideal laboratories to study SMBH growth.  However, AGN accretion systems are spatially unresolved which calls the need for time-domain studies to probe their structures.  

Reverberation Mapping (RM) is a powerful technique to map the structure and kinematics of AGN.  RM is based on the empirical fact that AGN exhibit continuum variability on that depend on luminosity, black hole mass, and wavelength (a few days to weeks or years).  Because the energetics of gas orbiting close to the black hole (Broad emission-Line Region, BLR) are dominated by photo-ionization[6], an increase in continuum emission will result -- after a time delay set by the light travel time between the continuum-emitting and emission-line regions -- in an increase in broad emission-line flux (Peterson 2014).  This gives rise to correlated light curves, emission-line lagging the continuum by the light travel time.  RM converts time delay into a spatial distance giving the size of the BLR.

The goal of my captone project is to design the module that generates emission-line light curves for specific emission lines.  In RM, ionizing photons from the continuum are absorbed and re-emitted as emission-line photons by the broad-line gas.  Thus, the emission-line light curve module will use input parameters -- emission line of interest, size of the BLR, inclination angle of the BLR, and line-of-sight velocity -- to simulate a transfer function, defining the emission-line response of the BLR model to the continuum variations.  

References:  
Capak, P., Balogh, M. L., Christiansen, J. L., et al. 2019, inBulletin of the American Astronomical Society, 51, 219.  
Peterson, B. M. 2014, Space Sci. Rev., 183, 253.  
&nbsp;

----  
[1]: The _Cosmological Advanced Survey Telescope for Optical and ultraviolet Research_ is proposed to perform imaging and spectroscopic surveys in three UV-optical bands from 1350 to 5500Å.  Visit https://www.castormission.org/ for more details.  

[2]: A black hole is an extremely compact object in the universe that forms when massive stars (several tens of times more massive than our Sun) die.  It is a region where matter is squeezed into a very small volume of space, giving rise to strong gravity that even light cannot escape.  

[3]: Galaxies are collections of stars, gas, and dust held together by gravity.  

[4]: One light year is the distance that light travels in a year which is 9.5 x 10^12^ kilometres per second.  

[5]: Active Galactic Nuclei are supermassive black holes located at the centres of massive galaxies where matter falls onto the central black hole through an 'accretion disk' of ionized gas and dust.  

[6]: Photo-ionization is the process in which electromagnetic radiation interacts with matter and dissociates it into electrically charged particles.
