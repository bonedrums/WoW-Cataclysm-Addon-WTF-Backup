<div align="center">
  <img src="https://github.com/user-attachments/assets/6028388e-2cf9-4923-9af9-84551d09604a" alt="Image" />
</div>

# WoW Cataclysm Addons and WTF Backup

This Python program facilitates backing up World of Warcraft (WoW) Classic addon and configuration files from specific directories to a chosen destination. It uses a graphical user interface (GUI) built with customtkinter for a modern look and functionality.

## Features

- **Backup Creation:** Allows selection of directories containing WoW addon and configuration files.
- **Zip and Move:** Archives selected directories into a timestamped ZIP file and moves it to the chosen backup destination.
- **Progress Tracking:** Displays real-time progress of the backup process including file-by-file progress and overall completion percentage.
- **Cancel Backup:** Provides an option to cancel the backup process at any time.

## Dependencies

### Running from Python

- Python 3.x

Install customtkinter using pip: ('pip install customtkinter')

## Usage

3. **Follow On-screen Instructions:**
   - Select backup directories and options using the GUI.
   - Start the backup process by clicking "Start Backup".
   - Cancel backup at any time by clicking "Cancel Backup".

### Running from Python

1. **Install Dependencies:**
   - Make sure Python 3.x is installed.

     ```
     pip install customtkinter
     ```
     ```
     pip install requests
     ```

2. **Launch the Script:**
   - Open a command prompt.
   - Navigate to the directory containing `backup_wow_addons_wtf.py`.
   - Run the script:
     
     ```
     python backup_wow_addons_wtf.py
     ```

3. **Follow On-screen Instructions:**
   - Select backup directories and options using the GUI.
   - Start the backup process by clicking "Start Backup".
   - Cancel backup at any time by clicking "Cancel Backup".

## Instructions

- Ensure Python and required dependencies are installed if running from Python.
- Ensure sufficient disk space and permissions for writing to the selected backup destination.
