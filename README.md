# Python for Variable Star Astronomy

The talk slides are [here](craig-aavso-fall-2017.pdf).

## Links to online (no install necessary) Jupyter notebook examples

+ Image reduction: `reducer`: https://goo.gl/rgyLf6
+ A few short example from an observational astronomy course: https://goo.gl/RG4uLg

## Install Python

All of the packages below should work with any Python distribution.

However, they are all easiest to install if you use the [Anaconda Python Distribution](https://www.anaconda.com/download/#macos). An alternative (and much smaller to download) is the [miniconda installer](https://conda.io/miniconda.html), which is the Anaconda distribution without several pre-installed packages.

## Links to software

The installation instructions below are for the Anaconda (or miniconda) Python distribution. For other Python distributions you can replace `conda` with `pip` to install the software.

+ The astropy core package
    * Documentation: http://astropy.readthedocs.io/
    * Source code/report bugs: https://github.com/astropy/astropy (click "Issues to report bugs")
    * Install: `conda install astropy`
    * Update: `conda update astropy`
+ Image reduction with ccdproc:
    * Documentation: http://ccdproc.readthedocs.io/
    * Source code/report bugs: https://github.com/astropy/ccdproc (click "Issues to report bugs")
    * Install: `conda install -c astropy ccdproc`
    * Update: `conda update -c astropy ccdproc`
+ Notebook-based GUI image reduction with reducer:
    * Documentation: http://reducer.readthedocs.io/
    * Source code/report bugs/suggest improvements: https://github.com/mwcraig/reducer (click "Issues to report bugs")
    * Install: `conda install -c conda-forge ccdproc`
    * Update: `conda update -c conda-forge ccdproc`
+ Photometry with photutils (IRAF-like source detection, aperture and PSF photometry)
    * Documentation: http://photutils.readthedocs.io/
    * Source code/report bugs: https://github.com/astropy/photutils (click "Issues to report bugs")
    * Install: `conda install -c astropy photutils`
    * Update: `conda update -c astropy photutils`
+ Photometry with sep (Source Extractor-like photometry):
    * Documentation: http://sep.readthedocs.io/
    * Source code/report bugs: https://github.com/kbarbary/sep (click "Issues to report bugs")
    * Install: `conda install -c conda-forge sep`
    * Update: `conda update -c conda-forge sep`
+ Catalog/data look-up with astroquery:
    * Documentation: http://astroquery.readthedocs.io/
    * Source code/report bugs: https://github.com/astropy/astroquery (click "Issues to report bugs")
    * Install: `conda install -c astropy astroquery`
    * Update: `conda update -c astropy astroquery`
+ Convenience functions/in-notebook visualization with glowing-waffles
    * Documentation: Coming soon!
    * Source code/report bugs/suggest new features: https://github.com/glowing-waffle/glowing-waffles (click "Issues to report bugs/suggest features")
    * Install: `pip install glowing-waffles` (Anaconda or any other python distribution)
    * Update: `pip install -U --no-deps glowing-waffles` (Anaconda or any other python distribution)
