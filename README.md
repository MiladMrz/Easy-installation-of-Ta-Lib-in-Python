# Easy-installation-of-Ta-Lib-in-Python (for windows)

For normal installation please visit https://github.com/mrjbq7/ta-lib but if you already failed at those instructions you are in the right place. 

I'm new in this environment, but **Ta_lib** take few hours of my time, which it shouldn't. Therefore, I made this step by step guide for other newbies who struggle just like me. As far as I know, there are two major errors with Ta_lib installation...

## 1: error: Microsoft Visual C++ 14.0 is required. Get it with "Microsoft Visual C++ Build Tools"

to solve this error there are two options:

  A. download from Microsoft website:  https://visualstudio.microsoft.com/downloads/#build-tools-for-visual-studio-2019
  
  - This option will force you to download and setup a program & at least download size of 5GB.
  - Due to installer issues, you may force to use offline installation which is worse. it may take up to even 40GB of downloading size and again time to setup.

  B. Use npm installation with **Node.js** 
  
  - You need to download Node.js from  https://nodejs.org/en/  (for exp: v12.18.3)
  - open `cmd` and run `npm install -g windows-build-tools` command. This will download all needed files and takes only few minutes.
  - If it didn't work try `npm install --global --production windows-build-tools@4.0.0` or visit https://github.com/felixrieseberg/windows-build-tools/issues/152

## 2: error: Cannot find ta-lib library, installation may fail.

If you cannot directly use the `$ pip install TA-Lib` you can use "whl" file installation

  - The installation file can be downloaded from: https://www.lfd.uci.edu/~gohlke/pythonlibs/#ta-lib
  - After downloading make sure to place the file in the same path as your terminal indicates
  - Now use the pip install command with the file name of the downloaded file. (for exp: “TA_Lib-0.4.18-cp38-cp38-win32.whl”) The command would be `pip install TA_Lib-0.4.18-cp38-cp38-win32.whl`
  - For more information visit https://blog.quantinsti.com/install-ta-lib-python/
  
  
  
  
  **hope this will help and save your time...**
  **feel free to send `LTC` to my wallet `LW1Ydexa4yFPQgujZPiW5NBh21ntJcXocV` :)** 
  
  
