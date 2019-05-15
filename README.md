# Awesome Pascal [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome Delphi, FreePascal and other *Pascal frameworks, libraries, resources, and shiny things. Inspired by awesome-... stuff.

**Note that only open-source projects are considered. Dead projects (not updated for 3 years or more) are mainly ignored except for those which do not have alive analogs.**
Feel free to suggest other missing nice projects either by comments or pull requests.

This awesome collection is also available on [Delphi.ZEEF.com](https://delphi.zeef.com/anton.frost)

:exclamation: **Note on compiler compatibility**. There are compiler/language dialect compatibility badges for all projects based on a project's description. No real compatibility with compilers not officially supported is checked. Often a code could be used with non-supported compiler/language dialect with minor modifications but there could be exceptions.

## Contents ##

- [Awesome Delphi](#awesome-delphi)
	- [General Libraries](#general-libraries)
	- [Multimedia](#multimedia)
		- [Audio](#audio)
		- [Video](#video)
		- [Graphic](#graphic)
	- [Game dev](#game-dev)
	- [Communications](#communications)
		- [Network](#network)
		- [Serial port](#serial-port)
	- [GUI](#gui)
		- [Control packs](#control-packs)
		- [Single controls](#single-controls)
		- [Editors](#editors)
		- [Viewers](#viewers)
		- [Other GUI](#other-gui)
	- [Database](#database)
	- [Scripting](#scripting)
	- [Non-visual Classes/Utils](#non-visual-classesutils)
		- [Compression](#compression)
		- [Encryption](#encryption)
		- [XML/JSON/YAML](#xmljsonyaml)
		- [Language](#language)
		- [Memory managers](#memory-managers)
		- [System](#system)
		- [Template](#template)
		- [Logging](#logging)
		- [Math](#math)
		- [Other non-visual](#other-non-visual)
	- [OS](#os)
	- [Report generating](#report-generating)
	- [Unit Testing](#unit-testing)
	- [Debugging / error handling](#debugging--error-handling)
	- [Utilities](#utilities)
		- [RAD Studio IDE plugins/wizards](#rad-studio-ide-pluginswizards)
		- [Plugins for other IDE's](#plugins-for-other-ides)
		- [Documentation](#documentation)
		- [Code check/review, debug](#code-checkreview-debug)
		- [Setup](#setup)
		- [Other](#other)

----------------------------------------------------------------------------------------------------------------

## General Libraries ##
*Big general-purpose libraries*

* [JCL](https://github.com/project-jedi/jcl). `[Delphi]` `[FPC]` Set of thoroughly tested and fully documented utility functions and non-visual classes which can be instantly reused in your Delphi and C++ Builder projects. The library is grouped into several categories such as Strings, Files and I/O, Security, Math and many, many more.

* [JVCL](https://github.com/project-jedi/jvcl). `[Delphi]` Library of over 600 Delphi components developed by "Project JEDI" members.
// *GUI, algorithms, classes, API headers etc.*

* [Alcinoe](http://sourceforge.net/projects/alcinoe) ([mirror at GH](https://github.com/Zeus64/alcinoe)). `[Delphi]` Library of visual and non-visual components for Delphi.
// *Network: FTP/Http/NNTP/POP3/SMTP, ISAPI, WinInet Http/FTP clients; DB: Firebird/MySQL/SQLite3/Memcached/MongoDb/SphinxQL; XML/JSON Parser; ZLIB; Cryptography: AES, Blowfish, MD5, SHA, secure keyed MD5/SHA; opengl video player; FireMnkey controls; Other: Self-Balancing Binary Trees, expression evaluator*

* [Fundamentals Code Library](http://sourceforge.net/projects/fundementals) (abandoned, more recent fork is [here](https://github.com/fundamentalslib/fundamentals4) - though it slightly differs in units set, f.ex. no XML. Recent major version 5 [here](https://github.com/fundamentalslib/fundamentals5)). `[Delphi]` `[FPC]` Collection of Delphi / FreePascal code units. Includes libraries for Unicode, Strings, Data Structures, Sockets and Mathematics.
// *Utils: ZLIB compression; JSON; XML; ProtocolBuffers; Unicode routines; data structures; Hashes: XOR, CRC, Adler, MD5, SHA, secure keyed MD5/SHA, etc; Network: blocking TCP client/server, HTTP(S) via SSL3/TLS1.0/TLS1.1/TLS1.2 (fully native); SQL parser; BitCoin MtGox client; Blaise script engine; Cipher: AES, DES, FUNE, RC2, RC4, RSA, Diffie-Hellman; Maths: matrix, complex, statistics, huge numbers*

* [Spring4D](https://bitbucket.org/sglienke/spring4d). `[Delphi]` Open-source code library for Embarcadero Delphi 2010 and higher. It consists of a number of different modules that contain a base class library (common types, interface based collection types, reflection extensions) and a dependency injection framework. Includes Encryption Library.
// *Collections and other containers using Generics and based on IEnumerable, probably more accurate and featured than RTL analogs; crypto: CRC, DES, MD5, SHA; file utils etc*

* [TheUnknownOnes](https://github.com/chaosben/theunknownones). `[Delphi]` Huge heap of classes, components, utilities for almost every purpose. Nearly undocumented and seems not very up-to-date though.

* [CNVCL](https://github.com/cnpack/cnvcl). `[Delphi]` CnPack Component Package. Large collection of visual components, classes and utilities. // *Lots of useful stuff; documentation and comments mainly in Chinese*

* [mORMot](https://github.com/synopse/mORMot). `[Delphi]` `[FPC]` Client-Server ORM/ODM SOA MVC framework for Delphi 6 and higher, or FPC 2.7. Direct SQL/NoSQL database access, ORM/ODM over objects, RESTful ORM and SOA services via interfaces over high performance HTTP server, MVC/MVVM web sites, testing including mocks and stubs, logging, cryptography, compression, huge documentation.

* [MARS - Curiosity](https://github.com/andrea-magni/MARS). `[Delphi]` Delphi REST Library. Pure REST approach, standard concepts in a familiar Delphi flavor (including a component based client library). Known compatibility: Delphi versions from XE to 10 Seattle. Some functionalities requires FireDAC.

* [ADAPT](https://github.com/LaKraven/ADAPT). `[Delphi]` Advanced Developer Async Programming Toolkit, foundation library intended to be used at the heart of your projects for the purpose of providing extremely powerful, multi-threaded (and thread-safe) capabilities. Event Engine - a very powerful system for producing Multi-Threaded, Asynchronous and Event-Driven programs. Generics Collections - highly efficient Collection Types (Lists, Trees, Maps etc.). Math Library - a library for Unit Conversion, special calculation and other useful mathematics routines. Package Engine - extension of the Streamables Engine supporting the packaging of files together (a VFS of sorts). Shared Streams Library - 100% Thread-Safe Stream Classes (Interfaced too) allowing read/write from multiple Threads. Stream Handling Library - makes working with Streams much easier! Handles Deleting, Inserting, Reading and Writing data.

* [Redux Delphi](https://github.com/pierrejean-coudert/ReduxDelphi). `[Delphi]` Predictable state container for Delphi apps utilizing a unidirectional data flow. Inspired by ReduxJS. Comes with Immutable Generic List.

* [GrijjyFoundation](https://github.com/grijjy/GrijjyFoundation). `[Delphi]` Foundation classes and utilities that are used throughout the other Grijjy Repositories.
// *BSON/JSON, IOCP/EPOLL sockets, socket pools, HTTP, HTTP/2, OpenSSL, ProtocolBuffers.*

* [unRxLib](http://www.micrel.cz/RxLib/dfiles.htm). `[Delphi]` Effort to keep RxLibrary (library of 60+ components) actual.

* [QuickLib](https://github.com/exilon/QuickLib). `[Delphi]` `[FPC]` Delphi/freepascal (Windows/Linux) library for Quick development and crossplatform support (Json Serialize, AutoMapper, Chronometer, Threads, Lists, Config, Console services and more).

* [KOL](https://sourceforge.net/projects/kolmck). `[Delphi]` `[FPC]` ([KOL-CE](https://sourceforge.net/p/kol-ce) port to FPC) KEY OBJECTS LIBRARY for Delphi (and FPC) - to make applications small and power. This library is freeware and open source. MCK is a kit of mirror classes for the VISUAL project development in Delphi environment using KOL library.


## Multimedia ##


## Audio

* [Audio Tools Library](http://mac.sourceforge.net/atl). `[Delphi]` For manipulating many audio formats file information.
//**Abandoned since 2005.**

* [Delphi ASIO & VST Project](http://sourceforge.net/projects/delphiasiovst). `[Delphi]` Framework for writing applications using the ASIO interface and VST plugins. It comes with countless DSP algorithms all demonstrated in dozens of examples.
//*Not very active lately, but the trunk is in a usable state*

* [NewAC - New Audio Components](http://code.google.com/p/newac) (abandoned, list of forks on GH [here](https://github.com/search?l=Pascal&o=desc&q=newac&s=updated&type=Repositories)). `[Delphi]` Designed to help your Delphi programs perform different sound processing tasks. With NewAC you can play audio stored in many formats (wav, Ogg Vorbis, FLAC, Monkey Audio, WavPack, MP3, Windows WMA, DTS, AC-3 (Dobly Surround), VOB (DVD files)).
// *Playback, recording, tag read/write, some audio editing tasks and conversions*

* [Audorra](https://sourceforge.net/projects/audorra). `[Delphi]` `[FPC]` Digital audio library for Delphi and Freepascal. Using a flexible plugin architecture, it allows you to exchange the audio backend (e.g. WaveOut, OpenAL), add protocol classes (e.g. file, http) and decoders.


## Video

* [DSPack](https://code.google.com/p/dspack) (abandoned, active fork is [here](https://github.com/micha137/dspack-continued-mirror-for-delphinus)). `[Delphi]` Set of components and classes to write Multimedia Applications using MS Direct Show and DirectX technologies.

* [Delphi-OpenCV](https://github.com/Laex/Delphi-OpenCV). `[Delphi]` Translation of OpenCV library header files in Delphi
// *Includes FFMPEG headers*

* [FFmpeg Delphi/Pascal Headers](http://www.delphiffmpeg.com/headers). `[Delphi]` `[FPC]` Open source translation of FFMPEG headers.

* [PasLibVlc](http://prog.olsztyn.pl/paslibvlc). `[Delphi]` `[FPC]` Interface to VideoLAN libvlc.dll and VCL player component for Delphi / FreePascal based on VideoLAN

* [fevh264](https://github.com/dpethes/fevh264). `[FPC]` Baseline h.264 encoder. Windows and Linux are supported


## Graphic

* [Graphics32](https://github.com/graphics32/graphics32). `[Delphi]` `[FPC]` Designed for fast 32-bit graphics handling on Delphi, Kylix and Lazarus. Optimized for 32-bit pixel formats, it provides fast operations with pixels and graphic primitives, and in most cases Graphics32 outperforms the standard TCanvas classes. It is almost a hundred times faster in per-pixel access and about 2-5 times faster in drawing lines.

* [GraphicEx](https://github.com/mike-lischke/GraphicEx). `[Delphi]` Addendum to Delphi's Graphics.pas to enable your application to load many common image formats. This library is primarily designed to load images as background (buttons, forms, toolbars) and textures (DirectX, OpenGL) or for image browsing and editing purposes as long as you don't need to save images.

* [Vampyre Imaging Library](http://imaginglib.sourceforge.net). `[Delphi]` `[FPC]` Cross-platform native Object Pascal (Delphi and Free Pascal) image loading, saving, and manipulation library.

* [CCR-EXIF](https://code.google.com/p/ccr-exif) (seems abandoned, list of forks on GH [here](https://github.com/search?l=Pascal&o=desc&q=ccr-exif&s=updated&type=Repositories)). `[Delphi]` Library to read and write Exif, IPTC and XMP metadata from JPEG, TIFF and PSD images.

* [KIcon](http://www.tkweb.eu/en/delphicomp/kicon.html). `[Delphi]` `[FPC]` This component makes sense if a more complex manipulation with icons (or better icon files *.ico) than just viewing is needed. Full PNG icon image support, correct rendering, icons with alpha channel.

* [Delphi Twain](http://www.kluug.net/delphitwain.php). `[Delphi]` `[FPC]` The library allows you to easily access scanning functions from Delphi and Lazarus.

* [Synopse PDF](https://github.com/synopse/SynPDF). `[Delphi]` `[FPC]` Fully featured Open Source PDF document creation library for Delphi, embedded in one unit. Pure Delphi code, Delphi 5 up to Delphi 10.3 Rio (and latest version of FPC), for Win32 and Win64 platforms.

* [PowerPDF](https://github.com/TurboPack/PowerPDF). `[Delphi]` VCL component to create PDF document visually. Like Forms, you can design PDF document easily on Delphi or C++Builder IDE.

* [IGDI+](https://sourceforge.net/projects/igdiplus). `[Delphi]` The free open source library allows quick and easy implementations of complex GDI+ applications, in a natural Delphi-friendly code.

* [GLScene](https://sourceforge.net/projects/glscene). `[Delphi]` `[FPC]` OpenGL based 3D library for Delphi, C++Builder and Lazarus. It provides visual components and objects allowing description and rendering of 3D scenes in an easy, no-hassle, yet powerful manner. GLScene is not just an OpenGL wrapper or utility library, it has grown to become a set of founding classes for a generic 3D engine with Rapid Application Development in mind. GLScene allows you to quickly design and render 3D scenes without having to learn the intricacies of OpenGL, if you know how to design a TForm, you'll easily master the basic operations of GLScene. The library comes with a large collections of demos showcasing the ease of use, and demonstrating RAD wasn't done at the expense of CPU/GPU horsepower.

* [SynGdiPlus](https://github.com/synopse/mORMot/blob/master/SynGdiPlus.pas). `[Delphi]` `[FPC]` Enables an application to load and save GIF, TIF, PNG and JPG pictures. It also allows anti-aliased drawing from any TMetaFile. That is, you can play a .emf content using GDI+ instead of GDI, for much better rendering result.

* [Andorra 2D](http://sourceforge.net/projects/andorra). `[Delphi]` `[FPC]` New generation 2D Engine for Delphi and Lazarus. Andorra 2D is capable to use DirectX or OpenGL through graphic plugins. Andorra 2D is built in a very modular way and is yet easy to use.

* [Transparent-canvas](https://github.com/vintagedave/transparent-canvas). `[Delphi]` Delphi VCL / Windows project for drawing semi-transparent alphablended graphics. It provides a class similar to TCanvas.

* [Fully-justified-text](https://github.com/vintagedave/fully-justified-text). `[Delphi]` Delphi VCL / Windows project for text output, allowing printing of fully justified text with a variety of options.

* [AsciiImage](https://github.com/Memnarch/AsciiImage). `[Delphi]` AsciiImage-Implementation for Delphi by Alexander Benikowski based on AsciiImage by Charles Parnot. Read more on [his article](http://cocoamine.net/blog/2015/03/20/replacing-photoshop-with-nsstring).
// *Creates scalable monochrome image from ASCII pixel map*

* [PngComponents](https://bitbucket.org/uweraabe/pngcomponents). `[Delphi]` PngComponents is a set of components that allows you to include in your application real PNG files. PNG files on their own do not generate an enourmous advantage, but their support for an alpha-channel does indeed have quite a charm to it.

* [AggPasMod](https://github.com/CWBudde/AggPasMod). `[Delphi]` Modernized Pascal Anti-Grain Geometry. Based on AggPas, which is itself based on the Anti-Grain Geometry, this project offers support for the latest Delphi Versions (XE and above) and contains some helper classes (VCL components and FireMonkey interface). 2D vector graphics library. Basically, you can think of AggPas as of a rendering engine that produces pixel images in memory from some vectorial data. But of course, AGG can do much more than that.
// *Vector graphic library, renders SVG and much more*

* [delphi-shader](https://github.com/WouterVanNifterick/delphi-shader). `[Delphi]` Hundreds of graphical effects, and a library that provides GLSL functionality in pure Delphi code. This project produces an executable with more than a hundred real-time graphical effects. All that is a 100% pascal implementation, without the use of exernal libraries or hardware acceleration.

* [dglOpenGL](https://github.com/SaschaWillems/dglOpenGL). `[Delphi]` `[FPC]` Delphi / Pascal OpenGL header translation.

* [DelphiZXingQRCodeEx](https://github.com/MichaelDemidov/DelphiZXingQRCodeEx). `[Delphi]` `[FPC]` Delphi/Lazarus port of the QR Code generating functionality from ZXing, an open source barcode image processing library.

* [ZXing.Delphi](https://github.com/Spelt/ZXing.Delphi). `[Delphi]` Native Object Pascal library for Delphi XE to 10.2 Tokyo that is based on the well known open source Barcode Scanning Library ZXing (Zebra Crossing). It is aimed at all of the FireMonkey mobile platforms and, starting from v3.1, it fully supports also Windows VCL applications (no dependencies on FMX.Graphics unit).

* [QuickImageFX](https://github.com/exilon/QuickImageFX). `[Delphi]` Delphi library for simplifying image load/save, conversion and transformation. Load/save png, jpg, gif and bmp. get image from different resources: file, stream, http, imagelist, associated windows icon, executable file icon, etc... Rotate, flip, grayscale and many other transformations.

* [NativeJpg](https://code.google.com/p/simdesign). `[Delphi]` Fully object-oriented Pascal implementation that allows to read and write Jpeg files. You can use this software to read and write Jpeg images from files or streams. It supports baseline and progressive Jpeg, support for metadata, as well as all conceivable lossless operations.


## Game dev ##

* [RecastNavigation](https://github.com/Kromster80/RecastNavigationDelphi). `[Delphi]` Navigation mesh construction toolset for games. Recast is accompanied with Detour, path-finding and spatial reasoning toolkit. You can use any navigation mesh with Detour, but of course the data generated with Recast fits perfectly. This is a port of the original RecastNavigation written in C++.

* [Kraft Physics Engine](https://github.com/BeRo1985/kraft). `[Delphi]` `[FPC]` Open source Object Pascal physics engine library that can be used in 3D games. Compatible with: Delphi 7-XE7 (but not with the Android and iOS targets), FreePascal >= 2.6.2 (with almost all FPC-supported targets including Android and iOS)

* [ZenGL](https://github.com/andru-kun/zengl). `[Delphi]` `[FPC]` OpenGL Cross-platform game development library written in Pascal, designed to provide necessary functionality for rendering 2D-graphics, handling input, sound output, etc.
// *Not updated lately, but is working ok*

* [Asphyre aka Platform eXtended Library (PXL)](https://sourceforge.net/projects/asphyre). `[Delphi]` `[FPC]` Cross-platform framework for developing 2D/3D video games, interactive and scientific applications. It aids the developer with mathematics, hardware control, resource management, displaying real-time graphics and text, handle user input and network communication capabilities.

* [CrystalPathFinding](https://github.com/d-mozulyov/CrystalPathFinding). `[Delphi]` `[FPC]` Simple and effective library with an open source intended for the searching of the shortest paths by algorithms A*/WA* for maps based on tiles with 4 (simple), 8 (diagonal/diagonalex) or 6 (hexagonal) neighbors.

* [Allegro-Pas](https://sourceforge.net/projects/allegro-pas) ([GitHub](https://github.com/niuniomartinez/allegro-pas)). `[Delphi]` `[FPC]` Wrapper to use the Allegro game library with Pascal/Delphi.

* [Castle Engine](https://github.com/castle-engine/castle-engine). `[FPC]` Complete Pascal Game Engine. Cross-platform 3D and 2D game engine with a lot of graphic effects and a scene graph based on X3D.

* [TileEngine](http://www.tilengine.org). ([GitHub](https://github.com/turric4n/PascalTileEngine)) `[Delphi]` `[FPC]` OOP Pascal Wrapper and bindings for Tilengine 2D retro graphics engine. Tilengine is a cross-platform 2D graphics engine for creating classic/retro games with tilemaps, sprites and palettes. Its scanline-based rendering algorithm makes raster effects a core feature, a technique used by many games running on real 2D graphics chips.

* [SDL2](http://www.freepascal-meets-sdl.net/) ([GitHub](https://github.com/ev1313/Pascal-SDL-2-Headers)). `[Delphi]` `[FPC]` Pascal SDL 2 Headers. Simple DirectMedia Layer is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D.

* [SFML](https://github.com/CWBudde/PasSFML). `[Delphi]` `[FPC]` Pascal SFML Headers. SFML provides a simple interface to the various components of your PC, to ease the development of games and multimedia applications. It is composed of five modules: system, window, graphics, audio and network. Currently Delphi and FPC/Lazarus are supported. However, due to a compiler incompatibility with the Delphi compiler (solved with workarounds), FPC is recommended at the moment.

* [pasvulkan](https://github.com/BeRo1985/pasvulkan). `[Delphi]` `[FPC]` Vulkan header generator, OOP-style API wrapper, framework and prospective Vulkan-based game engine for Object Pascal.

* [DarkGlass](https://github.com/chapmanworld/DarkGlass). `[Delphi]` DarkGlass is a general purpose game engine written using Delphi.

* [JEDI-SDL](https://sourceforge.net/projects/jedi-sdl). `[Delphi]` `[FPC]` Pascal headers for SDL from JEDI. Works with Delphi, Kylix, Free Pascal, Gnu Pascal and TMT Pascal.


## Communications ##


## Network
*Socket communication, network protocols, encodings, etc*

* [Internet Component Suite](http://www.overbyte.be/frame_index.html). `[Delphi]` Asynchronous-based library composed of various Internet components and applications. Clients/servers for TCP, UDP, raw sockets, FTP, SMTP, POP3, NNTP, HTTP, Telnet and more. Supports SSL and TLS with the help of OpenSSL. Also includes Mime Decoder, SHA1/MD4/MD5 hashes, DES encryption.

* [Indy](https://github.com/IndySockets/Indy). `[Delphi]` `[FPC]` Network components for Delphi, C++Builder, Delphi.NET, and FreePascal
// *All-in-one network library based on blocking sockets and threads. Included in default RAD studio installation since 2006.*

* [Ararat Synapse](https://sourceforge.net/p/synalist). `[Delphi]` `[FPC]` Pascal TCP/IP Library for Dephi, C++Builder, Kylix and FreePascal. Deals with network communication by means of blocking (synchronous) sockets or with limited non-blocking mode. This project not using asynchronous sockets! The Project contains simple low level non-visual objects for easiest programming without problems (no required multithread synchronisation, no need for windows message processing,...) Great for command line utilities, visual projects, NT services,...
// *TCP, UDP, ICMP, RAW; ICMP, DNS, SMTP, HTTP, SNMP, NTP, FTP, LDAP, NNTP, Telnet;  IPv6; SOCKS proxy; SSL/TLS (via OpenSSL or Windows CryptoApi); PING; character code transcoding; MIME coding and decoding; CRC16, CRC32, MD5 and HMAC-MD5.*

* [Internet Professional](http://sourceforge.net/projects/tpipro2010). `[Delphi]` Set of VCL components providing Internet connectivity for Borland Delphi & C++Builder. iPRO includes POP3, SMTP, NNTP, FTP, HTTP, Instant Messaging, & HTML viewer components, as well as components for low-level socket access.
// *Seems abandoned but contains pretty large set of features incl ICMP, POP, SMTP, HTTP, NNTP, NTP, FTP, SMTP; HTML parser and viewer; MIME utils; cookies, certificates, caching, encryption etc*

* [SynCrtSock](https://github.com/synopse/mORMot/blob/master/SynCrtSock.pas). `[Delphi]` `[FPC]` Features several sockets and HTTP client-server classes, including a high-performance http.sys based server under Windows, and a new thread-pool powered socket server.
// *Also implements http.sys binding under Windows and cURL binding under nix*

* [TML Messaging Suite](http://www.libtml.org/docs/libtml-pascal). `[Delphi]` `[FPC]` Network messaging library for rapid development of extensible and scalable interfaces. Based on the peer to peer standard protocol [BEEP (Blocks Extensible Exchange Protocol)](http://www.beepcore.org), defined in [RFC3080](https://tools.ietf.org/html/rfc3080) and [RFC3081](https://tools.ietf.org/html/rfc3081). libTML is suitable for many use cases and communication patterns. Equipped with a type safe data API, TML can transport hierarchical data structures fast and reliable.
// *The libTML Object Pascal Components are not only a language binding to the core library but a complete set of non visual components to simplify the usage of libTML with Embarcadero RAD Studio and Lazarus.*

* [DMVCFramework](https://github.com/danieleteti/delphimvcframework). `[Delphi]` Popular and powerful framework for web solution in Delphi.

* [Delphi IOCP](https://github.com/ymofen/diocp-v5). `[Delphi]` Implements several network classes based on Windows IOCP technology. Socket, HTTP, Ntrip servers and clients.
// *Quite well documented and good styled code but Chinese only.*

* [delphi-aws-ses](https://github.com/monde-sistemas/delphi-aws-ses). `[Delphi]` Amazon Simple Email Service (AWS SES) library for Delphi applications.

* [delphi-slackbot](https://github.com/monde-sistemas/delphi-slackbot). `[Delphi]` Delphi library to send messages on [Slack](https://slack.com) using slackbot.

* [Kitto](https://github.com/EtheaDev/kitto). `[Delphi]` Allows to create Rich Internet Applications based on a data model that can be mapped onto any database. The client-side part uses ExtJS (through the ExtPascal library) to create a fully AJAX application, allowing you to build standard and advanced data-manipulating forms in a fraction of the time. Kitto is aimed at Delphi developers that need to create web application without delving into the intricacies of HTML, CSS, Javascript or learning to use a particular library such as ExtJS, yet it allows access to the bare metal if required.

* [Daraja Framework](https://github.com/michaelJustin/daraja-framework). `[Delphi]` `[FPC]` Lightweight HTTP server framework for Object Pascal (Delphi 2009+ / Free Pascal 3.0). Implementing RESTful services is supported via the [daraja-restful](https://github.com/michaelJustin/daraja-restful) extension.

* [Alcinoe](#general-libraries). FTP/Http/NNTP/POP3/SMTP, ISAPI, WinInet Http/FTP clients.

* [Fundamentals Code Library](#general-libraries). Blocking TCP client/server, HTTP(S) via SSL3/TLS1.0/TLS1.1/TLS1.2 (fully native).

* [mORMot](#general-libraries). RESTful ORM and SOA services via interfaces over high performance HTTP server, MVC/MVVM web sites

* [SDriver](https://github.com/andrea-magni/SDriver). `[Delphi]` Delphi wrapper for [Slack](https://slack.com) API.

* [Hprose for Delphi/Lazarus](https://github.com/hprose/hprose-delphi). `[Delphi]` `[FPC]` High Performance Remote Object Service Engine. It is a modern, lightweight, cross-language, cross-platform, object-oriented, high performance, remote dynamic communication middleware. It is not only easy to use, but powerful. This project is the implementation of Hprose for Delphi/Lazarus.

* [TelegAPI](https://github.com/ms301/TelegAPI). `[Delphi]` Library for working with Telegram messenger Bot API in Delphi.

* [DelphiZeroMQ](https://github.com/grijjy/DelphiZeroMQ). `[Delphi]` Delphi implementation of ZeroMQ Majordomo protocol and CZMQ high level binding.

* [GrijjyFoundation](#general-libraries). IOCP/EPOLL sockets, socket pools, HTTP, HTTP/2, OpenSSL, ProtocolBuffers.

* [Rest-Dataware-Componentes](https://github.com/Rest-Dataware/RDW-Componente). `[Delphi]` `[FPC]` Was created to facilitate the creation of CRUDs in the same model that we created applications for Client / Server Database. With REST DW, you no longer have to worry about creating SQL Insertion, Deletion, Read and Execution methods via Webservice; Simply add a RESTDataBase connection component and add a RESTClientSQL component that will already have your SQL solution fully functional as it did back in the day and with all the power of modern REST / JSON technology with data compression and everything the language can offer.

* [STOMP Client](https://github.com/danieleteti/delphistompclient). `[Delphi]` `[FPC]` STOMP client for Embarcadero Delphi and FreePascal. The project can use INDY (Delphi) or Synapse (Delphi or FreePascal).

* [delphiXero](https://github.com/littleearth/delphiXERO). `[Delphi]` XERO cloud accounting API for Delphi.

* [BesaSoap](https://github.com/besasoftware/besasoap). `[Delphi]` The BesaSoap library is designed to help programmers develop faster and more native web service client applications. Represents C# or Java like native class support, nullable data types and custom attributes.

* [IndySoap](https://sourceforge.net/projects/indysoap). `[Delphi]` Open Source Library for implementing Web services using Delphi/CBuilder Compilers. IndySoap isn't tied to Indy for transport services, though Indy based transport services are included.

* [Fano Framework](https://fanoframework.github.io). `[FPC]` Web application framework for modern Pascal programming language. It is written in Free Pascal.

* [Internet Tools](#xmljsonyaml). XPath/XQuery/JSONiq/CSS/HTML; functions to perform HTTP/S requests on Windows/Linux/MacOSX/Android, an XSLT-inspired webscraping language, and an auto update class.

* [Delphi Cross Socket](https://github.com/winddriver/Delphi-Cross-Socket/). `[Delphi]` Delphi cross platform socket library (Chinese). Uses different IO models for different platforms: IOCP (Windows), KQUEUE (FreeBSD(MacOSX, iOS...)), EPOLL (Linux(Linux, Android...)).


## Serial port

* [Synaser](http://sourceforge.net/p/synalist/code/HEAD/tree/trunk/synaser.pas). `[Delphi]` `[FPC]` Library for blocking communication on serial ports. It is non-visual class as in Synapse, and programmer interface is very similar to Synapse.

* [Async Professional](http://sourceforge.net/projects/tpapro) ([Newest](https://github.com/TurboPack/AsyncPro) and maintained version for recent compiler version only). `[Delphi]` Comprehensive communications toolkit for Embarcadero Delphi, C++Builder, & ActiveX environments. It provides direct access to serial ports, TAPI and the Microsoft Speech API (TTS/Speech recognition). It supports faxing, terminal emulation, VOIP, RAS dial & more.
// *Seems outdated (last update in 2011) but adapted to XE and should be easy to use in newer versions. The project is also very thoroughly documented. Second link points to an adapted version for newest compiler versions.*

* [TComPort](https://sourceforge.net/projects/comport). `[Delphi]` Delphi/C++ Builder serial communications components. It is generally easy to use for basic Serial Communications purposes.
// *Seems abandoned since 2011*


## GUI ##
*Visual components*


## Control packs
*Large sets of GUI controls*

* [Cindy components](http://sourceforge.net/projects/tcycomponents). `[Delphi]` Packages with 71 components: VCL controls (labels, buttons, panels, Edits, TabControls, StaticText) with features like background gradient, colored bevels, wallpaper, shadowText, caption orientation etc...

* [Orpheus](http://sourceforge.net/projects/tporpheus) ([Newest](https://github.com/TurboPack/Orpheus) and maintained version for recent compiler version only). `[Delphi]` Award-winning UI toolkit for Borland Delphi & C++Builder. It contains over 120 components covering everything from data entry to calendars and clocks. Other noteworthy components include an Object Inspector, LookOut bar & report views.
// *Advanced edits, comboboxes, grids + component (de)serializers. GUI components look rather old-style, theme support might be limited. Package contains many demos but no docs seem available. Second link points to an adapted version for newest compiler versions.*

* [KControls](http://www.tkweb.eu/en/delphicomp/kcontrols.html). `[Delphi]` `[FPC]` Control components. All controls have been written with the aim to become both cross-IDE compatible (Delphi/C++Builder VCL and Lazarus LCL) and cross-platform compatible in Lazarus.
// *Most useful are TKGrid with its DB-aware heritage TKDBGrid — a very full-featured grid implementation incl. inplace editors. There's also hex editor, print preview, editors, labels, buttons etc.*

* [D.P.F Delphi Android](http://sourceforge.net/projects/dpfdelphiandroid) / [D.P.F Delphi iOS](http://sourceforge.net/projects/dpfdelphiios) native components. `[Delphi]` D.P.F Delphi Native Components, 100% iOS Performance and styles. Develop iPhone & iPad & iPod Touch applications with fast native performance and native styles. Use native Android controls and services. Fast native performance. Mixed with FM VCL controls. Can be quick updated with latest Android controls & features.

* [Essentials](https://github.com/TurboPack/Essentials). `[Delphi]` Contains 13 native VCL controls for Embarcadero Delphi and C++Builder. The controls include drop-down calendars and calculators, roll-up dialogs, 3-D labels, tiled backgrounds, scrolling messages, menu buttons, and more.

* [FreeEsVCLComponents](https://github.com/errorcalc/FreeEsVCLComponents). `[Delphi]` Free library of VCL components for Delphi and C++Builder. This new controls and components to improve the appearance applications and to better user experience. Components support visual styles and has modern style. All components has best support transparency, not flicker, and has support interesting possibility for double buffering for TGraphicControl heirs.

* [SpTBXLib](https://github.com/SilverpointDev/sptbxlib). `[Delphi]` Add on package for Toolbar2000 components, it adds the following features: Skins, Unicode support, Custom painting events and many more.


## Single controls

* [EasyListView](http://code.google.com/p/mustangpeakeasylistview) (seems abandoned, active fork on GH [here](https://github.com/TurboPack/MustangpeakEasyListview)). `[Delphi]` Part of VirtualShellTools for the Listview but can be used for a TListview Replacement that is faster and more customizable.
// *Feature-rich Listview implementing virtual (callback-based) MVC paradigm.*

* [VirtualTreeView](https://github.com/Virtual-TreeView/Virtual-TreeView). `[Delphi]` ([VirtualTreeView-Lazarus](https://github.com/blikblum/VirtualTreeView-Lazarus) port to FPC `[FPC]`). Treeview control built from ground up. Many years of development made it one of the most flexible and advanced tree controls available today.
// *Extremely flexible visual component implementing virtual (callback-based) MVC paradigm. Could be also used as a listview or grid. Used in RAD Studio GUI.*

* [Delphi Chromium Embedded](https://github.com/hgourvest/dcef3). `[Delphi]` Embedding Chromium in Delphi, tested on Delphi 2010, XE, XE2, Delphi 7.
// *Several Chromium DLLs required*

* [TChromeTabs](https://github.com/norgepaul/tchrometabs). `[Delphi]` Comprehensive implementation of Google Chrome's tabs for Delphi 6 - Delphi 10.1 Berlin

* [TFrameStand](https://github.com/andrea-magni/TFrameStand). `[Delphi]` Easily use TFrame(s) in your FireMonkey (FMX) applications to gain visual consistency though the whole user experience and easily add modern looking elements like effects and transitions.

* [TPrintPreview](https://github.com/landrix/TPrintPreview-for-Delphi). `[Delphi]` Print Preview Component for Delphi Vcl Win32/Win64

* [VolgaDB](https://sourceforge.net/projects/volgadb). `[Delphi]` Pretty customizable DBgrid for Delphi. TCustomGrid descendant. CheckBox, ComboBox column styles. Also includes TVolgaDBEdit that replaces TDBEdit, TDBComboBox, TDBLookupCombo, TDBLookupTree andTDBDatePicker in one component. TVolgaDBEdit may be DB-aware and non DB-aware.
// *Seems abandoned since 2013*

* [TTreeListView](http://github.com/benibela/treelistview). `[Delphi]` `[FPC]` This component is a mix between TTreeView and TListView and can paint a tree whose nodes have additional information sorted in columns.

* [neTabControl](https://github.com/jkour/neTabControl). `[Delphi]` FireMonkey control for Delphi. It builds on the native TabControl and adds a number of features.

* [ATTabs](https://github.com/Alexey-T/ATTabs). `[Delphi]` `[FPC]` Delphi/Lazarus component for lite tabs. OS independent, fully custom drawn.


## Editors

* [SynEdit](https://sourceforge.net/projects/synedit) ([mirror at GitHub](https://github.com/TurboPack/SynEdit)). `[Delphi]` Syntax highlighting edit control, not based on the Windows common controls. SynEdit is compatible with both Delphi and Kylix

* [BCEditor](https://github.com/bonecode/BCEditor). `[Delphi]` Syntax highlighting edit control with code folding, minimap, external JSON highlighter and color scheme files, etc.
// *Seems abandoned. Developer recommends using SynEdit instead*

* [LazEdit](https://svn.code.sf.net/p/lazarus-ccr/svn/applications/lazedit). `[FPC]` General text editor with syntax highlighting and tools to help edit HTML.


## Viewers

* [ATViewer](https://sourceforge.net/projects/atviewer) ([mirror at GitHub](https://github.com/Alexey-T/ATViewer)). `[Delphi]` Delphi components to view various file types: text, binary, images, multimedia, webpages, etc.
// *Used in Universal Viewer software. Could be used to display hex dumps, features fast display of unlimited size files/streams. Supports Total Commander Lister plugins.*

* [ATImageMap](https://sourceforge.net/projects/atviewer/files/ATImageMap) ([mirror at GitHub](https://github.com/Alexey-T/ATViewer)). `[Delphi]` Component designed to show many images (parts of the whole image) as a single map. For example, you may have array of images, 200 by X, and 100 by Y and control will show them as a single map. Component also allows to draw paths: each path consists of many lines, points, and icons.

* [HtmlViewer](https://github.com/BerndGabriel/HtmlViewer). `[Delphi]` `[FPC]` Delphi/Lazarus HtmlViewer/FrameViewer.
// *Html visualiser supporting majority of tags, inline styles and CSS.*

* [SciDe](https://github.com/da-baranov/SciDe). `[Delphi]` `[FPC]` [Sciter](https://sciter.com) (Embeddable HTML/CSS/script engine) wrapper for Delphi.

* [ATBinHex for Delphi](https://github.com/Alexey-T/ATViewer/blob/master/Source/ATBinHex.pas) `[Delphi]`, [ATBinHex for Laz](https://github.com/Alexey-T/ATBinHex-Lazarus). `[FPC]` Viewer for files of unlimited size like in Total Commander.

* [ATImageBox for Delphi](https://github.com/Alexey-T/ATViewer/blob/master/Source/ATImageBox.pas) `[Delphi]`, [ATImageBox for Laz](https://github.com/Alexey-T/ATImageBox-Lazarus). `[FPC]` TScrollBox with embedded TImage. Control can auto position image inside.


## Other GUI

* [GMLib](https://code.google.com/p/gmlibrary) (Google Maps Library) (seems abandoned, active fork on GH [here](https://github.com/bero/GMLibrary) and [here](https://github.com/cadetill/gmlib_v1)). `[Delphi]` Components for Delphi/C++ Builder that encapsulate the GoogleMaps API to administrate a map, markers, polygons, rectangles, polylines,... All objects that you can put into a map.

* [VCL Styles Utils](https://github.com/rruz/vcl-styles-utils). `[Delphi]` Collection of classes and style hooks, which extend, fix QC reports and add new features to the VCL Styles.
// *Collection of patches/enhancements that promote stock VCL style engine to a new level. Styling for Inno setup and NSIS also available.*

* [TaskbarListComponents](https://github.com/chaosben/theunknownones/tree/master/Components/TaskBarList). `[Delphi]` Set of components designed as Delphi wrappers for the Windows 7 Taskbarlist Interfaces (e.g. ITaskbarlist3)
// *Requires JVCL*

* [TFireMonkeyContainer](https://github.com/vintagedave/firemonkey-container). `[Delphi]` Delphi VCL component to host a FMX HD or 3D form. It means you can embed a FireMonkey (FMX) form as a control in a VCL form, so you can design a FMX form and use it in your VCL app.

* [PascalSCADA](http://sourceforge.net/projects/pascalscada). `[Delphi]` `[FPC]` Set of components (framework) for Delphi/Lazarus to make easy the development of industrial applications (HMI=Human Machine Interface/SCADA=System Control And Data Acquisition). It runs on Windows, Linux and FreeBSD.

* [Windows Ribbon Framework for Delphi](https://github.com/turbopack/ribbonframework). `[Delphi]` This Delphi library allows Delphi developers to use of the Windows Ribbon Framework in their Delphi applications. This library uses the native Windows library to implement the Ribbon functionality. It does not emulate the Ribbon user interface like other Delphi component sets do (or Delphi's built-in Ribbon emulation components).

* [DKLang](https://github.com/yktoo/dklang). `[Delphi]` DKLang Localization Package is a set of classes intended to simplify the localization of applications written in Delphi.

* [GNU Gettext for Delphi, C++ and Kylix](https://sourceforge.net/projects/dxgettext/). `[Delphi]` GNU GetText translation tools for Borland Delphi and Borland C++ Builder.

* [OpenWire](https://sourceforge.net/projects/openwireproject). `[Delphi]` The library allows writing advanced VCL and FireMonkey components for rapid codeless application development. The components developed with the library allow creation of complex applications with zero lines of program code.

* [SynTaskDialog](https://github.com/synopse/mORMot/blob/master/SynTaskDialog.pas). `[Delphi]` `[FPC]` Implement TaskDialog window (native on Vista/Seven, emulated on XP)

* [AnyiQuack](https://github.com/WladiD/AnyiQuack). `[Delphi]` jQuery-like control animation framework.

* [TLanguages](https://github.com/albertodev01/TLanguages). `[Delphi]` Localization tool for VCL and FMX.


## Database ##

* [ZeosLib](http://sourceforge.net/projects/zeoslib). `[Delphi]` `[FPC]` Set of database components for MySQL, PostgreSQL, Interbase, Firebird, MS SQL, Sybase, Oracle and SQLite.

* [Unified Interbase](https://github.com/hgourvest/uib). `[Delphi]` Set of components to use Interbase, FireBird and YAFFIL. These components were born from the need to use Interbase, FireBird or Yaffil indifferently as fast as possible in a Multithreading environment, a Server for example.

* [ASQLite](https://github.com/remobjects/ASQLite3). `[Delphi]` Delphi SQLite set of DAC components from aducom software, based on their latest release for Delphi 2009, and updated to support newer editions of Delphi as included in RemObjects Data Abstract for Delphi.

* [TxQuery](https://github.com/ccy/txquery). `[Delphi]` TDataSet descendant component that can be used to query one or more TDataSet descendant components using SQL statements. It is implemented in Delphi 100% source code, no DLL required, because it implements its own SQL syntax parser and SQL engine.

* [Delphi-ORM](https://github.com/danieleteti/delphi-orm). `[Delphi]` Object-Relational Mapping for Delphi XE2-7 (Win32). Supports for FirebirdSQL, SQLServer and SQLite3.

* [delphimemcache](https://code.google.com/p/delphimemcache). `[Delphi]` Implements a thread safe client for memcached.
// *Requires Indy 10*

* [SynDB](https://github.com/synopse/mORMot) ([docs](http://synopse.info/files/html/Synopse%20mORMot%20Framework%20SAD%201.18.html#TITL_126)). `[Delphi]` `[FPC]` High performance direct access to SQLite3, Oracle, MSSQL, PostgreSQL, Firebird, MySQL, ODBC, OleDB, including remote HTTP connection and direct JSON support.

* [SynMongoDB](https://github.com/synopse/mORMot/blob/master/SynMongoDB.pas) ([docs](http://blog.synopse.info/post/2014/05/07/MongoDB-database-access)). `[Delphi]` `[FPC]` Offers direct low-level access to any MongoDB server, its custom data types, JSON or via `TDocVariant` custom variant document storage.

* [DSharp](https://bitbucket.org/sglienke/dsharp). `[Delphi]` Small library for providing data binding in Delphi. It does not require special components to data bind to properties. It also provides dependency injection, MVVM and more interesting utilities.

* [ghORM](https://github.com/leledumbo/ghORM). `[FPC]` Object Relational Mapping unit to ease database access from Free Pascal, by abstracting the backend and simple data retrieval (with filtering), insertion and update.

* [tDBF](http://sourceforge.net/p/tdbf/code/HEAD/tree). `[Delphi]` `[FPC]` Native dBASE III+, dBase IV and dBase 2k data access component for Delphi, BCB, Kylix, FreePascal. It allows you to create very compact database programs which don't need any special installer programs. The DB engine code is compiled right into your executable.

* [Redis client](https://github.com/danieleteti/delphiredisclient) `[Delphi]` Delphi Redis Client version 2 is compatible with Delphi 10.1 Berlin and better. WARNING! If you use an older Delphi version you have to use [Delphi Redis Client Version 1](https://github.com/danieleteti/delphiredisclient/tree/DELPHI_REDIS_CLIENT_VERSION_1) wich works for Delphi 10 Seattle, XE8, XE7, XE6 and XE5 (should works also with older versions). This client is able to send all Redis commands and read the response using an internal parser.

* [QDAC3](http://blog.qdac.cc/?page_id=139) (SVN: svn://www.qdac.cc/QDAC3). `[Delphi]` Stands for quick data access components. Useful units such as QJson (easy to use json unit), QWorker (job delivery) etc.
// *Description and comments in Chinese, author is not good at English. Haven't tested this library by myself.*

* [InstantObjects](https://github.com/EtheaDev/InstantObjects). `[Delphi]` Integrated framework for developing object-oriented business solutions in Delphi. The framework provides the foundation for the development process as well as the engine that powers the final application. InstantObjects offers: Model realization in the Delphi IDE via integrated two-way tools; Object persistence in the most common relational databases or flat XML-based files; Object presentation via standard data-aware controls.

* [Alcinoe](#general-libraries). Firebird/MySQL/SQLite3/Memcached/MongoDb/SphinxQL.

* [SynBigTable](https://github.com/synopse/mORMot/blob/master/SynBigTable.pas). `[Delphi]` `[FPC]` Class used to store huge amount of data with fast retrieval.

* [tiOPF](https://github.com/graemeg/tiopf). `[Delphi]` `[FPC]` Object Persistent Framework written in Object Pascal, for use with Delphi and Free Pascal (FPC) compilers. tiOPF simplifies the mapping of an object oriented business model into a relational database. Persistence layers are available for Firebird, Oracle, MS SQL Server, MySQL, PostgreSQL, SQLite, NexusDB, XML, CSV, TAB, Remote (via HTTP) and many more. It also allows you to use your choice of database connection components, like IBX, dbExpress, DOA, SqlDB, FBLib etc.

* [hcOPF](https://sourceforge.net/projects/larryhengensopf). `[Delphi]` Object Persistent Framework written in Embarcadero's Delphi (Object Pascal). This Value Type Framework provides a base class (ThcObject) composed of attribute objects that can be automatically persisted to an object store (normally an RDBMS).

* [Marshmallow](https://bitbucket.org/soundvibe/marshmallow/wiki/Home). `[Delphi]` Object-Relational Mapping for Delphi XE2-7 (Win32) inspired by .NET micro ORM's (mostly by PetaPoco) and Java Hibernate. Developed  by Linas Naginionis. Supports SQLite, Sybase ASA, SQL Server, Firebird, Oracle, MySQL, PostgreSQL, MongoDB. Uses [Spring](http://code.google.com/p/delphi-spring-framework/) Framework. In active development.

* [DelphiCassandra](https://github.com/grijjy/DelphiCassandra). `[Delphi]` Delphi driver classes to communicate with Cassandra database.

* [DelphiCouchbase](https://github.com/grijjy/DelphiCouchbase). `[Delphi]` Delphi driver classes to communicate with Couchbase database.

* [DelphiMongoDB](https://github.com/grijjy/DelphiMongoDB). `[Delphi]` Delphi driver classes to communicate with MongoDB database.

* [QuickORM](https://github.com/exilon/QuickORM). `[Delphi]` `[FPC]` QuickORM is a simple RestServer and Restclient based on mORMot framework. Provides a fast implementation of client-server applications in few minutes.


## Scripting ##
*Using script engine in your applications*

* [Pascal Script](https://github.com/remobjects/pascalscript). `[Delphi]` `[FPC]` Free scripting engine that allows you to use most of the Object Pascal language within your Delphi or Free Pascal projects at runtime. Written completely in Delphi, it is composed of a set of units that can be compiled into your executable, eliminating the need to distribute any external files. Pascal Script started out as a need for a good working script, when there were none available at the time.

* [DWScript](https://bitbucket.org/egrange/dwscript). `[Delphi]` Object-oriented scripting engine for Delphi based on the Delphi language, with extensions borrowed from other Pascal languages (FreePascal, Prism, etc.). It introduces a few Pascal language extensions of its own as well.

* [Delphi-Javascript](https://code.google.com/p/delphi-javascript). `[Delphi]` Javascript engine for delphi based on Mozilla's Spidermonkey.
// *Spidermonkey DLL required*

* [Blaise](http://sourceforge.net/projects/blaise). `[Delphi]` Open-source object-oriented scripting language. Language features: Object-oriented; Unicode support; Optional typing, ie dynamic or static typing; Richly typed; Higher-level mathematics support, for example Complex numbers, Rational numbers and Matrices; Virtual Machine architecture; Co-routines; Familiar language syntax, influenced by Object Pascal, Python and Ada.

* [SpiderMonkey](https://github.com/synopse/mORMot/blob/master/SynSM.pas). `[Delphi]` `[FPC]` Binding for Mozilla JavaScript engine, including JIT and multi-threading, with easy objects access via Delphi variants.
// *Spidermonkey DLL required*

* [BESEN](https://github.com/BeRo1985/besen). `[Delphi]` `[FPC]` Complete ECMAScript Fifth Edition Implementation in Object Pascal, which is compilable with Delphi >=7 and Free Pascal >= 2.5.1 (maybe also 2.4.1).

* [Python for Delphi (P4D)](https://github.com/pyscripter/python4delphi). `[Delphi]` `[FPC]` Set of free components that wrap up the Python dll into Delphi and Lazarus (FPC). They let you easily execute Python scripts, create new Python modules and new Python types. You can create Python extensions as dlls and much more

* [CrystalLUA](https://github.com/d-mozulyov/CrystalLUA). `[Delphi]` Lua binding (Delphi6-2007).
// *LUA DLL required*

* [lua4delphi](https://github.com/danieleteti/lua4delphi). `[Delphi]` Delphi binding for Lua 5.1 language.
// *LUA DLL required*

* [chakracore-delphi](https://github.com/tondrej/chakracore-delphi). `[Delphi]` `[FPC]` Delphi and Free Pascal bindings and classes for Microsoft's ChakraCore JavaScript engine library.

* [VerySimple.Lua](https://github.com/Dennis1000/verysimplelua). `[Delphi]` Lua Wrapper for Delphi XE5-D10.1 which automatically creates OOP callback functions for Delphi <-> Lua.
// *LUA DLL required*


## Non-visual Classes/Utils ##


## Compression

* [FWZip](https://github.com/AlexanderBagel/FWZip). `[Delphi]` Classes to work with Zip archives using Store and Deflate methods, supports ZIP64, DataDescryptors, PKWARE encryption, NTFS attributes, Utf8 in filenames.
// *Uses stock ZLIB.obj that gets compiled into binary. Comments and description in Russian.*

* [Abbrevia](http://sourceforge.net/p/tpabbrevia) ([Newest](https://github.com/TurboPack/Abbrevia) and maintained version for recent compiler version only). `[Delphi]` Advanced data compression toolkit for Delphi and C++Builder. Supports PKZIP, Microsoft CAB, tar, gzip, and bzip2 archives, and can create self-extracting executables. On Windows it also provides Delphi wrappers for the LZMA, Bzip2, and WavPack SDKs, and PPMd decompression. Abbrevia also has several visual controls that simplify displaying and manipulating archives, including treeview and listview components. Features: Unicode filenames in all archive formats; Decompress most .zipx and legacy (PKZIP v1) zips; ZIP64 support for archives larger than 2GB; Spanned and split zip archives; Cross-platform (Windows, OS X, and Linux); No DLLs required; Includes COM component; Extensive documentation
// *Second link points to an adapted version for newest compiler versions.*

* [SynLZ SynLZO SynZip PasZip](https://github.com/synopse/mORMot). `[Delphi]` `[FPC]` Several high speed compression units, featuring ZIP/LZ77 Deflate/Inflate, LZO and SynLZ algorithm, in pascal and optimized assembler.

* [Delphi zlib](http://www.base2ti.com/?id=delphi.zlib). `[Delphi]` Wrapper for zlib.obj originally used by Borland. Delphi up to XE3 supported.

* [DIUcl](http://www.yunqa.de/delphi/products/ucl/index). `[Delphi]` DIUcl is a lossless compression library with extremely fast and small (200 bytes only!) ASM decompressor. Compression times and ratios are similar to those of deflate/zip and bzip2. Delphi port of the popular UCL Compression Library, which is also used by the popular and well known UPX Ultimate Packer for eXecutables.


## Encryption

* [Delphi Encryption Compendium (DEC)](https://github.com/winkelsdorf/DelphiEncryptionCompendium). `[Delphi]` Cryptographic library for Delphi & C++ Builder. Symmetric cryptographic functions: Blowfish, Twofish, IDEA, Cast128, Cast256, Mars, RC2, RC4, RC5, RC6, Rijndael / AES, Square, SCOP, Sapphire, 1DES, 2DES, 3DES, 2DDES, 3DDES, 3TDES, 3Way, Gost, Misty, NewDES, Q128, SAFER, Shark, Skipjack, TEA, TEAN; Block cipher modes of operation: CTSx, CBCx, CFB8, CFBx, OFB8, OFBx, CFSx, ECBx; Hashes: MD2, MD4, MD5, RipeMD128, RipeMD160, RipeMD256, RipeMD320, SHA, SHA1, SHA256, SHA384, SHA512, Haval128, Haval160, Haval192, Haval224, Haval256, Tiger, Panama, Whirlpool, Whirlpool1, Square, Snefru128, Snefru256, Sapphire.
// *No updates since 2010, some activity started at 2018 in **development** branch. Anyway features list so huge that it couldn't be ignored*

* [LockBox](http://sourceforge.net/projects/tplockbox) ([Newest](https://github.com/TurboPack/LockBox3) and maintained version for recent compiler version only). `[Delphi]` Delphi library for cryptography. Currently supported Delphi XE6. It provides support for AES, DES, 3DES, Blowfish, Twofish, SHA2 (including the new SHA-512/224 & SHA-512/256), MD5; ECB, CBC, CFB8, CFB, CTR, ECB, OFB, PCBC chaining modes, RSA digital signature and verification. Has interface to OpenSSL library.
// *Check out [this](https://github.com/jarto/lockbox2) page as well for alternative version.*

* [SynCrypto](https://github.com/synopse/mORMot/blob/master/SynCrypto.pas). `[Delphi]` `[FPC]` Fast cryptographic routines (hashing and cypher), implementing AES, XOR, RC4, ADLER32, MD5, SHA1, SHA256 algorithms, optimized for speed (tuned assembler and VIA PADLOCK optional support).

* [TForge](https://bitbucket.org/sergworks/tforge). `[Delphi]` `[FPC]` Open-source crypto library written in Delphi, compatible with Free Pascal Compiler. MD5, SHA1, SHA256, CRC32, Jenkins-One-At-Time, HMAC, PBKDF1, PBKDF2, AES, DES, RC4, RC5, Salsa20.

* [Spring4D](#general-libraries). CRC, DES, MD5, SHA

* [Fundamentals Code Library](#general-libraries). Hashes: XOR, CRC, Adler, MD5, SHA, secure keyed MD5/SHA, etc; Cipher: AES, DES, FUNE, RC2/4, RSA.

* [Alcinoe](#general-libraries). AES, Blowfish, MD5, SHA, secure keyed MD5/SHA.

* [DCPcrypt (fork #1)](https://sourceforge.net/projects/dcpcrypt), [DCPcrypt (fork #2)](https://bitbucket.org/wpostma/dcpcrypt2010). `[Delphi]` Suite of cryptographic components for Delphi.

* [HashLib4Pascal](https://github.com/Xor-el/HashLib4Pascal). `[Delphi]` `[FPC]` Delphi/FreePascal compatible library that provides an easy to use interface for computing hashes and checksums of strings (with a specified encoding), files, streams, byte arrays and untyped data to mention but a few. It also supports Incremental Hashing.

* [CRC/Hash](http://www.wolfgang-ehrhardt.de/crchash_en.html). `[Delphi]` `[FPC]` Pascal / Delphi source and binary files related to CRC, hash, and HMAC calculations. CRC, Adler, BJ lookup, MD5, SHA, Whirlpool, Blake

* [Crypto](http://www.wolfgang-ehrhardt.de/crypt_en.html). `[Delphi]` `[FPC]` Several cipher algorithms: the 128-bit block ciphers AES and Twofish, the 64-bit block cipher Blowfish, and the stream ciphers Salsa20/XSalsa20/ChaCha and Sosemanuk.


## XML/JSON/YAML

* [OmniXML](https://github.com/mremec/omnixml). `[Delphi]` XML parser written in Delphi. Full support for Document Object Model (DOM) Level 1 specification; Supports Extensible Markup Language (XML) 1.0 (Second Edition) specification; Has built-in support for different code pages (main 8-bit code pages, UTF-8, UTF-16); Is compatible with MS XML parser; Fast parsing even large and highly structured documents; Includes helper functions to ease processing XML documents; Simplified XPath support.

* [SAX for Pascal](http://sourceforge.net/projects/saxforpascal). `[Delphi]` `[FPC]` Designed to implement the Simple API for XML Parsing in Pascal/Delphi.
// *Callback-based XML parser, useful for processing huge XML streams. Abandoned since 2004 but is almost the only SAX implementation available.*

* [KDS XML](http://sourceforge.net/projects/kdsxml). `[Delphi]` Class library for streamed parsing, validating and generating XML. It is written in Object Pascal/Delphi and works on Win32 (Delphi) and Linux (Kylix). Parts of it depend on the SAX for Pascal interface specifications.
// *Seems dead.*

* [XML Partner](http://sourceforge.net/projects/tpxmlpartner). `[Delphi]` Helps add the power of XML to Borland Delphi, C++ Builder, and Kylix projects through native, easy to use VCL and CLX components. These powerful components simplify the process of creating, modifying, and parsing XML data documents.
// *Seems dead, check out [this](http://www.songbeamer.com/delphi) page for probably newer version.*

* [Open XML](http://www.philo.de/xml/downloads.shtml). `[Delphi]` Provides a wide range of methods, components and foundation classes. It can be used for Win32/Kylix as well as for .NET development.

* [SuperObject](https://github.com/hgourvest/superobject). `[Delphi]` `[FPC]` Parser/writer for JSON data format. This toolkit is designed to work with Delphi and FreePascal (win32, win64, linux32, linux64, MacOSX Intel). Supports reading/writing XML as well.

* [Libxml2 for pascal](https://sourceforge.net/projects/libxml2-pas). `[Delphi]` `[FPC]` Pascal units accessing the popular XML API from Daniel Veillard. This should be usable at least from Kylix and Delphi, but hopefully also from other Pascal compilers (like freepascal).

* [NativeXml](https://code.google.com/p/simdesign). `[Delphi]` This component contains a small-footprint Object Pascal (Delphi) XML implementation that allows to read and write XML documents. You basically only need one unit and you can simply add it to the "uses" clause. You can use this software to read XML documents from files, streams or strings. The load routine generates events that can be used to display load progress on the fly. You can also use it to create and save XML documents.

* [Delphi-XmlLite](https://github.com/the-Arioch/Delphi-XmlLite). `[Delphi]` Header translation for Microsoft XmlLite. XmlLite is a native C++ implementation of .NET XmlReader+Writer for stream-based, forward-only XML parsing and creation. XmlLite.dll is required. It is included with all new versions of Windows, and service packs for old versions. XmlReader's pull-based interface is cleaner to use than SAX's event-based interface.
// *Seems abandoned and reported to be somewhat buggy.*

* [Chimera](https://bitbucket.org/sivv/chimera). `[Delphi]` Open Source (MIT License) library for Delphi XE2 which provides a fast and cross platform JSON generator/parser (serializer/deserializer) under a license that doesn't suck.

* [SynCommons](https://github.com/synopse/mORMot/blob/master/SynCommons.pas). `[Delphi]` `[FPC]` High speed JSON library, using `TDocVariant` custom variant type for storage and access.

* [SynCrossPlatformJSON](https://github.com/synopse/mORMot/blob/master/CrossPlatform/SynCrossPlatformJSON.pas). `[Delphi]` `[FPC]` High speed cross-platform JSON library, using `TJSONVariant` custom variant type for storage and access.

* [Json Data Objects](https://github.com/ahausladen/JsonDataObjects). `[Delphi]` This Delphi unit contains a JSON parser that supports Delphi 2009-10Seattle and the platforms Win32, Win64 and ARM Android (MacOS and iOS may work).

* [TinyJSON](http://sourceforge.net/projects/tiny-json) ([mirror at GH](https://github.com/tmcdos/tiny-json)). `[Delphi]` This is a small and clean library for associative arrays with Boolean / Integer / Float / WideString values. Allows import (export) from (to) JSON text. Extensive error-checking. Uses FunHash (by Sokolov Yura), HatTrie (by Daniel C. Jones), FastInt64 and FastMove (by FastCode project).

* [JSON delphi library](http://sourceforge.net/projects/lkjson). `[Delphi]` This is a delphi library implementing JSON data format and objects structure. Lightweight and fast.

* [dwsJSON](https://bitbucket.org/egrange/dwscript/src/b9f99d4b8187defac3f3713e2ae0f7b83b63d516/Source/dwsJSON.pas?at=master). `[Delphi]` `[FPC]` dwsJSON is a unit that supports JSON parsing/creating, it's part of DWScript but relatively "standalone", in that if you add it in your Delphi (or FPC) projects, it won't pull the whole of DWScript library, and thus can be used anywhere you need.

* [Fundamentals Code Library](#general-libraries). JSON, XML.

* [Alcinoe](#general-libraries). XML/JSON Parser.

* [delphi-yaml](https://bitbucket.org/OCTAGRAM/delphi-yaml). `[Delphi]` Delphi 7 compatible bindings for libyaml, YAML parser and emitter library implemented in C. Four layers of bindings are proposed.

* [GrijjyFoundation](#general-libraries). JSON/BSON.

* [VerySimpleXML](https://github.com/Dennis1000/verysimplexml). `[Delphi]` Lightweight, one-unit, cross-platform XML reader/writer for Delphi 2010 - 10.2.2 Tokyo

* [XSuperObject](https://github.com/onryldz/x-superobject). `[Delphi]` Delphi Cross Platform Rapid JSON

* [Internet Tools](https://github.com/benibela/internettools). `[Delphi]` `[FPC]` Package provides standard conformant XPath 2.0, XQuery 1.0 and XPath/XQuery 3.0 interpreters with extensions for - among others - JSONiq, pattern matching, CSS and HTML; as well as functions to perform HTTP/S requests on Windows/Linux/MacOSX/Android, an XSLT-inspired webscraping language, and an auto update class.

* [Delphi-JsonToDelphiClass](https://github.com/PKGeorgiev/Delphi-JsonToDelphiClass). `[Delphi]` Generates Delphi Classes based on JSON string (Json To Delphi Class Generator / JSON Data Binding Tool). Also includes unit for interaction with GitHub.

* [XML Parser](http://www.destructor.de/xmlparser). `[Delphi]` `[FPC]` Lightweight ObjectPascal XML parser for Delphi and FreePascal. By leaving out syntax checking, well-formedness checks and/or validation, and by choosing a progressive scanning technique, this parser is very fast.


## Language
*Tools for Pascal and other languages*

* [Next Delphi Yacc & Lex](https://github.com/RomanYankovsky/ndyacclex). `[Delphi]` Parser generator toolset for Delphi.

* [Abstract Syntax Tree Builder](https://github.com/RomanYankovsky/DelphiAST). `[Delphi]` With DelphiAST you can take real Delphi code and get an abstract syntax tree. One unit at time and without a symbol table though.

* [Castalia-Delphi-Parser](https://github.com/jacobthurman/Castalia-Delphi-Parser). `[Delphi]` These files make up a hand-written high speed parser for the Object Pascal dialect known as "Delphi". The original work was done by Martin Waldenburg in the late 1990s, and the project was abandoned sometime before 2003, when I found the code and began working on it.  I have kept it updated as necessary to work with my project, called "Castalia".

* [CrossPascal](https://github.com/BeRo1985/crosspascal). `[Delphi]` Aims to be a Delphi 7 compatible cross-platform source-to-source compiler (together with the new unicode string types from XE3 but where ansistring is still the default string type for to be still Delphi 7 compatible) which generates intermediate C code.
// *Quite interesting project though seems abandoned*

* [pas2js](https://svn.freepascal.org/svn/projects/pas2js/trunk), [docs](http://wiki.freepascal.org/pas2js). `[Delphi]` `[FPC]` An open source Pascal to JavaScript transpiler. It parses Object Pascal and emits JavaScript. The JavaScript is currently of level ECMAScript 5 and should run in any browser or in Node.js (target "nodejs"). Basically, Delphi 7 syntax is supported. Used in tools like TMS WebCore and Elevate Web Builder.


## Memory managers
*Libraries that implement dynamic memory allocation*

* [FastMM](https://github.com/pleriche/FastMM4). `[Delphi]` Lightning fast replacement memory manager for Embarcadero Delphi Win32 and Win64 applications that is not prone to memory fragmentation, and supports shared memory without the use of external .DLL files.
// *Used as stock memory manager since 2006 but in simplified version. Provides powerful memory leak/corruption detection instruments.*

* [ScaleMM](https://github.com/andremussche/scalemm). `[Delphi]` Fast scaling memory manager for Delphi

* [BrainMM](https://github.com/d-mozulyov/BrainMM). `[Delphi]` Extremely fast memory manager for Delphi.
// *Advanced memory allocation functions for faster aligned operations.*

* [FastMM4-AVX](https://github.com/maximmasiutin/FastMM4-AVX). `[Delphi]` `[FPC]` FastMM4 fork with AVX support and multi-threaded enhancements (faster locking)


## System
*Low-level helper stuff: memory, threading etc*

* [OmniThreadLibrary](https://github.com/gabr42/OmniThreadLibrary). `[Delphi]` Simple to use threading library for Delphi.
// *Easy integration of async processes in your app*

* [Delphi Detours Library](https://github.com/mahdisafsafi/delphi-detours-library). `[Delphi]` `[FPC]` Library allowing you to hook Delphi functions and object methods and Windows API functions. It provides an easy way to insert and remove hook.
// *Supports x64, calling original functions, multi hooks, COM/Interfaces/win32api, object methods hooking, fully thread-safe, Delphi 7/2005-2010/XE-XE7 & Lazarus/FPC, 64 bit address is supported.*

* [MemoryModule](https://github.com/Fr0sT-Brutal/Delphi_MemoryModule). `[Delphi]` `[FPC]` With the MemoryModule engine you can store all required DLLs inside your binary to keep it standalone. Additional hook units allow transparent using of MM engine thus allowing switching MM/WinAPI loading as well as enabling 3rd party dynamic-load DLL interfaces that are unaware of MM (tested with Interbase Express components and Firebird client library). MemoryModule is a Pascal port of Joachim Bauch's C MemoryModule.

* [DirectoryWatcher](https://github.com/Wosi/DirectoryWatcher). `[Delphi]` Watch changes in directories on different platforms (Windows/Linux/Mac OS).


## Template
*Engines to generate text output based on templates*

* [SynMustache](https://github.com/synopse/dmustache). `[Delphi]` `[FPC]` Delphi implementation of the Mustache template language, supporting Delphi 6 up to Delphi 10 Seattle (and FPC/Lazarus compilation).

* [Delphi Template Engine](http://sourceforge.net/projects/delphi-templeng). `[Delphi]` Template engine designed to be used as a library in Delphi (mainly Delphi 7) applications, allowing developers to use templating on their software with no worry about implementing it.

* [MustaPAS](https://github.com/leledumbo/mustapas). `[Delphi]` `[FPC]` Mustache implementation in simple procedural Pascal.


## Logging

* [Log4d](https://github.com/landrix/Log4d-for-Delphi). `[Delphi]` `[FPC]` Implementation of logging system for Delphi, based on Log4j.

* [TraceTool](http://tracetool.sourceforge.net/). `[Delphi]` C#, C++, Delphi, ActiveX and Java trace framework and a trace viewer.

* [LoggerPro](https://github.com/danieleteti/loggerpro). `[Delphi]` A modern and pluggable logging framework for Delphi.

* [SynLog](https://github.com/synopse/mORMot/blob/master/SynLog.pas). `[Delphi]` `[FPC]` Logging functions used by Synopse projects.

* [slf4p](https://github.com/michaelJustin/slf4p). `[Delphi]` `[FPC]` A simple logging facade with support for LazLogger, Log4D, and other logging frameworks.

* [GrijjyCloudLogger](https://github.com/grijjy/GrijjyCloudLogger). `[Delphi]` Remote logging tool that allows you to send log messages over the Intranet or Internet from Windows, Linux, iOS, Android and macOS devices to a viewer running on Windows. Besides sending messages along with any data, it has numerous features including custom live watches, remote live views of objects, tracking live memory usage, object allocations, growth leaks and more.

* [QuickLogger](https://github.com/exilon/QuickLogger). `[Delphi]` `[FPC]` Delphi/freepascal/.NET (Windows/Linux) library for logging on files, console, memory, email, rest, telegram, slack, eventlog, redis, ide debug messages and throw events..


## Math

* [Big Decimal Math](https://github.com/benibela/bigdecimalmath). `[Delphi]` This unit provides a arbitrary precision BCD float number type. It can be used like any numeric type and supports: At least numbers between 10-2147483647 to 102147483647 with 2147483647 decimal digit precision; All standard arithmetic and comparison operators; Rounding functions (floor, ceil, to-even, ..); Some more advanced operations, e.g. power and sqrt.

* [TIntX](https://github.com/Xor-el/IntXLib4Pascal). `[Delphi]` `[FPC]` Pascal port of IntX arbitrary precision Integer library with fast, about O(N * log N) multiplication/division algorithms implementation. It provides all the basic arithmetic operations on Integers, comparing, bitwise shifting etc. It also allows parsing numbers in different bases and converting them to string, also in any base. The advantage of this library is its fast multiplication, division and from base/to base conversion algorithms. all the fast versions of the algorithms are based on fast multiplication of big Integers using Fast Hartley Transform which runs for O(N * log N * log log N) time instead of classic O(N^2).

* [DelphiBigNumberXLib](https://github.com/Xor-el/DelphiBigNumberXLib). `[Delphi]` Arbitrary Precision Library for Delphi with Support for Integer and Floating Point Computations.

* [FastMath](https://github.com/neslib/FastMath). `[Delphi]` Delphi math library that is optimized for fast performance (sometimes at the cost of not performing error checking or losing a little accuracy). It uses hand-optimized assembly code to achieve much better performance then the equivalent functions provided by the Delphi RTL.
// *Floating-point, vector, matrix operations.*

* [MPArith](http://www.wolfgang-ehrhardt.de/misc_en.html#mparith). `[Delphi]` Multi precision integer, rational, real, and complex arithmetic.

* [AMath](http://www.wolfgang-ehrhardt.de/misc_en.html#amath) and [DAMath](http://www.wolfgang-ehrhardt.de/misc_en.html#damath). `[Delphi]` Accurate mathematical methods without using multi precision arithmetic and double precision accurate mathematical methods without using multi precision arithmetic or assembler respectively.

* [ALGLIB](http://www.alglib.net/download.php). `[Delphi]` `[FPC]` Cross-platform numerical analysis and data processing library. It supports several operating systems (Windows and POSIX, including Linux). ALGLIB features include: Data analysis (classification/regression, statistics); Optimization and nonlinear solvers; Interpolation and linear/nonlinear least-squares fitting; Linear algebra (direct algorithms, EVD/SVD), direct and iterative linear solvers; Fast Fourier Transform and many other algorithms.
// Free edition is Delphi wrapper around generic C core licensed for Personal and Academic Use.


## Other non-visual

* [TRegExpr](https://github.com/ashumkin/RegExpr). `[Delphi]` Easy to use and powerful tool for sophisticated search and substitutioning and for template-based text input check.
// *Abandoned since 2004 but unlike stock RAD Studio implementation doesn't use PCRE obj files that add dependency on msvcrt.dll*

* [FLRE](https://github.com/BeRo1985/flre). `[Delphi]` `[FPC]` FLRE ( F ast L ight R egular E xpressions) is a fast, safe and efficient regular expression library, which is implemented in Object Pascal (Delphi and Free Pascal) but which is even usable from other languages like C/C++ and so on.

* [OnGuard](http://sourceforge.net/projects/tponguard) ([Alternate](https://github.com/TurboPack/OnGuard-VCL) and maintained version for recent compiler version only). `[Delphi]` Library to create demo versions of your Borland Delphi & C++Builder applications. Create demo versions that are time-limited, feature-limited, limited to a certain number of uses, or limited to a certain # of concurrent network users.
// *Second link points to an adapted version for newest compiler versions.*

* [StringSimilarity](https://github.com/chaosben/theunknownones). `[Delphi]` Package designed for some fuzzy and phonetic string comparison algorithms. So far implemented are the following algorithms: DamerauLevenshtein, Koelner Phonetik, SoundEx, Metaphone, DoubleMetaphone, NGram, Dice, JaroWinkler, NeedlemanWunch, SmithWatermanGotoh, MongeElkan.

* [PubSub Chimera](https://code.google.com/p/pubsubchimera). `[Delphi]` Open Source (MIT License) library for Delphi which provides a fast and cross platform PubSub and Message Queue implementation under a license that doesn't suck.

* [DuckDuckDelphi](https://code.google.com/p/duckduckdelphi). `[Delphi]` Adds simple duck typing to Delphi Objects and provides an RTTI helper class to simplify many common RTTI tasks.

* [byterage](https://github.com/quartexNOR/byterage). `[Delphi]` Object pascal class library designed to remove some of the limitations of streams. The framework is very simple to use, with only one common ancestor class (TBRBuffer) which defines a set of storage agnostic mechanisms for allocating, scaling, inserting, deleting and otherwise manipulating a segment of raw binary data.

* [stateless](https://github.com/SirRufo/stateless). `[Delphi]` Simple library for creating state machines in Delphi code.

* [GenericTree](https://github.com/davidberneda/GenericTree). `[Delphi]` Delphi implementation of a generic Tree structure.

* [Delphi Event Bus](https://github.com/spinettaro/delphi-event-bus) (for short DEB). `[Delphi]` Event Bus framework for Delphi.

* [DelphiEventBus](https://github.com/BitecSPB/DelphiEventBus). `[Delphi]` Yet another Event Bus framework for Delphi, with annotations and rich event filtering.

* [DHibernate](https://github.com/thecocce/delphi-hibernate). `[Delphi]` Object Persistent Framework based on Hibernate and NHibernate for Delphi.
// *Abandoned since 2012*

* [UniConv](https://github.com/d-mozulyov/UniConv). `[Delphi]` `[FPC]` Universal text conversion library is a universal quick and compact library intended for conversion, comparison and change of the register of text in concordance with the latest standards of the Unicode Consortium. The librarys function greatly resembles ICU, libiconv and Windows.kernel which are de facto standard for popular operating systems.

* [CachedBuffers](https://github.com/d-mozulyov/CachedBuffers). `[Delphi]` `[FPC]` The library is irreplaceable for the tasks of sequential data reading or writing, especially if the requirements for the performance are increased and there are much data.

* [CachedTexts](https://github.com/d-mozulyov/CachedTexts). `[Delphi]` `[FPC]` Powerful and compact cross-platform library aimed at parsing and generating of text data with the maximum possible performance. Depends on the two other libraries: CachedBuffers and UniConv.

* [ZEXMLSS](https://github.com/Avemey/zexmlss). `[Delphi]` `[FPC]` Lazarus/Delphi component for read/write ods, excel xml, xlsx.

* [PasMP](https://github.com/BeRo1985/pasmp). `[Delphi]` `[FPC]` Parallel-processing/multi-processing library for Object Pascal.

* [TCommandLineReader](https://github.com/benibela/rcmdline). `[Delphi]` `[FPC]` This unit provides an advanced, platform-independent command line parser for Lazarus and Delphi. It checks for allowed options, automatically prints a help with a list of all of them, and - contrary to the parser in the rtl - behaves the same on Windows and Linux.

* [ICU4PAS](http://www.crossgl.com/icu4pas/index.html). `[Delphi]` `[FPC]` Object Pascal, cross platform, Direct Class Wrapper over the mature and widely used set of C/C++ ICU libraries providing Unicode support, software internationalization (i18n) and globalization (g11n), giving applications the same results on all platforms. You can use it on Windows with Delphi and FreePascal and on Linux with Kylix and FreePascal.
// *Hadn't been updated since 2007 but ICU interface probably remains the same...*

* [CommandLineParser](https://github.com/VSoftTechnologies/VSoft.CommandLineParser). `[Delphi]` Simple Command Line Options Parser - spawned from the DUnitX Project.

* [GpCommandLineParser](https://github.com/gabr42/GpDelphiUnits/blob/master/src/GpCommandLineParser.pas). `[Delphi]` Attribute based command line parser.

* [GpDelphiUnits](https://github.com/gabr42/GpDelphiUnits). `[Delphi]` Collection of useful Delphi units. Various TList descendants, TList-compatible, and TList-similar classes. Dynamically allocated, O(1) enqueue and dequeue, threadsafe, microlocking queue. Interface to 64-bit file functions with some added functionality. String hash, table and dictionary. Collection of Win32/Win64 wrappers and helper functions. Time Zone Routines. Embedded file system.

* [BaseNcodingPascal](https://github.com/Xor-el/BaseNcodingPascal). `[Delphi]` `[FPC]` Library for encoding of binary data into strings using base32, base85, base128 and other algorithms for FPC and Delphi.

* [ByteSizeLibPascal](https://github.com/Xor-el/ByteSizeLibPascal). `[Delphi]` `[FPC]` TByteSize is a utility "record" that makes byte size representation in code easier by removing ambiguity of the value being represented.

* [EmailValidationPascal](https://github.com/Xor-el/EmailValidationPascal). `[Delphi]` `[FPC]` Simple Class for Validating Email Address Syntax in Pascal/Delphi.

* [PRNG](http://www.wolfgang-ehrhardt.de/misc_en.html#prng). `[Delphi]` Seven fast pseudo random number generators with period lengths much greater than Pascal's random function. All are implemented with context records, therefore several independent generators can be used simultaneously, they are not cryptographically secure. In addition there are three cryptographic generators.

* [CSV File and String Reader](https://www.codeproject.com/Tips/783493/Delphi-CSV-File-and-String-Reader-Classes). `[Delphi]` TnvvCSVFileReader and TnvvCSVStringReader are light weighted and fast classes that resemble unidirectional data set.

* [HTMLBuilder](https://github.com/guitorres/htmlbuilder). `[Delphi]` Build simplified html with pascal code.

* [Marvin.IA](https://github.com/marvinbraga/Marvin.IA). `[Delphi]` Machine learning collection of object-oriented Pascal primitives (only interfaces and classes).

* [FreePascal Generics.Collections](https://github.com/maciej-izak/generics.collections). `[FPC]` FreePascal Generics.Collections library (TList, TDictionary, THashMap and more...)

* [FuzzyWuzzy.pas](https://github.com/DavidMoraisFerreira/FuzzyWuzzy.pas). `[FPC]` Port of the well-known Python fuzzy string matching package that uses the Levenshtein distance to compute differences between string sequences.


## OS ##
*Tools that help dealing with OS-specific internals*

* [GLibWMI](http://sourceforge.net/projects/glibwmi). `[Delphi]` Component Library for Delphi that encapsulate the classes for access to WMI of Windows in a set of VCL. BiosInfo, PrinterInfo, DiskInfo,... Allow access WMI Classes: WIN32_Bios, WIN32_Printers, WIN32_DiskDrive.

* [MemoryMap](https://github.com/AlexanderBagel/ProcessMemoryMap/tree/master/MemoryMap). `[Delphi]` Set of classes to get all the info about a memory of a running process.

* [The new Drag and Drop Component Suite](https://github.com/DelphiPraxis/The-Drag-and-Drop-Component-Suite-for-Delphi). `[Delphi]` VCL component library that enables your Delphi and C++Builder applications to support COM based drag and drop and integrate with the Windows clipboard.

* [TSMBIOS](https://github.com/RRUZ/tsmbios). `[Delphi]` `[FPC]` Allows access the System Management BIOS (SMBIOS) using the Object Pascal language (Delphi or Free Pascal). The SMBIOS (System Management BIOS) is a standard developed by the DMTF. The information stored in the SMBIOS includes devices manufacturer, model name, serial number, BIOS version, asset tag, processors, ports and device memory installed.

* [VersionInfo for Delphi](http://melander.dk/articles/versioninfo). `[Delphi]` The library makes it very easy to read values from the Version Info resource of Windows executables and DLLs. Optionally extends the TApplication class with a version info property via class helper.

* [Magenta Systems WMI and SMART Component](http://www.magsys.co.uk/delphi/magwmi.asp). `[Delphi]` Contains WMI, SMART and SCSI PassThrough functions, of particular use for getting hard disk information and configuring network adaptors, but also for many other general uses. MagWMI provides general view access to any WMI information using SQL like commands, and also a number of dedicated function relating to TCP/IP configuration, such as setting the adaptor IP addresses, the computer name, domain/workgroup, BIOS and disk drive information.

* [madKernel](http://help.madshi.net/madKernel.htm). `[Delphi]` The package is about Kernel Objects for the biggest part. The most important object types are wrapped up in  interfaces, utilizing all the specific kernel32 APIs. Has interface wrappers for: Events, Mutexes, Threads, Processes, Windows, Modules, Tray Icons, shared memory buffers.
// *Free with source for non-commercial usage (only) with some [conditions](http://help.madshi.net/License.htm). Available to download as part of `madCollection` installer. Pretty well documented. Requires `madBasic` package.*

* [madSecurity](http://help.madshi.net/madSecurity.htm). `[Delphi]` The package makes it easily possible to handle Shares and other Security Objects like file security or registry security. To be able to do so, this package also features functionality around Accounts and ACEs and ACLs.
// *Free with source for non-commercial usage (only) with some [conditions](http://help.madshi.net/License.htm). Available to download as part of `madCollection` installer. Pretty well documented. Requires `madBasic` package.*

* [madShell](http://help.madshi.net/madShell.htm). `[Delphi]` The package implements often needed shell functionality, beginning with Special Folders like the "Windows" folder or the "Program Files" folder, continuing with Shell ID Lists, Shell Objects and Shell Events. Then you'll find functionality around ShortCuts/ShellLinks and finally everything about Display Modes.
// *Free with source for non-commercial usage (only) with some [conditions](http://help.madshi.net/License.htm). Available to download as part of `madCollection` installer. Pretty well documented. Requires `madBasic` package.*

* [WindowsAutorun](https://github.com/ms301/WindowsAutorun). `[Delphi]` Helps you manage autoload in Windows OS.


## Report generating ##

* [Report Manager](http://reportman.sourceforge.net). `[Delphi]` Report manager is a reporting application (Report Manager Designer) and a set of libraries and utilities to preview, export or print reports. Include native .Net and Delphi/C++Builder libraries, ActiveX component and also standard dynamic link library for use in any language like GNU C.

* [FortesReport](https://github.com/fortesinformatica/fortesreport-ce). `[Delphi]` The FortesReport is a powerful report generator available as a package of components for Delphi.

* [mORMotReport](https://github.com/synopse/mORMot/blob/master/SQLite3/mORMotReport.pas) ([docs](http://synopse.info/files/html/api-1.18/mORMotReport.html)). `[Delphi]` Fast and efficient code-based reporting component, with preview form and PDF export.


## Unit Testing ##

* [DUnitX](https://github.com/VSoftTechnologies/DUnitX). `[Delphi]` New test framework, taking ideas from DUnit, NUnit and other test frameworks. It is designed to work with Delphi 2010 or later, it makes use of language/RTL features that are not available in older versions of Delphi.

* [DUnit](http://dunit.sourceforge.net). Unit Testing Framework, that has been the standard testing framework for years, the Delphi IDE now ships with this library.
// *Included since XE, deprecated since XE8 in favor of DUnitX; seems abandoned.*

* [DUnit2](http://dunit2.sourceforge.net). `[Delphi]` Fork of the DUnit Project that adds several new features.
// *Seems abandoned, lacks some features from last DUnit version.*

* [DelphiSpec](https://github.com/RomanYankovsky/DelphiSpec). `[Delphi]` Library for running automated tests written in plain language. Because they're written in plain language, they can be read by anyone on your team. Because they can be read by anyone, you can use them to help improve communication, collaboration and trust on your team.

* [Delphi-Mocks](https://github.com/VSoftTechnologies/Delphi-Mocks). `[Delphi]` Simple mocking framework for Delphi XE2 or later. Allow you to mock both classes and interfaces for testing.

* [DUnit-XML](https://github.com/VSoftTechnologies/DUnit-XML). `[Delphi]` Test runner that allows DUnit Tests to output NUnit compatible XML.

* [Smoketest](https://github.com/deltics/delphi.libs/tree/master/smoketest). `[Delphi]` Framework for writing tests and performance benchmarks using the Delphi language for Microsoft Windows. It has been tested on all versions of Delphi from 7 thru to 2010.

* [SynTests](https://github.com/synopse/mORMot/blob/master/SynTests.pas). `[Delphi]` `[FPC]` Unit test functions including mocks and stubs.

* [OpenCTF](http://openctf.sourceforge.net). Test framework add-on for Embarcadero Delphi which performs automatic checks of all components in Forms (or DataModules). It provides an easy way to build automatic quality checks for large projects where many components have to pass repeated tests. OpenCTF is based on the DUnit open source test framework and extends it by specialized test classes and helper functions.

* [DelphiUIAutomation](https://github.com/jhc-systems/DelphiUIAutomation). `[Delphi]` Delphi classes that wrap the MS UIAutomation library. DelphiUIAutomation is a framework for automating rich client applications based on Win32 (and specifically tested with Delphi XE5). It is written in Delphi XE5 and it requires no use of scripting languages. It provides a consistent object-oriented API, hiding the complexity of Microsoft's UIAutomation library and windows messages.


## Debugging / error handling ##

* [Delphi LeakCheck](https://bitbucket.org/shadow_cs/delphi-leakcheck). `[Delphi]` Free code library to check the memory leaks in the DUnit and DUnit2 tests. Supports Delphi XE-XE7.

* [FastMM](#memory-managers). Provides powerful memory leak/corruption detection instruments.

* [JclDebug (part of Project JEDI)](https://github.com/project-jedi/jcl/blob/master/jcl/source/windows/JclDebug.pas). `[Delphi]` `[FPC]` Tracing, MAP file parser, exception report generation, exception stack traces.


## Utilities ##
*Free non-opensource products allowed here.*


## RAD Studio IDE plugins/wizards

* [Delphi IDE theme editor / Delphi IDE Colorizer](https://github.com/rruz/delphi-ide-theme-editor). Tool to change the IDE color highlighting of several Object Pascal IDE's like Delphi (RAD Studio), Appmethod, Lazarus  and Smart Mobile Studio. DITE supports Delphi 5-7, 2005-2010, XE-XE8, Appmethod 1.13-1.14, Lazarus v1.0.1.3 and Smart Mobile Studio IDE v1.1.2.17. The Delphi IDE Colorizer (DIC) is a plugin which allows to customize the look and feel of the workspace of the RAD Studio IDE and Appmethod.

* [DDevExtensions](http://andy.jgknet.de/blog/ide-tools/ddevextensions). Extends the Delphi/C++Builder IDE by adding some new productivity features
// *Many useful IDE tweaks, must have.*

* [VCL Fix Pack](http://andy.jgknet.de/blog/bugfix-units/vclfixpack-10). Delphi unit that fixes VCL and RTL bugs at runtime by patching the original functions. If you want all IDE Fix Pack fixes in your application this unit is what you are looking for. Adding the unit to your project (Delphi and C++Builder) automatically installs the patches that are available for your Delphi/C++Builder version.
// *Actual for Delphi/C++ 6..2009*

* [IDE Fix Pack](http://andy.jgknet.de/blog/ide-tools/ide-fix-pack). Collection of unofficial bug fixes and performance optimizations for the RAD Studio IDE, Win32/Win64 compiler and Win32 debugger. IDE Fix Pack is an IDE plugin for RAD Studio 2009-XE6 that fixes IDE bugs at runtime. All changes are done in memory. No files on disk are modified. None of your projects are modified or benefit from the IDE Fix Pack other than being compiled faster. Only the IDE gets the fixes and optimizations.
// *Supports all RAD Studio versions since 2007. Removes lots of annoying bugs that EMBT haven't fixed for years. Yay!*

* [GExperts](https://sourceforge.net/projects/gexperts). Free set of tools built to increase the productivity of Delphi and C++Builder programmers by adding several features to the IDE. GExperts is developed as Open Source software and we encourage user contributions to the project. Grep search and replace supporting unicode files, DFMs, etc; Automatically rename components, insert text macros, open recent files; Easily backup your projects, with custom additional file lists; Keep nested lists of favorite files for quick access; Track dependencies between units in your project; Quickly jump to any procedure in the current unit; And much, much more...

* [CnWizards](https://github.com/cnpack). Free Plug-in Tool Set for Delphi/C++ Builder/CodeGear RAD Studio to Improve Development Efficiency.

* [Delphi Package Installer (DelphiPI)](https://bitbucket.org/idursun/delphipi). Tool which aids you installing components to your Delphi IDE. DelphiPI automatically resolves dependencies between packages, compiles, installs and adds source paths to your IDE.

* [ResEd](https://github.com/chaosben/theunknownones). Expert for Delphi 2005, 2006, 2007, 2009, 2010 and XE. This expert is designed for editing the resource files (.res; .resx) that are linked to the active project. It will automatically search for all occurrences of {$R xyz.res} lines and will open/create resourcefiles for them. The expert registers itself in the menubar of Delphi under View.

* [Parnassus Bookmarks](https://parnassus.co/delphi-tools/bookmarks). IDE plugin that extends bookmark functionality.

* [DelphiSettingManager](https://github.com/Arvur/DelphiSettingManager). Multiple IDE profiles for Delphi (up to XE6). Allows to install multiple versions of the same component or different component sets for different projects.

* [Delphinus](https://github.com/Memnarch/Delphinus). New Packagemanager which runs on Delphi XE and newer and uses Github as a Backend to Provide the packages.

* [Parnassus Bookmarks](https://parnassus.co/delphi-tools/bookmarks). IDE plugin that extends bookmark functionality.

* [TestInsight](https://bitbucket.org/sglienke/testinsight/wiki/Home). Unit testing IDE Plugin for Delphi. It supports all versions from XE to 10 Seattle. Supports DUnit, DUnit2, DUnitX frameworks.

* [Delphi IDE Explorer](https://github.com/DGH2112/Delphi-IDE-Explorer). Wizard / expert / plugin that allows you to browser the internal fields, methods, properties and events of the IDE.
// *Mainly useful for developers of IDE experts*

* [Multi-RAD Studio IDE Expert Manager](http://www.davidghoyle.co.uk/WordPress/?page_id=1361). Application is for editing the installed experts in all versions of RAD Studio (and older Delphi and C++ Builder) on a machine.

* [OTA Interface Search](https://github.com/DGH2112/OTA-Interface-Search). Application helps to find Open Tools API (OTA) interfaces, methods and properties and understand how to get to those interfaces or methods / properties of the interfaces.

* [AutoSave](https://github.com/DGH2112/Auto-Save). Expert that periodically auto saves all the open modified IDE files.

* [Browse and Doc It](http://www.davidghoyle.co.uk/WordPress/?page_id=872). Plug-in allows you to document and browse your code from within the IDE.

* [Integrated Testing Helper](http://www.davidghoyle.co.uk/WordPress/?page_id=874). Plugin for Delphi and RAD Studio that allows you to run command-line application before and after the compilation of you projects. It also provides the ability to zip you projects files into an archive on each compile/build and manage the application's version information.

* [Project Magician](https://www.uweraabe.de/Blog/2018/05/17/keep-your-project-files-clean-with-project-magician). Wizard for advanced project options manipulation.

* [Selective Debugging](http://www.uweraabe.de/Blog/2015/05/08/selective-debugging/). Wizard that allows to tune for which units their debug version will be used.

* [MMX Code Explorer](https://www.mmx-delphi.de). Feature-rich productivity enhancing plugin. Includes refactoring, class browser, advanced editing, metrict and many more.

* [FormResource](http://chapmanworld.com/2017/03/22/formresource-a-free-delphi-component-for-organizing-product-dependencies). Wizard that helps storing various data as form resources.

* [Delphi Library Helper](https://github.com/littleearth/delphi-library-helper) Tool to assist Delphi developers configuring library folders.

* [Mobile Image Creator](https://github.com/littleearth/mobile-image-creator) Creating Icons and Launcher Images for Delphi Mobile Applications (Firemonkey). This is a fork of Mobile Gfx created by [Thomas Grubb of RiverSoftAVG](http://riversoftavg.com/blogs/index.php/2014/02/03/creating-icons-and-launchers-for-delphi-mobile-applications/).

* [Delphi-Adb-WiFi](https://github.com/ms301/Delphi-Adb-WiFi). Plugin for RAD Studio, which allows launching and debugging on an Android device without connecting to a computer via USB. Works over WiFi.

* [RADSplit](https://github.com/LaKraven/RADSplit). Dockable Split-Screen Editors for RAD Studio (Delphi and C++ Builder)


## Plugins for other IDE's

* [Delphi IDE theme editor / Delphi IDE Colorizer](#rad-studio-ide-pluginswizards). Supports Appmethod, Lazarus and Smart Mobile Studio.


## Documentation

* [SynProject](https://github.com/synopse/SynProject) ([docs](http://synopse.info/fossil/wiki?name=SynProject)). Tool for code source versioning and automated documentation of Delphi projects.

* [PasDoc](https://sourceforge.net/projects/pasdoc). `[Delphi]` `[FPC]` Documentation tool for ObjectPascal (FreePascal and Delphi) source code. Documentation is generated from comments found in source code. Available output formats are HTML, HtmlHelp, LaTeX, latex2rtf, simplexml. More output formats may be added in the future.

* [DIPasDoc](http://www.yunqa.de/delphi/products/pasdoc/index). `[Delphi]` `[FPC]` Generates HTML documentation from comments in Pascal source code files. It outputs browsable help as standard HTML files or customizable MS HTML Help projects.


## Code check/review, debug

* [GpProfiler2017](https://github.com/ase379/gpprofile2017). `[Delphi]` Source code instrumenting profiler for Delphi XE and higher. Other forks support older versions.

* [SamplingProfiler](https://www.delphitools.info/samplingprofiler). `[Delphi]` Performance profiling tool for Delphi 5 to 32bits Delphi XE4. Its purpose is to help locate bottlenecks, even in final, optimized code running at full-speed.

* [Delphi Code Coverage](https://sourceforge.net/projects/delphicodecoverage). `[Delphi]` Simple Code Coverage tool for Delphi that creates code coverage reports based on detailed MAP files.

* [Pascal Analyzer](http://www.peganza.com/products_pal.html) (free Lite version available). `[Delphi]` Pascal Analyzer, or PAL for short, parses Delphi or Borland Pascal source code. It builds large internal tables of identifiers, and collects other information such as calls between subprograms. When the parsing is completed, extensive reports are produced. These reports contain a great deal of important information about the source code. This information will help you understand your source code better, and assist you in producing code of higher quality and reliability.

* [madExcept](http://madshi.net/madExceptShop.htm). `[Delphi]` madExcept was built to help you locate bugs in your software. Whenever there's a crash/exception in your program, madExcept will automatically catch it, analyze it, collect lots of useful information, and give the end user the possibility to send you a full bug report. madExcept is also able to find memory leaks, resource leaks and buffer overruns for you.
// **Free **without source** for non-commercial usage (only) with some [conditions](http://help.madshi.net/License.htm). Available to download as part of `madCollection` installer (you'll need to install `madExcept` item). Pretty well documented.*

* [delphiunitsizes](https://github.com/VilleKrumlinde/delphiunitsizes). `[Delphi]` Tool to display the sizes of each unit in a Delphi executable. Shows the size of each unit that is included in a Delphi exe-file. It also shows an approximate size of each symbol (classes, methods, procedures etc) in a unit.

* [MapFileStats](https://www.delphitools.info/other-tools/mapfilestats). `[Delphi]` Tool that provides simple binary size statistics from .MAP files (any Delphi version up to at least Delphi XE5).

* [Spider](https://github.com/yavfast/dbg-spider). `[Delphi]` Real time profiler for Delphi applications


## Setup

* [Lazy Delphi Builder](https://bitbucket.org/tdelphi/lazy-delphi-builder-downloads). Build tool for Delphi. Recompile projects/packages from sources with all dependencies, without need to mess around with configs. Quickly (re-)install components from sources into IDE, with no need to change your Library Path.
// *Powerful automating tool. Freeware but not open source*

* [Inno Setup](http://www.jrsoftware.org/isinfo.php). Free installer for Windows programs. First introduced in 1997, Inno Setup today rivals and even surpasses many commercial installers in feature set and stability.

* [WinSparkle](https://winsparkle.org) and its [Delphi wrapper](https://github.com/jkour/neSparkleComponent). WinSparkle is an easy-to-use software update library for Windows developers. WinSparkle is a heavily (to the point of being its almost-port) inspired by the Sparkle framework originally by Andy Matuschak that became the de facto standard for software updates on macOS.

* [Silverpoint MultiInstaller](http://www.silverpointdevelopment.com/multiinstaller/index.htm). Multi component package installer for Embarcadero Delphi and C++Builder, it was created to ease the components installation on the IDE.


## Other

* [WMI Delphi Code Creator](https://github.com/RRUZ/wmi-delphi-code-creator). Allows you to generate Object Pascal, Oxygene, C++ and C# code to access the WMI (Windows Management Instrumentation) classes, events and methods. Also includes a set of tools to explorer and Query the content of the WMI.

* [Delphi Preview Handler](https://github.com/RRUZ/delphi-preview-handler). Preview handler for Windows Vista, 7 and 8 which allow you read your object pascal, C++ and Assembly code with Syntax highlighting without open in a editor

* [Delphi Dev. Shell Tools](https://github.com/RRUZ/delphi-dev-shell-tools). Windows shell extension with useful tasks for Object Pascal Developers (Delphi, Free Pascal).

* [Delphi.gitignore](https://github.com/github/gitignore). .gitignore templates for Delphi. There is also one for Lazarus.

* [OmniPascal](http://omnipascal.com). Project that enables Delphi and Free Pascal developers to write and maintain code using the modern editor [Visual Studio Code](https://code.visualstudio.com).

* [Delphi Unit Tests](https://bitbucket.org/NickHodges/delphi-unit-tests). Set of unit tests for Delphi's libraries. Delphi community members are encouraged to fork the repository, add tests, and create a pull request. Embarcadero employees are particularly encouraged to add tests from the internal tests that are run with official Delphi builds.

* [madDisAsm](http://help.madshi.net/madDisAsm.htm). The package features a full x86 disassembler including MMX, 3dNow enhanced, SSE and SSE2 support. The disassembler can examine a single x86 instruction (see ParseCode) or a full function (see ParseFunction) and either return a short analysis or a full text disassembly. Register contents are watched/followed if possible, this improves the analyses for jump/call targets. Case/switch jump tables are automatically detected and handled correctly.
// *Free **without source** for non-commercial usage (only) with some [conditions](http://help.madshi.net/License.htm). Available to download as part of `madCollection` installer (you'll need to install `madExcept` item). Pretty well documented.*

* [Chet - C Header Translator for Delphi](https://github.com/neslib/Chet). Chet is a .h-to-.pas translator powered by libclang for Delphi. Uses the Clang compiler to parse header files, resulting in more accurate translations that require fewer manual adjustments.


## License ##

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0)
