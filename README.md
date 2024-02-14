# reds-recall-index-correlations
## Purpose of the Repository
Code repository to accompany "Genetic regulation of carnitine metabolism controls lipid damage repair and aging RBC hemolysis in vivo and in vitro."

The code is in the form of one R markdown file that, when executed, generates plots of recall versus index metabolite abundances.

## Assumptions
To use this code, the user will need the following skills:
- Basic proficiency cloning source code from GitHub,
- Basic proficiency executing rmarkdown scripts in RStudio
- Basic proficiency creating folder structures in macOS and/or Windows, depending on the platform which the user executes this script on.

## How to Use This Code
### Install R and RStudio (if needed)
If you have not installed R and Rstudio, please install them from the following sources:
- [Download R here](https://www.r-project.org/)
- [Downlaod RStudio here](https://posit.co/download/rstudio-desktop/)

### Install Packages
If you do not already have the following packages installed, please install them:

```
install.packages("tidyverse")
install.packages("here")
install.packages("readxl")
```

### Fork and Clone the Repository
Obtain this source code by cloning this repository. If you need help cloning this repository, [please consult GitHub's official documentation on cloning](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository). Alternatively, if you want to track changes to the code for your own purposes, please fork and clone this repository.

### Create Folder Structure
To keep input files, output files, and code separate this script uses the following folders for its related files. All paths are relative to the folder where you place this script after you clone it.

#### Input Folder and File
The Excel file needed by this script is not included in this repository, but has been released as supplemental data with the paper. The file is called `Recall vs Index correlations.xlsx`. Once you obtain this file, please create the following folder and place the Excel file into an `input/` folder within under the folder you have cloned this repository into.

### Output Folders
The script will produce two `.csv` files and a bunch of plots (in `.png` format) as outputs. Simularly to the input file, these files will be placed in an `output` folder underneath the folder into which this repository is cloned. Therefore, please create the following folders for the script to work:
```
output/
output/plots/
```

### Create an RStudio Project
Create an RStudio project associated with your cloned repository with the `input/`, `output/`, and `output/plots` folders in it.

### Execute the Script
Load `all_correlations.Rmd` in RStudio and select the "Session > Restart R and run all chunks" menu option.

### Observe the output
Find the plots of the correlations in `output/plots/` and the `.csv` files in `output/`.

## Publication Credits
### Title
"Genetic regulation of carnitine metabolism controls lipid damage repair and aging RBC hemolysis in vivo and in vitro"
### Authors
Travis Nemkov (University of Colorado Anschutz Medical Campus, United States) Alicia Key
(University of Colorado Anschutz Medical Campus, United States) Daniel Stephenson (University of
Colorado Denver - Anschutz Medical Campus, United States) Eric Earley (RTI International, United
States) Gregory Keele (RTI, United States) Ariel Hay (University of Virginia, United States) Pascal
Amireault (Institut IMAGINE INSERM U1163, France) Madeleine Casimir (Institut IMAGINE INSERM U1163,
France) Michaël Dussiot (Institut IMAGINE INSERM U1163, France) Monika Dzieciatkowska (University
of Colorado Denver - Anschutz Medical Campus, United States) Julie Reisz (University of Colorado
Denver, United States) Xutao Deng (Vitalant Research Institute, United States) Mars Stone (Vitalant
Research Institute, United States) Steven Kleinman (Kleinman Biomedical Research, Canada) Steven
Spitalnik (Columbia University, United States) Kirk Hansen (UC Denver, United States) Philip Norris
(Vitalant Research Institute, United States) Gary Churchill (Jackson Labs, United States) Michael
Busch (Vitalant Research Institute, United States) Nareg Roubinian (Kaiser Permanente Division of
Research, United States) Grier Page (RTI International, United States) James Zimring (University of
Virginia, United States) Arduino Arduini (CoreQuest Sagl, Switzerland) Angelo D'Alessandro
(University of Colorado Denver, United States)
