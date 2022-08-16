# Studwiz-Download
Easily download any PDF file from Studwiz.com with a simple iOS Shortcut

# How it works
Studwiz stores their PDF files in URLs which are basically identical to the URL of the viewer that's normally used to view a file. 

The usual URL format for the viewer is www.studwiz.com/notes/random/things/<span style="color:red">**viewer**</span>/directory/subdirectory/file-name.<span style="color:blue">**html**</span>, while the usual format for the stored PDF file is www.studwiz.com/notes/random/things/<span style="color:red">**uploads**</span>/directory/subdirectory/file-name.<span style="color:blue">**pdf**</span>.

This means that a simple Shortcut that replaces <span style="color:red">**viewer**</span> with <span style="color:red">**uploads**</span> and <span style="color:blue">**html**</span> with <span style="color:blue">**pdf**</span> is required, and this Shortcut does just that.

# How to use

This Shortcut is setup so that it appears in Safari's Share Sheet. After visiting the viewer page of the needed file just open the Share Sheet and run the Shortcut:

![An example of the viewer page and how to open the Share Sheet](https://raw.githubusercontent.com/Andreag00/Studwiz-Download/main/README-Screenshots/Viewer-Page.jpg)

![Executing the Shortcut from the Share Sheet](https://raw.githubusercontent.com/Andreag00/Studwiz-Download/main/README-Screenshots/Share-Sheet.jpg)

After doing that the Shortcut will open the PDF file in a new page in Safari:

![Downloaded PDF](https://raw.githubusercontent.com/Andreag00/Studwiz-Download/main/README-Screenshots/Downloaded-PDF.jpg)