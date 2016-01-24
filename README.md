Protein_Corona
==============
Files are from:

Protein Corona Fingerprinting Predicts the Cell Association of Gold Nanoparticles, Supplementary Info. 
http://pubs.acs.org/doi/abs/10.1021/nn406018q


File format 
==============

### Note: this 12-line header parser is deprecated in favour of more flexible Excel parser https://github.com/enanomapper/nmdataparser and [XLSX+JSON](https://apps.ideaconsult.net/enanomapper/ui/uploadsubstance1) upload

* The file [MergetSheets.csv](https://github.com/ideaconsult/Protein_Corona/blob/master/MergedSheets.csv) contains all nanoparticles and related experiments from the above paper
* Format: Comma separated, with 12 header lines
* Parser: [loom-nm](https://github.com/vedina/loom/tree/master/loom-nm) package
* Import: The CSV format and parser are sufficiently generic to allow import into [AMBIT substances](https://apps.ideaconsult.net/enanomapper/ui/uploadsubstance)

###File header
####Row	1 
endpointcategory. Specifies an endpoint category. Should be one of [this list](endpointcategory.md).

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


Examples
-----

* [Nano particles, experiments](example1.md)
* [Chemicals, experiments](example2.md)


API to use for upload to AMBIT
----

 See [Substance resource](https://github.com/ideaconsult/examples-ambit/blob/master/ambit-json-docs/substance.md)

