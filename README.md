# Previous-Projects
Projects from August 2024 and Before

# PROJECT LIST
## Main Feature: magiQuest, JUNE 2022
A Java version of the fantasy game found at Niagara Great Wolf Lodge. Users need to complete the Adventure of defeating Charlock, a dragon that has been terrorizing the locals and stealing their gold.

To do this, they need to go on quests to get four Runes that give them special powers; the Portal Rune, the Freeze Rune, the Ice Arrow Rune, and the Protection Rune. To do so, they have to find various artifacts in the Artifact Hall. They can also get powerups in the form of toppers from the shop.

Here is a list of classes found in this project:
- ICS4U_FP (main/quest stones) - main hub for all code; gives player quests, allows them to pick where to go, see quest progress, etc
- Password - used files to allow user to login to the game/have multiple saved games on one computer
- DrawingCanvas - used graphics to display a title card at the start of the game
- Shop - allows user to buy toppers/powerups
- Hallways - holds Artifact Hall (artifact locations) in a 2D array
    - Messages (extends Hallways) - contains the messages the artifacts "say" when selected - general messages, quest-specific messages, gold acquisition, etc.
- Queue - base queue class for Rune Quests/Charlock Adventure, so artifacts are found in right order
    - PortalQueue (extends Queue) - uses Queue to create a queue with all of the clues for artifacts in the Portal Rune quest in the right order
    - FreezeQueue (extends Queue) - uses Queue to create a queue with all of the clues for artifacts in the Freeze Rune quest in the right order
    - IceArrowQueue (extends Queue) - uses Queue to create a queue with all of the clues for artifacts in the Ice Arrow Rune quest in the right order
    - ProtectionQueue (extends Queue) - uses Queue to create a queue with all of the clues for artifacts in the Protection Rune quest in the right order




- salonSoftware, APRIL 2022 --> group project making a software for a hypothetical salon
    - Main Class --> coded by collaborator to bring everyone's parts together
    - Inventory --> stores data on the inventory in the salon
    - Equipment --> extension of Inventory to track quantity and quality of equipment
    - Supplies --> extention of Inventory to track quantities of supplies
    - inventoryClient --> client management of supplies and equipment   
- mastermind, JANUARY 2021 --> text-based mastermind game, using letters instead of colors
- roman_numeral_conversion, DECEMBER 2020 --> converts roman numerals to base 10, then to other bases