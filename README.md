### Description: 
Currently, the web file-manager that CompleteFTP supports is based on the elFiner file manager (more information can be found [here](https://enterprisedt.com/products/completeftp/doc/guide/html/howtousefilemanager.html)).
However, it's possible that you can replace the existing file-manager by a more modern, multilingual one and a better solution for mobile. And what we recommend you to try is the [angular file-manager](https://github.com/joni2back/angular-filemanager).
You can either replace the existing file-manager by the new one or still use them both side by side.

The following are the step-by-step instructions on how to install the angular file-manager in CompleteFTP in two different ways.

### 1. Install the angular file-amanger and still keeps the existing one.

**1.** First, clone the repository of the web file-manager [here](https://github.com/EnterpriseDT/completeftp-filemanager).

**2.** Then launch the *CompleteFTP Manager* and go to the *Folders* panel.
 
![Select Folders panel](/img/selectFolderPanel.png)

**3.** Click *Add root folder* at the top of the panel and select *Windows Folder* menu item to add a root Windows folder in the virtual file-system.

![Add root Windows folder](/img/addRootWindowsFolder.png)

**4.** Then map it to the cloned folder (i.e. *completeftp-filemanager*) in the Windows file-system and press *OK* button.

![Mapping folder](/img/mapFolder.png)

**5.** (Optional) Change the name of the newly created folder to whatever you like by clicking the ellipsis button of the *Name* property, typing a name (e.g. *NewFileManager*) and pressing *OK* button. 

![Change folder name](/img/changeFolderName.png)

**6.** Click *Apply changes* button to save the changes to the CompleteFTP server.

![Apply change](/img/applyChanges.png)

**7.** Now, open a web browser, navigate to your CompleteFTP server (e.g. http://myserver), and login if you haven't logged in yet.

![Login](/img/login.png)

**8.** After logging in successfully, navigate to the new file-manager at http://myserver/NewFileManager.

![New File-Manager](/img/installFileManagerResult.png)


### 2. Replace the existing file-amanger by the new one.

**1.** First, clone the repository of the web file-manager [here](https://github.com/EnterpriseDT/completeftp-filemanager).

**2.** Then launch the *CompleteFTP Manager* and go to the *Folders* panel.

![Select Folders panel](/img/selectFolderPanel.png)

**3.** Show the system folders by checking the *Show system users/folders/sites* in the main form's Options menu.

![Show system users/folders/sites](/img/showSystemFolders.png)

**4.** Select the *FileManager* folder in the folder list and change its path by clicking the ellipsis button of the *Path* property.

![Select File Manager](/img/selectFileManagerFolder.png)

**5.** That will bring up the *Select a folder* dialog. Select the cloned folder (i.e. *completeftp-filemanager*) in the Windows file-system and click *OK* button.

![Mapping folder](/img/mapFolder.png)

**6.** Click *Apply changes* button on the top-right of the CompleteFTP Manager.

![Apply change](/img/applyChanges.png)

**7.** Launch a web browser, navigate to your CompleteFTP server (e.g. http://myserver) and login.

![Login](/img/login.png)

**8.** After logging in successfully, the new file-manager will be loaded straight away.

![New File-Manager](/img/replaceFileManagerResult.png)
 

