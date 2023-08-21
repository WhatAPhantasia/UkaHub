fontinstaller.dll

----------------------------------------------------------------------------------------
Utility : checking a font is installed, modifying an installed font, installing or uninstalling a font for the current user. It's installing the font for the current user only.

----------------------------------------------------------------------------------------
Usage : It's used with FUNCTIONEX("fontinstaller.dll",Arguments), you can use SAORI() instead of FUNCTIONEX() depending on your environnement.

Keep in mind installing, deleting or modifying a font is touching Windows settings, thus asking the user before doing it is a good practice.

------
Different commands are available :

	- Get the path to the font file (can be used to check if the font is installed)
		Argument0 : "get"
		Argument1 : the name of the font	
	
	- Install a font
		Argument0 : "install"
		Argument1 : the name of the font
		Argument2 : the path to the font file
		
	- Update an already installed font
		Argument0 : "update"
		Argument1 : the name of the font
		Argument2 : the path to the font file
		
	- Removing a font
		Argument0 : "remove"
		Argument1 : the name of the font
		
Windows generally uses the format "FontName (TrueType)" for .ttf and .otf fonts, you can use this format too to stick to Windows' format.

Example : FUNCTIONEX("fontinstaller.dll", "install", "My Font (TrueType)", "path\to\the\font.ttf")

------
Version : 1.0
Author : Azura Levidre
		 https://levidre.github.io/