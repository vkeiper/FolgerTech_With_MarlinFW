## Author: Vince Keiper
### Description: FolgerTech I3 2020 w/ MPX .3 controller running the latest updated Marlin firmware from th Google drive link from FT. 


Installation Notes: 
1. Clone repo to desired folder. 
2. Download Arduino IDE 1.6.5 and extract to desired folder. 
- newer versions will inject build errors, they can be resolved but easier to just use the intended IDE version.
3. Open Arduino IDE. Select Tools, Board, Arduino/Genuino Mega or Mega 2650, then find the com port the MPX controller got assigned in Windows device manager. Usually COM3 isf running default settings in FW. The buad rate default is 250 Kbps, could be 115200 also 
4. Open the firmware via the xxxxx.ino file located in the top folder  
5. Upload the firmware via the Arduino upload button.

- The Folgertech I3 2020 uses 4 start leadscrews for the Z-axis and will require the steps/mm to be set at 400 to start with. 
- The X axis has the endstop on the left side and will need to have direction changed in FW and the endstop

