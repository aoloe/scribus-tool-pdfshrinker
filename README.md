# scribus-tool-pdfshrinker


Small tool using Ghostscript to simplify PDFs created by Scribus, make them smaller in size and better suited for publishing on the web.

gs -sDEVICE=pdfwrite -dCompatibilityLevel=1.4 -dPDFSETTINGS=/prepress 
-dNOPAUSE -dQUIET -dBATCH -sOutputFile=newfile.pdf myfile.pdf

If the file is for screen viewing use

gs -sDEVICE=pdfwrite -dCompatibilityLevel=1.4 -dPDFSETTINGS=/screen 
-dNOPAUSE -dQUIET -dBATCH -sOutputFile=newfile.pdf myfile.pdf

I do this regularly with files to be sent to print and there has never 
been any problem

# TODO

- find a name for the project

# Resources

- <http://askubuntu.com/a/446736> (probably only on ubuntu)
- <http://wiki.scribus.net/canvas/Reduce_the_size_of_Scribus_generated_PDFs>
- <http://libregraphicsworld.org/blog/entry/qml-exporting-script-makes-gimp-a-ui-design-tool7>
- <http://www.ics.com/blog/whole-shebang-running-qml-files-directly>
- http://arstechnica.com/information-technology/2009/03/how-to-deploying-pyqt-applications-on-windows-and-mac-os-x/
- http://www.riverbankcomputing.co.uk/software/pyqt/download5
