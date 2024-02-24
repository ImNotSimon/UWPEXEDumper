## [Download latest binary here!](https://github.com/ImNotSimon/UWPEXEDumper/releases/)

---

Fork/edit of Wunkolo's UWPDumper that only dumps the .exe files instead of the whole game. Useful of game pass modding.


Run "EXEInjector.exe" and enter valid UWP Process ID to inject into.
.exe files will be dumped into:

`C:\Users\(Username)\AppData\Local\Packages\(Package Family Name)\TempState\DUMP`

To get a list of command line arguments run the command

`EXEInjector.exe -h`

UWPEXEDumper requires the [Windows 10 SDK](https://developer.microsoft.com/en-us/windows/downloads/windows-10-sdk) and C++ ATL for v143 build tools (x86-64 or ARM, depending on what you want to compile for) to be compiled.
