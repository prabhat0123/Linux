# Basic Commands 

## Locate Command 

## Q.  How to locate all conf file
        locate *.conf
        
## Q.  How to locate all conf file, in case insensitive way
       locate -i *.conf

## Q.  How to locate all conf file, in case insensitive way and limit output
       locate --limit 3 -i *.conf


## Q.  How to get info about locate db
       locate -S

## Q.  How to get all conf file with existing check
       locate -e *.conf

## Q.  How to update locate db
       sudo updatedb
