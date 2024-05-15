# CompileAndRun
A macro for Notepad++ made for ENGGEN 131 students learning C.
Works for GCC and Microsoft Visual Studio Compiler.

## Method
1. In Notepad++ press F5 or click Run > Run to open the Run prompt.
2. If you are using GCC, paste the contents of CompileAndRunGCC.txt into the text field. If you are using Microsoft Visual Studio Compiler, paste the contents of CompileAndRunVs.txt instead.
3. The path provided in CompileAndRunVS.txt (C:\Program Files (x86)\Microsoft Visual Studio\2019\Community\Common7\Tools\VsDevCmd.bat) is the default directory for the VsDevCmd.bat file. If you have installed Visual Studio in a different location or have a different version, locate the batch file manually and replace the default path in the txt file with your path.
4. Click Save to create a shortcut and hotkey to run the command.

**Notes:**  
* When the command is run, the executable will be named the same as the source file and will be saved in the same directory.  
* A simple test program has been included. If the command executes successfully, a command window will open displaying "Hello World".
