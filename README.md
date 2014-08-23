Zim-export-template-responsive
==============================

# A Zim export template for a responsive website
## Introduction
The [Zim wiki](http://www.zim-wiki.org/) can export notebooks as websites (see the [Zim manual](http://zim-wiki.org/manual/Help/Export.html) for more information). It offers a number of nice templates for regular websites, webpages to be used in presentations, etc. A disadvantage of these default templates is that they are not really responsive, i.e., they do not adapt really well to different screen sizes. Here I provide a template that can be used to export your Zim notebook as a responsive website. 

It uses jquery and jquerymobile to create responsive webpages with an index in a side panel. The webpages should therefore look good on your mobile device, but also reasonable on your desktop. 

## Example
For examples of websites created using this template, see:
* http://notebook.ecodiv.org
* http://maps.vegetationmap4africa.org/docs.html
* http://www.penwatch.net/morrowind_dnd_zim/

## Version
The current template has been updated to work with Zim 0.61. If you are using Zim 0.60 you (1) may want to consider upgrading your Zim, or (2) use the template in the folder ecodiv60.

## Adapting the template for your own use
The template can be used as it is, but most likely you will want to make some changes. If you open the ecodiv.html file, you will see a number of comments (text between <!--  -->) with suggestions for changes to consider.

## Installing the template

### Option 1: use the web & file browser
1. Download the files 
2. Copy or move the ecodiv.html and ecodiv folder from there to the ~/.local/share/zim/templates/html

### Option 2: use the command line
Use the commands below (works on Linux)

```bash
cd
mkdir tempzim
cd tempzim
git clone https://github.com/ecodiv/Zim-export-template-responsive.git
cd Zim-export-template-responsive
mv ecodiv.html ~/.local/share/zim/templates/html
mv ecodiv ~/.local/share/zim/templates/html
```
### Note
* You do not need to move the ecodiv.html and ecodiv folder to the ~/.local/share/zim/templates/html folder. It is convenient as it makes the template available through the drop down menu (File --> Export) and it is available through Edit --> Template. However, when exporting you can always select a template from any location on your computer. So, if you copy the ecodiv.html and ecodiv folder to e.g., your Documents folder, you can then select the ecodiv.html from there using File --> Export menu.

* But whatever solution you go for, just make sure to copy the folder ecodiv to the same folder as the ecodiv.html file, otherwise the result will not be as intended.


