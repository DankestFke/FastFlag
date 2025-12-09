### TL:DR 

Set /ClientSettings/IxpSettings.json to read-only after changing fastflags.


Open Roblox’s Local Folder
Press **`Win + R`** on your keyboard.

Type **`%localappdata%\Roblox`**
Press Enter

Navigate to ClientSettings

Open the folder:
**`/ClientSettings`**

Inside it, find the file:
**```IxpSettings.json```**

(If the folder or file doesn’t exist, you may need to create them.)

Import Your FastFlags

Open IxpSettings.json with a text editor

Paste or edit your FastFlags.

Save the file and close the editor.

Lock the File (Important!)

<img width="389" height="99" alt="image" src="https://github.com/user-attachments/assets/3a71bc01-2412-404d-b74b-39b8ea2bbfdb" />


Right-click on **IxpSettings.json**.
Select **Propertie**s.
Check the box **Read-only**.


Click **Apply**, then OK.

This step is necessary because if you don’t set the file to Read-only, Roblox will overwrite it with defaults the next time you launch the client. Without this, you’d have to redo the setup every time.
