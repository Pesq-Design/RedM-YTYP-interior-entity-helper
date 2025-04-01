# RedM YTYP Parser

This is a Python application for parsing `.ytyp` xml files and managing entities, rooms, and portals.

## Features
- Parse `.ytyp` files and extract entity information.
- Simulate deletion of entities and update attached objects.
- Display detailed information about rooms and portals.
- Search for entities by ID, Index, or Archetype Name.

## How to Install
1. Download the Exe file. and Enjoy.

## Zip file is Python code for anyone who wants to modify this.
1. Clone this repository.
2. Install the required dependencies (`tkinter` and `xml.etree.ElementTree` are included in Python's standard library).
3. Run the script using Python 3.x.

## How to Use it

1. Export your ytyp file as xml using Codex.
2. Click Upload File.
3. Select the file you exported as XML.

##Upload tab. 
![image](https://github.com/user-attachments/assets/94358ce2-3322-4ffc-9aa6-be99e8496c08)
'Line' will show the line in which you will find the archetype inside the ytyp file.
'Index' tells you the entity index used in the Room or Portals attached objects.
'Archetype' tells you the entity name.
'ID' is the id of the entity not always present in the entity.

#Delete tab
![image](https://github.com/user-attachments/assets/37beebaa-0b65-438e-b79e-0c108a0b29a2)
Enter the Archetype name and the index, if they match it will show you the modifications you need to do to your attachedobjects array at the bottom.

##Information tab.
![image](https://github.com/user-attachments/assets/3e28f4f3-8385-4134-a2fb-c3bbaea5aec8)
Click Display Information button to get the information of the ytyp file. 

## Search tab
![image](https://github.com/user-attachments/assets/2c85be6c-044c-413a-81e3-9b06ad27e06a)
Provides useful information from the entity.

## License
This project is licensed under the MIT License.
