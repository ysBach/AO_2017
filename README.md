# AO2017

All the lecture notes primarily made by Yoonsoo P. Bach. I tried not to make typo, logically wrong statement, etc. If any problem is there in the note, that's solely my fault, so please be kind and let me know so that the notes can be updated.

## Instructors
Astronomical Observation and Lab. 1 (AO1) and 2 (AO2) at Seoul National University (SNU) in 2017 

* Lecturer: professor Masateru Ishiguro 
* TA: **Yoonsoo P. Bach**

For the detailed introduction, see the prefaces.

Outline of TA sessions for 2017 AO1: Uploaded on Google Drive: [Link](https://drive.google.com/open?id=1Tt-j8SrdfzE-gBOzgxW061ngEbRz5njnbw-8lHO9GnI)


## TA Lecture Notes Outline

The following lecture notes only gives you idea how to use tools for data reduction. **You *must* be aware of what you are doing!** Identical procedure to the lecture note may give different results, depending on what you've done other than what I did when I make the notes.

Preface in [English](https://github.com/ysBach/AO_2017/blob/master/00_Preface_English.md) and [Korean](http://nbviewer.jupyter.org/github/ysbach/AO_2017/blob/master/00_Preface-Korean.ipynb) (Korean version is not being updated for months: please see the Eng version)

​		Photometry (AO1)

1. [Installation](http://nbviewer.jupyter.org/github/ysbach/AO_2017/blob/master/01_Installation.ipynb) and [LINUX Basic](http://nbviewer.jupyter.org/github/ysbach/AO_2017/blob/master/01_LINUX_Shell.ipynb)

2. [Python Basic](http://nbviewer.jupyter.org/github/ysbach/AO_2017/blob/master/02_Python_Basic.ipynb)

3. [Get the Taste](http://nbviewer.jupyter.org/github/ysbach/AO_2017/blob/master/03_Get_the_Taste.ipynb) (showing few examples using HST data)

4. [Reducing Ground-Based Observation Data: Concepts](http://nbviewer.jupyter.org/github/ysbach/AO_2017/blob/master/04_Ground_Based_Concept.ipynb)

5. [How to IRAF](http://nbviewer.jupyter.org/github/ysbach/AO_2017/blob/master/05_IRAF_Tutorial.ipynb)

6. [Simple Preprocessing Using Python](http://nbviewer.jupyter.org/github/ysbach/AO_2017/blob/master/06_Preprocessing_with_Python.ipynb)

7. [Cosmic-Ray Rejection](http://nbviewer.jupyter.org/github/ysbach/AO_2017/blob/master/07_Cosmic_Ray_Rejection.ipynb)

8. [photutils (1): Star Finding](http://nbviewer.jupyter.org/github/ysbach/AO_2017/blob/master/08_Photutils_StarFinder.ipynb)

9. [photutils (2): SExtractor Sky](http://nbviewer.jupyter.org/github/ysbach/AO_2017/blob/master/09_Photutils_SExtractor_Background.ipynb)

10. [photutils (3): Annulus Sky](http://nbviewer.jupyter.org/github/ysbach/AO_2017/blob/master/10_Photutils_Annulus_Background.ipynb)

11. [photutils (4): Aperture Photometry](http://nbviewer.jupyter.org/github/ysbach/AO_2017/blob/master/11_Photutils_Aperture_Photometry.ipynb)

12. [photutils (5): Extended Sources and Morphology, Sersic Profile](http://nbviewer.jupyter.org/github/ysbach/AO_2017/blob/master/12_Photutils_Extended_Sources.ipynb)

13. [Useful Functionalitis](http://nbviewer.jupyter.org/github/ysbach/AO_2017/blob/master/13_Useful_Functionalities.ipynb)

    -----

    Spectroscopy (AO2)

14. [Spectroscopy Concepts](http://nbviewer.jupyter.org/github/ysbach/AO_2017/blob/master/14_Spectroscopy_Concept.ipynb)
* Appendix A. [Photometric Errors](http://nbviewer.jupyter.org/github/ysbach/AO_2017/blob/master/App_A_Photometric_Errors.ipynb)
* Appendix B. [Using Astropy for FITS](http://nbviewer.jupyter.org/github/ysbach/AO_2017/blob/master/App_B_Using_Astropy_for_FITS.ipynb)
* Appendix C. [Spyder](http://nbviewer.jupyter.org/github/ysbach/AO_2017/blob/master/App_C_Spyder.ipynb)

Notes 00, 01, and 02 are not covered in class times.

## Schedules

### Photometry (AO1)

| Date           | Contents                                 | Notes                                    |
| -------------- | ---------------------------------------- | ---------------------------------------- |
| 2017-04-13     | Introduction + TA show using [HLA](http://hla.stsci.edu/) | [Presentation](https://drive.google.com/file/d/0B-MLFRYnMxUvQ1BJTkhNcVNveFFkYURLdDVMaWZkVDA5V05J/view?usp=sharing), Corresponding notebook = 03 |
| 2017-04-18     | Basic Knowledge on Preprocessing, Aperture Photometry, and Statistics | [Presentation](https://drive.google.com/open?id=0B-MLFRYnMxUvcnVjZ19teS02LWdxR004Mlp4MFlibWtLVmNj)  Corresponding notebook = Appendix A |
| 2017-04-20, 25 | Legacy sessions: IRAF Tutorial Using Archived Data | Corresponding notebook = 05 (and 04)     |
| 2017-04-27     | Preprocessing using Python with `ccdproc` | Corresponding notebook = 06              |
| 2017-05-02     | Cosmic-Ray Rejection + Using `photutils` (1) : Star Finding (`DAOStarFinder`) and Aperture Plot | Corresponding notebook = 07 & 08         |
| 2017-05-08     | Using `photutils` (2) : Background Estimation (SExtractor) + Using `photutils` (3) : Background Estimation (Annulus) + Using `photutils` (4) : Aperture Photometry | Corresponding notebook = 09, 10, 11      |
| 2017-05-16     | Using `photutils` (5) : Extended Sources and Morphology, Sersic Profile | Corresponding notebook = 12              |

### Spectroscopy (AO2)

| Date           | Contents                                 | Notes                       |
| -------------- | ---------------------------------------- | --------------------------- |
| 2017-10-10     | Spectroscopy Concepts                    | Corresponding notebook = 14 |
| 2017-10-19, 23 | Legacy sessions: Using IRAF for spectroscopy |                             |
| 2017-10-       | Wavelength Identification                |                             |
|                | Coordinate transformation                |                             |
|                | Background (sky) Subtraction             |                             |
|                | Flux Calibration                         |                             |
|                | Further corrections                      |                             |
|                |                                          |                             |
|                |                                          |                             |



## Group Project Topic Candidates
See [here](http://nbviewer.jupyter.org/github/ysbach/AO_2017/blob/master/00_Group_Project_Topics.ipynb). This contains only the theory-group topics yet.

You can freely choose your own group project topics other than these list (it's even encouraged).



