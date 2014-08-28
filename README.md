# Awesome Delphi
A curated list of awesome Delphi frameworks, libraries, resources, and shiny things. Inspired by awesome-... stuff.

- [Awesome Delphi](#awesome-delphi)
	- [General Libraries](#general-libraries)
	- [Multimedia](#multimedia)
	- [Network](#network)
	- [GUI](#gui)
	- [Database](#database)
	- [Non-visual Classes/Utils](#non-visual-classesutils)
	- [Scripting](#scripting)
	- [System](#system)
	- [Other](#other)
	- [Utilities](#utilities)

## General Libraries
*Big general-purpose libraries*

* [JVCL](http://sourceforge.net/projects/jvc) - library of over 600 Delphi components developed by "Project JEDI" members.
// *GUI, algorithms, classes etc.*

* [Alcinoe](http://sourceforge.net/projects/alcinoe) - Compoments suite for Delphi.
// *Network: FTP/Http/NNTP/POP3/SMTP Client, DB: Firebird/MySQL/SQLite3/Memcached/MongoDb client, Xml/Json Parser, Other: encryption, Self-Balancing Binary Trees*

## Multimedia
*Audio, video, graphic*

* [Audio Tools Library](http://mac.sourceforge.net/atl) - for manipulating with many audio formats file information. Abandoned since 2005.

* [New Audio Components (NewAC)](http://code.google.com/p/newac) designed to help your Delphi programs perform different sound processing tasks. With NewAC you can play audio stored in many formats (wav, Ogg Vorbis, FLAC, Monkey Audio, WavPack, MP3, Windows WMA, DTS, AC-3 (Dobly Surround), VOB (DVD files)).
// *Playback, recording, tag read/write, some audio editing tasks and conversions*

* [DSPack](https://code.google.com/p/dspack) is a set of Components and class to write Multimedia Applications using MS Direct Show and DirectX technologies.

* [Graphics32](http://sourceforge.net/projects/graphics32) designed for fast 32-bit graphics handling on Delphi, Kylix and Lazarus. Optimized for 32-bit pixel formats, it provides fast operations with pixels and graphic primitives, and in most cases Graphics32 outperforms the standard TCanvas classes. It is almost a hundred times faster in per-pixel access and about 2–5 times faster in drawing lines.

* [GraphicEx](http://www.delphi-gems.com/index.php/libs/graphicex-library) is an addendum to Delphi's Graphics.pas to enable your application to load many common image formats. This library is primarily designed to load images as background (buttons, forms, toolbars) and textures (DirectX, OpenGL) or for image browsing and editing purposes as long as you don't need to save images.

* [Vampyre Imaging Library](http://imaginglib.sourceforge.net) - cross-platform native Object Pascal (Delphi and Free Pascal) image loading, saving, and manipulation library.

* [CCR-EXIF](http://ccr-exif.googlecode.com) - library to read and write Exif, IPTC and XMP metadata from JPEG, TIFF and PSD images.

## Network
*Socket communication, network protocols, encodings, etc*

* [Internet Component Suite](http://www.overbyte.be/frame_index.html) - asynchronous-based library composed of various Internet components and applications. Clients/servers for TCP, UDP, raw sockets, FTP, SMTP, POP3, NNTP, HTTP, Telnet and more. Supports SSL and TLS with the help of OpenSSL. Also includes Mime Decoder, SHA1/MD4/MD5 hashes, DES encryption.

* [Indy](https://code.google.com/p/indyproject) components for Delphi, C++Builder, Delphi.NET, and FreePascal
// *All-in-one network library based on blocking sockets and threads. Included in default RAD studio installation since 2006.*

## GUI
*Visual components*

* [EasyListView](http://code.google.com/p/mustangpeakeasylistview) - Part of VirtualShellTools for the Listview but can be used for a TListview Replacement that is faster and more customizable.
// *Feature-rich Listview capable with virtual (callback-based) MVC paradigm.*

* [VirtualTreeView](http://code.google.com/p/virtual-treeview) - treeview control built from ground up. Many years of development made it one of the most flexible and advanced tree controls available today.
// *Extremely flexible visual component implementing virtual (callback-based) MVC paradigm. Could be also used as a listview or grid.*

* [HtmlViewer](http://github.com/BerndGabriel/HtmlViewer) - The well-known Delphi/Lazarus HtmlViewer/FrameViewer.
// *Html visualiser supporting majority of tags, inline styles and CSS.*

* [SynEdit](http://sourceforge.net/projects/synedit) is a syntax highlighting edit control, not based on the Windows common controls. SynEdit is compatible with both Delphi and Kylix

* [Cindy components](http://sourceforge.net/projects/tcycomponents) - Packages with 71 components: VCL controls (labels, buttons, panels, Edits, TabControls, StaticText) with features like background gradient, colored bevels, wallpaper, shadowText, caption orientation etc...

* [Delphi Chromium Embedded](https://code.google.com/p/delphichromiumembedded) - Embedding Chromium in Delphi, tested on Delphi 2010, XE, XE2, Delphi 7.

## Database

* [ZeosLib](http://sourceforge.net/projects/zeoslib) - set of database components for MySQL, PostgreSQL, Interbase, Firebird, MS SQL, Sybase, Oracle and SQLite.

* [Unified Interbase](http://sourceforge.net/projects/uib) is a set of components to use Interbase, FireBird and YAFFIL. These components were born from the need to use Interbase, FireBird or Yaffil indifferently as fast as possible in a Multithreading environment, a Server for example.

## Non-visual Classes/Utils

* [TRegExpr](http://regexpstudio.com/TRegExpr/TRegExpr.html) - Easy to use and powerful tool for sophisticated search and substitutioning and for template-based text input check.

## Scripting

* [Pascal Script](https://github.com/remobjects/pascalscript) - Pascal Script is a free scripting engine that allows you to use most of the Object Pascal language within your Delphi or Free Pascal projects at runtime. Written completely in Delphi, it is composed of a set of units that can be compiled into your executable, eliminating the need to distribute any external files. Pascal Script started out as a need for a good working script, when there were none available at the time.

* [DWScript](https://code.google.com/p/dwscript) is an object-oriented scripting engine for Delphi based on the Delphi language, with extensions borrowed from other Pascal languages (FreePascal, Prism, etc.). It introduces a few Pascal language extensions of its own as well.

* [Delphi-Javascript](https://code.google.com/p/delphi-javascript) Javascript engine for delphi based on spidermonkey.
// *DLL required*

## System
*Low-level helper stuff: memory, threading etc*

* [FastMM](http://sourceforge.net/projects/fastmm) - is a lightning fast replacement memory manager for Embarcadero Delphi Win32 and Win64 applications that is not prone to memory fragmentation, and supports shared memory without the use of external .DLL files.
// *Used as stock memory manager since 2006 but in simplified version. Provides powerful memory leak/corruption detection instruments.*

* [OmniThreadLibrary](https://code.google.com/p/omnithreadlibrary) is a simple to use threading library for Delphi.
// *Easy integration of async processes in your app*

* [ScaleMM](https://code.google.com/p/scalemm) - Fast scaling memory manager for Delphi

## Other

* [GMLib](https://code.google.com/p/gmlibrary) (Google Maps Library) are components for Delphi/C++ Builder that encapsulate the GoogleMaps API to administrate a map, markers, polygons, rectangles, polylines,... All objects that you can put into a map.

## Utilities
*Useful dev tools/IDE plugins*

* [Lazy Delphi Builder](https://bitbucket.org/tdelphi/lazy-delphi-builder-downloads/downloads) - build tool for Delphi. Recompile projects/packages from sources with all dependencies, without need to mess around with configs. Quickly (re-)install components from sources into IDE, with no need to change your Library Path.
// *Powerful automating tool. Freeware but not open source*

* [Delphi IDE theme editor / Delphi IDE Colorizer](https://code.google.com/p/delphi-ide-theme-editor). The Delphi IDE Theme Editor (DITE) is a tool to change the IDE color highlighting of several Object Pascal IDE's like Delphi (RAD Studio), Appmethod, Lazarus  and Smart Mobile Studio. DITE supports Delphi 5-7, 2005-2010, XE-XE6, Appmethod 1.13-1.14, Lazarus v1.0.1.3 and Smart Mobile Studio IDE v1.1.2.17. The Delphi IDE Colorizer (DIC) is a plugin which allows to customize the look and feel of the workspace of the RAD Studio IDE and Appmethod.

* [DDevExtensions](http://andy.jgknet.de/blog/ide-tools/ddevextensions) extends the Delphi/C++Builder IDE by adding some new productivity features
// *Many useful IDE tweaks, must have.*

* [VCL Fix Pack](http://andy.jgknet.de/blog/bugfix-units/vclfixpack-10) is a Delphi unit that fixes VCL and RTL bugs at runtime by patching the original functions. If you want all IDE Fix Pack fixes in your application this unit is what you are looking for. Adding the unit to your project (Delphi and C++Builder) automatically installs the patches that are available for your Delphi/C++Builder version.
// *Actual for Delphi/C++ 6..2009*

* [IDE Fix Pack](http://andy.jgknet.de/blog/ide-tools/ide-fix-pack) is a collection of unofficial bug fixes and performance optimizations for the RAD Studio IDE, Win32/Win64 compiler and Win32 debugger. IDE Fix Pack is an IDE plugin for RAD Studio 2009-XE6 that fixes IDE bugs at runtime. All changes are done in memory. No files on disk are modified. None of your projects are modified or benefit from the IDE Fix Pack other than being compiled faster. Only the IDE gets the fixes and optimizations.
// *Supports all RAD Studio versions since 2007. Removes lots of annoying bugs that EBMT haven't fixed for years. Yay!*
