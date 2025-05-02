# Linux-Code

poirier_backup.sh is a bash script file that makes a new BACK-UP directory and then copy all files from a specific directory and then outputs information about each file. 

poirier_fasta_script.sh and the bigdata.fna.gz file should be located within a new folder called RAW_DATA. This bash script splits a fasta file into 50,000 sequences, checks how many sequences are in the fasta file and outputs the number into a new file called log.txt. Then every file in the directory is outputed and makes a new file for each splitted sequences. Then, all the instances are counted for each file and then all files are moved to P_DATA. 

poirier_project_bash.sh and the primer.csv file should be located in the same directory. This script makes a new directory called RAW_DATA and copies all .fna files made by the poirier_fasta_script.sh and the primer.csv into RAW_DATA. It then makes 2 new directories, P_DATA and RESULTS, adds all directories of interest into your PATH and outputs all contents to a readme.txt file. 
