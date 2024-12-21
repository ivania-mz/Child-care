# New Jersey childcare facilities and potential users
### Final project for Seminar in Public Informatics: Command Line GIS
### Presented by Ivania Martinez

#### Description of the data sets 
The following three maps are related to childcare facilities. The first map is made with the dataset with the Census ACS variable for the population under 5 years old, in which I had to aggregate B01001_003E: Male under 5 years and B01001_027E: Female under 5 years. I merged this data with the NGHIS block boundaries. For the second map, the process was similar, except that I used the variable B23025_004E to plot employment estimates and B23025_004M for their margins of error.
The third map is interactive, and it shows the names of the childcare facilities available in Middlesex. As all the previous maps focus on Middlesex, NJ, I filtered the locations for this only county. The three maps are related because childcare facilities are of importance for employed citizens specially when they have kids under 5 years old.
The only issue encountered in the data was while computing CVs for employment because when employment is zero, the division was not defined, so a filter was needed in the data pre processing.

<img src="Pop under 5 y.jpeg" alt="Description of the image" width="800">
<br>
<img src="middlesex county employed.jpeg" alt="Description of the image" width="800">
<br>
<iframe src="nj_msx_child_care.html" width="800" height="500"></iframe>
You can also explore [this map as its own web page here](nj_msx_child_care.html)
