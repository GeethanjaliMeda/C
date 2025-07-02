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



