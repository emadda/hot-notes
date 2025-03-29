<p align="center">
  <a href="https://github.com/emadda/hot-notes/raw/main/HotNotes.dmg" download>
    <img src="./misc/img/blue-download-button.svg" alt="Download HotNotes for macOS">
  </a>
</p>

<p align="center">
  <em>After downloading, open the file, and drag and drop the <code>HotNotes</code> app onto the <code>Applications</code> folder.</em>
</p>

# Intro

- Hot Notes is an app to quickly open any folder or note in Apple Notes using fuzzy search.
- The search window can be opened from anywhere using a keyboard shortcut.



https://github.com/user-attachments/assets/252dd85b-2e64-4d60-a7d6-97af40216ad2

- Note: The videos have audio.
- Tip: When searching use the first two letters of each word. No space is needed.
	- E.g. Finding a note titled "Exporting Artwork", you can find it with "exar".


# Installing

https://github.com/user-attachments/assets/3038b680-dff5-437b-b0cb-54ee623769c7


# Create a keyboard shortcut to open Hot Notes

https://github.com/user-attachments/assets/564d0bff-d619-4335-9ebf-97eec93bec5f


# How Hot Notes differs from other Apple Note jumpers

- Stays fast with large numbers of folders and notes.
	- It has been tested with 10,000 folders and notes, and should perform ok with higher numbers.


- Fuzzy search.
	- This allows you to type just the first few letters of every word to find a match.


- No key logging.
	- Hot Notes uses the Apple Shortcuts program for launching, so it does not need to key log all of your keystrokes to watch for a keyboard shortcut.
	
- No full disk access.
	- Some of the other jumper programs use the Full Disk Access permission which lets them read all of your files and data on your Mac.
	- Hot Notes just requests access to the directory with your Apple Notes.
	
- Does not connect to the internet.
	- Hot Notes does not connect to the internet for any reason.

- Signed code only.
	- Hot Notes is [notarized](https://developer.apple.com/documentation/security/notarizing_macos_software_before_distribution) by Apple.
	- See [What is Apple Notarization](#what-is-apple-notarization).
	- Other apps have plugin systems which means the code is not checked by Apple, and developers may not be verified.




# What is Apple Notarization

Hot Notes is [notarized](https://developer.apple.com/documentation/security/notarizing_macos_software_before_distribution) by Apple, which has the following benefits:

- It has been scanned and verified to be malware free.
- The app cannot be modified in any way, so the code that was checked by Apple is the code that runs.
- The developer ID is verified.
- Apple can remotely disable any apps found to contain malware in the future.

