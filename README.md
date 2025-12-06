# Walking Towards Longer Sleep
Data Exploration 5101 - Fall 2025 Final Project source code

## Abstract
This study investigates the correlation between daily physical activity and length of nightly sleep using personal health data sourced from my Apple Health XML export. Operating under the alternate hypothesis that increased activity promotes greater sleep, the methodology involved cleaning step counts (using only Apple Watch data) and defining a night's sleep duration. Three correlation tests were run, comparing steps, physical activity minutes, and intensive activity (excluding walking) against sleep duration. The results found no significant relationship between daily activity and nightly sleep duration (p-values ranged from 0.5432 to 0.6938). The study concluded that physical activity alone does not meaningfully predict the amount of sleep experienced in a night. A key limitation was the single-participant sample size, suggesting future studies should involve more participants and/or examine weekly trends.

The original XML export was 2.47 GB and too large for GitHub, so I processed the XML into smaller CSV files in the following R file : FinalProject_Dagostino_working_data

The exported CSV files can be found in the /data directory. Two of the data files have been zipped up to file wihtin the GitHub upload limits as they exceeding 100 MB. So Please unzip them if you with to use the data.

