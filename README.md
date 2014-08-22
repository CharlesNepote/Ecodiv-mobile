Zim-export-template-responsive
==============================

## ecodiv.html template

An template to export ZIM-wiki notebooks as a website. The website uses jquery and jquerymobile to create responsive webpages with an index in a side panel. The webpages should therefore look good on the desktop or your mobile device. 

The current template has been updated to work with Zim 0.61.If you are using Zim 0.60 you 1) may want to consider upgrading your Zim, or 2) use the template in the folder ecodiv60.

## Example

For examples of websites based on this template, see:
* http://notebook.ecodiv.org
* http://maps.vegetationmap4africa.org/docs.html
* http://www.penwatch.net/morrowind_dnd_zim/


## Adapting the template for your own use

Open the ecodiv.html file and check the comments (text between <-- -->) for suggestions of changes you may want to condider

## Installing the template

You can pull the files to a (temporary folder), and copy the ecodiv.html and ecodiv folder from there to the ~/.local/share/zim/templates/html

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

Note that you do not need to move the ecodiv.html and ecodiv folder to the ~/.local/share/zim/templates/html folder. It is convenient as it makes the template available through the drop down menu (File --> Export) and it is available through Edit --> Template. However, when exporting you can always select a template from any location on your computer. So, if you copy the ecodiv.html and ecodiv folder to e.g., your Documents folder, you can then select the ecodiv.html from there using File --> Export menu.

But whatever solution you go for, just make sure to copy the folder ecodiv to the same folder as the ecodiv.html file, otherwise the result will not be as intended.

For more information, see http://zim-wiki.org/manual/Help/Export.html
