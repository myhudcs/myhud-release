## **2.4.28**

### **What's New**

* **🎛️ Configurable Sponsor Height**
  * **Height Range**: Adjustable from 50px to 200px with 5px increments
  * **Real-time Preview**: See changes instantly in the configuration panel
  * **Persistent Setting**: Height preference is saved and applied automatically

* **📁 Players & Teams Import/Export**
  **Streamline your workflow with powerful data management!** The new import/export system allows users to easily backup, share, and transfer their player and team configurations across different installations or share them with colleagues.
  * **Selective Export**: Choose to export only players, only teams, or both
  * **Smart Import Options**: Merge with existing data or completely overwrite
  * **Duplicate Prevention**: Built-in warnings when merging to avoid data conflicts

* **🌍 Swedish Translation Support**
  Added Swedish language support to make MyHUD accessible to even more users worldwide!
  * **Special Thanks**: Huge shoutout to **@mrmn_** for the Swedish translation contribution 🙌
  * **Complete Coverage**: Swedish joins our 10 supported languages (EN, FR, DE, ES, CN, RU, UA, SE, RO, HU)

* **🛠️ Code Quality Improvements**
  * Simplified configuration system with cleaner debounce logic
  * Better error handling and performance optimization
  * Improved component architecture for maintainability

## **2.4.20**

### **What's New**

* **New “My Account” Section**
  A brand-new area dedicated to user account management has been added.
  Users can now view all their personal and billing details, including:
  * Their **email address**
  * **Subscription start date**
  * **Subscription end date** (if the subscription is ending)
  * **Next billing date** (if the subscription is active)
  * A full list of **all invoices**, available to view or download anytime
    This section allows users to manage their subscription and recover documents without needing to contact support.

* **Miscellaneous Improvements**
  Several minor enhancements and optimizations have been made to improve the overall user experience.

## **2.4.15**

### **What's New**

* **Required Fields Highlighting**
  Mandatory player fields (Nickname, SteamID, etc.) now highlight in **red** when invalid or missing, helping users instantly identify what's required.

* **Improved Player Creation UX**
  Users can no longer create a player with incomplete mandatory data.
  Visual indicators now clearly guide the user.

* **Smart Player Logo Fallback System**
  The correct image is always displayed thanks to improved fallback logic:
  * If the player has **no personal image** but **has a team**, the **team logo** is shown.
  * If the player has **no image** and **no team**, the **Steam profile picture** is used.
  * If a **team has no logo**, default **CT/T icons** are displayed.

* **Config Files Health Check**
  The software now checks whether config files are correctly installed in the CS2 directory.
  * A **red cross** appears when something is wrong.
  * A clear and explicit error message explains the issue.

* **HUD Stability Improvements**
  Closing the software while reviewing a demo no longer triggers repeated error pop-ups — spam completely removed.

* **Cooldown Screen Localization**
  All cooldown screens are now properly translated in every supported language.

* **Subscription / Unsubscription Fix**
  A bug preventing users from unsubscribing has been fixed.
  Users can now freely and correctly **cancel their subscription**.

* **Miscellaneous Fixes**
  Several small bugs and issues have been fixed to improve stability and overall user experience.

## 2.4

### New Features

- **New Auth System**: You can now create an account and log into the app. It's a real step forward for us to achieve more professional account management in the future.  
- **Browser Source**: Highly requested; you can now use our link directly in OBS to get your HUD in the output for spectators. This will enable new possibilities, as shown in the roadmap, such as additional HUDs like **Replay** or **Clutch mode**, and will improve production/observer workflows.  

### Some QoL changes:

- Added a **"Reload HUD"** button to easily refresh it without closing the HUD.
- The **"Search for a player by team name"** text field is now **persistant**, no more rewriting after each modification of a player
- You can now **update HLAE** directly in MyHUD and never be outdated again.

---

## 2.3.6

### New Features

- **HLAE Update**: Updated to the latest version (2.186.14).  

---

## 2.3.5

### New Features

- **HLAE Update**: Updated to the latest version (2.186.13).  

---

## 2.3.4

### New Features

- **HLAE Update**: Updated to the latest version (working again).  
- **Minimap Bomb on Player**: The player carrying the bomb is now displayed on the minimap.  
- **Team Without Logo**: If a team has no logo, the default CT/T logos are displayed.  

---

## 2.3.3

### New Features

- **HLAE Update**: Updated to the latest version (2.186.9).  
- **Subscription**: Prices updated according to the previous announcement.  

---

## 2.3.2

### New Features

- **Refreshed Options Screen**: The options screen has been redesigned.  
- **New Colors Category**: Partners now have a dedicated category for their colors.  
- **Player Names**: Names now default to the server-provided ones.  

### Under the Hood

- **Electron Update**: Updated to the latest version.  
- **Remote Colors**: Colors are now stored remotely.  
  - ⚠️ If you were using a default color prior to this update, you will have to select it again.  

---


## 2.3.1

### New Features

