# VSCode C++ compile and launch settings windows
 Hey, these are my settings for compiling, linking and launching .cpp files. You can use them after configuring a GCC compiler and adding c++ extension.

If you configure VSCode for the first time, I refer you to:
 https://code.visualstudio.com/docs/languages/cpp

tasks.json
 This file is used to run a build task. (compiling+linking)
 Remember to change the path to the compiler if it doesn't match.

launch.json
 This file is used to launch the program.
 Choose the option from the bottom bar in VSCode after debugging (F5) once. Default option is Launch.  
 Possible launch options are:
 Launch (Launch program in windows terminal)
 Debug  (Debug program in VSCode)

My strategy:
 1. Putting .vscode\\tasks.json and .vscode\\launch.json in a folder
 2. Copy the folder every time you want to create .cpp files in a new directory
 3. Open the folder in VSCode
 4. Create .cpp files in newly copied folder
 5. Build and run the program
