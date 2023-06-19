================================================================================
    MICROSOFT Basic Class Library: MiniAIDemo Project Overview
===============================================================================

The application wizard has created this MiniAIFaceDemo application for you. This application not only demonstrates the basic usage of the Microsoft foundation classes, but also serves as a starting point for writing your applications。

This file provides an overview of the contents of each file that makes up the MiniAIFaceDemo application.

MiniAIFaceDemo.vcxproj
    This is the main project file for a VC++ project generated using the AppWizard, and contains information about the version of Visual C++ that generated it, as well as information about the platform, configuration, and project features selected using the AppWizard。

MiniAIFaceDemo.vcxproj.filters
    This is a VC++ project filter file generated using the AppWizard. It contains information about the association between project files and filters. In the IDE, through this association, files with similar extensions are shown grouped under a specific node. For example, ".cpp" files are associated with the "Source Files" filter。

MiniAIFaceDemo.h
    This is the main header file of the application.
    It includes other project-specific headers, including Resource.h, and declares the CMiniAIFaceDemoApp application class.

MiniAIFaceDemo.cpp
    This is the main application source file that contains the application class CMiniAIFaceDemoApp.

MiniAIFaceDemo.rc
    This is a list of all Microsoft Windows resources used by the program. It includes icons, bitmaps, and cursors stored in the RES subdirectory. This file can be edited directly in Microsoft Visual C++. Project resources included in 2022。

res\MiniAIFaceDemo.ico
    This is the icon file used as the application icon. This icon is included in the main resource file MiniAIFaceDemo.rc.

res\MiniAIFaceDemo.rc2
    This file contains resources that are not edited in Microsoft Visual C++. You should place all resources that are not editable by the resource editor in this file.


/////////////////////////////////////////////////////////////////////////////

AppWizard creates a dialog class:

MiniAIFaceDemoDlg.h、MiniAIFaceDemoDlg.cpp - 对话框
    These files contain the CMiniAIFaceDemoDlg class. This class defines the behavior of the application's main dialog. The dialog template is contained in MiniAIFaceDemo.rc, which can be edited in Microsoft Visual C++.

/////////////////////////////////////////////////////////////////////////////

Other functions:

ActiveX control
    The application includes support for using ActiveX controls.

/////////////////////////////////////////////////////////////////////////////

Other standard documents:

StdAfx.h, StdAfx.cpp
    These files are used to generate a precompiled header (PCH) file named MiniAIFaceDemo.pch and a precompiled type file named StdAfx.obj。

Resource.h
    This is the standard header file that can be used to define new resource IDs. Microsoft Visual C++ will read and update this file.

MiniAIFaceDemo.manifest
	Windows XP uses an application manifest file to describe application dependencies for specific versions of side-by-side assemblies. The loader uses this information to load the appropriate assembly from the assembly cache and protect it from being accessed by the application. The application manifest may be included for redistribution as an external .manifest file installed in the same folder as the application executable, or it may be included in the executable as a resource。
/////////////////////////////////////////////////////////////////////////////

Other notes:

AppWizard uses "TODO:" to indicate parts of the source code that should be added or customized.

If your application uses MFC in a shared DLL, you will need to redistribute the MFC DLL. If the language used by the application is different from the locale of the operating system, the corresponding localized resource mfc110XXX.DLL also needs to be redistributed.
For more information on the above topics, see the section on redistributing Visual C++ applications in the MSDN documentation.

/////////////////////////////////////////////////////////////////////////////
