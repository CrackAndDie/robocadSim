<h1>How to use robocadSim C++ library in your project</h1>  
  
  
1. You need open-cv installed in your project ([How to install example](https://www.youtube.com/watch?v=M-VHaLHC4XI))  
2. Right click on Your project name in **Solution explorer** -> **Properties** -> **Configuration Properties** -> **C/C++** -> **General** -> click on **Additional Include Directories** and click **Edit** -> create new line and paste here path to C++ header files (.\robocadSim\Lib\cpp\robocadSimLibCpp) -> click **OK**  
3. Go to **Linker** -> **General** -> **Additional Library Directories** -> **Edit** -> create new line and paste here path to .lib file (.\robocadSim\Lib\cpp\x64\Release) -> click **OK**  
4. Go to **Linker** -> **Input** -> **Additional dependencies** -> **Edit** -> paste here **robocadSimLibCpp.lib** line -> click **OK**  
5. Now You can use robocadSim C++ library in Your project!  

<h1>If You can't use some header files</h1>  
  
  
1. Copy .dll file in robocadSim release folder (.\robocadSim\Lib\cpp\x64\Release)  
2. Paste it to the path: **path_to_your_project/your_project_name/your_project_name/**
