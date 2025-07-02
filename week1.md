
**DAY 2**

After performing save operation to quit vi text editor back to your command prompt to use GCC tool 
To perform quit operation the command is
:q <enter> (to quit from vi text editor )
To compile the file in text editor we have to use this command
gcc filename.c
In vi text editor after the compilation an executable file gets created named a.out .
We can also see the files which are created and what time it is created , size of the file and permissions of the file by using the command ls with -l flag or option which the command is ls -l
After giving the above command the green colour files are executable files.
During recompilation the old executable file (a.out) is replaced with new executable file
Executable files are not generated during compilation error.
Step 3: Executing a file
When we want to execute the executable file (a.out) we have to give the command in text editor is ./a.out to run or execute a file.
Program Execution
1.User/program point of view (C code)
Program execution starts from main function (entry point)
User space program only have one entry point whereas in kernal space there are multiple entry points.
2.System point of view (Instructions)
i.Changes seen in RAM
ii.Changes seen in CPU
$./a.out here ./ is used to push the executable file into harddisk
After compilation the executable file is generated and stored in your Harddisk.
Executable file is loaded to your RAM during program execution.
CPU --> Executes instuctions
{ Fetches
  Decode         Instruction pipelines
  Executes}
CPU fetches ,decode and executes each instuctions one-by-one
After CPU executes all the instructions the executable file is completely offloaded from RAM.
"A program which is loaded intto RAM for execution is known as process."

**DAY 2**  
Micro controller                                            MicroProcessor
Low speed <100 MHz                                          High speed > 1GHz - 5GHz
Single cores                                                Multi cores
Kell IDE tools                                              Embedded OS / Moblie OS /RTO's
Memory (Kb's & Mb's)                                        Memory (Mb's & Gb's)
Single task                                                 Multiple task(Process)
What is the command we can use to display information about process that running inside your system 
$ ps -ef here ef is flagss/option.
To get documentstion for ps
$ man ps
$ ps --help
GUI Application to display process in system monitor 
To combine save and quit operation (:w + :q ) is
:x 
For copying and Pasting in vi text editor
to copy a single line --> yy  (y stands for yanking)
to copy multiple lines --> nyy (n = number of lines you want to yank)
to paste a single line --> p
to paste multiple lines --> p
If you copy more than two lines the screen displays 5 lines yanked in the bottom left hand side as well as pasting lines it displays a message 7 more lines
To copy a single word --> yw
to paste it --> p
If you have to quit the file without saving we can use this command :q!
A proper quit operation can be performed only when we complete save operation.
To shift cursor to the last line --> G
To shift cursor to the first line --> gg
shift or move cursor to the particular line --> nG,ngg,:n <enter> (n= which line you to move the cursor)
To delete an entire line --> dd 
for multiple lines --> ndd (n is how many lines you want to delete)
NOTE:
These commands only performed in Command mode.

