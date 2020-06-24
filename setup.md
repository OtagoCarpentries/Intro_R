# Software Install Instructions


Please try and have both R and RStudio installed on your computer prior to the workshop. 

For any assistance installing please email carpentries@otago.ac.nz


## R  
Latest Release, Arbor Day, R-4.0.1

go to [Download R](https://cran.stat.auckland.ac.nz/) at the Auckland CRAN mirror site.
Click on the Download R for "YOUR SYSTEM" link at the top of the page.
Click on the file containing the latest version of R under "Files."

For **Mac** it is the .pkg file

For **Windows** go to base then the Download at the top

**Linux** have various options and the best is to directly install from the command line. Such as

```
   sudo apt-get update
   sudo apt-get install r-base
```

## RStudio  
Before installing RStudio you need to have installed R 

1. Go to [https://rstudio.com/products/rstudio/download/#download](https://rstudio.com/products/rstudio/download/#download) 
2. Click on the version installers recommended for your system, Windows, Mac and Linux are all supported.

after install, R-Studio should recognise your default R installation, if not you may have to direct R-Studio where to go.

[YouTube](https://www.youtube.com/watch?v=9-RrkJQQYqY) has a number of videos to help show the steps. This one is for Windows 10

Tidyverse
If you are attending Introduction to R this will be covered during the lesson.

Otherwise, make sure you have the latest version of R installed

Open up RStudio and in the console type

```install.packages('tidyverse')```  
Select the mirror to download from and wait for the install to complete. After install type 

```library(tidyverse)```

 and your output should look similar to this.    

```
> library(tidyverse)
── Attaching packages ────────────────────────────────────────────────────────────────────────────────────────────────────────── tidyverse 1.3.0 ──
✓ ggplot2 3.3.0     ✓ purrr   0.3.4
✓ tibble  3.0.1     ✓ dplyr   0.8.5
✓ tidyr   1.0.3     ✓ stringr 1.4.0
✓ readr   1.3.1     ✓ forcats 0.5.0
── Conflicts ───────────────────────────────────────────────────────────────────────────────────────────────────────────── tidyverse_conflicts() ──
x dplyr::filter()  masks stats::filter()
x purrr::is_null() masks testthat::is_null()
x dplyr::lag()     masks stats::lag()
x dplyr::matches() masks tidyr::matches(), testthat::matches()
```
If you get the following:
```
Error in library(tidyverse) : there is no package called ‘tidyverse’
```

If it hasn't installed correctly, please e-mail for assitance.

