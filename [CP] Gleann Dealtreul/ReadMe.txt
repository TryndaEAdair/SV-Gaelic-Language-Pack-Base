Ceud mìle fàilte gu Gleann Dealtreul! 
A Hundred Thousand Welcomes to Stardew Valley!


=== Installation instructions ===
Requirements: SMAPI 2.6 or above installed and Content Patcher 1.4 mod or higher installed
SMAPI: https://www.nexusmods.com/stardewvalley/mods/2400?tab=files
Content Patcher: https://www.nexusmods.com/stardewvalley/mods/1915?tab=files
Note: Only when installing SMAPI will there be the Mods folder


Step 1: Extract the downloaded .zip file

Step 2: Copy the entire folder [CP] Gaelic to the Mods folder in the folder where the game is installed.
Windows example - "C: \ Program Files \ Stardew Valley \ Mods" or "Steam \ steamapps \ common \ Stardew Valley \ Mods"
Andriod example - "\ Stardew Valley \ Mods "

Step 3: Enter the game, if you are seeing "Gleann Dealtreul" in place of "Stardew Valley" you have installed the mod successfully. 
		*If you do not see this, check the game installation directory in step 1.
		
		


*** If you would like to help contribute to this translation, or to fork this branch 
and translate in your own dialect, the code repository is located at:

https://github.com/SkyEdwards/SV-Gaelic-Language-Pack-Base

all you need to do is swap out the english :) 


=== Change Log ===
1.0 	- File structure setup and first sprite modifications.
1.1 	- File structure rename to allow for easier future langugae support.
1.1.1 	- Cleaning up file structure and updating content.json format to most current supported version.
1.2 	- Updating simple UI strings in following files:
			- Content/Strings/UI.gd_GD.json
			- Content/Strings/Lexicon.gd-GD.json
			- Content/String/StringsFromCSFiles.gd-GD.json
		- Updated g (gold) to sg (sgillinn)
1.2.1 	- Completed translations in Content/Strings/Lexicon.gd-GD.json
1.3.0 	- Completed translations in Content/Strings/NPCNames.gd-GD.json
		- Updating simple UI strings in following files:
			- Content/Strings/UI.gd_GD.json		
		- Updated Stardew Valley name strings with Gleann Dealtreul.
			- Bulk updated various text strings of name (See GIT repo for full list of changed files)
			- Updated sprite images with Gleann Dealtreul name in following files:
				- Content/LooseSprites/logo.gd-GD.png
				- Content/LooseSprites/LanguageButtons.png
				- Content/Minigames/Intro.gd-GD.png
				- Content/Minigames/yellowLettersLogo.gd-GD.png
				- Content/Minigames/TitleButtons.gd-GD.png
				- Content/Maps/Festivals.gd-GD.png
		- Updated The Stardrop Saloon name strings with "an Òsta Dealtreul".
			- Updated text string for 'The Stardrop Saloon' in follwoing files:
				- Content/String/StringsFromCSFiles.gd-GD.json
				- Content/Characters/Dialogue/Gus.gd-GD.json
				- Content/Data/mail.gd-GD.json
				- Content/Strings/Characters.gd-GD.json
			- Updated sprite images with An Òsta Dealtreul name in following files:
				- Content/Maps/fall_town.gd-GD.png
				- Content/Maps/spring_town.gd-GD.png
				- Content/Maps/summer_town.gd-GD.png
				- Content/Maps/winter_town.gd-GD.png
		- Updated sprite images with additional translations in following files:
			- Content/LooseSprites/Cursors.gd-GD.png
			- Content/LooseSprites/Cursors2.gd-GD.png
			- Content/LooseSprites/JunimoNote.gd-GD.png
			- Content/LooseSprites/MobileAtlas_manually_made.gd-GD.png			
			- Content/Maps/samshowtiles.gd-GD.png
			- Content/Maps/Festivals.gd-GD.png			
			- Content/Maps/fall_town.gd-GD.png
			- Content/Maps/spring_town.gd-GD.png
			- Content/Maps/summer_town.gd-GD.png
			- Content/Maps/winter_town.gd-GD.png
		- Updated sg(sgillinn) to òg/ò(-gold- anns a Gáilig) to work better with graphics.
		- Updated simple strings for winter (Geamhramh) and summer (Samhramh) with Gáilig Dhail Riada spellings in following files: 
			- Content/String/StringsFromCSFiles.gd-GD.json
		- Added Clann Éiri Gréine flag easter egg for their support in this project. Located in file:
			- /Content/TileSheets/furniture.gd-GD.png
		- Added references in /content.json file:
			- craneGame_international.png instead of English interface
			- logo.gd-GD.png
			- LanguageButtons.gd-GD.png 
				- This is a proactive mesure to ensure the sprite file is not overwriten by accident by an update.
				  The basic LanguageButtons.png  is required to be mirrored to ensure languages sprite is present on load. 
			- MobileAtlas_manually_made.gd-GD.png
		- Added missing mobile UI strings in file:
			- Content/Strings/UI.gd_GD.json	
1.3.0.1	- Removed duplicate referance to language buttons causing conflict on load on content.json
1.3.0.2	- Renamed CP_gaelicSV.txt to ReadMe.txt for clarity
		- Corrected typo of Gleann Dealtreul in Intro.gd-GD.png
		- Updated Manifest with new mod name of -Gleann Dealtreul- and updated version.
1.4 - Correcting version number in manifest file to allow mod to run. 
1.5 - Updating to include multiple dialtects at request of local language community.
		- Updating language selection sprite to include multiple dialects
		- setting Gaedhlig Uisge Dhearg as default dialect at request of diaspora community.
	- Making Load Screen icon's font more clear.