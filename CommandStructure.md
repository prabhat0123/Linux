# Linux Commnad structure 

## Q.  How to know path of folder where command is "which commandName"
 ``` which echo ```

## Q: How to get manual of the command  
 ``` man -k commandNmae eg: man -k which  ```

## Q: How to open manual page: 
    man sectionNum commandName eg : man 1  which

## Q: what does symbols refer to in manual pages
	1) [] -> optional 
	2) . . . -> can have many 
	3) <> -> Mandatory 
	4)[-a | -f] -> optional but one of them is mandatory
	eg: which [ -a | -b ] <something> ...
