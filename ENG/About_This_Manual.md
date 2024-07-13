# About This Manual

This manual is the latest release of the Library Overview for Run-Time Library 4.6. The purpose of this manual is to provide overview-level information about the PlayStation® libraries. For related descriptions of the PlayStation run-time library functions and structures, please refer to the Run-Time Library Reference.

# Changes Since Last Release

Since release 4.5 of the Run-Time Library Overview, the following changes have been made:

**Ch. 8: Basic Graphics Library**

A “GPU timeout message” item has been added to the “Cautionary Programming Notes” section.

**Ch. 11: CD/Streaming Library**

Corrections have been made in the “Skipped Sections” item of the “Notes on Using Low Level Function Groups" section.

**Ch. 19: PDA Library**

A note has been added to the “Game selection icon image” item of table 19-3 in the “File Header” section.
Additional information has been added to the “Game selection icons” item in the “File header” section.
A “Notes on icon entry table and icon image position” item has been added to the “Icons” section.

# Related Documentation

This manual should be read in conjunction with the Run-Time Library Reference, which defines all structures and functions available in the Run-Time Library.

# Manual Structure

|Chapter|Description|
|-------|-----------|
|Ch. 1: Overview of the PlayStation OS|Summarizes the PlayStation operating system and the run-time libraries.|
|Ch. 2: Kernel Library|Describes the Kernel library (libapi), which provides an interface between applications and the PlayStation OS.|
|Ch. 3: Standard C Library|Describes the PlayStation’s subset of the standard C library (libc/libc2). This library includes character functions, memory operation functions, character class tests, non-local jumps, and utility functions.|
|Ch. 4: Math Library|Describes the Math Library (libmath), which contains ANSI/IEEE754 compliant math functions, including a software floating point computation package.|
|Ch. 5: Memory Card Library|Describes the Memory Card Library (libcard) for reading/writing to the PlayStation Memory Card and calling the Memory Card BIOS service.|
|Ch. 6: Extended Memory Card Library|Describes the Extended Memory Card Library (libmcard), which provides a high-level interface for accessing the Memory Card.|
|Ch. 7: Data Compression Library|Describes the Data Compression Library (libpress) for compressing (encoding) and expanding (decoding) image and sound data.|
|Ch. 8: Basic Graphics Library|Describes the Basic Graphics Library (libgpu) for drawing primitives such as sprites, polygons, and lines.|
|Ch. 9: Basic Geometry Library|Describes the Basic Geometry Library (libgte), which uses the PlayStation GTE coprocessor to handle high-speed geometry operations.|
|Ch. 10: Extended Graphics Library|Describes the Extended Graphics Library (libgs) which uses the libgpu and the libgte to construct a 3-dimensional graphics system. It deals with more abstract entities such as objects and background |surfaces.|
|Ch. 11: CD-ROM Library|Describes the CD-ROM Library (libcd), for controlling the PlayStation CD-ROM drive. It also contains functions for “streaming” realtime data such as movies, sounds or vertex data stored on high-capacity media.|
|Ch. 12: Extended CD-ROM Library|Describes the Extended CD-ROM Library (libds), which builds a new interface to the libcd kernel. It has the same capabilities as libcd, and places further emphasis on reliable CD-ROM controls such as recovery from system errors.|
|Ch. 13: Controller/Peripherals Library|Describes the Controller/Peripherals Library, which consists of a group of libraries (libetc, libgun, libtap, and libpad) for performing low-level interrupt processing and controller-related functions.|
|Ch. 14: Link Cable Library|Describes the Link Cable Library (libcomb), which provides services for connecting PlayStation units via a “link” cable.|
|Ch. 15: Extended Sound Library|Describes the Extended Sound Library (libsnd), which provides functions for working with sound data on the PlayStation.|
|Ch. 16: Basic Sound Library|Describes the Basic Sound Library (libspu) for controlling the SPU (sound processing unit).|
|Ch. 17: Serial Input/Output Library|Describes the Serial Input/Output Library (libsio) for supporting communications between the PlayStation and a PC.|
|Ch. 18: HMD Library|Describes the HMD Library (libhmd), which provides functions and definitions for handling the HMD format, which integrates modeling, animation, texture, and MIMe data.|
|Ch. 19: PDA Library|Describes the PDA Library (libmcx) used to provide access to PDA functions when it is inserted into a Memory Card slot.|
|Ch. 20: mcgui Module|Describes the module for saving and loading data in game titles, as well as support for the user interface|

