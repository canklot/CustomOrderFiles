# SortMyFiles VSCode Extension

Re-order files and folders in VS Code explorer. Create a file named `.order` in the root of your workspace.
List the file names in the order you wish. One line for a file. Example:

    VeryImportantFolder
    MyFolder/MyCode.js
    MyFolder/MyLibrary.js
    ImportantFile.js
    LessImportantFile.js

## How it works

Changes file sorting to last modified date.
Everytime a save detected extension activates.
Changes the last modified date of the files specified in the `.order` file.
Only works if you open a worspace (folder)

[VSCode Marketplace Page](https://marketplace.visualstudio.com/items?itemName=CanklotSoftware.SortMyFiles)

## Known Issues

Folders are always displayed first.

If you face any problems, you can find the logs in `OUTPUT` tab. From the drop-down menu you can select `SortMyFiles`  and check the logs.

## Screen Shots

BEFORE             |  AFTER
:-------------------------:|:-------------------------:
![](images/before.png)  |  ![](images/after.png)

## Release Notes

### 0.1.0

Initial release of extension


