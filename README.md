# OneThemer

This application has been designed to help customise existing One Commander themes visually - rather than modifying xaml in a text editor.\
The focus is purely on color changes, so for other theme changes you'll still need to get your hands dirty :)
\
\
Background
\
One Commander is a fantastic file manager for Windows 10 and Windows 11.
\
Please visit https://www.onecommander.com/ for more information.



\
How to use OneThemer:  
Download and unzip OneThemer.zip from the Releases link\
Launch OneThemer.exe\
\
The main screen will be shown:

![Screenshot](screenshot.png)

\
Load Theme - Load a One Commander xaml theme (you'll have to navigate to the correct folder...)

Dark/Light Toggle - When modifying a light or dark theme it's often easier to match the UI required. So click the Dark/Light Toggle button as appropriate

Palatte 1,2,3 - These are sample palettes of colors that should work well together

Name Order / Color Order / File Order - Sort the items in the main list

A R G B Sliders / Edit boxes - Alpha (transparency), Red, Green, Blue hex entries for the currently selected value in the list

Apply Single - Update the color change for the selected value in the list

Apply Matches - Update all entries that share the same color as the selected value in the list

Save Changes - Saves the changes to the selected theme file and creates a backup of the original



\
\
When you select an item from the left hand list it appears in the middle section color box. 
Vertically next to this in the narrow column are shown minor color changes (ligher and darker) - any can be clicked
Alternatively select a color from one of the palette entries and tweak using the sliders.
\
\
Note: Hovering over an entry in the left hand list displays a tooltip giving details on what it represents in the One Commander GUI


\
\
Guidelines - How to create a theme:
Navigate to \OneCommanderFolder\Themes\ (portable version of One Commander) or to C:\Users\Yourname\OneCommander\Themes (Microsoft Store version)
Duplicate a theme folder of the theme that is the closest starting point to the one you want to create and give it a new name
In One Commander open Settings and select that new theme
Open OneThemer and navigate to the same new folder and open the .xaml file from the folder
\
The typical iteration process is:
Select an entry in OneThemer and change its color (Apply Single button) or all entries in the theme that share the color (Apply Matches button)
Click the Save Changes button
Switch to One Commander and press Ctrl+Shift+F5 to reload the theme and see the changes

