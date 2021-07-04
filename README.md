# [CP] Scots Gaelic Language Pack
This is a repository containing a basic structure for a Stardew Valley content pack to add custom language support for Scottish Gaelic. Only files containing updatable text will be included to reduce download sizes. Some text is built into the images and will require modification with a tool like Photoshop/GIMP, so some similar fonts have been included as a starting point to achieving this.



=== Included Assets & Resources ===
- Stardew Valley Styled Fonts
- GIMP Project Files for modified sprite images
- Microsoft Scottish Gaelic Style Guide. This is a guideline for UI (User Interface) development. 



=== Content Pack Requirements ===
SMAPI 2.6 or above installed and Content Patcher 1.4 mod or higher installed. 
*Note: Only when installing SMAPI will there be the Mods folder

SMAPI: https://www.nexusmods.com/stardewvalley/mods/2400?tab=files
Content Patcher: https://www.nexusmods.com/stardewvalley/mods/1915?tab=files



=== Current Development Points of Interest ===
Files will be updated as nessesary as new text is added to the base game and if any base strings are missed.

I'm still working on some minor things, like how to add a language to the list of languages properly, currently only strings can be changed out.


=== Easter Eggs ===
Pelican Town has been renamed to Selkirk (Salcraig), the town where the content pack creator grew up around.






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