# Proof of Concept for Spoken Natural Language Descriptions of Phenotypes for Association Genetics Applications

Please visit: https://dill-picl.org/

## ABSTRACT

Imagine walking through a field and saying aloud what you see, then using that audio file to conduct an association study. Advancements in Natural Language Processing (NLP) have allowed for processing large volumes of descriptive data. To make these advancements applicable for biologists interested in better understanding phenotypes and traits, we are developing methods to collect and process in-field descriptions of maize using recordings of spoken phenotype descriptions. We planted the Wisconsin Diversity panel in Boone, Iowa (summer of 2021). Nine undergraduate student workers recorded spoken descriptions of the Wisconsin Diversity panel lines in the field. We instructed the students to describe certain plant parts and other miscellaneous attributes using their own words. For comparative purposes, we also collected numerically scored phenotypes using traditional data collection techniques and images of each line. Our pipeline for processing the hundreds of hours of spoken descriptive data starts with the Amazon Web Services (AWS) cost-effective transcription service Transcribe. We can compute on the text descriptions of plants produced by Transcribe using NLP tools, which enables us to generate the input for tools that are commonly used by the maize research community to perform Genome-Wide Association Studies (GWAS). The results of the association studies completed using spoken data are then compared to published associations. Generating spoken descriptive datasets and protocols for demonstrating biologically relevant approaches for these data are anticipated to enable the maize research community to use innovations in language processing for in-field phenotyping methods.


## METHODS

### STEP 1: SPEECH-TO-TEXT
<p align="center">
<img src="https://github.com/CFYanarella/Spoken_Natural_Language_Descriptions_of_Phenotypes_for_Association_Genetics_Applications/blob/main/step_1.png" width=60% height=60%>
</p>

### STEP 2: TEXT-TO-SIMILARITY SCORE
<p align="center">
<img src="https://github.com/CFYanarella/Spoken_Natural_Language_Descriptions_of_Phenotypes_for_Association_Genetics_Applications/blob/main/step_2.png" width=90% height=90%>
</p>

### STEP 3: EXAMPLE OF GWAS RESULTS
<p align="center">
<img src="https://github.com/CFYanarella/Spoken_Natural_Language_Descriptions_of_Phenotypes_for_Association_Genetics_Applications/blob/main/step_3.png" width=60% height=60%>
</p>

## AWS PROCESSING & OBSERVATION SUMMARIES


<p align="center">
<img src="https://github.com/CFYanarella/Spoken_Natural_Language_Descriptions_of_Phenotypes_for_Association_Genetics_Applications/blob/main/aws_processing_observation_summaries.png" width=90% height=90%>
</p>



## SIGNIFICANCE

* We are developing methods for recording spoken descriptions of plants in the field
* We aim to use natural language processing to determine scores for traits to perform association studies for the Wisconsin Diversity panel


## NEXT STEPS

* Perform Method 1 and Method 2 for text-to- similarity score determination (STEP 2: TEXT-TO- SIMILARITY SCORE described above)
* Perform GWAS (STEP 3: EXAMPLE OF GWAS RESULTS described above) and compare to previous association studies using the Wisconsin Diversity panel


## ACKNOWLEDGMENTS 

**2021 Student Workers:** Delta, Golf, Kilo, Lima, Mike, Quebec, Victor, Yankee, & Zulu 

**2021 WiDiv Field:** Craig Abel, Jode Edwards, John Golden, Dior Kelley, Miriam Lopez, Justin Walley, & Marna Yandeau-Nelson

**Helpful Discussions:** Nick Lauter, Brian Dilkes, Rajdeep Khangura, & Amanpreet Kaur

**Researchers Who Worked on Generating Wisconsin Diversity Panel Genotype Data:** (2019) M. Mazaheri, M. Heckwolf, B. Vaillancourt, J. L. Gage,
B. Burdo, S. Heckwolf, K. Barry, A. Lipzen, C. B. Ribeiro, T. J. Y. Kono, H. F. Kaeppler, E. P. Spalding, C. N. Hirsch, C. R. Buell, N. de Leon, & S. M. Kaeppler (2022) R. Mural, G. Sun, M. Grzybowski, M. C. Tross, H. Jin, C. Smith, L. Newton, A. M. Thompson, B. Sigmon, & J. C. Schnable



## AUTHORS
Colleen F. Yanarella<sup>1 2</sup>, 

Leila Fattel<sup>2 3</sup>, 

Ásrún Ý. Kristmundsdóttir<sup>4</sup>, &

