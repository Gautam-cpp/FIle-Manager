# File Manager with Auto-Sorting

This is a Python-based file manager with automatic file sorting using `Tkinter` for the graphical interface and `Watchdog` for monitoring the file system. The application can automatically sort files into predefined categories (images, videos, music, and documents), provide cut, copy, and paste functionality, and allow users to delete and open files from the GUI.

## Features

- **Automatic Sorting**: Files are automatically sorted into categories (images, videos, music, documents) based on their extensions.
- **File Operations**: Cut, copy, paste, and delete files from the interface.
- **Directory Navigation**: Navigate through directories, open files or folders, and go back to the parent folder.
- **Watchdog Observer**: Continuously monitors changes in the source directory to automatically move new files to their appropriate category.
- **Logging**: Displays logs for file movements and other operations within the GUI.

## Installation

### Prerequisites

- Python 3.x
- Install the necessary Python libraries:
  ```bash
  pip install watchdog
