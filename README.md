# WiXTestSetup
A bare-bones [WiX](https://wixtoolset.org/) setup that demonstrates copying files to the Program Files directory and interacts with the files in it.

The generated msi installs `install-plugin.bat` and `plugin.txt` into "C:\Program Files (x86)\WiXTestSetup", then executes the `install-plugin.bat` which places the `plugin.txt` in "C:\Program Files\Common Files\VST3".

## Referenced Tutorials:
- https://www.firegiant.com/wix/tutorial/getting-started/the-files-inside/
- https://www.add-in-express.com/docs/wix-setup-package.php
- https://www.codeproject.com/Tips/105638/A-quick-introduction-Create-an-MSI-installer-with
- https://stackoverflow.com/questions/22979129/how-to-execute-an-exe-during-wix-install
- https://www.firegiant.com/wix/tutorial/