- **Custom Color Profiles**: You can now create and save up to 8 color profiles for the HUD. Your current custom color will automatically be turned into a profile.  
- **TeamID Overhead (HLAE)**: The TeamID Overhead now uses the colors of the HUD.  
- **Sponsors File Browser**: Added a button to choose images and a drag-and-drop system, instead of only a URL field.  
- **HLAE Update**: Updated to the latest version (2.186.1).  

### Fixes

- **Header Top**: The new header now displays properly if the match is paused (Tech pause).  

---

## 2.3.0

### New Features

- **New Header Top**: A new header design is now available for the HUD (enabled by default).  
- **Hide Team Name**: With the new header, you can now hide team names during the round.  
- **Hide Players Alive**: Added an option to constantly hide the number of players alive during the round (top right corner).  

---

## 2.1.7

### New Features

- **File Chooser**: Added a button to choose images (players/teams) and a drag-and-drop system, instead of only a URL field.  
- **Scoreboard Avatars**: Player avatars are now displayed in the scoreboard.  

### Fixes

- **Performance**: Reduced the number of GSIs to only one for both HUD and Minimap (direct FPS gain).  
- **BO3 Setup**: BO3 setup is no longer overwritten and now works properly.  
- **HLAE Update**: Updated to the latest version.  
- **Translations**: Revised translations to provide more details (player image link, etc.).  
- **Multiple Fixes**: Numerous small fixes to stabilize the software.  

---

## 2.1.0

### New Features

- **HLAE Support**: Added the option to launch the game with HLAE (included in MyHUD).  
- **Custom Killfeed (HLAE)**: Possibility to display the killfeed personalized (colors, player names, etc.).  
- **xRay (HLAE)**: Possibility to display the xRay (glow around players) in the colors of the HUD.  
- **Trails (HLAE)**: Possibility to display grenade trajectories in the colors of the HUD.  
- **Smokes (HLAE)**: Possibility to display smokes in the colors of the HUD.  
- **Automatic Update**: The software now checks and installs updates automatically.  
- **Country Search**: Added the possibility to search the country of a player in the list.  
- **Scoreboard Bind**: Possibility to display the scoreboard when pressing a key.  

### Fixes

- **Translations**: Some translations have been revised for better accuracy (player image link, etc.).  
- **Multiple Fixes**: Numerous small fixes to stabilize the software.  

---

## 2.0.8

### New Features

- **2K/4K Screen Support**: The HUD now automatically adapts to your screen, ensuring the same rendering on Full HD / 2K / 4K displays.  
- **No Timer for Bomb/Defuse**: Added an option to hide the remaining time for defuse or bomb on top of the progress bar.  
- **BO Maps in Finished Screen**: Displays the remaining maps (BO3/BO5) on the end-of-map screen.  
- **New Language: Hungarian**: Thanks @LiToNN & @TechBarát! Hungarian is now available in the application.  
- **Delete Active Team**: You can now delete active teams directly next to the team in question instead of searching for them in the list.  
- **Country Flag for Players**: Adds a player's country when you override them so that their flag appears on the HUD.  

### Fixes

- **Webcam Size**: Fixed an issue with webcams displaying incorrectly with or without sponsors configured below.  
- **Translations**: Revised for better accuracy (player image link, etc.).  
- **Multiple Fixes**: Numerous small fixes to stabilize the software.  


## 2.0.7

### New Features

- **AI/Round Prediction**: When the bomb is planted, an AI prediction appears to indicate which team has a higher chance of winning the round. (122k snapshot to train neural network)
- **AI/Round Prediction Configuration**: You can choose between two different positions for this feature and select the displayed name (Round Prediction or AI Prediction).
- **Tenths of Seconds**: Bomb/defuse timers now display tenths of a second when less than 10 seconds remain.
- **New Language: Chinese**: Thanks to @zcce1s! A new language is now available in the application.
- **New Design for Saved Teams**: Teams are now displayed as cards instead of a list, making it easier to view players.
- **New Design for Saved Players**: Players are now displayed as cards instead of a list, making it easier to view teams.
- **Delete All Players Button**: Added an option to delete all saved players at once.
- **Delete All Teams Button**: Added an option to delete all saved teams at once.

### Fixes

- **Vertical Mode**: Reduced width and increased height for a better display in vertical mode.
- **Minimap on ESL Impact Servers**: The minimap now works correctly even if coaches are present on the server.
- **Translations**: Some translations have been revised for better accuracy (player image link, etc.).
- **Multiple Fixes**: Various small fixes have been made to improve software stability.


## 2.0.6

### What's new

- **Scoreboard during Timeout**: During the break of one of the teams, a scoreboard now appears under the timer
- **Webcams supported**: Added a link in each edited player to add the webcam (the delay is not managed by MyHUD)
- **Picture player in Finished Screen**: Player images are displayed in the scoreboard on the end screen
- **New players/team managed**: New system for teams/players (a team no longer contains a player, and a player contains a team)
- **New Esportligaen theme colors**: New custom color to formalize the partnership with Esportligaen
- **New config when server doesn't send team name**: New system to enter the team name manually if the server does not return the information

### Fixes

