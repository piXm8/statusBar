/////////////////////////////////////////////////
////////      A3 EPOCH STATUS BAR       /////////
////////      by piX (Orig. Osef)       /////////
/////////////////////////////////////////////////

1: Copy the 'dialogs' and 'scripts' folders into your ROOT mission Folder (with init.sqf and description.ext)


2: Add - 
				[] execVM "scripts\fn_statusBar.sqf"; 
				
				to your init.sqf (or copy from the example init.sqf)
				

3: Add - 				class RscTitles
				{
	
						#include "dialog\statusBar.hpp"
				};
				
				to the bottom of your description.ext (or copy from from the example description.ext)
				
				
4: BattlEye Filters -

				TO BE UPDATED
				

Customization:

statusBar.hpp: 
				color = "#b20000"; // Changes the colour of the text
				