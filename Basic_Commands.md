# Basic Commands

## Wild cards

```
* -> anything

? -> anything for one place

[ ] -> anything for one place from the provided pattern eg: ls file[0-9abc].txt 
```

# Navigation

## Q.  How to list files in directory 
      ls -lh
## Q. How to list hidden files and folder on linux
    ls -lha
## Q.  List contents of multiple folders : 
    ls folder1 folder2 folder3
## Q.  What is use of file command.
     file command give details about the file . Its syntex is : file  filename

# Create file/folder

## Q. how to create directory inside directory which don't exist. 
      mkdir -p /bla/bla/thisfolder

## Q. write a command to create directory with folder name as  jan_2010 to dec_2022
      mkdir {jan,fab,mar,april,may,jun,jul,aug,sep,oct,nov,dec}_{2010..2022}

## Q. write a command to create 100 files named as file1.txt to file100.txt in above folders
      mkdir {jan,fab,mar,april,may,jun,jul,aug,sep,oct,nov,dec}_{2010..2022}/file{1..100}.txt

# Delete File
## Q. How to delete multiple files residing at different locations
     rm folder1/file1.txt file2.txt folder3/folder2/file.txt

## Q. How to delete directories. 
    rm -r derectoryName
