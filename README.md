## Multi Packer by Shocker  
This project is currently closed source, only executable download is available. You can do that [here](https://github.com/Shocker/soft_multipacker_/releases)

With Multi Packer you can create different types of packed stand-alone applications. Depdending on the packed file types, you can choose from 3 types of packing:
- Application pack: This is for packing other applications. You can select multiple executables, dynamic link libraries [.DLL] and any other files. After that, select one main executable [by clicking the Set main .EXE button] that will be launched when the pack is launched by the user.
- WebPage pack: If you have a webpage / website and you want to transport it in a compact way, this type of pack is the option you need to select. You can pack .HTM / .HTML files and select one index file [by clicking on the Set index file button] with which the executable shall start when the pack is launched. Ofcourse, you can also include pictures of any kind, or any other files. You can also choose a caption for your "website".
- Picture Slideshow: If pictures are what you want to compact, then select this option. It create a slideshow of pictures/images. The created executable is fully customizable: background color, title, items displayed, animation type, etc...

## Screenshots
<img src="https://raw.githubusercontent.com/Shocker/soft_multipacker_/master/screenshots/main.png" width="200" />
<img src="https://raw.githubusercontent.com/Shocker/soft_multipacker_/master/screenshots/pictures.png" width="200" />
<img src="https://raw.githubusercontent.com/Shocker/soft_multipacker_/master/screenshots/picture_result.png" width="200" />  
<img src="https://raw.githubusercontent.com/Shocker/soft_multipacker_/master/screenshots/application.png" width="200" />
<img src="https://raw.githubusercontent.com/Shocker/soft_multipacker_/master/screenshots/webpage.png" width="200" />


## History

v2.12:
 - Added French language (Thanks to Patrick.Bertin)

v2.11:
 - Added Sweedish language (Thanks to Lasseca)
 - Removed ugly about box

v2.10:
 - Added option "Check for updates on startup" to enable/disable automatic update checking on program startup
 - Added Hungarian language (Thanks to ZityiSoft - http://zityi33.fw.hu)
 - Added Polski (Polish) language (Thanks to EL GRITON)

v2.08:
 - Added Espanol (Ecuador) language (Thanks to JCVO 100% Ecuatoriano)

v2.07:
 - Added Portuguese (Braziliian) language (Thanks to Edilson Caldas)

v2.06:
 - Added German (Deutsch) language (Thanks to Andreas Michael Glasauer)

v2.05:
 - Buffered pack creating and extracting, no more low memory problems
 - Bugfix: at Picture Slideshow streched pictures were cut at the top and bottom ends
 - More accurate progress bar

v2.01:
 - Fixed the "Update" function [again]
 - Bugfix: user couldn't cancel or exit the application if the password fields didn't match
 - Added automatic background check for updates at program startup
 - Fixed a MAJOR bug, packs were not working

v2.00:
 - Fixed the "Update" function
 - Added the posibility to choose comments for each image from Picture Slideshow
 - Improved "Simple" encryption time, 4 times faster
 - Added "Jump box" at the App/WebPage Pack screen, above the directory treeview, enter path and press enter
 - Added "Exclusion List" at compression, user can choose which files should not be compressed
 - Bugfix: "Use Compression" state is now saved in / read from project files
 - Added progress bar at the pack-creating step
 - Application / WebPage pack directory treeview now shows hidden folders
 - User must now enter the password twice at the final step before creating the pack
 - Bugfix: Error while handling very BIG images, now draws error text on image, not crashing the app
 - User can now CANCEL the pack creation process
 - Minor fixes at the "Set Language" function
 - Pack creating procedure is now multi threaded, no more application freezing
 - Added posibility to add a Navigation Toolbar at "WebPage Pack"
 - Picture Slideshow toolbar static background color [black]
 - Picture Slideshow: Ignore extension and treat images based on their real content type
 - User can now press <Enter> to submit the password at the Password Screen or <ESC> to quit
 - Files aren't extracted in temporary directory at Picture Slideshow anymore
 - Some major fixes at the isotropic resizing
 - Added "Preview" checkbox
 - Added loading screen at created packs
 - Bugfix: Move Up / Move Down buttons on opened projects
 - Pack size decreased

v1.20:
 - Changed the isotropic resizing procedure, more accurate and faster
 - Replaced the Blowfish and Cast256 encryption algorithms with Twofish and Rijndael
 - The hash stored in the pack file is salted now

v1.11:
 - Added isotropic resizing with blur if "Stretch" button checked [at Picture Slideshow]
 - Added shell integration for .MPK files [associated Multi Packer with .mpk files]
 - Changed the compression routine
 - DelZip179.dll is not needed anymore, pack size decreased

v1.1:
 - Added "Command line" feature for Application Pack
 - Added "Check for updates" feature
 - Bugfix: error with DelZip179.dll
 - Bugfix at password-protected packs, multiple password requests repaired
 - Bugfix when setting the InstallPath in registry on application install

v1.0:
 - First public release
