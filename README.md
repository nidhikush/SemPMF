# SemPMF
Implementation of the corrected mapping of DBpedia and MovieLens1M used in the paper 
"SemPMF: Semantic Inclusion by Probabilistic Matrix Factorization for Recommender System"
accepted for publication in PAAMS 2016 (http://www.paams.net/submission)

1. DB_MV(Mapping_code) has java code for finding the corrected mapping.
Beside this automated code, We have also done manual check for it. The corrected reasons after manual check is given in "Correction_Reasons" 
file. Two files DB.txt and Org_DB_withID.txt have been used intially and then mapping was found using Levenshtein Distance.

2. Original mapping was in the file "DBpedia+MovieLens10M_Mapping" after applying the code and manual check updated and corrected mapping is in 
"Updated_DBpedia+MovieLens1M_Mapping" file.

3. After corrected mapping was done, this file has been used for feature generation using the SPARQL querying mentioned in 
"SPARQL_Queries" file.

4. code for generation of Item-Property files are given in "Matrix.zip" folder.

5. Modification in SemPMF code is in progress and will be available soon.
