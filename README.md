# SQL
SQL code

# Intro

There are a few things you will need to prepare before coming to class. We'll be using sqlite3 as the version of SQL for class. Installation instructions are below. If you encounter any problems, just come to class 15 mins early and your instructor will help you get set up.  

Additionally, we'll be working with a combination of command line statements and sql commands from text files for class.  Please install Sublime Text, which has a free trial version you can download from their website (http://www.sublimetext.com/).

If you're completely unfamiliar with the command line, I suggest you take some time to learn the basics before class.  It's not absolutely necessary, but you'll be able to spend more of your focus on learning SQL if you spend a little time preparing.  Here are a couple tutorials with some basics about the command line.  Watch the first few videos in the tutorial series:

     - For Macs Users - www.youtube.com/watch?v=b93ehHTCZAE
     - For Windows Users - www.youtube.com/watch?v=MBBWVgE0ewk

## Installation

Instructions to run the application without setting up the Qt project code.
1. Download Deployment_executable.zip.
2. Unzip the file.
3. Run CASA_GUI.exe.

Instructions for local project setup:

1. Install Qt creator (community edition)
	- choose the Qt 5.4.2 MSVC2013 OpenGL 64-bit kit
2. Install Basler Pylon v4.2.1 (64-bit)
	- If plugging in the Basler camera via USB does not automatically install
		the required driver, navigate to the
		Basler\pylon 4\bin\drivers\Basler Pylon USB Driver folder and execute
		dpinst.exe
3. Install openvc v2.4.9
4. Download fftw 64-bit or get it from Kiran to avoid having to create the .lib files
	- downloading directly will require the .lib files to be created manually.
5. Make sure all Microsoft Visual C++ redistributables are up-to-date
	- Visual Studio 2013
6. Create a new Qt Widgets Application
7. Add all existing CASA_GUI .pro, .cpp, .h, and .ui files to the project
8. Configure the CASA_GUI.pro file to contain the appropriate paths to the
	Pylon, genicam, opencv, and fftw .lib files as given in the .pro file.
9. Add the following four paths in Qt by going to the Projects window,
	scrolling down to Build Environment, clicking on Details, selecting
	the PATH variable, and clicking
	
## Meta

Name – DUCK HA HWANG

## Contributing

1. Fork it (<https://github.com/personableduck>)
