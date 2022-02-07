# Zotero-Dark-Theme
userChrome.css file for a Zotero dark theme. Suggestions for improvements are welcome.

Created for Zotero 5.0.92. Windows 10 compatible. Cannot vouch for other OSes.

<p align="center">
<img src="https://github.com/Rosmaninho/Zotero-Dark-Theme/blob/main/zotero_refined_2.png"  width="600" height="333" />
</p>

To use it follow the following steps:

1 - Go to your user Profile folder - C:\Users\User_name\AppData\Roaming\Zotero\Zotero\Profiles\user_profile.default\

2 - Create a chrome folder,

3 - Place the userChrome.css file in there,

4 - Start Zotero and enjoy


I  encourage everyone to play around with this and try to improve on it and theme things that I didn't manage to. These include the following elements:

1 -  couldn't theme the scrollbars (even tried creating a userContent.css  like in Firefox but it didn't work), 

3 - the  menus colors,

4 - the New Item sub-menu in the File drop down menu (it assumes the white color of the menu categories),

5 - the sub-categories in the Preferences dialog. I am not satisfied with the preferences dialog but it's the best I could make it.


If you wish to explore for additional elements to alter:
1 - Go to the folder of my Zotero install (C:\Programs(x86)\Zotero); 

2 - Copy the zotero.jar folder to another folder; 

3 - Use 7zip to unzip zotero.jar to a zotero folder; 

4 - Go to D:\X\zotero\chrome\skin\default\zotero; 

5 - Look at ALL .css files in this folder; 

6 - Start testing different pieces of code to change the defaults in the userchrome.css file.

To implement a dark theme in the Note Editor (credit to 10cks) follow the following steps:

1 - Start Zotero;

2 - Go to Preferences -> Advanced -> Config Editor;

3 - Select "I accept the risks!";

4 - Search extensions.zotero.note.css and double-click it;

5 - Insert the string in the Note_editor_css.txt file;

6 - click "OK" or close the dialog box;

7 - Restart Zotero.
    
