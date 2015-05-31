# MGL804-PLINK1.9-Mac
Code source de Plink adapté pour Mac

# Version Mac
Yosemite version 10.10.3

# Use code below with CLion IDE
1. Download the project on github
2. Import the project in CLion: File -> Import Project -> Choose the project "plink_src".
3. Build the project: Run -> Build. (This command will create the executable file name: plink.)
4. Go to the "Edit Configurations" menu: Run -> Edit Configurations
	1. Create an application. 
	2. The "Name" is the name of the project.
	3. The "Target" is the your project "plink_src"
	4. The "Configuration" doesn’t work, so you can put any options.
	5. The "Executable" is the executable file generated by the "Build" command. 
	6. The program arguments is the instructions to run the plink program. Ex: --file toy --make-bed --out test1 , to create the binary files. 
5. Run the project: Run -> Run "plink_src"
