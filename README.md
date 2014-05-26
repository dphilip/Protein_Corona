Protein_Corona
==============
Files are from:

Protein Corona Fingerprinting Predicts the Cell Association of Gold Nanoparticles, Supplementary Info. 
http://pubs.acs.org/doi/abs/10.1021/nn406018q


File format 
==============

* The file [MergetSheets.csv](https://github.com/ideaconsult/Protein_Corona/blob/master/MergedSheets.csv) contains all nanoparticles and related experiments from the above paper
* Format: Comma separated, with 12 header lines
* Parser: [loom-nm](https://github.com/vedina/loom/tree/master/loom-nm) package
* Import: The CSV format and parser are sufficiently generic to allow import into [AMBIT substances](http://apps.ideaconsult.net:8080/enanomapper/ui/uploadsubstance)

###File header

####Row	1 
	endpointcategory. One of :
GI_GENERAL_INFORM,PC_MELTING,PC_BOILING,PC_GRANULOMETRY,PC_VAPOUR,PC_PARTITION,PC_WATER_SOL,PC_SOL_ORGANIC,PC_NON_SATURATED_PH,PC_DISSOCIATION,AGGLOMERATION_AGGREGATION,CRYSTALLINE_PHASE,CRYSTALLITE_AND_GRAIN_SIZE,ASPECT_RATIO_SHAPE,SPECIFIC_SURFACE_AREA,ZETA_POTENTIAL,SURFACE_CHEMISTRY,DUSTINESS,POROSITY,POUR_DENSITY,PHOTOCATALYTIC_ACTIVITY,CATALYTIC_ACTIVITY,PC_UNKNOWN,TO_PHOTOTRANS_AIR,TO_HYDROLYSIS,TO_BIODEG_WATER_SCREEN,TO_BIODEG_WATER_SIM,EN_STABILITY_IN_SOIL,EN_BIOACCUMULATION,EN_BIOACCU_TERR,EN_ADSORPTION,EN_HENRY_LAW,EC_FISHTOX,EC_CHRONFISHTOX,EC_DAPHNIATOX,EC_CHRONDAPHNIATOX,EC_ALGAETOX,EC_BACTOX,EC_SEDIMENTDWELLINGTOX,EC_SOILDWELLINGTOX,EC_HONEYBEESTOX,EC_PLANTTOX,EC_SOIL_MICRO_TOX,TO_ACUTE_ORAL,TO_ACUTE_INHAL,TO_ACUTE_DERMAL,TO_SKIN_IRRITATION,TO_EYE_IRRITATION,TO_SENSITIZATION,TO_REPEATED_ORAL,TO_REPEATED_INHAL,TO_REPEATED_DERMAL,TO_GENETIC_IN_VITRO,TO_GENETIC_IN_VIVO,TO_CARCINOGENICITY,TO_REPRODUCTION,TO_DEVELOPMENTAL,UNKNOWN_TOXICITY,PROTEOMICS

####Row	2 
	protocol
####Row	3 
	guideline
####Row	4 
	type_of_study
####Row	5 
	type_of_method
####Row	6 
	data_gathering_instruments
####Row	7 
	endpoint
####Row	8 
	condition1
####Row	9 
	condition2
####Row	10 
	condition3
####Row	11 
	result
####Row	12 
	units

