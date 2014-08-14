Zim-export-template-responsive
==============================

ZIM-Wiki export template

An template to export ZIM-wiki notebooks as a website, as explained here: http://zim-wiki.org/manual/Help/Export.html.

The website uses jquery and jquerymobile to create responsive webpages with an index in a side panel. The webpages should therefore look good on the desktop or your mobile device.

http://pvanb.wordpress.com/2014/06/06/a-zim-wiki-export-template-for-a-adaptive-website/

## Note
The latest Zim version (0.61) introduced a number of changes to how templates are handled by Zim. This template will therefore only work with Zim 0.6 until later notice.

## Installing the template

### Option 1
You can pull the files to a temporary folder, and copy the ecodiv.html and ecodiv folder to the ~/.local/share/zim/templates/html

```bash
cd
mkdir tempzim
cd tempzim
git clone https://github.com/ecodiv/Zim-export-template-responsive.git
cd Zim-export-template-responsive
mv ecodiv.html ~/.local/share/zim/templates/html
mv ecodiv ~/.local/share/zim/templates/html
```

After this you can delete the tempzim folder if you like or leave it, to get updates from the github repository.

### Option 2
Alternatively, you can download the zip file using the download link, unzip it to a (temporary) folder and copy the required files to ~/.local/share/zim/templates/html using the command line (see above) or your favorite file manager.

### Option 3
Note that you do not need to move the ecodiv.html and ecodiv folder to the ~/.local/share/zim/templates/html folder. It is convenient as it makes the template available through the drop down menu (File --> Export) and it is available through Edit --> Template. However, when exporting you can always select a template from any location on your computer. So, if you copy the ecodiv.html and ecodiv folder to e.g., your Documents folder, you can then select the ecodiv.html from the File --> Export menu.

### Important
But whatever solution you go for, just make sure to copy the folder ecodiv to the same folder as the ecodiv.html file, otherwise the result will not be as intended.

