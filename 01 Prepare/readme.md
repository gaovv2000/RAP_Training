# Prepare

### 1. ABAP environment
>- S4HANA OP / S4HANA PCE / S4HANA Cloud / BTP ABAP enviroment
### 2. Eclipse ADT (Development CDS view) 
> - Download the zip file of [Eclipse](https://www.eclipse.org/downloads/packages/)
>> - Unzip to a working directory.
> - Install  ADT to Eclipse.
>> - Open the Eclipse 
>> - If you are opening it for the first time, please select a directory as your workspace. 
>> - Open the menu **Help->Install New Software**
>> - Input https://tools.hana.ondemand.com/latest.
>> - Select ABAP Development Tools and click the Next button. On the Install page, click the Finish button.
>> - When finished, click the restart confirmation button that pops up.
> - Connect to ABAP environment
>> - Open the menu **File->New->ABAP Project*
>> - Select the SAPGUI configuration and click Next.
>> - Configuration Connection Settings and click Next.
>> - Enter your ABAP system connection details, such as the client, user, Password, and Language, and click finish.
### 3. Visual Studio Code (Development Fiori Apps)
> - Download the zip file of [Visual Studio Code](https://code.visualstudio.com/download)
>> - Unzip to a working directory
> - Install Extensions in VS Code
>> - Open Visual Studio Code
>> - Click on the Extensions icon on the sidebar, or use the shortcut Ctrl+Shift+X (Windows/Linux) or Cmd+Shift+X (macOS) to open the Extensions view.
>> - Search for SAP Fiori tools or click [VS Code marketplace link](https://help.sap.com/docs/link-disclaimer?site=https%3A%2F%2Fmarketplace.visualstudio.com%2Fitems%3FitemName%3DSAPSE.sap-ux-fiori-tools-extension-pack)
>> - Click on the 'Install' button. Wait for the plugin to finish installing.
> - Connect to ABAP environment
>> - Click on the Extensions icon on the sidebar
>> - Open the Command Palette with Ctrl+Shift+P (Windows/Linux) or Cmd+Shift+P (macOS).
>> - Type "Fiori: ADD SAP System" and select it.
>> - Enter your ABAP system connection details, such as the server URL, client, user, and password.
>> - Click "Test connection"
>> - Last, click "Save"
### 4. Nodejs 
>- Download the zip file of [Nodejs win x64 ](https:///nodejs.org/dist/v20.14.0/node-v20.14.0-win-x64.zip)
> - Unzip to a working directory
> - Add unzip directory to OS nviornment variables Path
> - Test command 'node -v' and 'npm -v' in CMD
