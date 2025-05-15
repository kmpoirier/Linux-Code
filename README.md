# Linux-Code

## poirier_fasta_script.sh:
- this bash file and bigdata.fna.gz file should be located within a new folder called RAW_DATA
- splits a fasta file into 50,000 sequences, checks how many sequences are in the fasta file and outputs the number into a new file called log.txt. Then every file in the directory is outputted and makes a new file for each spitted sequences. Lastly, all the instances are counted for each file and then all files are moved to P_DATA 

## poirier_project_bash.sh:
- this bash file and primer.csv file should be located in the same directory
- makes a new directory called RAW_DATA and copies all .fna files made by the poirier_fasta_script.sh and the primer.csv into RAW_DATA. It then makes 2 new directories, P_DATA and RESULTS, adds all directories of interest into your PATH and outputs all contents to a readme.txt file.
- The poirier_project_bash.sh should be run first before poirier_fasta_script.sh becasue it makes the correct directories and moves the files of interest

## poirier_backup.sh:
- copies all files in a directory to a file called BACK-UP files 


