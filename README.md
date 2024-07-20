# Simple Journal Application

## Overview
This is a command-line journal application that allows users to create, edit, and view journal entries. It's designed for easy daily use and personal reflection.

## Features
- Add multi-line journal entries
- Edit existing entries
- View all entries or a specific entry
- Unique IDs for each entry
- JSON storage for data persistence

## Requirements
- Python 3.6+

## Installation
1. Clone the repository:
   ```
   
   ```

## Usage
Run the application:
```
python main.py
```

Follow the on-screen menu to:
1. Add a new entry (use ':q' to save, ':x' to cancel)
2. Edit an entry
3. View all entries
4. View a specific entry
5. Exit

## File Structure
- `main.py`: Entry point of the application
- `journal_app.py`: Manages the user interface
- `journal.py`: Handles entry management and file I/O
- `journal_entry.py`: Defines the JournalEntry class
- `journal.json`: Stores journal entries

## Contributing
Contributions are welcome. Please fork the repository and submit a pull request with your changes.
