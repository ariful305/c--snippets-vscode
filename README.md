
## C++ setup in vscode/vscodium

This guide will walk you through the process of setting up a C++ development environment in Visual Studio Code or VSCodium. Both are powerful, open-source code editors that provide excellent support for various programming languages, including C++.

## setup process

* Download **vscode** [this link](https://code.visualstudio.com/download) and install  

  or download **vscodium** [this link](https://vscodium.com/) and install 

* Once you have installed vscode or vscodium, now its time to install some extensions.  
    - [C/C++](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools)
    - [Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner)
    - [Competitive Programming Helper (cph)](https://marketplace.visualstudio.com/items?itemName=DivyanshuAgrawal.competitive-programming-helper)

* Download **MinGW** [this link](https://sourceforge.net/projects/mingw/) and install

* Now open 'This PC' and open 'local Disk C' you should see mingw file and click on bin folder.   Now you have to copy the folder destination.

* Now search **View advance system setting** in windows setting and open it and goto **Environment Variables** . Now click on the path in **system variable** and click on edit and now click on new and paste the bin path that we have copied in the previous step and then click Ok.Now click ok till there are no pop ups left.

* Let's check if MinGW has been successfully installed or not. open command prompt and run 
```bash
  g++ --version
```
* if you see the g++ version , you did it. 
* Now open vscode and make a file with a extension of .cpp. lets type our first code. You can copy and paste the code that I have provided below
```bash
  #include<iostream>
  using namespace std;
  int main()
  {
      cout<<"hello world";
  }
```
* Right click and click on run or press keyboard shortcut **'Ctrl+Alt+N'**.

* You can also run input and output test case use **Competitive Programming Helper (cph)** .

* You can import custom snippets .To access this setting, you can either click on the **settings icon** on the **sidebar** and then click on **user snippets** create a new snippets and copy the **cpp.json** on this repository and paste it to your file and save it.








