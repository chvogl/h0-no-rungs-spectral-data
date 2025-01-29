# **H0 No Rungs Attached: Re-Reduced ePESSTO+ Spectral Data for Type II Supernovae**  

## **Overview**  
This repository contains **re-reduced classification spectra from the ePESSTO+ survey**, used in the paper:  

### **["No rungs attached: A distance-ladder free determination of the Hubble constant through type II supernova spectral modelling."](https://ui.adsabs.harvard.edu/abs/2024arXiv241104968V/abstract)**
by **C. Vogl et al. (2024)**.  

The dataset supports the **tailored Expanding Photosphere Method (EPM)** applied to Type II Supernovae (SNe II) to measure the **Hubble constant (H0)** without reliance on traditional distance ladders.  

## **Supernova Sample**  
The re-reduced spectra correspond to the following **ePESSTO+ SNe II**:  

| **Supernova** | **Host Galaxy** | **Redshift (z_CMB)** | **First Detection (UT)** |
|--------------|---------------|-------------------|------------------|
| SN 2019luo  | MCG -01-01-040 | 0.03908          | 2019-07-16      |
| SN 2020bad  | WISEA J092426.48+203802.9 | 0.02811 | 2020-01-23 |
| SN 2020cvy  | IC 2217        | 0.01801          | 2020-02-19      |
| SN 2021gvv  | WISEA J170435.95+140450.4 | 0.03789 | 2021-03-22 |
| SN 2021hkf  | CGCG 040-036   | 0.02077          | 2021-03-29      |
| SN 2021acvc | WISEA J053038.62-225410.2 | 0.03157 | 2021-10-28 |

## **Data Processing**  
The **raw ePESSTO+ spectra** were **reduced and calibrated** following these steps:  
- **Flat-fielding and cosmic ray removal**
- **optimal, variance-weighted extraction** with IRAF
- **Wavelength calibration** using arc lamps and verified against night sky lines  
- **Correction for second-order contamination**  
- **Flux calibration** based on standard star observations  
- **Telluric correction** applied via IRAF  

** No Milky Way extinction corrections** were applied to the data.
The spectra have **not been re-calibrated** against the photometry.
More details on the data reduction can be found in the **Spectroscopy** section of the paper.

## **Acknowledgements**  
If you use this data, please acknowledge **ePESSTO/ePESSTO+** in the acknowledgements section of your work:  

> **Based on observations collected at the European Organisation for Astronomical Research in the Southern Hemisphere, Chile, as part of ePESSTO/ePESSTO+ (the extended Public ESO Spectroscopic Survey for Transient Objects Survey) under ESO programmes 1103.D-0328, 1106.D-0811, and 1108.D-0740.**  

We also extend our thanks to **Joe Lyman and Matt Nicholl** for taking the **calibration data necessary for the EFOSC2 second-order correction**.  

## **License**  
- **Data**: Released under **Creative Commons Zero v1.0 (CC0)** *(public domain, no restrictions)*.  
- **Code (if applicable)**: MIT License.  

## **Citation**  
If you use this dataset, please cite:

BibTeX:  
```bibtex
@ARTICLE{2024arXiv241104968V,
       author = {{Vogl}, Christian and {Taubenberger}, Stefan and {Cs{\"o}rnyei}, G{\'e}za and {Leibundgut}, Bruno and {Kerzendorf}, Wolfgang E. and {Sim}, Stuart A. and {Blondin}, St{\'e}phane and {Fl{\"o}rs}, Andreas and {Holas}, Alexander and {Shields}, Joshua V. and {Spyromilio}, Jason and {Suyu}, Sherry H. and {Hillebrandt}, Wolfgang},
        title = "{No rungs attached: A distance-ladder free determination of the Hubble constant through type II supernova spectral modelling}",
      journal = {arXiv e-prints},
     keywords = {Astrophysics - Cosmology and Nongalactic Astrophysics, Astrophysics - High Energy Astrophysical Phenomena, Astrophysics - Solar and Stellar Astrophysics},
         year = 2024,
        month = nov,
          eid = {arXiv:2411.04968},
        pages = {arXiv:2411.04968},
          doi = {10.48550/arXiv.2411.04968},
archivePrefix = {arXiv},
       eprint = {2411.04968},
 primaryClass = {astro-ph.CO},
       adsurl = {https://ui.adsabs.harvard.edu/abs/2024arXiv241104968V},
      adsnote = {Provided by the SAO/NASA Astrophysics Data System}
}
```
