# Global-Proteomic-Analysis-of-murine-cerebral-microvessels

## Abstract
This code will process global proteomics data obtained from the analysis of murine cerebral microvessels isolated from animals administered intravenously with PBS, extracellular vesicles (EVS) secreted from human triple-negative breast cancer cells MDA-MB-231 (P-EVs) and their respective brainseeking cell line (Br-EVs)

## Installation R and R studio
To install  R and Rstudio, please click on this link https://rstudio-education.github.io/hopr/starting.html and follow the steps 

## Installation library packages 
To install the necessary library packages, run the following command in the Rstudio Console :

`
install.packages(readxl) ,
install.packages(pheatmap) ,
install.packages(corrplot) ,
install.packages(dplyr) ,
install.packages(ggplot2) ,
install.packages(factoextra) ,
install.packages(eulerr) ,
`
## Import raw data file on Rstudio

**Creating Data Sets**

To create the datasets `db`, `sb`, and `sb3` with all the raw data, follow these steps:

1. **Download the Excel file** containing the raw data to your computer.

2. **Import the dataset** into your R environment by copying the local path of the downloaded Excel file and replacing the placeholder text `COPY AND PASTE HERE THE FILE PATH` in the code below. Ensure to retain the quotation marks around the file path.

**Example:**
```R


# Import the data sets
sb3 <- read_excel("COPY AND PASTE HERE THE FILE PATH")
```

**Replace the placeholder text** in the example with the actual file path on your computer. For instance, if the file is located at `/Users/JOHNDOE/Desktop/Rstudio_MosesLab_SB_Raw numbers_08.17.23.xlsx`, your code should look like this:

```R
sb3 <- read_excel("/Users/JOHNDOE/Desktop/Rstudio_MosesLab_SB_Raw numbers_08.17.23.xlsx")
```

Make sure to use the correct paths for each dataset (`db`, `sb`, and `sb3`).

## Run the program 

One the files are imported click on RUN ALL on your top right corner of the terminal .

## License
This project is licensed under the MIT License. 

## Contact
If you have any question about the code, please contact [s.busatto.89@gmail.com](mailto:s.busatto.89@gmail.com)


