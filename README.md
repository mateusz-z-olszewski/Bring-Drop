# PowerShell Script: BringDrop

## Description
This simple utility program brings files/folders which have the `Dekstop` folder as one of its ancestors in the folder tree.

## Usage
1. Download script and refer to it in the `$profile` powershell file
2. To bring files/folders onto the Desktop, use `bring filename`. If there is more than one file/folder matching your query, you will be prompted to choose one of them.
3. To return a file/folder, use `drop filename`