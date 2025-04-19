Using-the-Autopsy-retrieve-the-deleted-files
AIM:

To use Autopsy in Kali Linux to retrieve and analyze deleted files from a disk image.
DESIGN STEPS:
Step 1:

Open Autopsy and create a new case with appropriate case details.
Step 2:

Add a disk image as a data source and let Autopsy analyze the content.
Step 3:

Navigate to the "Deleted Files" section in Autopsy and examine or recover the deleted files.
PROGRAM:
1. Copy Files to the Virtual Disk

    Open File Explorer → Go to the new drive (C: or D:), where the folder created in the New Virtual Disk
    Create a new folder (Autospy) and copy images or files into it.

2. Delete the Files

    Select any one or two images → Press Delete.
    Empty the Recycle Bin to permanently delete them.

3. Recover Deleted Files Using Autopsy
Open Autopsy & Create a New Case

    Launch Autopsy and Run as a administrator

    Click Create New Case.
    image

    Enter a Case Name (e.g., Autopsy1).

    Choose a Case Folder location.

    Click Next → Click Finish.

image
Add the Virtual Disk as an Evidence Source

    Click Add Data Source → Select Host image

    Select Local Disk → next image

    Select Disk → Choose the VHD drive (Drive1)

image

    Click Next → Keep default settings → Click Finish.
    Wait for Autopsy to process the disk.

Recover Deleted Files

    Go to File Views (left panel).
    image image

    Click Deleted Files → Find your deleted images.

    Right-click an image → Click Extract File.
    image

    Select a folder to see the recovered files (e.g., C:\forensic).

    Image is recovered successfully.

Output :
Folder before deleting the files

image
Folder after deleting the files

image
Folder after extracting the deleted images using autopsy

image
RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.
