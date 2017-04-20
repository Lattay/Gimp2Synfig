#synfigexport.py

Fork of [synfigexport.py](https://sites.google.com/site/akhilman/synfigexport.py)

Plug-in for [GIMP](http://gimp.org) (__happy 20th birthday!!!__) raster editor, to allow the direct exporting 
of multi-layered images to corresponding layers of the 2D animation package [Synfig](http://synfig.org).

#Installation

* 1- Copy your .py files inside this proyects to GIMP path, in general -> .../GIMP 2/lib/gimp/2.0/plug-ins 
* 2- Load GIMP again in order that GIMP search for your Synfig Export Plugin
* 3- Do your stuff and export as synfig studio format and enjoy your proyect in synfig studio format :D
For more info, please refer to official plugins installation on [GIMP documentation](https://docs.gimp.org/2.8/en/gimp-scripting.html#gimp-plugins-install wiki) / [Hacking GIMP Wiki](https://wiki.gimp.org/wiki/Hacking:Plugins#Installation_of_GIMP_Plug-ins) for developer point of view.

#Usage

* __synfigfu.py__ must be present in __PYTHONPATH__ (at least in same folder than this synfigexport.py)

```
<Image>/File/Export/
```

Open the Export (or "Export As") dialog box, select "Synfig Studio" has file type (.sifz),
choose a destination folder and a name, and exports gimp document to synfig's canvas and png images.

See also [Gimp2Synfig](http://wiki.synfig.org/Doc:Gimp2synfig) from Synfig documentation.

#Author
IL'dar AKHmetgaleev aka AkhIL - [blog akhil](http://blog.akhil.ru/)

##Contribution
* dooglus
* [d.j.a.y](https://github.com/d-j-a-y/Gimp2Synfig)

#Licence
This program is licensed under [Creative Commons Attribution 3.0 Unported License](http://creativecommons.org/licenses/by/3.0/)

__Distribution and updating of the code is appreciated.__

#History
* 2008-01-31  first public release
* 2008-04-26  gimp-2.2 compatibility fix by dooglus
* 2008-08-18  now works without alpha channel
* 2015-11-25  this fork
* 2015-12-03  fix empty name error + add choose file dialog
* 2016-02-19  registration into export dialog + localization mechanism
* 2016-02-22  synfig stuff to synfigfu module + fix issue #5 filename forbiden chars
* 2016-02-25  switch group option