Carolyn J. Lawrence-Dill<sup>1 2 3 4 5</sup>


## AUTHOR AFFILIATIONS

<sup>1</sup> Interdepartmental Bioinformatics and Computational Biology, Iowa State University, Ames, IA 

<sup>2</sup> Department of Agronomy, Iowa State University, Ames, IA

<sup>3</sup>  Interdepartmental Genetics and Genomics, Iowa State University, Ames, IA

<sup>4</sup>  College of Agriculture and Life Sciences, Iowa State University, Ames, IA

<sup>5</sup>  Department of Genetics, Development, and Cell Biology, Iowa State University, Ames, IA



## FUNDING
* National Science Foundation (NSF), 
* United States Department of Agriculture (USDA), 
* Iowa State University Plant Sciences Institute, 
* P3 NSF Research Traineeship DGE#1545463, 
* AIIRA NSF & USDA NIFA Award #2021-67021-35329, &
* IOW04714 Hatch Funding to Iowa State University

<p align="left">
<img src="https://github.com/CFYanarella/Spoken_Natural_Language_Descriptions_of_Phenotypes_for_Association_Genetics_Applications/blob/main/P3_logo.png" width=20% height=20%><img src="https://github.com/CFYanarella/Spoken_Natural_Language_Descriptions_of_Phenotypes_for_Association_Genetics_Applications/blob/main/AIIRA_logo.png" width=5% height=5%>
</p>




## FULL POSTER

<p align="center">
<img src="https://github.com/CFYanarella/Spoken_Natural_Language_Descriptions_of_Phenotypes_for_Association_Genetics_Applications/blob/main/CFY_23_MM_poster_final.png" width=100% height=100%>
</p>




## REFERENCES

Amazon Transcribe Developer Guide. (n.d.). https://docs.aws.amazon.com/pdfs/transcribe/latest/dg/transcribe-dg.pdf#what-is

Braun, I. R., Yanarella, C. F., & Lawrence-Dill, C. J. (2020). Computing on Phenotypic Descriptions for Candidate Gene Discovery and Crop
Improvement. Plant Phenomics, 2020, 1–4. https://doi.org/10.34133/2020/1963251

Mazaheri, M., Heckwolf, M., Vaillancourt, B., Gage, J. L., Burdo, B., Heckwolf, S., Barry, K., Lipzen, A., Ribeiro, C. B., Kono, T. J. Y., Kaeppler, H. F.,
Spalding, E. P., Hirsch, C. N., Robin Buell, C., de Leon, N., & Kaeppler, S. M. (2019). Genome-wide association analysis of stalk biomass and
anatomical traits in maize. BMC Plant Biology, 19(1). https://doi.org/10.1186/s12870-019-1653-x

Mazaheri, M., Heckwolf, M., Vaillancourt, B., Gage, J. L., Burdo, B., Heckwolf, S., Barry, K., Lipzen, A., Ribeiro, C. B., Kono, T. J. Y, Kaeppler, H. F.,
Spalding, E. P., Hirsch, C. N., Buell, C. R., de Leon, N., & Kaeppler, S. M. (2019). Data from: Genome-wide association analysis of stalk biomass
and anatomical traits in maize. https://doi.org/10.5061/dryad.n0m260p

Montani, I., Honnibal, M., Honnibal, M., Sofie Van Landeghem, Boyd, A., Peters, H., Paul O'Leary McCann, geovedi, jim, O’Regan, J., Maxim
Samsonov, Orosz, G., Daniël de Kok, Blättermann, M., Duygu Altinok, Søren Lind Kristiansen, Kannan, M., Mitsch, R., Raphaël Bournhonesque, Edward, & Miranda, L. (2023). explosion/spaCy: v3.5.1: spancat for multi-class labeling, fixes for textcat+transformers and more. https://doi.org/10.5281/zenodo.7715077

Mural, R. V., Sun, G., Grzybowski, M., Tross, M. C., Jin, H., Smith, C., Newton, L., Andorf, C. M., Woodhouse, M. R., Thompson, A. M., Sigmon, B., & Schnable, J. C. (2022). Association mapping across a multitude of traits collected in diverse environments in maize. GigaScience, 11. https://doi.org/10.1093/gigascience/giac080

Mural, R., Sun, G., Grzybowski, M., Tross, M. C., Jin, H., Smith, C., Newton, L., Thompson, A. M., Sigmon, B., & Schnable, J. C. (2022). Maize_WiDiv_SAM_1051Genotype.vcf.gz genotype file. https://doi.org/10.6084/m9.figshare.19175888.v1


