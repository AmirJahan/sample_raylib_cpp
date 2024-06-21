## Sample Raylib C++


### Instructions to get started

- From https://github.com/raysan5/raylib/releases download the correct version. Most likely it will be raylib5_win64.msvc
- Place the downloaded file in a folder such as C:\libraries
- In VS 2022, “Create a new project”. Choose Empty, C++ project
- Add at least one “.cpp” file to force the settings to recognise the CPP project. Let’s say “main.cpp”
- Right click on project name, choose Properties.
- In properties window, in C/C++ -> General, go to “Additional Include Directories” and add the following folder: C:\libraries\YOUR_LIB_FOLDER\include
- In properties windows, in Linker -> General, go to “Additional Library Directories” and add the following  folder: C:\libraries\YOUR_LIB_FOLDER\lib
- In properties windows, in Linker -> Input, go to “Additional Dependencies” and add the following two: raylib.lib and winmm.lib
- You can then copy the code at the end of this email and try it.
- Couple of things to keep in mind,
  - On campus machines, you might run into issues with access
  - I also recommend that once you have the setup ready. Save the project and then each time, open a new copy of it. Basically treat it like a template so you don’t have to setup everything from scratch.
  - The code on https://www.raylib.com/examples.html is usually in C-style which might need a little change in C++ (usually for compound literals)

Code example is Converted from https://github.com/raysan5/raylib-games/blob/master/classics/src/arkanoid.c. 
