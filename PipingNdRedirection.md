# PipingNdRedirection

## Q. How many ways in total are there to get data into and out of a command?
     4

## Q. What are Data Streams ?
     Standard output , Standard Input , Standard error

## Q. What is Standard Output Connected to By Default ?
     Terminal

## Q. What is Standard Error Connected to By Default?
     Terminal

## Q. What is the Standard Input Data Stream Connected to by default?
     Keyboard

## Q. What are number associated with Standard output , Standard Input , Standard error ?
     Standard Input (0) Standard output (1)  Standard error (2)  

## Q. Cat command to write to file 
     cat > output.txt 
     This will delete everything and rewrite to file

## Q. Cat command to write to file 
     cat >> output.txt 
     This will preserve content of file

## Q. Cat command to read from file and output to terminal
     cat < input.txt 

## Q. Cat command to read from file(input.txt) and output(output.txt) to file and error(error.txt)  
     cat < input.txt 1>> output.txt 2>>error.txt

## Q. Data pipeing example with date and cut command, to write day name to dat.txt got from date command
     date | cut -d " "  -f 1 > date.txt

## Q. How to send output to two directions (Tee Command)?
     date | tee fulldate.txt | cut -d " "  -f 1 > date.txt

## Q. How to pipe to command that don't accept standard input
     cat fileName.txt | xargs rm
     date | xargs echo

## Q. What is use of .bash_aliases ?
     To store aliases

## Q. How to create aliases
     alias c='clear'

## Q. Create alias with xargs
     alias calmag='xargs cal -A 1 -B 1'
     echo 12 2019 | calmag
