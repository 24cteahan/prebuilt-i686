# prebuilt-i686
 
### This is a [gcc](https://drive.google.com/file/d/0B85K_c7mx3QjUnZuaFRPWlBIcXM/edit?resourcekey=0-QZ6H1d0gsc4vLcfvfV7XEA) reposotory with the required [MinGW](https://sourceforge.net/projects/mingw/) libs included


## --------------------------------------------------
### Installation
## --------------------------------------------------
##### Note: This is only confirmed to work for windows
#####
#### 1. place "ghost-i686-elf-tools" in any directory that will be reffered to as "fpth" for the remainder of the instructions
#### 2. pick either 2a or 2b
##### 2a. run `C:\Windows\System32\SystemPropertiesAdvanced.exe` in cmd/powershell
##### 2b. open adanced system settings
#### 3. Open enviornment variables select path under System Variables
#### 4. Add 
```
fpth\ghost-i686-elf-tools\i686-elf\bin
fpth\ghost-i686-elf-tools\bin
```
#### 5. You should be able to run any gcc command now