# Developer Reference Series

This manual is part of the Developer Reference Series, a series of technical reference volumes covering all aspects of PlayStation development. The complete series is listed below:

|Manual|Description|
|------|-----------|
|PlayStation Hardware|Describes the PlayStation hardware architecture and overviews its subsystems.|
|PlayStation Operating System|Describes the PlayStation operating system and related programming fundamentals.|
|Run-Time Library Overview|Describes the structure and purpose of the run-time libraries provided for PlayStation software development.|
|Run-Time Library Reference|Defines all available PlayStation run-time library functions, macros and structures.|
|Inline Programming Reference|Describes in-line programming using DMPSX, GTE inline macro and GTE register information.|
|SDevTC Development Environment|Describes the SDevTC (formerly "Psy-Q") Development Environment for PlayStation software development.|
|3D Graphics Tools|	Describes how to use the PlayStation 3D Graphics Tools, including the animation and material editors.|
|Sprite Editor|Describes the Sprite Editor tool for creating sprite data and background picture components.|
|Sound Artist Tool|Provides installation and operation instructions for the DTL-H800 Sound Artist Board and explains how to use the Sound Artist Tool software.|
|File Formats|Describes all native PlayStation data formats.|
|Data Conversion Utilities|Describes all available PlayStation data conversion utilities, including both standalone and plug-in programs.|
|CD Emulator|Provides installation and operation instructions for the CD Emulator subsystem and related software.|
|CD-ROM Generator|Describes how to use the CD-ROM Generator software to write CD-R discs.|
|Performance Analyzer User Guide|Provides general instructions for using the Performance Analyzer software.|
|Performance Analyzer Technical Reference|Describes how to measure software performance and interpret the results using the Performance Analyzer.|
|DTL-H2000 Installation and Operation|Provides installation and operation instructions for the DTL-H2000 Development System.|
|DTL-H2500/2700 Installation and Provides installation and operation Operation|instructions for the DTL-H2500/H2700 Development Systems.

# Typographic Conventions

Certain Typographic Conventions are used throughout this manual to clarify the meaning of the text:

|Convention|Meaning|
|---------|--------|
|courier|Indicates literal program code.|
|italic|Indicates names of arguments and structure members (in structure/function definitions only).|

# Developer Support

Sony Computer Entertainment America (SCEA)
SCEA developer support is available to licensees in North America only. You may obtain developer support or additional copies of this documentation by contacting the following addresses:
Order Information	Developer Support
In North America:	In North America:
Attn: Developer Tools Coordinator	E-mail:
Sony Computer Entertainment America DevTech_Support@playstation.sony.com
919 East Hillsdale Blvd., 2nd floor	Web: http://www.scea.sony.com/dev
Foster City, CA 94404	Developer Support Hotline: (650) 655-8181
Tel: (650) 655-8000	(Call Monday through Friday,
8 a.m. to 5 p.m., PST/PDT)

Sony Computer Entertainment Europe (SCEE)
SCEE developer support is available to licensees in Europe only. You may obtain developer support or additional copies of this documentation by contacting the following addresses:
Order Information	Developer Support
In Europe: Attn: Production Coordinator Sony Computer Entertainment Europe Waverley House 7-12 Noel Street London W1V 4HH Tel: +44 (0) 171 447 1600	In Europe: E-mail: dev_support@playstation.co.uk Web: https://www-s.playstation.co.uk Developer Support Hotline: +44 (0) 171 447 1680 (Call Monday through Friday, 9 a.m. to 6 p.m., GMT or BST/BDT)