related
=======

**This was updated on 10-June-2022, and should now be compatible with R v4.2 and higher. Installation instructions for Windows and Linux can be found in the tutorial. However, such instructions have changed for the Mac, so please see below for updated instructions on a Mac.**

Here you can download files for the related package.

GenotypeData.txt = example genotype file that can be used for testing.

simrel.txt = example genotype file for testing group relatedness function.

related_1.0.tar.gz = source code that can be downloaded and compiled on Windows, Linux, and Mac operating systems


*******************************
Installation
*******************************
Installation instructions for Windows and Linux can be found in the Tutorial.

For a Mac, please follow the steps below.
1. Install XCode command line functionality:
   - Open the Terminal App and type `sudo xcode-select --install`
2. Install/update [XQuartz](https://www.xquartz.org)
3. Install `gfortran` (required for compiling):
    - Appropriate versions can be downloaded [here](https://mac.r-project.org/tools/).
4. Tell your computer the appropriate path to `gfortran`
    - In your Terminal App type `export PATH=$PATH:/usr/local/gfortran/bin`
5. Update to the latest versions of [R](https://www.r-project.org) and [RStudio](https://www.rstudio.com) (ensure that you are installing a version compatible with your version of Mac OS!).
6. Install the `devtools` package
    - From RStudio, go to Tools -> Install Packages
    - Under the **Install From** option, select `Repository (CRAN)`
    - In the **Packages** window, type `devtools`
    - Ensure that the **Install Dependencies** box is checked
    - Click **Install**
6. Install the `ggplot2` package
    - From RStudio, go to Tools -> Install Packages
    - Under the **Install From** option, select `Repository (CRAN)`
    - In the **Packages** window, type `ggplot2`
    - Ensure that the **Install Dependencies** box is checked
    - Click **Install**
7. Download the three `.dylib` files:
    - `libgcc_s.1.dylib`
    - `libgfortran.3.dylib`
    - `libquadmath.0.dylib`
8. Place these three files in the `/usr/local/lib/` directory
7. Install `related`:
    - Download the `.tar.gz` file
    - From RStudio, go to Tools -> Install Packages
    - Under the **Install From** option, select `Package Archive File (.tgz; .tar.gz)`
    - Navigate to the location of the `.tar.gz` file and select it
    - Click **Install**

You may see a number of warnings, but no errors. These warnings are OK, and can be safely ignored.

Please let me know if you run into problems with this.

**Note that the versions of R and gfortran that you download need to be compatible with your computer. The main difference now is that older Macs will have an Intel processor, whereas newer Macs will have the M1 (or later) processors. These require different versions of these programs.**
