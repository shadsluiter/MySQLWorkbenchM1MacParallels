# MySQLWorkbenchM1MacParallels
Installer for Mysql Workbench on Macintosh M1 M2 ARM processor using Parallels.

How to Make MySQL Workbench run on Macintosh M1 and Windows with Parallels

Problem:

Windows for ARM will not permit the MySQL Workbench installer run.  When trying to install Workbench the following error is displayed:

"The processor is not adequate for running MySQL Workbench 8.0 CE."

Workaround:

Option 1: Use a modified version of the MySQL Workbench installer.

The modified version can be found here

https://github.com/shadsluiter/MySQLWorkbenchM1MacParallels 



Option 2:
Modify the installer to ignore the Intel processor check.  

This requires running Orca to modify the msi installation file.  

Instructions for running orca are found here.

https://stackoverflow.com/questions/71461848/mysql-workbench-failing-to-download
 
