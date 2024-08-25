This folder system is required to sort and manage Catia V5 Parts and Files.
To commit anything to this repository you are required to follow this structure.
If you don't follow this structure, you will not be able to contribute to this repository!

Catia V5 Naming rules
	-No Dots, Commas, or Spaces are allowed, as well as no special characters! They have the power to break the Catia V5 Products!
	-Every part has a partnumber that is created in the following way: 
		L-40 (Project)
			01 (Part Belongs to the engine block)
				01 (Parts folder or Subsystem)
					Name (Created by Developer with logic)
						Version (No Dots. Commas, or Dashes-) 
							Short end of Name (SomeGermanEngineer -> SGE)

	=> L-40_01_01_0001_Block_Main_V01_SGE

	-If the Naming rules are not followed, your parts wont be commited to the repository!
	-If you rename a part it needs to be reconnected within the Product file. So avoid this if possible.

Product Files are only allowed to be created by Admins or Moderators!


If multiple people work on one Part you are allowed to create subfolders like this:

-Part
	-Winning Design (Gets filled with the finished part of the Person that managed to Develop the best part)
	-Person 1
	-Person 2
			-Developement


Documents must be saved in the public Documents folder to avoid saving things multiple times!




Name Translations:

Block		= Engine Block		(Main Parts, Including things like the frontcover)
Kopf		= Engine Head		(Including Bearings for valve train)
Kurbelwelle	= Crankshaft		(Including Bearings)
Pleul		= Connecting Rod	(All connecting rod geometry including rod pin to Piston)
Kolben		= Piston		(Geometry of combustion chamber and Pistonrings)
Ventile		= Valvetrain		(Including gears for Valvetrain)
Wasser		= Water / Watercooling	(Every connection outside of other Parts, Radiators,...)
Oel		= Oil / Oilmanagement	(Every part needed to create the Oilsystem)
Ansaugung	= Air Intake		(Every part above the Valvetrain)
Zuendung	= Ignition		(Every part required for Ignition)
Abgasstrang	= Exhaust		(Every part within the Exhaust)
Organisation	= Organisation		(Everything to organize something not directly related to a part group)



If you notice that folders get chaotic please request a restructuring in one specific section.

Example 

Section Oil has the following parts:
-Oiltank
-Oilhoses
-Oilpump
-Drysump
-Oil_cyclon
-Ventilation

The Oilpump may have multiple parts within it like:
-Gears
-Pump
-housing


If restructuring is necesarry the folder structure should look like this:

01_Oiltank
02_Oilhoses
03_Oilpump
04_Drysump
05_Oil_cyclon
06_Ventilation

The Documents and Sonstiges (other) folders get added to each part. Resorting of the old folders may be usefull.
