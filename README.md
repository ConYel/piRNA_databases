# Comparing existing piRNA databases 
 
In this project we compare piRNA databases that have been updated   
recently so as understand the main differences and how can be utilised.  

Databases in comparison are:  
piRBase v2.0 http://www.regulatoryrna.org/database/piRNA/  
piRNAdb v1.8 https://www.pirnadb.org/  
piRNA clusterDB https://www.smallrnagroup.uni-mainz.de/piCdb/

To reproduce the analysis you need to have installed docker.   
For more information about that please follow the information here: https://www.docker.com/get-started   

To start the analysis you have to download the docker :
'docker pull congelos/rocker_tidyverse_plus_de_pckages'   
and then run:   
'docker run --rm -ti -v "$(pwd)":/home/my_data docker pull congelos/rocker_tidyverse_plus_de_pckages'  
'git clone https://github.com/ConYel/piRNA_databases.git'  
and start the analysis
