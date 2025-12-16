# Python File Organizer

This script automatically organizes files in a specified folder by sorting them into subfolders based on file type.

## How It Works
- Scans the target folder
- Detects file extensions
- Moves files into categorized folders (Images, Documents, Audio, etc.)

## Setup
1. Open `file_organizer.py` in VS Code
2. Change the `folder_path` to the folder you want to organize
3. Run the script

## Example
Before: Downloads/ ├── photo.jpg ├── resume.pdf ├── song.mp3

After: Downloads/ ├── Images/photo.jpg ├── Documents/resume.pdf ├── Audio/song.mp3

## Notes
- You can customize file types in the `file_types` dictionary
- Files with unknown extensions go to the "Others" folder
