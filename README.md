Turns Metatrader4/Metatrader5 into websockets client. 

Note: make sure you have VSredist: https://www.microsoft.com/en-ie/download/details.aspx?id=48145

Copy MQL4 folder to Data folder of mt4 (how to get where is Data folder is localted, open mt4, click File->Open Data Folder or just click Ctrl+Shft+D).
In MT4 Navigator (to show Naavigator click Ctrl+N) select Expert Advisors->Advisors. Right click on websockets, select Modify. Editor will be opened, press F7 to compile. Done.


Compile Instructions:

1. Install Visual Studio 2022
2. Install cygwin and install mingw64 compnets that are active
3. install vcpkg along with boost and ixwebsocket
4. vcpkg integrate install
5. in visula studio switch to release and build
6. done