- **Number slot in horizontal mode**: Observation numbers do not overlap more on horizontal mode
- **Pseudo in Finished Screen**: Now if the player is overloaded by the Pro Mode or by the user the correct nickname is displayed in the end screen
- **Translations**: Translations have been revised to provide more precision (player image link etc.)
- **Multi fixes**: Many small fixes have been made to stabilize the software

## 2.0.4

### New features
 
- **Flashed players** : Now when a player is flashed InGame, it appears on the HUD (vertical mode)
- **New option Local Picture** : add option to switch profile picture of your players to pro picture (too large)
- **Shortcut to Open/Close HUD** : Add shortcut configuration to change open/close HUD
- **Timeout Remaining** : Add remaining pause when team take timeout
- **Switch weapon active player** : On player focus, visible weapon is active between Rifles and Pistols

### Fixes

- **Picture pro vertical mode** : Fix center image in vertical mode when is pro picture
- **Nan when disconnected** : When player deconnected, no observer slot appear NaN

## 2.0.3

### New features
 
- **Flashed players** : Now when a player is flashed InGame, it appears on the HUD

### Fixes

- **Override teams/players local** : Fix or when opening the HUD, overloaded players and teams were not displayed.


## 2.0.2

### New features

- **Change the minimap size**: You can now choose the size of the minimap (from 300 to 450 px).
- **Enable/Disable the minimap background**: Option to remove the transparent square beneath the minimap.
- **Add bombsite names to the minimap**: Bombsite names are now displayed on every radar for all maps.
- **Progressive HP loss in horizontal mode**: Gradual HP loss when a player takes damage in horizontal mode (already available in vertical mode).
- **Equipment bar**: Displays the team's inventory bar constantly (if disabled, it will only appear at the start of the round).
- **Money on dead players (horizontal mode)**: Displays a player's money when they are K.O. (already available in vertical mode).

### Fixes

- **Map name not displaying in certain games**: At the top left of the HUD, either the map being played or the configured BO will now be displayed.
- **Fix for utility on the minimap**: Utility trajectories on the minimap have been fixed.
- **HUD launch optimization**: Improved server queries to retrieve player data, etc.
- **Missing translations**: Added missing translations.

## 2.0.1

### New features

- **Remote Configuration for Teams/Players**: We have transferred your entire configuration to one of our servers. This allows you to retain your settings when changing PCs or to share your configuration with someone else.
- **Automatic Display of Pro Players/Teams**: Pro player and team data now automatically appear on the HUD, with no additional setup needed. We’ve collected over 100 teams, logos, and player images for you.
- **MVP Player Animation**: When a player scores more than 3 kills in a round and their team wins, an MVP animation will highlight their performance!
- **Player Number Design**: In horizontal mode, player numbers have been added to their cards (with the focused player highlighted).
- **HUD Redesign**: Fresh new look! The software interface, especially the configuration panel, has been redesigned for a more modern experience.

### Fixes

- **Vertigo Minimap Image Fix**: The Vertigo minimap image now displays correctly.
- **Team Flame Bug Fix**: Resolved the issue where team flames would persist after a side switch.
- **New Flame Design**: Player flames in horizontal mode have been revised.
- **Improved Money Visibility**: The money display in horizontal mode has been enhanced, providing better visibility during buy rounds.

## 1.2.6

### New features

- **New team logo**: A brand-new design for the team logo has been added.
- **MyHUD heats up**:
  - Players on fire: If a player gets more than 3 kills in a single round, their icon will be set ablaze.
  - Team on fire: If a team wins more than 4 rounds in a row, their icon will be surrounded by flames.
- Redesign of the BO3 / BO5 layout with 1 round displayed every 2 rounds during freezetime instead of every 5 rounds.

### Fixes

- **BO3 Display**: Fixed an issue with the display when teams switch sides in BO3 matches. Now, the score and team information will be shown correctly after the side change.

## 1.2.4

### Fixes

- Two modifications to the minimap:
  - Added a subtle glow around player dots to improve visibility, especially with darker color choices
  - Added adaptive contrast for player numbers on the minimap
- Enlarged and readjusted the image of the focused player (in the central frame)
- The display in the top left corner now correctly shows which team picked the map in a BO3/5 if the team is customized

## 1.2.3

### New features

- Player colors on the minimap are now synchronized with HUD colors (change in the config to sync them).
- Polishing the end-game scoreboard:
 - New animation for the end-game scoreboard, it's smooth and pretty, let us know what you think.
 - Display of the map MVP based on K/D, in a nice golden frame.
- In the "maps" tab, if you don't configure anything, the map you're currently viewing will be displayed by default in the top left!
- Revamped "MyHUD" CFG, no more binds, you can simply type "exec MyHUD" in your console to disable the game's default HUD directly.
- Review and update of the "help & tutorials" tab in the app.

### Fixes

- The timer no longer weirdly drops in the middle of the screen at round 0.
- The timer used to show 1:00, then 60, then 0:59 during each round. The countdown now correctly goes from 1:00 to 0:59.
- Round 25 was not recognized as overtime.
- Changed the ports of the entire application and configuration files to avoid interference with other software/HUDs.
- Removed the background video from the software for optimization.
- Player names who plant or defuse the bomb are correctly overridden if you change their nickname in the "Players" tab.
