# Resource Hacker
![Old Version of Resource Hacker](https://web.archive.org/web/20060208015850im_/http://angusj.com/resourcehacker/specialmenu.gif)

Old Version of Resource Hacker[^1]
	
## Introduction
![Logo of Resource Hacker](https://upload.wikimedia.org/wikipedia/en/2/2f/Resource_hacker_icon.png)

Logo of Resource Hacker[^2]

Resource Hacker is a file/resource editing tool on Windows developed by Angus John, which has more than 20 years of history. It was initially released in December 1999 and has been continuously updated throughout the years. This resource editor has a graphical user interface (GUI) that can help users easily view the internal resource of an executable program (.exe) or resource file (.res)[^3] in an intuitive and organized structure. This tool also allows in-editor script writing, compiling, and decompiling so that users are able to create new resource or modify existing resource conveniently.

* Type: Resource Editing Tool (Editor/Compiler/Decompiler)
* Developer: Angus Johnson
* Initial Release: December 3, 1999
* Latest Version: 5.1.8 (November 20, 2020)
* Status: Free Download; Not Open-source
* Platform: Windows
* Language: English, Chinese, Japanese

## Download
The Resource Hacker software can be downloaded from its official website: http://www.angusj.com/resourcehacker/#download. The software can be downloaded in .exe or .zip format.
![Download](https://user-images.githubusercontent.com/47571034/158008900-d0373169-3b00-4e5c-bed2-209692ee8f1c.JPG)

Click "Next" to continue the installation:

![2](https://user-images.githubusercontent.com/47571034/158008976-9e3ad3b9-8cef-468d-92e4-56aedf60665c.JPG)

Click "Install" to continue the installation:

![3](https://user-images.githubusercontent.com/47571034/158008979-b2fca4e6-13fc-4372-9657-ab57dd54863e.JPG)

Click "Finish" to continue the installation:

![4](https://user-images.githubusercontent.com/47571034/158008982-ae649440-7219-4fd0-9d67-495286f19b93.JPG)

## Interface
Launch the software and the friendly user interface is shown on the screen. Since there is no file imported yet, the windows are blank.

![5](https://user-images.githubusercontent.com/47571034/158008989-ef552ecf-8f00-4ea2-9f9e-0799c344ef09.JPG)

* A menu bar on the top containing all actions (File, Edit, View, Action, Help)
* A tool bar to some quick file creating/loading/saving, list expanding/collapsing, copying/pasting, finding, and compiling
* A resource window on the left where the target program displays all its resource files as a list (tree)
* A script window on the right where the selected resource file is displayed as decompile script or binary format

## Functionality
### 1. Resource Browsing
After installing the software, we can now explore the functionalities of Resource Hacker. When a file is opened in Resource Hacker, the resource of this file is shown as a well-categorized list. From this list, there are folders with names such as AVI, Cursor, Bitmap, Icon, Menu, Dialog, and so on, which clearly indicate the content of the resource folder, helping users find the resource they want conveniently. After viewing the resource, users are able to save its content in different format for further usage.

Use **File >> Open** on the menu bar to select a target resource (ex. *.exe) to open in this editor.:

![Open a Resource](https://user-images.githubusercontent.com/47571034/158007676-1134f2f1-cc53-47dc-8546-cf8c4bbf2f0a.JPG)

Then the resource will be displayed as a list of folders in the left panel:

![List of Resource](https://user-images.githubusercontent.com/47571034/158007188-e58268d9-a31e-48b5-8d59-c38a8d9613c6.JPG)

Click on "Save As" button to save a selected component of the current resource to local:

![Save Button](https://user-images.githubusercontent.com/47571034/158007243-334afbfb-4992-4a0d-96f0-58b705825b19.JPG)

### 2. Software Optimization
Software optimization includes customization of software icon, cursor, bitmap, and other personalizable features. Users can also delete unused or useless resource from the target software to effectively reduce its memory usage. Contrary to that, users can add extra resources to the target software to expand its functionality range. Use the DropDown Menu via **Action** to modify or save resource component conveniently:

![Action Menu](https://user-images.githubusercontent.com/47571034/158008810-01da07f7-d1a1-44ab-bc31-c4692cfdc3c1.JPG)

The following table gives a quick guidance on how to realize desired modifications:

| Functionality        | Action           | Steps |
| ------------- |:-------------:| ------------- |
| Reduce Size of Software | Delete Unused Resource | Select Resource >> Action >> Delete Resource >> Click "Yes" |
| Add Esixting Resource to Software | Action >> Add an Image or Other Binary Resource/Add from a Resource file | Add an Image or Other Binary Resource/Add from a Resource file >> Select from Local Directory |
| Add New Resource to Software | Action >> Add from Blank Script/Add using Script Template | Add from Blank Script/Add using Script Template >> Write Script >> Compile >> Add to Software|
| Replace Target Resource | Action >> Replace Resource | Replace Resource >> Select a New Resource File from Local >> Specify the Resource Type/Name to Replace >> Click "Replace" |
| Modify Target Resource | In the Script Window | Decompile a Target Resource >> Edit the Script of Resource >> Recompile |
| Rename Target Resource | Action >> Rename this Resource | Rename this Resource >> Enter New Name >> Click "OK" |
| Change Resource Language | Action >> Change Language for this Resource/All Resources | Specify Language, Sub-language, or enter language code >> Click "Change" |

If you are not familiar with the language code while changing the language, this Microsoft Documentation Page might be very helpful: https://docs.microsoft.com/en-us/openspecs/office_standards/ms-oe376/6c085406-a698-4e12-9d4d-c3b0ee3dbc4a [^4]

### 3. Software Cracking
Software cracking a black hat usage of this editor, which will remove or modify some key resource of a program, making the target program disabled to realize some functionalities.

## Examples
### 1. Change Icon
1. Open the target program in Resource Hacker, whose icon is a blue flower.

<img width="432" alt="image" src="https://user-images.githubusercontent.com/47571034/158039263-45af6ecc-6365-4365-b401-2e70ba9272d1.png">

### 2. 

### 3. Software Cracking (by modifying the dialog)
In this case, the team would like to present how to modify or delete the content from a dialog window so that the user will be no longer able to use that functionality. The dialog we would lile to crack is the "Create New Compressed File" dialog below.

![14](https://user-images.githubusercontent.com/47571034/158043147-b90540bb-84e9-4e35-a6f3-ed141d79b4e1.JPG)

1. Open the target program (**File >> Open**); in our case the software to crack is winRAR.exe.

![10](https://user-images.githubusercontent.com/47571034/158043152-9b2ee43d-dd43-4aea-ac1c-2068e2b91ef1.JPG)

![11](https://user-images.githubusercontent.com/47571034/158043154-81b26f97-cff1-4a01-aac6-2ece3ddb1c3b.JPG)

2. The resource list is displayed on the left; expand the dialog tree.

![12](https://user-images.githubusercontent.com/47571034/158043158-d6ff4190-ebc7-450c-9992-5d71bef5cf90.JPG)

![13](https://user-images.githubusercontent.com/47571034/158043165-81232cbd-746d-4d2a-8027-6c59db39e4cc.JPG)

3. There are too many dialog files, which makes it difficult to find the one we want. However, we can search that dialog by keyword. It can be noticed that there is a word "update mode" in the dialog we want, so we click on the magnifier icon and enter the keyword "update mode". Then we successfully find it. When we click on a dialog resource, a template of that dialog window will be displayed on the right-bottom corner of the screen. Users can even drag each component on the template to re-locate them. In the meanwhile, the coordinates value of that component in the script will be changed as well to reflect the position changing.

![15](https://user-images.githubusercontent.com/47571034/158043253-3f0744cc-51b6-4fc5-ad43-ccbef91a924d.JPG)

![16](https://user-images.githubusercontent.com/47571034/158043308-ed9a9a6b-b6c2-49cb-8ddd-3f521d03022a.JPG)

4.Firstly, we would like to play with the dialog. How about changing the text for each radio button (for selecting the compressed file type) from "RAR, RAR4, ZIP" to "HELLO, WORLD, HAHA!". To do this, we need to find the information related to these radiobuttons from the decompiled result in the script window on the right.

![17](https://user-images.githubusercontent.com/47571034/158043391-1426239e-675a-4bf8-bab4-e12be5dcf444.JPG)

5. Change them into the text words we want.

![18](https://user-images.githubusercontent.com/47571034/158043406-ea8dcc12-79a3-42ad-b8d5-e58ace677c20.JPG)

6. Click the green compile button to recompile the script back into a resource file. Reopen the dialog and the text is replaced as expected.

![19](https://user-images.githubusercontent.com/47571034/158043425-33146220-8057-4a39-95f3-cfde21f69f31.JPG)

![20](https://user-images.githubusercontent.com/47571034/158043428-f3e0313e-6954-47d8-8d63-4d9f03d17663.JPG)

7. Finally, let's remove all other buttons or text information except leaving a message from hackers. Recompile the script and save the modified winRAR.exe program to local.

![21](https://user-images.githubusercontent.com/47571034/158043456-ce4d9d55-fc80-4148-a3f0-b278b788bd7e.JPG)

8. Open the modified program. When we try to compress a file, all the setting options are gone and this functionality has been disabled.

![23](https://user-images.githubusercontent.com/47571034/158043521-68e1c6d3-dacd-4dbe-8739-a1b0cd828206.JPG)

## Useful Links
* Official Website: http://www.angusj.com/resourcehacker/
* Basic Resource Hacker Tutorial: https://wexpert.webs.com/documents/Resouce%20hacker%20tutorial.pdf
* Scripts Syntax to Launch an Action: https://guidedhacking.com/resources/resource-hacker.32/

## References
[^1]: Resource Hacker Screenshot, [https://web.archive.org/web/20060208015850/http://angusj.com/resourcehacker/rh_shot.html](https://web.archive.org/web/20060208015850/http://angusj.com/resourcehacker/rh_shot.html).
[^2]: Wikipedia, [https://en.wikipedia.org/wiki/File:Resource_hacker_icon.png#/media/File:Resource_hacker_icon2.png](https://en.wikipedia.org/wiki/File:Resource_hacker_icon.png#/media/File:Resource_hacker_icon2.png).
[^3]: Resource Hacker, [http://www.angusj.com/resourcehacker/](http://www.angusj.com/resourcehacker/).
[^4]: Microsoft Docs, [https://docs.microsoft.com/en-us/openspecs/office_standards/ms-oe376/6c085406-a698-4e12-9d4d-c3b0ee3dbc4a](https://docs.microsoft.com/en-us/openspecs/office_standards/ms-oe376/6c085406-a698-4e12-9d4d-c3b0ee3dbc4a).
