This is the github repository for the 2020 CAD model. there are separate folders for parts, assemblies and design definition information (interfaces)

setup environemtn
- Instal solidworks if you have not already.
- In Solidworks, Go to System options (the gear on the top) --> Backup/Recovery --> uncheck the box labeled "Number of backup copies per document"
- create a personal github account if you have not already
- request access to sytemoverloadrobotics organization in github (ask Ollie, Danny or Michael)
- in webbrowser install GitHub Desktop
- clone the 2020InfiniteRechargeCAD to your local computer

How to use Github
clone - 
commit - 
publish/push - 
branch - 
merge - 

Important Items
2020InfinitRechargeCAD - is the ONLY repository to be used by manufacturing team in 2020 season
Assembly Library - folder for all .SLDASM files
Interface Library - (admin level DO NOT TOUCH!) this is the folder for all interfacing parts and information.
Parts Library - folder for all parts (COTS, fabricated, game pieces, etc.)
6059Robot - (admin level DO NOT TOUCH!) this is the master assembly for the full robot

Making Edits to the Reposity
before making any changes please make a new branch

Adding Parts
ADD ALL PARTS TO THE PARTS LIBRARY regardless of if they are used for your assembly or all assemblies.

Adding General Assemblies
ADD ALL GENERAL ASSEMBLIES TO THE OTHER ASSEMBLIES folder under assemblies library. this will ensure that assemblies that are not specific to one system can be used by all groups (example would be the VEXpro linear motion kit assembly). please do not delete these assemblies or make edits to them without consulting the other subteams as this may break other assemblies (a better alternative is to create a copy and add Rev#.# after). 

Adding Subsytem Assemblies
ADD ALL ASSEMBLIES SPECIFIC TO A SYSTEM TO THAT SPECIFIC SYSTEM. If subteams only use their folders to add assemblies there is no way to accidentally commit changes to the wrong assembly.

Interfaces
PLEASE DO NOT EDIT INTERFACES UNLESS YOU ARE MANUFACTURING DIRECTOR OR HAVE BEEN ASSIGNED TO DO SO BY THE DIRECTOR. the point of interfaces is to create a constant mating point between the subsystem and allow changes to be made within subassemblies without breaking the 6059Robot assembly



