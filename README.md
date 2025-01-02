# MutatedModManager

MutatedModManager is a powerful and user-friendly tool designed to streamline the creation and management of mods for DayZ. Whether you're a seasoned modder or just getting started, MutatedModManager provides all the necessary features to convert, configure, and package your custom assets efficiently. Packed into a standalone executable, it ensures a hassle-free experience without the need for additional dependencies.


MutatedModManager is designed with user friendly experience while still providing limited customization depending on the mod, as each mod will have something slightly different at the least. A program to help server owner's manger mod settings on their servers, it streamlines the scripting/modifications needed to implement options and even assets and offers the user the option to streamline the .pbo packing process, speeding up the process and minimizing confusion on what does what and how it works.

This will change over time depending on what mods are being supported and added over time. (NOTE: Keep in mind, if a mod updates this may need to)

I will try to work closely with the mod owner's though, some may just be added due to user demand and need for it. This program will not require you to take or use any mod in a way that would be against the mod author permissions and/or requests. (If the mod author allows for it to happen, then it can happen)

This program does not intend to cover all features as this is a **__FREE VERSION__** and the **__PRO VERSION__** will include many more enhanced and complex capabilities that will enhance the user's experience ten fold. The free version will cover the main feature to both versions and that is user friendly experience, its just a bit more limited with the free version.

