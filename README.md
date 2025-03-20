<img src="https://github.com/user-attachments/assets/c4a846be-a88e-4474-a66c-a37b10334727" width="300">

# voidtools
Locate files and folders by name instantly

## How It Works?
![image](https://github.com/user-attachments/assets/e2084e7e-39c3-4b90-afe1-aaff912967d3)

## What is "Everything"?
"Everything" is search engine that locates files and folders by filename instantly for Windows.

Unlike Windows search "Everything" initially displays every file and folder on your computer (hence the name "Everything").

You type in a search filter to limit what files and folders are displayed.

## How long will it take to index my files?
"Everything" only indexes file and folder names and generally takes a few seconds to build its database.

A fresh install of Windows 10 (about 120,000 files) will take about 1 second to index.

1,000,000 files will take about 1 minute.

## Does "Everything" hog my system resources?
No, "Everything" uses very little system resources.

A fresh install of Windows 10 (about 120,000 files) will use about 14 MB of ram and less than 9 MB of disk space.

1,000,000 files will use about 75 MB of ram and 45 MB of disk space.

## Does "Everything" monitor file system changes?
Yes, "Everything" does monitor your file systems for all changes.

Your search results will update in real-time to reflect any changes.

Everything will automatically keep your NTFS indexes up to date with the NTFS USN Journal.

Changes will not be missed when Everything is not running as the system maintains the NTFS USN Journal.

## Is "Everything" free?
Yes, "Everything" is Freeware.

Please consider donating.

## Does "Everything" contain any malware, spyware or adware?
No, "Everything" does not contain any malware, spyware or adware.

## Does "Everything" miss changes made to the file system if it is not running?
No, "Everything" can be closed and restarted without missing changes made to the file system (even across system restarts).

"Everything" updates the database when it is started.

## What are the system requirements for "Everything"?
"Everything" will run on Windows XP, Vista, Windows 7, Windows 8, Windows 10 and Windows 11.

NTFS indexing requires the Everything service or running "Everything" as administrator.

## What is the Lite version of "Everything"?
The Lite version of Everything is the same as the normal multilingual version of Everything, except it has some features removed:

- Removed ETP/FTP Server.
- Removed HTTP Server.
- Removed IPC.

The Command line interface / ES will not work with the Lite version.
The SDK will not work with the Lite version.
Windows accessibility features and screen readers will not work with the Lite version.

## How do I index a FAT volume?

To add a FAT, FAT32 or exFAT volume to your Everything index:
- In "Everything", from the Tools menu, click Options.
- Click the Folders tab on the left.
- Click Add....
- Select your FAT volume and click OK.
- Click OK.

## How do I index a mapped network drive/NAS/Network share?

To add a mapped network drive/NAS/Network share to your Everything index:

- In "Everything", from the Tools menu, click Options.
- Click the Folders tab on the left.
- Click Add....
- Select the mapped network drive/NAS/Network share and click OK.
- Click OK.

**If network drive is not listed in Everything, please try running Everything as a standard user:**

- In "Everything", from the Tools menu, click Options.
- Click the General tab on the left.
- Check Everything service.
- Uncheck Run as administrator.
- Click OK.
- Restart "Everything" (right click the Everything tray icon and click Exit).

## How do I convert a volume to NTFS?
Please backup anything important before converting a volume to NTFS.

Once a volume is converted to NTFS it can not be converted back to FAT, FAT32 or exFAT without reformatting.

Please note that some devices may not be able to read NTFS volumes on USB disks / USB drives.

To convert a volume to NTFS:

- From the Start menu, search for: cmd
- Click Command Prompt.
- In the command prompt, type in the following and press ENTER:
convert D: /fs:ntfs
where D: is the drive to convert.

## How do I install "Everything"?
Install from Releases

