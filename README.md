## APT Package Transfer Tool

This tool will help you transfer packages from one computer to another one. It is particularly useful if you want to create multiple computers of the exact same  package makeup. I use it at work and thought others may find it handy. The best thing is that is requires no extra packages or dependencies!


####Usage:

   **1.** First run the makelist (./makelist) command on the computer that you are transferring packages from to compile a list of the currently installed packages.  
   **2.** Transfer the generated packages file and the install script to the destination computer.  
   **3.** With both files in the same directory, run the install (./install) script on the computer that you want to transfer packages to. 
The install script will invoke apt to install all packages in the packages file. 
