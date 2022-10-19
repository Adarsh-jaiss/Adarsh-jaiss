- ``` echo``` command prints the text.
      
      Ex :  echo "Welcome to Unix
      
      output -  Welcome to Unix
      
      ex :2 - witing text in a file using echo 
      
      synatx : echo "Hello World!" > myfile.txt 

      
 
 - ``` pwd``` - print working directory.
 - ``` cat``` - prints the content of the file.
              - concantenate two files
              
              
            synatx (reading the content of the file) : cat myfile.txt
            
            syantx (concantenating two files) : cat anotherfile.txt >> myfile.txt
            
      
- ```man``` (manual) - prints the information about the commands
                  
               ex:   syantax : man cat
                            
                            man pwd
 
                
- ```ls``` - Listing Directory Contents
            
            ls    = A regular sorted list of all the files in a directory
            ls -l = A more sorted list with permissions.
            ls -a = shows hidden files as well
            ls -m = shows a comma seperated directory
            ls -R = shows included file and thier contents.
            
  >**Note**
  >The -R argument stands for recursive. This is a very important argument when you are dealing with directories because you can have many nested directories and you may want your commands to apply to them all.

- ``` cd``` - changing directory
            
            ex: syantx : cd directory-name 
                         cd test
           
- ``` mkdir``` - making a new directory

            synatx : mkdir test
            check : ls -a
        
- ``` touch``` - for creating a new file

            syntax : touch newfile.txt
            
- ```rmdir``` - removing empty directory

            syntax : rmdir test
            
- ```mv``` - moving a file or renaming a file

            syntax : mv filename destination
            ex : mv *.c code
            
            rename : mv readme.txt README.txt
            
- ```cp``` - copy files and directory's

            syantx : cp file.txt FILE.txt
                     cp -R code backup
                     tree
                     
                     here: The backup directory was created, and the contents of the code directory was copied to the backup directory.
                     
               
 - ```stat``` -  Displays file status using            
                  
                  syantx    : stat file destination/filename
                  syantx ex : stat workspace/code/src/average.c

- ```file``` - Determines file type
                  
                  syantx   : file destination
                  syantx ex: file code/src/average.c
                  
- ``` grep``` - searches for pattern in a file 

                  syantx : grep option pattern file directory
               ex syantx : grep -w printf code/src/*.c
