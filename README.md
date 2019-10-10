# Simple Implementation of the Kernighan-Lin-algorithm
### KL algorithm in PERL
#### EEL4932 - Grace Brazil Fall 2019 

## Running the script in your terminal:
1. cd into the location where you saved the perl script
> cd /Desktop/Sandbox

2. run the perl script (UNIX)
> perl KL.pl

How do I know if I have the interpreter?  
>'perl -v' 

try it in your terminal, if it gives you an error you don't have it!
If you don't have it go here: http://www.perl.org/get.html
Afterwards, you should be able to do perl <space> anyperlscript.pl in your terminal

3. the script will ask you to give the input folder's path name. It is recommended that you create a folder 'in' and put the input files you want ran.
Prompt:
"Give the input folder's path name "
> /Users/Desktop/in


## After running the script:
You will be getting one output per input file and one file for summary. For 01.in you will be getting  01.out and for 02.in and 02.out

- the 01.out will contain the final cut and the partition assignment of Node 1 to Node n
- the summary.out will contain the input file's initial cutsize, initial execution time in calculating initial cutsize, final cutsize and time elapsed for the final cutsize

### Disclosure
I know this script can be further optimized so that the runtime is improved. I will be updating the main code whenever I get the chance to (still in college with many other projects/assignments). Otherwise, feel free to contact me/contribute to the project.
