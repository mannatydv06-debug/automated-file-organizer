Automated File Organizer — Interactive Version

A Python utility that sorts files into category folders by extension. It previews planned changes and requires confirmation before moving files.

Features :-
Prompts for source and destination directories
Categorizes files as Images, Documents, Archives, Media, Code, or Others
Shows a preview before changes
Requires typing YES before moving files
Prevents overwrites by adding suffixes such as _1
Skips subdirectories and the running script
Writes an organizer_log.txt execution log
Reports invalid paths and file-system errors

Requirements :-
Python 3.9+ recommended
No third-party packages

Run :- 
python main.py
Enter the path to a folder containing sample files, then a different destination folder. Check the preview and type YES only if it is correct.

Safe Test :- 
Create a test folder named organizer_test.
Copy a few non-important files into it, such as .txt, .png, .pdf, and .py files.
Choose a separate destination such as organized_test.
Review the preview before confirming.
Check the category folders and organizer_log.txt.
Do not test first on your Downloads folder or on important files.

Categories :-
Images: .png, .jpg, .gif, .svg
Documents: .pdf, .docx, .txt, .xlsx, .pptx
Archives: .zip, .rar, .7z, .tar
Media: .mp3, .wav, .mp4, .mkv
Code: .py, .java, .cpp, .html, .css, .json
Others: extensions not listed above

Safety Notes :- 
The program does not recursively organize subdirectories. Files in use or blocked by permissions may fail to move and will be reported. Moving files changes their location, so keep backups of important files.

Concepts Practised :- 
pathlib, shutil, dictionaries, functions, input validation, exception handling, and file automation. 