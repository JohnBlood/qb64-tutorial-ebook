# QB64 Game Programming

## Introduction

This ebook was originally created so that I could read Terry Ritchie's QB64 Game Programming tutorial on my phone. I talked to Terry and he gave me permission to make this book available to everyone. I hope you enjoy. The rest of the book is all Terry's work.

John Paul Wohlscheid

## So you want to be a programmer

**Awesome!** Welcome to my humble little QB64 game programming tutorial, I'm thrilled that you have stopped by.  

The first half of this tutorial was designed for the beginner to programming. It will walk you through the basic concepts and terminology of programming as well as teach the core QB64 command set along the way. The second half of the tutorial gets into the more powerful command set that QB64 offers and how to incorporate them into game programming techniques. The following suggestions will help you get the most from this course.  

### Type, Type, Type

Type the code examples in by hand. Repetitive coding through the keyboard will help you get a "feel" for source code. There are certain constructs that commands require such as parenthesis, commas, quotation marks, and symbols that are going to feel strange typing in at first. Only through the repetition of typing these commands in over and over will you start to develop the muscle memory for coding. When I started coding back in the early 80's the most common way to learn coding was though books and magazine articles that contained source code listings. Typing those listings in over and over again definitely helps.  

### Ask Questions

The [QB64 forum](https://www.qb64.org/forum/) is full of knowledgeable people willing to answer your questions. **Don't hesitate to ask a question because you feel it's dumb. There are no dumb questions**... we all were beginners at one time. Go over to the forum now, create an account, and say "hi". Everyone there is very friendly and helpful.  

### Don't Give Up!

You are not going to write awesome code at first so don't set your expectations too high. It takes time, patience, and persistence to learn how to code fluently. I've been dabbling in programming for 35 years and I still learn better ways of coding all the time.  

### Be Curious

I was a high school computer science teacher for 18 years. During that time I taught Visual Basic, C#, PHP, WScript, VBScript, Python, and QB64\. Regardless of the language being presented I noticed one common trait amongst my students that went on to become successful programmers... **curiosity**. If you find programming and computers in general fascinating and have a sincere desire to learn their inner secrets then you will do fine.  

Again, welcome to my little corner of the web. Happy coding!  

Terry Ritchie

## Task 1: Installing QB64

A quick note about Linux and MacOS. This course will assume that you are using Windows and all of the content contained within has been written with Windows in mind. If you are using Linux or MacOS most of the source code will work as written. Where possible source code changes will be pointed out that need to made in order for it to operate correctly in non-Windows systems.  
  
Before you can get started with this course you'll need to install QB64 and the assets (source code, graphics, and sound files) that are used throughout this course. Click on the QB64 icon below to download the version of QB64 appropriate for your computer system (Linux, MacOS, or PC).  
  
Windows Users: Install QB64 onto your desktop by dragging the "qb64" folder from the ZIP file to your desktop. Download the asset file below and drag the "tutorial" folder from the ZIP into the "qb64" folder now on your desktop. Detailed instructions are included below if you need them.  
  
Linux Users: Place the "tutorial" subdirectory from the assets file inside the QB64 installation directory.  
  
MacOS Users: Place the "tutorial" folder from the assets file inside the QB64 installation folder.  
  
If you are installing to Linux or MacOS [click here to visit the section in the Wiki](http://www.qb64.org/wiki/QB64_FAQ#Q:_How_do_I_install_QB64_on_Windows.2C_Linux.2C_macOS.3F) describing the installation procedures. MacOS and Linux require dependencies that may need installing. Be sure to visit this section in the Wiki.  
  
  
[![](qb64.png)](https://github.com/QB64Team/qb64/releases/latest)Click the QB64 icon to download the latest version of QB64.  
  
[![](IconTask13.png)](tutorial.zip)Click on the folder icon to download the asset files.  
  
Virus False Positives - Your anti-virus program may mark QB64 as a threat. You'll need to white list the folder that contains QB64 if you try to start QB64 and nothing happens or your anti-virus program is flagging anything QB64 related as a threat. This is a definite known problem if you attempt to install QB64 to your "Program Files" folder.  
  

* * *

Detailed Installation Instructions for Windows  

* * *

  
Step 1: Go to the [QB64 web site](https://www.qb64.org/portal/) and scroll down to "Get QB64 v1.4". See Figure 1 below.  
  

![](task1figure1.png)  

Figure 1 - Get QB64 v1.4  

  
Step 2: Click on the orange "Download QB64 v1.4" button. Then scroll down to the versions of QB64 available for download as seen in Figure 2 below.  
  

![](task1figure2.png)  

Figure 2 - Various OS versions of QB64  

  
Step 3: Click on "qb64\_1.4\_win\_x86.zip" next to the icon with "Windows 32-bit (From XP to 10)" under it. This will open a dialog box as seen in Figure 3 below.  
  

![](task1figure3.png)  

Figure 3 - The Download Dialog Box (as seen in Firefox).  

  
Step 4: Click the radio button labeled "Save File" then click OK. This will open the Save To dialog box as seen in Figure 4 below.  
  
Note: if your browser did not offer you the option of where to save the file to then you'll need to manually move the file from your browser's download folder to the desktop.  
  

![](task1figure4.png)  

Figure 4 - The Save To Dialog Box  

  
Step 5: Choose the "Desktop" as the folder to download to then click Save. An icon as seen in Figure 5 below will now be on your desktop.  
  

![](task1figure5.png)  

Figure 5 - The Downloaded ZIP file On The Desktop  

  
Step 6: Double click on the ZIP file located on your desktop to open the Extract dialog box as seen in Figure 6 below.  
  

![](task1figure6.png)  

Figure 6 - The Extract Dialog Box  

  
Step 7: Drag the "qb64" folder seen in the Extract dialog window and drop it onto your desktop. A progress bar as seen in Figure 7 below will show the extraction progress.  
  

![](task1figure7.png)  

Figure 7 - QB64 Extracting To The Desktop  

  
Step 8: When extraction has finished close the extraction dialog box. Double click on the "qb64" folder now seen on your desktop as it appears in Figure 8 below.  
  

![](task1figure8.png)  

Figure 8 - The qb64 Folder On Your Desktop  

  
Step 9: Double click on the "qb64" folder on your desktop to open the folder as seen in Figure 9 below.  
  

![](task1figure9.png)  

Figure 9 - The QB64 Programming Package  

  
Step 10: Double click on the "qb64" icon to start the QB64 IDE and proceed to Task 2.