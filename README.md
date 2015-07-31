# Awesome Delphi
A curated list of awesome Delphi frameworks, libraries, resources, and shiny things. Inspired by awesome-... stuff.

**Note that only open-source projects are considered. Dead projects are mainly ignored except for those which do not have alive analogs.**
Feel free to suggest other missing nice projects either by comments or pull requests.

This awesome collection is also available on [Delphi.ZEEF.com](https://delphi.zeef.com/anton.frost)

- [Awesome Delphi](#awesome-delphi)
	- [General Libraries](#general-libraries)
	- [Multimedia](#multimedia)
		- [Audio](#audio)
		- [Video](#video)
		- [Graphic](#graphic)
	- [Communications](#communications)
		- [Network](#network)
		- [Serial port](#serial-port)
	- [GUI](#gui)
		- [Control packs](#control-packs)
		- [Single controls](#single-controls)
		- [Other GUI](#other-gui)
	- [Database](#database)
	- [Scripting](#scripting)
	- [Non-visual Classes/Utils](#non-visual-classesutils)
		- [Compression](#compression)
		- [Encryption](#encryption)
		- [XML/JSON](#xmljson)
		- [System](#system)
		- [Other non-visual](#other-non-visual)
	- [OS](#os)
	- [Unit Testing](#unit-testing)
	- [Utilities](#utilities)


## General Libraries
*Big general-purpose libraries*

* [JVCL](http://sourceforge.net/projects/jvcl). Library of over 600 Delphi components developed by "Project JEDI" members.
// *GUI, algorithms, classes, API headers etc.*

* [Alcinoe](http://sourceforge.net/projects/alcinoe). Components suite for Delphi.
// *Network: FTP/Http/NNTP/POP3/SMTP, ISAPI, WinInet Http/FTP clients; DB: Firebird/MySQL/SQLite3/Memcached/MongoDb/SphinxQL; XML/JSON Parser; ZLIB; Cryptography: AES, Blowfish, MD5, SHA, secure keyed MD5/SHA; Other: Self-Balancing Binary Trees, expression evaluator*

* [Fundamentals Code Library](http://sourceforge.net/projects/fundementals). Collection of Delphi / FreePascal code units. Includes libraries for Unicode, Strings, Data Structures, Sockets and Mathematics.
// *Utils: ZLIB compression; JSON; XML; ProtocolBuffers; Hashes: XOR, CRC, Adler, MD5, SHA, secure keyed MD5/SHA, etc; Network: blocking TCP client/server, HTTP(S) via SSL3/TLS1.0/TLS1.1/TLS1.2 (fully native); SQL parser; BitCoin MtGox client; Blaise script engine; Cipher: AES, DES, FUNE, RC2/4, RSA; Maths: matrix, complex, statistics*

* [Spring4D](https://bitbucket.org/sglienke/spring4d). Open-source code library for Embarcadero Delphi 2010 and higher. It consists of a number of different modules that contain a base class library (common types, interface based collection types, reflection extensions) and a dependency injection framework. Includes Encryption Library.
// *Collections and other containers using Generics and based on IEnumerable, probably more accurate and featured than RTL analogs; crypto: CRC, DES, MD5, SHA; file utils etc*

* [TheUnknownOnes](http://code.google.com/p/theunknownones). Huge heap of classes, components, utilities for almost every purpose. Nearly undocumented and seems not very up-to-date though.

* [CNVCL](https://github.com/cnpack/cnvcl). CnPack Component Package. Large collection of visual components, classes and utilities. // *Lots of useful stuff; documentation and comments mainly in Chinese*

* [mORMot](https://github.com/synopse/mORMot). Client-Server ORM/ODM SOA MVC framework for Delphi 6 and higher, or FPC 2.7. Direct SQL/NoSQL database access, ORM/ODM over objects, RESTful ORM and SOA services via interfaces over high performance HTTP server, MVC/MVVM web sites, testing including mocks and stubs, logging, huge documentation.

## Multimedia

## Audio

* [Audio Tools Library](http://mac.sourceforge.net/atl). For manipulating many audio formats file information.
//**Abandoned since 2005.**

* [Delphi ASIO & VST Project](http://sourceforge.net/projects/delphiasiovst). Framework for writing applications using the ASIO interface and VST plugins. It comes with countless DSP algorithms all demonstrated in dozens of examples.
//*Not very active lately, but the trunk is in a usable state .*

* [NewAC — New Audio Components](http://code.google.com/p/newac). Designed to help your Delphi programs perform different sound processing tasks. With NewAC you can play audio stored in many formats (wav, Ogg Vorbis, FLAC, Monkey Audio, WavPack, MP3, Windows WMA, DTS, AC-3 (Dobly Surround), VOB (DVD files)).
// *Playback, recording, tag read/write, some audio editing tasks and conversions*

## Video

* [DSPack](https://code.google.com/p/dspack). Set of components and classes to write Multimedia Applications using MS Direct Show and DirectX technologies.

* [Delphi-OpenCV](https://github.com/Laex/Delphi-OpenCV). Translation of OpenCV library header files in Delphi
// *Includes FFMPEG headers*

* [FFmpeg Delphi/Pascal Headers] (http://www.delphiffmpeg.com/headers). Open source translation of FFMPEG headers.

* [PasLibVlc](http://prog.olsztyn.pl/paslibvlc). Interface to VideoLAN libvlc.dll and VCL player component for Delphi / FreePascal based on VideoLAN

## Graphic

* [Graphics32](http://sourceforge.net/projects/graphics32). Designed for fast 32-bit graphics handling on Delphi, Kylix and Lazarus. Optimized for 32-bit pixel formats, it provides fast operations with pixels and graphic primitives, and in most cases Graphics32 outperforms the standard TCanvas classes. It is almost a hundred times faster in per-pixel access and about 2-5 times faster in drawing lines.

* [GraphicEx](http://www.delphi-gems.com/index.php/libs/graphicex-library). Addendum to Delphi's Graphics.pas to enable your application to load many common image formats. This library is primarily designed to load images as background (buttons, forms, toolbars) and textures (DirectX, OpenGL) or for image browsing and editing purposes as long as you don't need to save images.

* [Vampyre Imaging Library](http://imaginglib.sourceforge.net). Cross-platform native Object Pascal (Delphi and Free Pascal) image loading, saving, and manipulation library.

* [CCR-EXIF](https://code.google.com/p/ccr-exif). Library to read and write Exif, IPTC and XMP metadata from JPEG, TIFF and PSD images.

* [KIcon](http://www.tkweb.eu/en/delphicomp/kicon.html). This component makes sense if a more complex manipulation with icons (or better icon files *.ico) than just viewing is needed. Full PNG icon image support, correct rendering, icons with alpha channel.

* [Delphi Twain](http://www.kluug.net/delphitwain.php). The library allows you to easily access scanning functions from Delphi and Lazarus.

* [Synopse PDF](https://github.com/synopse/SynPDF). Fully featured Open Source PDF document creation library for Delphi, embedded in one unit. Pure Delphi code, Delphi 5 up to XE7, for Win32 and Win64 platforms.

* [PowerPDF](https://github.com/TurboPack/PowerPDF). VCL component to create PDF docment visually. Like Forms, you can design PDF document easily on Delphi or C++Builder IDE.

* [IGDI+](https://sourceforge.net/projects/igdiplus). The free open source library allows quick and easy implementations of complex GDI+ applications, in a natural Delphi-friendly code.

* [GLScene](https://sourceforge.net/projects/glscene). OpenGL based 3D library for Delphi. It provides visual components and objects allowing description and rendering of 3D scenes in an easy, no-hassle, yet powerful manner. GLScene is not just an OpenGL wrapper or utility library, it has grown to become a set of founding classes for a generic 3D engine with Rapid Application Development in mind. GLScene allows you to quickly design and render 3D scenes without having to learn the intricacies of OpenGL, if you know how to design a TForm, you'll easily master the basic operations of GLScene. The library comes with a large collections of demos showcasing the ease of use, and demonstrating RAD wasn't done at the expense of CPU/GPU horsepower.

* [SynGdiPlus](https://github.com/synopse/mORMot/blob/master/SynGdiPlus.pas). Enables an application to load and save GIF, TIF, PNG and JPG pictures. It also allows anti-aliased drawing from any TMetaFile. That is, you can play a .emf content using GDI+ instead of GDI, for much better rendering result.


## Communications

## Network
*Socket communication, network protocols, encodings, etc*

* [Internet Component Suite](http://www.overbyte.be/frame_index.html). Asynchronous-based library composed of various Internet components and applications. Clients/servers for TCP, UDP, raw sockets, FTP, SMTP, POP3, NNTP, HTTP, Telnet and more. Supports SSL and TLS with the help of OpenSSL. Also includes Mime Decoder, SHA1/MD4/MD5 hashes, DES encryption.

* [Indy](https://code.google.com/p/indyproject). Network components for Delphi, C++Builder, Delphi.NET, and FreePascal
// *All-in-one network library based on blocking sockets and threads. Included in default RAD studio installation since 2006.*

* [Ararat Synapse](https://sourceforge.net/p/synalist). Pascal TCP/IP Library for Dephi, C++Builder, Kylix and FreePascal. Deals with network communication by means of blocking (synchronous) sockets or with limited non-blocking mode. This project not using asynchronous sockets! The Project contains simple low level non-visual objects for easiest programming without problems (no required multithread synchronisation, no need for windows message processing,…) Great for command line utilities, visual projects, NT services,…
// *TCP, UDP, ICMP, RAW; ICMP, DNS, SMTP, HTTP, SNMP, NTP, FTP, LDAP, NNTP, Telnet;  IPv6; SOCKS proxy; SSL/TLS (via OpenSSL or Windows CryptoApi); PING; character code transcoding; MIME coding and decoding; CRC16, CRC32, MD5 and HMAC-MD5.*

* [Internet Professional](http://sourceforge.net/projects/tpipro2010). Set of VCL components providing Internet connectivity for Borland Delphi & C++Builder. iPRO includes POP3, SMTP, NNTP, FTP, HTTP, Instant Messaging, & HTML viewer components, as well as components for low-level socket access.
// *Seems abandoned but contains pretty large set of features incl ICMP, POP, SMTP, HTTP, NNTP, NTP, FTP, SMTP; HTML parser and viewer; MIME utils; cookies, certificates, caching, encryption etc*

* [SynCrtSock](https://github.com/synopse/mORMot/blob/master/SynCrtSock.pas). Features several sockets and HTTP client-server classes, including a high-performance http.sys based server under Windows, and a new thread-pool powered socket server.
// *Also implements http.sys binding under Windows and cURL binding under nix*

## Serial port

* [Synaser](http://sourceforge.net/p/synalist/code/HEAD/tree/trunk/synaser.pas). Library for blocking communication on serial ports. It is non-visual class as in Synapse, and programmer interface is very similar to Synapse.

* [Async Professional](http://sourceforge.net/projects/tpapro) ([Newest](https://github.com/TurboPack/AsyncPro) and maintained version for recent compiler version only). Comprehensive communications toolkit for Embarcadero Delphi, C++Builder, & ActiveX environments. It provides direct access to serial ports, TAPI and the Microsoft Speech API (TTS/Speech recognition). It supports faxing, terminal emulation, VOIP, RAS dial & more.
// *Seems outdated (last update in 2011) but adapted to XE and should be easy to use in newer versions. The project is also very thoroughly documented. Second link points to an adapted version for newest compiler versions.*


## GUI
*Visual components*

## Control packs
*Large sets of GUI controls*

* [Cindy components](http://sourceforge.net/projects/tcycomponents). Packages with 71 components: VCL controls (labels, buttons, panels, Edits, TabControls, StaticText) with features like background gradient, colored bevels, wallpaper, shadowText, caption orientation etc...

* [Orpheus](http://sourceforge.net/projects/tporpheus) ([Newest](https://github.com/TurboPack/Orpheus) and maintained version for recent compiler version only). Award-winning UI toolkit for Borland Delphi & C++Builder. It contains over 120 components covering everything from data entry to calendars and clocks. Other noteworthy components include an Object Inspector, LookOut bar & report views.
// *Advanced edits, comboboxes, grids + component (de)serializers. GUI components look rather old-style, theme support might be limited. Package contains many demos but no docs seem available. Second link points to an adapted version for newest compiler versions.*

* [KControls](http://www.tkweb.eu/en/delphicomp/kcontrols.html). Control components. All controls have been written with the aim to become both cross-IDE compatible (Delphi/C++Builder VCL and Lazarus LCL) and cross-platform compatible in Lazarus.
// *Most useful are TKGrid with its DB-aware heritage TKDBGrid — a very full-featured grid implementation incl. inplace editors. There's also hex editor, print preview, editors, labels, buttons etc.*

* [D.P.F Delphi Android](http://sourceforge.net/projects/dpfdelphiandroid) / [D.P.F Delphi iOS](http://sourceforge.net/projects/dpfdelphiios) native components. D.P.F Delphi Native Components, 100% iOS Performance and styles. Develop iPhone & iPad & iPod Touch applications with fast native performance and native styles. Use native Android controls and services. Fast native performance. Mixed with FM VCL controls. Can be quick updated with latest Android controls & features.

* [Essentials](https://github.com/TurboPack/Essentials). Contains 13 native VCL controls for Embarcadero Delphi and C++Builder. The controls include drop-down calendars and calculators, roll-up dialogs, 3-D labels, tiled backgrounds, scrolling messages, menu buttons, and more.

## Single controls

* [EasyListView](http://code.google.com/p/mustangpeakeasylistview). Part of VirtualShellTools for the Listview but can be used for a TListview Replacement that is faster and more customizable.
// *Feature-rich Listview implementing virtual (callback-based) MVC paradigm.*

* [VirtualTreeView](https://github.com/Virtual-TreeView/Virtual-TreeView). Treeview control built from ground up. Many years of development made it one of the most flexible and advanced tree controls available today.
// *Extremely flexible visual component implementing virtual (callback-based) MVC paradigm. Could be also used as a listview or grid. Used in RAD Studio GUI.*

* [HtmlViewer](http://github.com/BerndGabriel/HtmlViewer). Delphi/Lazarus HtmlViewer/FrameViewer.
// *Html visualiser supporting majority of tags, inline styles and CSS.*

* [SynEdit](http://sourceforge.net/projects/synedit) ([mirror at GitHub](https://github.com/TurboPack/SynEdit)). Syntax highlighting edit control, not based on the Windows common controls. SynEdit is compatible with both Delphi and Kylix

* [Delphi Chromium Embedded](https://code.google.com/p/delphichromiumembedded). Embedding Chromium in Delphi, tested on Delphi 2010, XE, XE2, Delphi 7.
// *Several DLLs required*

* [ATViewer](https://sourceforge.net/projects/atviewer). Delphi components to view various file types: text, binary, images, multimedia, webpages, etc.
// *Used in Universal Viewer software. Could be used to display hex dumps, features fast display of unlimited size files/streams. Supports Total Commander Lister plugins.*

* [ATImageMap](http://sourceforge.net/projects/atviewer/files/ATImageMap). Component designed to show many images (parts of the whole image) as a single map. For example, you may have array of images, 200 by X, and 100 by Y — control will show them as a single map. Component also allows to draw paths: each path consists of many lines, points, and icons.

* [TChromeTabs](http://code.google.com/p/delphi-chrome-tabs). Comprehensive implementation of Google Chrome's tabs for Delph7 — Delphi XE7

## Other GUI

* [GMLib](https://code.google.com/p/gmlibrary) (Google Maps Library). Components for Delphi/C++ Builder that encapsulate the GoogleMaps API to administrate a map, markers, polygons, rectangles, polylines,... All objects that you can put into a map.

* [VCL Styles Utils](https://code.google.com/p/vcl-styles-utils). Collection of classes and style hooks, which extend, fix QC reports and add new features to the VCL Styles.
// *Collection of patches/enhancements that promote stock VCL style engine to a new level. Styling for Inno setup and NSIS also available.*

* [TaskbarListComponents](http://code.google.com/p/theunknownones). Set of components designed as Delphi wrappers for the Windows 7 Taskbarlist Interfaces (e.g. ITaskbarlist3)
// *Requires JVCL*

## Database

* [ZeosLib](http://sourceforge.net/projects/zeoslib). Set of database components for MySQL, PostgreSQL, Interbase, Firebird, MS SQL, Sybase, Oracle and SQLite.

* [Unified Interbase](http://sourceforge.net/projects/uib). Set of components to use Interbase, FireBird and YAFFIL. These components were born from the need to use Interbase, FireBird or Yaffil indifferently as fast as possible in a Multithreading environment, a Server for example.

* [ASQLite](https://github.com/remobjects/ASQLite3). Delphi SQLite set of DAC components from aducom software, based on their latest release for Delphi 2009, and updated to support newer editions of Delphi as included in RemObjects Data Abstract for Delphi.

* [TxQuery](https://github.com/ccy/txquery). TDataSet descendant component that can be used to query one or more TDataSet descendant components using SQL statements. It is implemented in Delphi 100% source code, no DLL required, because it implements its own SQL syntax parser and SQL engine.

* [Delphi-ORM](https://code.google.com/p/delphi-orm). Object-Relational Mapping for Delphi XE7, XE6, XE5, XE4, XE3 and XE2 (Win32). Supports for FirebirdSQL, SQLServer and SQLite3.

* [delphimemcache](https://code.google.com/p/delphimemcache). Implements a thread safe client for memcached.
// *Requires Indy 10*

* [SynDB](https://github.com/synopse/mORMot/blob/master) ([docs](http://synopse.info/files/html/Synopse%20mORMot%20Framework%20SAD%201.18.html#TITL_126)). High performance direct access to SQLite3, Oracle, MSSQL, PostgreSQL, Firebird, MySQL, ODBC, OleDB, including remote HTTP connection and direct JSON support.

* [SynMongoDB](https://github.com/synopse/mORMot/blob/master/SynMongoDB.pas) ([docs](http://blog.synopse.info/post/2014/05/07/MongoDB-database-access)). Offers direct low-level access to any MongoDB server, its custom data types, JSON or via `TDocVariant` custom variant document storage.

## Scripting
*Using script engine in your applications*

* [Pascal Script](https://github.com/remobjects/pascalscript). Free scripting engine that allows you to use most of the Object Pascal language within your Delphi or Free Pascal projects at runtime. Written completely in Delphi, it is composed of a set of units that can be compiled into your executable, eliminating the need to distribute any external files. Pascal Script started out as a need for a good working script, when there were none available at the time.

* [DWScript](https://bitbucket.org/egrange/dwscript). Object-oriented scripting engine for Delphi based on the Delphi language, with extensions borrowed from other Pascal languages (FreePascal, Prism, etc.). It introduces a few Pascal language extensions of its own as well.

* [Delphi-Javascript](https://code.google.com/p/delphi-javascript). Javascript engine for delphi based on Mozilla's Spidermonkey.
// *Spidermonkey DLL required*

* [Blaise](http://sourceforge.net/projects/blaise). Open-source object-oriented scripting language. Language features: Object-oriented; Unicode support; Optional typing, ie dynamic or static typing; Richly typed; Higher-level mathematics support, for example Complex numbers, Rational numbers and Matrices; Virtual Machine architecture; Co-routines; Familiar language syntax, influenced by Object Pascal, Python and Ada.

* [SpiderMonkey](https://github.com/synopse/mORMot). Binding for Mozilla JavaScript engine, including JIT and multi-threading, with easy objects access via Delphi variants.
// *Spidermonkey DLL required*

## Non-visual Classes/Utils

## Compression

* [FWZip](https://github.com/AlexanderBagel/FWZip). Classes to work with Zip archives using Store and Deflate methods, supports ZIP64, DataDescryptors, PKWARE encryption, NTFS attributes, Utf8 in filenames.
// *Uses stock ZLIB.obj that gets compiled into binary*

* [Abbrevia](http://sourceforge.net/p/tpabbrevia) ([Newest](https://github.com/TurboPack/Abbrevia) and maintained version for recent compiler version only). Advanced data compression toolkit for Delphi and C++Builder. Supports PKZIP, Microsoft CAB, tar, gzip, and bzip2 archives, and can create self-extracting executables. On Windows it also provides Delphi wrappers for the LZMA, Bzip2, and WavPack SDKs, and PPMd decompression. Abbrevia also has several visual controls that simplify displaying and manipulating archives, including treeview and listview components. Features: Unicode filenames in all archive formats; Decompress most .zipx and legacy (PKZIP v1) zips; ZIP64 support for archives larger than 2GB; Spanned and split zip archives; Cross-platform (Windows, OS X, and Linux); No DLLs required; Includes COM component; Extensive documentation
// *Second link points to an adapted version for newest compiler versions.*

* [SynLZ SynLZO SynZip](https://github.com/synopse/mORMot). Several high speed compression units, featuring ZIP, LZO and SynLZ algorithm, in pascal and optimized assembler.

## Encryption

* [Delphi Encryption Compendium (DEC)](https://github.com/winkelsdorf/DelphiEncryptionCompendium/releases). Cryptographic library for Delphi & C++ Builder. Symmetric cryptographic functions: Blowfish, Twofish, IDEA, Cast128, Cast256, Mars, RC2, RC4, RC5, RC6, Rijndael / AES, Square, SCOP, Sapphire, 1DES, 2DES, 3DES, 2DDES, 3DDES, 3TDES, 3Way, Gost, Misty, NewDES, Q128, SAFER, Shark, Skipjack, TEA, TEAN; Block cipher modes of operation: CTSx, CBCx, CFB8, CFBx, OFB8, OFBx, CFSx, ECBx; Hashes: MD2, MD4, MD5, RipeMD128, RipeMD160, RipeMD256, RipeMD320, SHA, SHA1, SHA256, SHA384, SHA512, Haval128, Haval160, Haval192, Haval224, Haval256, Tiger, Panama, Whirlpool, Whirlpool1, Square, Snefru128, Snefru256, Sapphire.
// *No updates since 2010 but features list so huge that it couldn't be ignored*

* [LockBox](http://sourceforge.net/projects/tplockbox) ([Newest](https://github.com/TurboPack/LockBox3) and maintained version for recent compiler version only). Delphi library for cryptography. Currently supported Delphi XE6. It provides support for AES, DES, 3DES, Blowfish, Twofish, SHA2 (including the new SHA-512/224 & SHA-512/256), MD5; ECB, CBC, CFB8, CFB, CTR, ECB, OFB, PCBC chaining modes, RSA digital signature and verification. Has interface to OpenSSL library.
// *Check out [this](https://github.com/jarto/lockbox2) page as well for alternative version.*

* [SynCrypto](https://github.com/synopse/mORMot/blob/master/SynCrypto.pas). Fast cryptographic routines (hashing and cypher), implementing AES, XOR, RC4, ADLER32, MD5, SHA1, SHA256 algorithms, optimized for speed (tuned assembler and VIA PADLOCK optional support).

## XML/JSON

* [OmniXML] (http://code.google.com/p/omnixml). XML parser written in Delphi. Full support for Document Object Model (DOM) Level 1 specification; Supports Extensible Markup Language (XML) 1.0 (Second Edition) specification; Has built-in support for different code pages (main 8-bit code pages, UTF-8, UTF-16); Is compatible with MS XML parser; Fast parsing even large and highly structured documents; Includes helper functions to ease processing XML documents; Simplified XPath support.

* [SAX for Pascal](http://sourceforge.net/projects/saxforpascal). Designed to implement the Simple API for XML Parsing in Pascal/Delphi.
// *Callback-based XML parser, useful for processing huge XML streams.*

* [KDS XML](http://sourceforge.net/projects/kdsxml). Class library for streamed parsing, validating and generating XML. It is written in Object Pascal/Delphi and works on Win32 (Delphi) and Linux (Kylix). Parts of it depend on the SAX for Pascal interface specifications.

* [XML Partner](http://sourceforge.net/projects/tpxmlpartner). Helps add the power of XML to Borland Delphi, C++ Builder, and Kylix projects through native, easy to use VCL and CLX components. These powerful components simplify the process of creating, modifying, and parsing XML data documents.
// *Seems dead, check out [this](http://www.songbeamer.com/delphi) page for probably newer version.*

* [Open XML](http://www.philo.de/xml/downloads.shtml). Provides a wide range of methods, components and foundation classes. It can be used for Win32/Kylix as well as for .NET development.

* [SuperObject](http://code.google.com/p/superobject). Parser/writer for JSON data format. This toolkit is designed to work with Delphi and FreePascal (win32, win64, linux32, linux64, MacOSX Intel)

* [OXml](http://www.kluug.net/oxml.php). New XML library for Delphi and Lazarus, developed in late 2013. I took some inspiration from OmniXML but wrote the library completely from scratch. The aim of OXml is to be the most versatile and fastest XML library for the Pascal language. OXml features a SAX parser, DOM implementation, a sequential DOM parser a direct XML reader/writer and a vendor for Delphi's XmlIntf.TXMLDocument. OXml supports all Delphi versions starting from Delphi 4 on all platforms: Win32, Win64, OSX, iOS, Android. OXml supports Lazarus 1.0 and newer on all platforms (tested Win32, Win64, Linux, MacOSX).

* [Libxml2 for pascal](https://sourceforge.net/projects/libxml2-pas). Pascal units accessing the popular XML API from Daniel Veillard. This should be usable at least from Kylix and Delphi, but hopefully also from other Pascal compilers (like freepascal).

* [NativeXml](https://code.google.com/p/simdesign). This component contains a small-footprint Object Pascal (Delphi) XML implementation that allows to read and write XML documents. You basically only need one unit and you can simply add it to the "uses" clause. You can use this software to read XML documents from files, streams or strings. The load routine generates events that can be used to display load progress on the fly. You can also use it to create and save XML documents.

* [Chimera](http://code.google.com/p/jsonchimera). Open Source (MIT License) library for Delphi XE2 which provides a fast and cross platform JSON generator/parser (serializer/deserializer) under a license that doesn't suck.

* [SynCommons](http://https://github.com/synopse/mORMot/blob/master/SynCommons.pas). High speed JSON library, using `TDocVariant` custom variant type for storage and access.

* [SynCrossPlatformJSON](https://github.com/synopse/mORMot/blob/master/CrossPlatform/SynCrossPlatformJSON.pas). High speed cross-platform JSON library, using `TJSONVariant` custom variant type for storage and access.

## System
*Low-level helper stuff: memory, threading etc*

* [FastMM](http://sourceforge.net/projects/fastmm). Lightning fast replacement memory manager for Embarcadero Delphi Win32 and Win64 applications that is not prone to memory fragmentation, and supports shared memory without the use of external .DLL files.
// *Used as stock memory manager since 2006 but in simplified version. Provides powerful memory leak/corruption detection instruments.*

* [OmniThreadLibrary](https://code.google.com/p/omnithreadlibrary). Simple to use threading library for Delphi.
// *Easy integration of async processes in your app*

* [ScaleMM](https://code.google.com/p/scalemm). Fast scaling memory manager for Delphi

* [Delphi Detours Library](http://code.google.com/p/delphi-detours-library). Library allowing you to hook Delphi functions and object methods and Windows API functions. It provides an easy way to insert and remove hook.
// *Supports x64, calling original functions, multi hooks, COM/Interfaces/win32api, object methods hooking, fully thread-safe, Delphi 7/2005-2010/XE-XE7 & Lazarus/FPC, 64 bit address is supported.*

* [MemoryModule](https://github.com/Fr0sT-Brutal/Delphi_MemoryModule). With the MemoryModule engine you can store all required DLLs inside your binary to keep it standalone. Additional hook units allow transparent using of MM engine thus allowing switching MM/WinAPI loading as well as enabling 3rd party dynamic-load DLL interfaces that are unaware of MM (tested with Interbase Express components and Firebird client library). MemoryModule is a Pascal port of Joachim Bauch's C MemoryModule.

## Other non-visual

* [TRegExpr](http://regexpstudio.com/TRegExpr/TRegExpr.html). Easy to use and powerful tool for sophisticated search and substitutioning and for template-based text input check.
// *Abandoned since 2004 but unlike stock RAD Studio implementation doesn't use PCRE obj files that add dependency on msvcrt.dll*

* [OnGuard](http://sourceforge.net/projects/tponguard) ([Alternate](https://github.com/TurboPack/OnGuard-VCL) and maintained version for recent compiler version only). Library to create demo versions of your Borland Delphi & C++Builder applications. Create demo versions that are time-limited, feature-limited, limited to a certain number of uses, or limited to a certain # of concurrent network users.
// *Second link points to an adapted version for newest compiler versions.*

* [StringSimilarity](http://code.google.com/p/theunknownones). Package designed for some fuzzy and phonetic string comparison algorithms. So far implemented are the following algorithms: DamerauLevenshtein, Koelner Phonetik, SoundEx, Metaphone, DoubleMetaphone, NGram, Dice, JaroWinkler, NeedlemanWunch, SmithWatermanGotoh, MongeElkan.

## OS
*Tools that help dealing with OS-specific internals*

* [GLibWMI](http://sourceforge.net/projects/glibwmi). Component Library for Delphi that encapsulate the classes for access to WMI of Windows in a set of VCL. BiosInfo, PrinterInfo, DiskInfo,... Allow access WMI Classes: WIN32_Bios, WIN32_Printers, WIN32_DiskDrive.

* [MemoryMap](https://github.com/AlexanderBagel/ProcessMemoryMap/tree/master/MemoryMap). Set of classes to get all the info about a memory of a running process.

* [The new Drag and Drop Component Suite ](https://github.com/landrix/The-new-Drag-and-Drop-Component-Suite-for-Delphi). VCL component library that enables your Delphi and C++Builder applications to support COM based drag and drop and integrate with the Windows clipboard.

## Unit Testing

* [DUnitX](https://github.com/VSoftTechnologies/DUnitX). New test framework, taking ideas from DUnit, NUnit and other test frameworks. It is designed to work with Delphi 2010 or later, it makes use of language/RTL features that are not available in older versions of Delphi.

* [DUnit](http://dunit.sourceforge.net). Unit Testing Framework, that has been the standard testing framework for years, the Delphi IDE now ships with this library. In addition to the drag and drop components, the Drag and Drop Component Suite also includes components that can be used to build Windows Shell Extensions.

* [DUnit2](http://dunit2.sourceforge.net). Fork of the DUnit Project that adds several new features.

* [DelphiSpec](https://github.com/RomanYankovsky/DelphiSpec). Library for running automated tests written in plain language. Because they're written in plain language, they can be read by anyone on your team. Because they can be read by anyone, you can use them to help improve communication, collaboration and trust on your team.

* [Delphi-Mocks](https://github.com/VSoftTechnologies/Delphi-Mocks). Simple mocking framework for Delphi XE2 or later. Allow you to mock both classes and interfaces for testing. 

* [DUnit-XML](https://github.com/VSoftTechnologies/DUnit-XML). Test runner that allows DUnit Tests to output NUnit compatible XML.


## Utilities
*Useful dev tools/IDE plugins*

* [Lazy Delphi Builder](https://bitbucket.org/tdelphi/lazy-delphi-builder-downloads/downloads). Build tool for Delphi. Recompile projects/packages from sources with all dependencies, without need to mess around with configs. Quickly (re-)install components from sources into IDE, with no need to change your Library Path.
// *Powerful automating tool. Freeware but not open source*

* [Delphi IDE theme editor / Delphi IDE Colorizer](https://code.google.com/p/delphi-ide-theme-editor). Tool to change the IDE color highlighting of several Object Pascal IDE's like Delphi (RAD Studio), Appmethod, Lazarus  and Smart Mobile Studio. DITE supports Delphi 5-7, 2005-2010, XE-XE6, Appmethod 1.13-1.14, Lazarus v1.0.1.3 and Smart Mobile Studio IDE v1.1.2.17. The Delphi IDE Colorizer (DIC) is a plugin which allows to customize the look and feel of the workspace of the RAD Studio IDE and Appmethod.

* [DDevExtensions](http://andy.jgknet.de/blog/ide-tools/ddevextensions). Extends the Delphi/C++Builder IDE by adding some new productivity features
// *Many useful IDE tweaks, must have.*

* [VCL Fix Pack](http://andy.jgknet.de/blog/bugfix-units/vclfixpack-10). Delphi unit that fixes VCL and RTL bugs at runtime by patching the original functions. If you want all IDE Fix Pack fixes in your application this unit is what you are looking for. Adding the unit to your project (Delphi and C++Builder) automatically installs the patches that are available for your Delphi/C++Builder version.
// *Actual for Delphi/C++ 6..2009*

* [IDE Fix Pack](http://andy.jgknet.de/blog/ide-tools/ide-fix-pack). Collection of unofficial bug fixes and performance optimizations for the RAD Studio IDE, Win32/Win64 compiler and Win32 debugger. IDE Fix Pack is an IDE plugin for RAD Studio 2009-XE6 that fixes IDE bugs at runtime. All changes are done in memory. No files on disk are modified. None of your projects are modified or benefit from the IDE Fix Pack other than being compiled faster. Only the IDE gets the fixes and optimizations.
// *Supports all RAD Studio versions since 2007. Removes lots of annoying bugs that EMBT haven't fixed for years. Yay!*

* [GExperts](https://sourceforge.net/projects/gexperts). Free set of tools built to increase the productivity of Delphi and C++Builder programmers by adding several features to the IDE. GExperts is developed as Open Source software and we encourage user contributions to the project. Grep search and replace supporting unicode files, DFMs, etc; Automatically rename components, insert text macros, open recent files; Easily backup your projects, with custom additional file lists; Keep nested lists of favorite files for quick access; Track dependencies between units in your project; Quickly jump to any procedure in the current unit; And much, much more...

* [CnWizards](https://github.com/cnpack). Free Plug-in Tool Set for Delphi/C++ Builder/CodeGear RAD Studio to Improve Development Efficiency.

* [Delphi Package Installer (DelphiPI)](https://bitbucket.org/idursun/delphipi) ([old repo](https://code.google.com/p/delphipi)). Tool which aids you installing components to your Delphi IDE. DelphiPI automatically resolves dependencies between packages, compiles, installs and adds source paths to your IDE.

* [ResEd](http://code.google.com/p/theunknownones). Expert for Delphi 2005, 2006, 2007, 2009, 2010 and XE. This expert is designed for editing the resource files (.res; .resx) that are linked to the active project. It will automatically search for all occurrences of {$R xyz.res} lines and will open/create resourcefiles for them. The expert registers itself in the menubar of Delphi under View.

* [Inno Setup](http://www.jrsoftware.org/isinfo.php). Free installer for Windows programs. First introduced in 1997, Inno Setup today rivals and even surpasses many commercial installers in feature set and stability.

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)