Mod Manager Selection Window
![MutatedModManager](https://github.com/user-attachments/assets/a49fffe6-0208-4737-8058-08fc2a51b06b)


FoX's Music Manager Window
![01 01 2025_00 27 07_REC](https://github.com/user-attachments/assets/d312e96a-4d22-4341-b687-b220af4f4bae)

## Supported Mods:

### FoXyRadio
### RadioFungi
### X-RED4CTED-X Sound Grenades

## Features
User Authentication: Secure login system with account creation to manage access.
Song Management: Easily add, edit, and organize single songs or playlists.
Audio Conversion: Convert MP3 files to OGG format for optimal compatibility.
Script Generation: Automatically generate necessary C++ configuration scripts for DayZ mods.
PBO Packaging: Package your mods into .pbo files ready for deployment using DayZTools.
Theming: Customize the application's appearance with multiple themes for a personalized experience.
Music Player: Built-in music player to preview your audio files directly within the application.
Logging and Error Handling: Comprehensive logging for monitoring operations and troubleshooting issues.

## Requirements
Before using MutatedModManager, ensure that your system meets the following requirements:

Operating System: Windows 10 or later.
DayZ Tools: Installed and configured. Download DayZ Tools
Internet Connection: Required for authentication and downloading necessary components.
Installation
Download the Executable:

Visit the [MutatedModManager GitHub Releases](https://github.com/Drews-Tools/MutatedModManager/releases) page and download the latest MutatedModManager.exe file.

## Extract the Files:

If the executable is part of a compressed archive (e.g., .zip), extract all contents to your desired installation directory, for example, C:\MutatedModManager.

## Launch the Application:

Navigate to the installation directory and double-click on MutatedModManager.exe to launch the application.

### Getting Started
Launching MutatedModManager
Upon launching MutatedModManager, you will be greeted with a sleek and intuitive interface. The main window provides access to all the essential features required to manage your DayZ audio mods.

## Logging In:

On the first launch, you'll need to create an account to access all features.

### Creating an Account:

Click on the "Create Account" button.
Fill in the Username and Email fields.
Click "Create Account".
A randomly generated password will be provided. Ensure you store this password securely, as it won't be displayed again.
After successful creation, return to the login screen.

### ## Logging In:

Enter your Username/Email and Password.
Optionally, check "Remember Me" to stay logged in on future launches.
Click "Login".
Upon successful authentication, you'll gain access to all functionalities of MutatedModManager.
Note: Authentication data is securely managed through GitHub's private repository. Your credentials are never exposed or stored insecurely.


### Adding a Single Song:

Navigate to Add Song.

In the main interface, click on the "Add Song" button to open the Add Song dialog.

### Fill in Song Details:

Class Name: Unique identifier for the song within the mod.
Display Name: The name displayed in-game.
Description: Brief description of the song.
Soundset: Defines the sound characteristics.
SoundShader: Links the audio file to the soundset.
Texture: Assign a custom texture if needed. (This is a Pro Feature)

### Select SoundShader:

Use the SoundShader dropdown to select from available soundshaders.
The Soundset field auto-populates based on the selected soundshader.

### Save the Song:

Click "Save" to add the song to your mod configuration.
The song will appear in the main song list within MutatedModManager.

### Navigate to Playlist:

Click on the "Create Playlist" button to switch to the Playlist management interface.
Fill in Playlist Details:

Class Name: Unique identifier for the playlist.
Display Name: The name displayed in-game.
Description: Brief description of the playlist.
Configure Playlist Entries:

Use the "Available SoundShaders" list to select multiple soundshaders.
Click "Add Selected SoundShaders" to include them in the playlist.
The selected entries will populate the Playlist Configuration section.

### Manage Playlist Entries:

To remove an entry, select it from the playlist and click "Remove Selected".

### Save the Playlist:

Click "Save Playlist" to add the playlist to your mod configuration.
The playlist will appear in the main song list within MutatedModManager.
Editing Existing Entries

### Select an Entry:

In the main song list, select the song or playlist you wish to edit.

### Edit Entry:

Click on the "Edit Selected" button to open the Edit Song dialog.
Modify the desired fields as needed.

### Save Changes:

After making the necessary changes, click "Save" to update the entry.
The changes will reflect immediately in the main song list.
Configuring Directories

## DayZTools Directory:

Click on the "Browse" button next to the DayZTools Directory field.
Navigate to the installation path of DayZTools (e.g., C:\Program Files (x86)\Steam\steamapps\common\DayZTools).
Select the directory to ensure MutatedModManager can access necessary executables.

### Source and Destination Directories:

Source Directory: Location where your MP3 files are stored.
Destination Directory: Where converted OGG files and mod configurations will be saved.
Use the "Browse" buttons to select the appropriate directories.
Note: Ensure that the selected directories have the necessary read/write permissions to allow MutatedModManager to perform operations seamlessly.

### Generating Scripts and Packing PBO:

After adding all desired songs and configuring directories, click on the "Create" button.

### Review Warning:

A warning message will appear emphasizing the importance of using copyright-compliant material.
Acknowledge the warning to proceed.

### Choose Packing Option:

Continue with Pack: Converts your mod into a .pbo file using DayZTools.
Continue without Packing: Generates scripts without packaging.

### PBO Packing Options:

If you choose to pack, select between "Use Existing Key" or "Create New Key".
Use Existing Key: Browse and select your existing .biprivatekey file.
Create New Key: Enter a name for the new key to be generated.

### Process Completion:

A loading dialog will display the progress of the conversion and packaging process.
Upon completion, you'll receive a success message.

## Access Packed Mod:

The generated .pbo file will be located in your specified destination directory, ready for deployment in DayZ.
Note: Properly managing your PBO keys is crucial for mod authentication and distribution. Ensure that your keys are securely stored and backed up.

## Theming and UI Customization:

### Changing Themes:

Navigate to the "Settings" section within the main interface.
Select your preferred theme from the available options (e.g., Light, DarkGreen, DarkBlue, Purple).

### Applying Themes:

Upon selection, the application's appearance will update immediately to reflect the chosen theme.
Themes adjust background colors, text colors, and UI element styles for optimal visibility and aesthetics.

### Saving Preferences:

Your theme preference is saved automatically and will persist across sessions.
To switch themes, simply revisit the "Settings" section and select a different option.

## Music Player:

### Selecting Music Directory:

In the "Music Player" section, browse and select the directory containing your .mp3, .ogg, or .wav files.

### Playback Controls:

Play/Pause: Toggle playback of the selected track.
Next/Previous: Navigate through your music library.
Volume Control: Adjust the playback volume using the slider.

### Playback Features:

Continuous playback ensures that your music runs smoothly without interruptions.
The player automatically transitions to the next track upon completion of the current one.

## Troubleshooting:

### Authentication Failures:

Issue: Unable to log in or create an account.
Solution: Ensure that you have an active internet connection. If problems persist, contact support via the [GitHub Issues](https://github.com/Drews-Tools/MutatedModManager/issues) page.

### Missing DayZTools Executables:

Issue: Application reports missing executables in DayZTools directory.
Solution: Verify that DayZTools is correctly installed. Reinstall if necessary and ensure that the path selected in MutatedModManager points to the correct installation directory.

### Audio Conversion Errors:

Issue: Failed to convert MP3 to OGG.
Solution: Check that your source directory contains valid .mp3 files. Ensure that you have sufficient permissions to read and write in the selected directories.

### PBO Packaging Failures:

Issue: Errors during PBO packing process.
Solution: Confirm that your DayZTools installation is functional. Ensure that the necessary keys are correctly selected and that the mod directory is properly configured.

### UI Glitches or Freezes:

Issue: Application becomes unresponsive or displays graphical glitches.
Solution: Restart MutatedModManager. If the problem continues, ensure that your system meets the required specifications and that your graphics drivers are up to date.
For unresolved issues, please submit a detailed report on the [GitHub Issues](https://github.com/Drews-Tools/MutatedModManager/issues) page.

Contributing
MutatedModManager is an open-source project, and contributions are welcome! Whether you're reporting bugs, suggesting features, or submitting code, your input helps improve the tool for everyone.

## License

### MutatedModManager is released under the MIT License.

Acknowledgements
FoX's Den DayZ Community: For their invaluable resources and support in mod development.
