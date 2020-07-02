# PasteWithFolderStructure
Tool to Paste files with maintaining folder structure

This Tool helps you overcome the problem many have faced similar to me.
I need to provide patch with only changed files to a customer and that too maintain the folder structure.

Steps to Get Started:
### 1. Checkout this attached PasteWithFolderStructure.exe
### 2. Take Full path of the exe
    ex : D:\Uthis\pwfs\trunk\PasteWithFolderStructure.exe
### 3. Open Registry 
    Press Win + R; type regedit and press Enter
    
![Registry](https://github.com/uthistran/pastewithfolderstructure/blob/master/blob/master/images/1.PNG)

### 4. Navigate to "Computer\HKEY_CLASSES_ROOT\Directory\Background\shell"

### 5. Add New key to the shell
    Right Click and Add New Key
    
### 6. Rename the key to your wish. I used PasteInFolderStructure
    This Name will be shown on context menu

### 7. Add new key called command in PasteInFolderStructure.
    The final look will be as below
![Registry2](https://github.com/uthistran/pastewithfolderstructure/blob/master/blob/master/images/2.PNG)


### 8. In the right side window, Right Click on Default and select modify
    Add the file path of the PasteWithFolderStructure.exe within quotes in Value data
![Registry3](https://github.com/uthistran/pastewithfolderstructure/blob/master/blob/master/images/3.PNG)    


### Now we are all set to use this tool

Copy any File/Files in a folder
Right click where you wan to paste the file(s) in folder structure
Click on PasteInFolderStructure (or the name you gave in step #6)
A window will display to select the base folder
![Tool1](https://github.com/uthistran/pastewithfolderstructure/blob/master/blob/master/images/4.PNG)  
Click the folder from which you want to maintain folder structure and click paste. I have selected Test in it
Your file(s) will be pasted with folder structure
