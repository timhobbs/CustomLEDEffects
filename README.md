## Initial DOF Setup

- Open DOF global config editor
  ```
  c:\DirectOutput\GlobalConfigEditor.exe
  ```
  **NOTE:** This path is an exampe, your path may vary.
- Under `IniFiles` tab, click the `Select Ini File Path` button and select the folder where your ini files are stored:
  ```
  c:\DirectOutput\Config
  ```
  [[images\dof-ini.png]]
- Under `Cabinet Config` tab, click `Select File` and select you cabinext file:
  ```
  c:\DirecOutput\Config\Cabinet.xml
  ```
  [[images/cabinet-cfg.png]]
- Under `Logging` tab verify these settings:
  - Enable logging: checked
  - Log file: `c:\DirecOutput\DirectOutput.log` (make sure this is the full path, not the relative path)
  - Clear log on session start: checked
  [[images/logging.png]]
- Click the `File` menu otion, then click `Save` and save the file in your `Config` folder as `GlobalConfig_B2SServer.xml`
- Make a copy of the `GlobalConfig_B2SServer.xml` and rename it to `GlobalConfig.xml`
- Copy the `GlobalConfig_B2SServer.xml` and `GlobalConfig.xml` files and save them in your DOF64 `COnfig` folder:
  ```
  c:\DirectOutput64\Config
  ```

## Custom Effects

- Visit the Facebook group
  ```
  [Virtual Pinball Custom LED Effects (VPCLE)](https://www.facebook.com/groups/515014447452704/)
  ```
- The group "About" section will have a link to the Google docs location for all the files (TODO: See about placing the files within the github repo)
- For your first time, visit the "Start Here" folder read the instructions.txt (TODO: See about just moving that content tot e readme)
- You can view the `_MX-TABLES` sheet for a lits of all the csutom effects, or you can simply view the folders with the Google drive.

### Adding Effects

To add the effects for a table:

- Click the link in the sheet or open the folder in the drive
- Open the version folder you wish to use
- Take a look at the relase nots to familiarize yourself with the changes
- Download the rar file to you DOF `Config` folder
- Extract the contents to the `Config` folder
- Open the text file and follow the instructions to update the DOF config for the table for your DOF account (TODO: see about getting the changes made as JSON and if it would be possible to update the DOF config tool to add an import capability)

