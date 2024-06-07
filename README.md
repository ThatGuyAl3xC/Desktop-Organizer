# Desktop-Organizer

The Desktop Organizer is a simple script designed to help you keep your desktop or any specified folder organized by automatically sorting files into subfolders based on their file extensions. This tool can help maintain a clean and tidy workspace, improving productivity and reducing clutter.

# Features
* Automatically sorts files into subfolders based on their extensions.
* Creates subfolders if they do not already exist.
* Handles file movements and skips files that already exist in the destination subfolder.

# Requirements
* Python

# Installation
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/desktop-organizer.git
   cd desktop-organizer
   ```
2. No additional packages are required beyond standard Python library.

# Usage
1. Open the script file `DesktopCleaner.py` in your preferred text editor.

2. Set the `folder_path` variable to the path of the folder you want to organize
   For example:
   ```folder_path = '/Users/YourUsername/Downloads'```
   
3. Run the script:
4. The script will scan the specified folder, create subfolders for each file type (if they do not already exist), and move the files accordingly

# How it works
The script performs the following steps:

1. Scans the specified folder for files.
2. Determines the file extension of each file.
3. Creates a subfolder for each file type (if it does not already exist).
4. Moves the files to the corresponding subfolders.
5. Skips files that already exist in the destination subfolder to prevent duplicates.

# Acknowledgements
This simple script was created to help keep workspaces organized and improve productivity.

