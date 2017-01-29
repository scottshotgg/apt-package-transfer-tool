# APT Package Transfer Tool

This tool will help you transfer packages from one computer to another one. It is particularly useful if you want to create multiple computers of the exact same  package makeup. I use it at work and thought others may find it handy. The best thing is that is requires no extra packages or dependencies!

To use this:
	First run the makelist command on the computer that you are transferring packages from
	Take the output file named packages and the install script, and with them both in the same directory, run the install script on the computer 
	that you want to transfer packages to. This will invoke apt to install all packages in the packages file. 
