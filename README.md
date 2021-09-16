# VSCode C++ build and launch settings windows
Hey, these are my settings for compiling, linking and launching .cpp files.
You can use them after configuring a GCC compiler and adding c++ extension.

If you are configuring VSCode for the first time, I refer you to:
https://code.visualstudio.com/docs/languages/cpp

### tasks.json
This file is used to run a build task. (compiling+linking)
Remember to change the path to the compiler if it doesn't match.

### launch.json
This file is used to launch and debug the program.
Choose the option from the blue bottom bar in VSCode after debugging (F5) once. 
Default option is Launch.
Remember to change the path to the debugger if it doesn't match.  

Possible launch options are:
- Launch (Launch program in windows terminal)
- Debug  (Debug program in VSCode)

### My strategy:
1. Download .zip file with code
2. Create .vscode folder, extract tasks.json and launch.json in the .vscode folder
3. Insert .vscode\tasks.json and .vscode\launch.json in a *new folder*
4. Do following tasks every time you want to create .cpp files in a new directory
    - Copy and rename the *new folder*
    - **Open the *folder*** in VSCode
    - Create .cpp files
    - Build and run the program

### Troubleshooting:
Try restarting VSCode, open your *folder* again.
