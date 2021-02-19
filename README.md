# COP400L Series KiCAD Library

Library of schematic components in the COP400 Microprocessor Family

Currently included are:
* COP310L
* COP311L
* COP410L
* COP411L

## Datasheets
* https://atarihq.com/danb/files/COP411.PDF

## Contributions
Please file an Issue or Pull Request at 
https://github.com/webaugur/cop41xl-kicad-library

## License 
Copyright 2021, David L Norris
This library is licensed under the GNU LGPL v3, which can be found in LICENSE.txt

## Library Setup

To add this library to your KiCad Project, do the following steps:

1. Copy the "cop41xl.lib" and "cop41xl.dcm" to the root of your KiCad project's folder.
1. In Eeschema (the schematic editor of KiCad) go to the "Preferences" -> "Manage Symbol Libraries..." menu option.
1. In the Symbol Libraries dialogue that appears, switch to the "Project Specific Libraries" tab.
1. Click "Append Library", beneath the table.
1. In the new line of the table, set Library Path to "$(KIPRJMOD)\cop41xl.lib" on Windows or "$(KIPRJMOD)/cop41xl.lib" on Linux/Mac, and ensure Plugin Type is "Legacy".
1. You can leave the Options and Description fields blank. You should set Nickname to something descriptive - for example, "65xx library".
1. All done: you are now ready to use these schematic components in your project!


