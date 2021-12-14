A Simple Windows Forms Application Project Template in C++/CLR.
Use this template to create a Windows Forms Application using C++. This is similar to the Windows Forms Application Project Template for C#, provided in VS by default.

VS2010 included something like this, but from 2021 it has been removed. So use this template to create GUI apps using C++/CLR with the WinForms Framework provided with .NET.

To install the extension, just download and run the installer.

To create a new project, Launch Vs, Create New Project->Search for CppWinForms

00000.png

Then Create the project.

If you are getting a build tools error like this,

image__1.png

Then, go to your project properties and choose your Visual Studio Version under platform toolset.

image__3.png

Hit OK.

Open, MyForm.h to view the GUI Form with the Designer (found under Header Files). If you are getting this error

image__4.png

Unload the project

image__5.png

Then reload

image__6.png

All problems should be solved now! Contact via Telegram for any suggestions, improvements or issues.
