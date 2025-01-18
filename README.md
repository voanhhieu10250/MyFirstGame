# MyFirstGame (Bullet Hell)
Fast Little Game written in C

## Original Tutorial
https://youtu.be/2B-pxN7W5Pw?si=LM7Nk5EsL67NT1--

## Setup Windows
- Download Visual Studio: https://visualstudio.microsoft.com/downloads/
- Download Cmake: https://cmake.org/download/

### Visual Studio Installation
![Visual Studio Installer](/assets/VisualStudioSetup.jpg?raw=true "Installation Options")

### CMake Installation
![Visual Studio Installer](/assets/CMakeSetup.jpg?raw=true "Installation Options")

### Project Setup
1. Clone the Repository
2. Inside the folder open up a `Terminal` and type in: `cmake -S . -B build`
3. Navigate into the `build` Folder and open the `game.sln` to start **Visual Studio**
4. In **Visual Studio** set the **game** Project to **Set as Startup Project**
5. Open **Properties** of **game**, **Debugging** -> **Working Directory** = `$(ProjectDir)\..`
