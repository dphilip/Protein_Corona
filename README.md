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

<table>
<tr><td>GI_GENERAL_INFORM</td></tr><tr><td>PC_MELTING</td></tr><tr><td>PC_BOILING</td></tr><tr><td>PC_GRANULOMETRY</td></tr><tr><td>PC_VAPOUR</td></tr><tr><td>PC_PARTITION</td></tr><tr><td>PC_WATER_SOL</td></tr><tr><td>PC_SOL_ORGANIC</td></tr><tr><td>PC_NON_SATURATED_PH</td></tr><tr><td>PC_DISSOCIATION</td></tr><tr><td>AGGLOMERATION_AGGREGATION</td></tr><tr><td>CRYSTALLINE_PHASE</td></tr><tr><td>CRYSTALLITE_AND_GRAIN_SIZE</td></tr><tr><td>ASPECT_RATIO_SHAPE</td></tr><tr><td>SPECIFIC_SURFACE_AREA</td></tr><tr><td>ZETA_POTENTIAL</td></tr><tr><td>SURFACE_CHEMISTRY</td></tr><tr><td>DUSTINESS</td></tr><tr><td>POROSITY</td></tr><tr><td>POUR_DENSITY</td></tr><tr><td>PHOTOCATALYTIC_ACTIVITY</td></tr><tr><td>CATALYTIC_ACTIVITY</td></tr><tr><td>PC_UNKNOWN</td></tr><tr><td>TO_PHOTOTRANS_AIR</td></tr><tr><td>TO_HYDROLYSIS</td></tr><tr><td>TO_BIODEG_WATER_SCREEN</td></tr><tr><td>TO_BIODEG_WATER_SIM</td></tr><tr><td>EN_STABILITY_IN_SOIL</td></tr><tr><td>EN_BIOACCUMULATION</td></tr><tr><td>EN_BIOACCU_TERR</td></tr><tr><td>EN_ADSORPTION</td></tr><tr><td>EN_HENRY_LAW</td></tr><tr><td>EC_FISHTOX</td></tr><tr><td>EC_CHRONFISHTOX</td></tr><tr><td>EC_DAPHNIATOX</td></tr><tr><td>EC_CHRONDAPHNIATOX</td></tr><tr><td>EC_ALGAETOX</td></tr><tr><td>EC_BACTOX</td></tr><tr><td>EC_SEDIMENTDWELLINGTOX</td></tr><tr><td>EC_SOILDWELLINGTOX</td></tr><tr><td>EC_HONEYBEESTOX</td></tr><tr><td>EC_PLANTTOX</td></tr><tr><td>EC_SOIL_MICRO_TOX</td></tr><tr><td>TO_ACUTE_ORAL</td></tr><tr><td>TO_ACUTE_INHAL</td></tr><tr><td>TO_ACUTE_DERMAL</td></tr><tr><td>TO_SKIN_IRRITATION</td></tr><tr><td>TO_EYE_IRRITATION</td></tr><tr><td>TO_SENSITIZATION</td></tr><tr><td>TO_REPEATED_ORAL</td></tr><tr><td>TO_REPEATED_INHAL</td></tr><tr><td>TO_REPEATED_DERMAL</td></tr><tr><td>TO_GENETIC_IN_VITRO</td></tr><tr><td>TO_GENETIC_IN_VIVO</td></tr><tr><td>TO_CARCINOGENICITY</td></tr><tr><td>TO_REPRODUCTION</td></tr><tr><td>TO_DEVELOPMENTAL</td></tr><tr><td>UNKNOWN_TOXICITY</td></tr><tr><td>PROTEOMICS</td></tr></table>
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


### Example

<table>
<tr>
<td>EndpointCategory</td><td>Core composition</td><td>Surface modifier</td><td>External Identifier</td><td>PC_GRANULOMETRY</td><td>PC_GRANULOMETRY</td><td>ZETA_POTENTIAL</td><td>ZETA_POTENTIAL</td>
</tr><tr>
<td>Protocol</td><td></td><td></td><td></td><td>TEM</td><td>TEM</td><td>DLS</td><td>DLS</td>
</tr><tr>
<td>Guideline</td><td></td><td></td><td></td><td>doi: 10.1021/nn406018q</td><td>doi: 10.1021/nn406018q</td><td>doi: 10.1021/nn406018q</td><td>doi: 10.1021/nn406018q</td>
</tr><tr>
<td>type_of_study</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td>
</tr><tr>
<td>type_of_method</td><td></td><td></td><td></td><td>TEM</td><td>TEM</td><td>DLS</td><td>DLS</td>
</tr><tr>
<td>data_gathering_instruments</td><td>Description</td><td></td><td></td><td>Tecnai 20 (FEI) microscope;Tecnai 20 (FEI) microscope;AMT 16000 camera</td><td>Tecnai 20 (FEI) microscope;Tecnai 20 (FEI) microscope;AMT 16000 camera</td><td>ZetaSizer Nano ZS (Malvern Instruments)</td><td>ZetaSizer Nano ZS (Malvern Instruments)</td>
</tr><tr>
<td>Endpoint</td><td>Element</td><td>Abbreviated</td><td>Classification</td><td>Core size</td><td>Core size</td><td>ZETA POTENTIAL</td><td>ZETA POTENTIAL</td>
</tr><tr>
<td>Cell</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td>
</tr><tr>
<td>MEDIUM</td><td></td><td></td><td></td><td></td><td></td><td>Human serum</td><td>Human serum</td>
</tr><tr>
<td>Condition</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td>
</tr><tr>
<td>Designation</td><td></td><td></td><td></td><td>Mean</td><td>SD</td><td>Mean</td><td>SD</td>
</tr><tr>
<td>Units</td><td></td><td></td><td></td><td>nm</td><td>nm</td><td>mV</td><td>nm</td>
</tr><tr>
<td>G15.AC</td><td>[Au]</td><td>AC</td><td>Anionic</td><td>14.9</td><td>1.2</td><td>-21.78</td><td>6.81</td>
</tr><tr>
<td>G15.AHT</td><td>[Au]</td><td>AHT</td><td>Cationic</td><td>14.9</td><td>1.2</td><td>15.22</td><td>3.05</td>
</tr><tr>
<td>G15.Ala-SH</td><td>[Au]</td><td>Ala-SH</td><td>Anionic</td><td>14.9</td><td>1.2</td><td>-24.08</td><td>0.68</td>
</tr><tr>
<td>G15.Asn-SH</td><td>[Au]</td><td>Asn-SH</td><td>Anionic</td><td>14.9</td><td>1.2</td><td>-20.27</td><td>6.1</td>
</tr><tr>
<td>G15.AUT</td><td>[Au]</td><td>AUT</td><td>Cationic</td><td></td><td></td><td>16.35</td><td>2.26</td>
</table>
