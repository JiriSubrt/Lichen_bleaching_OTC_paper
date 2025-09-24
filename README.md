# Lichen_bleaching_OTC
Data and code for the article: Šubrt et al. (submitted to Functional Ecology). Lichen bleaching as a response to long-term experimental warming in the High Arctic.

# Authors
Jiří Šubrt, Mariana García Criado, Kevin K. Newsham, Claudia Colesie
Contact: Jiří Šubrt, subrt.jirka1@gmail.com

# Data use guidelines
Data output from this manuscript are publicly available using a Creative Commons Attribution 4.0 International copyright (see license.txt). Data are fully public but should be referenced by citing the paper. 

# Data
This folder includes all data needed to reproduce the analysis. The folder contains the following datasets, ordered by the order of analyses in the manuscript. They can be ran independently of each other:
1. microclimate: contains folder iButtons_OTCs (RH and VPD data), TOMST folder (data from TOMST loggers for temperature), and a file light_final.csv (contains data from light meter meaurements from the OTCs)
2. LRCs - contains two files, lrc_data.csv (data used to construct light response curves - Figures S3 and S4)
3. dessication curves - contains file correct_wc_cleaned.csv (data used to create desiccation curves - figure S1)
4. temperature_response - contains file np_dr_gp_raw_long.csv (data used to model and bootstrap temperature response - Figure 4)
5. cue - contains file np_dr_gp_corresponding.csv (data used to calculate Carbon Use Efficiency - Figure 5) 
6. traits - contains two files, algal_layer.csv and chlorophyll.csv (used to calculate chlorophyll content and photobiont to mycobiont ratio)

# Scripts
This folder contains all the analyses for this manuscript, they are split into following scripts. They can be ran independently from each other. 
1. abiotic_analysis.R - all microclimate measurements
2. map.R - code to create map in Figure 1a
3. light_responses.R - Light response curves and Light Saturation Points
4. desiccation_curves.R
5. temp_curves_models.R
6. traits.R - chlorophyll content and photobiont to mycobiont ratio calculations

# Outcomes
This folder contains figures that were used for the manuscript.

# Software requirements
R version 4.2.0. or greater.

