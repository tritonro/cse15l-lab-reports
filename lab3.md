# Lab Report 3
by Rosario Ortiz

## Alternate Uses for Grep 

### -r 
This option allows you to search for a pattern in all files in a directory (and any subdirectories) recursively, and print any lines that contain the pattern.

example 1
```
$ grep -r biophysics
./technical/plos/journal.pbio.0020067.txt:        College London's physics department and director of a biophysics research unit sponsored by
./technical/plos/journal.pbio.0020012.txt:        Kenyon, professor of biochemistry and biophysics at the University of California at San
./technical/biomed/gb-2001-2-4-research0012.txt:          expression and membrane biophysics
./technical/biomed/gb-2001-2-4-research0012.txt:        biophysics of ion transport. The value of such
./technical/biomed/gb-2001-3-1-research0001.txt:        understanding of the biophysics of water flow across plant
```
 In this example, grep recursively searches every directory in the working directory (docsearch), and returns all the files that contain the given string. Below each file path, grep -r prints the line that contains the string being searched for. 
example 2
```
oi ello
```
 a sentence or two about what it’s doing and why it’s useful.
 
 Citation + URL 
 
### -l 
This option allows you to search for a pattern in all files in a directory, but print out the filenames containing it rather than the lines themselves. 

example 1 
```
$  grep -l biophysics
# nothing is returned 
```
 a sentence or two about what it’s doing and why it’s useful.
example 2
```
oi ello
```
 a sentence or two about what it’s doing and why it’s useful.
  Citation + URL 

### -c
This option counts the number of lines that match a pattern and prints this number out. 

example 1 
```
oi ello
```
 a sentence or two about what it’s doing and why it’s useful.
 
example 2
```
oi ello
```
 a sentence or two about what it’s doing and why it’s useful.
  Citation + URL 
 
### --include="*.fileType"

This will search for the given pattern in all files with the fiven file extension in the current directory and print out any lines that contain the pattern. The --include option is used to specify the file type to search in.


## ChatGPT 
 The prompts I gave ChatGPT were:
 - Hi ChatGPT ! Can you give me four alternate ways to use grep in terminal ? 
 - Thanks ChatGPT ! Do you have any more ?
 
Its outputs, respectively, were:
- Sure, here are four different ways to use grep in the terminal:

  Search for a pattern in a single file:
    ```
    perl
    Copy code
    grep "pattern" filename.txt
    This will search for the given pattern in the file filename.txt and print out any lines that contain the pattern. 
    ```
    Search for a pattern in all files in a directory:
    ```
    perl
    Copy code
    grep "pattern" *
    This will search for the given pattern in all files in the current directory and print out any lines that contain the pattern.
    ```

   Search for a pattern in all files in a directory recursively:

    perl
    Copy code
    grep -r "pattern" *
    This will search for the given pattern in all files in the current directory and any subdirectories, and print out any lines that contain the pattern.

   Search for a pattern in all files in a directory, but only print out the filenames:

perl
Copy code
grep -l "pattern" *
This will search for the given pattern in all files in the current directory and print out only the names of the files that contain the pattern, rather than the actual lines.

- Sure, here are four more ways to use grep in the terminal:

  Use grep to count the number of lines that match a pattern:

    perl
    Copy code
    grep -c "pattern" filename.txt
    This will search for the given pattern in the file filename.txt and print out the number of lines that contain the pattern.

  Use grep to search for multiple patterns:

    perl
    Copy code
    grep -e "pattern1" -e "pattern2" filename.txt
    This will search for both "pattern1" and "pattern2" in the file filename.txt and print out any lines that contain either pattern.

 Use grep to search for a pattern in a compressed file:

     arduino
     Copy code
     zgrep "pattern" filename.txt.gz
     This will search for the given pattern in a compressed file filename.txt.gz and print out any lines that contain the pattern. The zgrep command is used to search for patterns in gzip-compressed files.

Use grep to search for a pattern in a specific type of file:

      perl
      Copy code
      grep "pattern" --include="*.txt" *
      This will search for the given pattern in all files with a .txt extension in the current directory and print out any lines that contain the pattern.       The --include option is used to specify the file type to search in.

I changed the output in my lab report by omitting ChatGPT's code examples and selecting four of the eight options to include in my report. The outputs I did include were copy- pasted and rephrased slightly to match the format of the report. 
