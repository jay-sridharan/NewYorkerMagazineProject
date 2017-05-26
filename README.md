# The Magazine Project
The Magazine Project is a project assigned anually to students of Glenwood High School. The assignment involves replicating the New Yorker of a certain time period. The most challenging aspect of this project is the formatting, which requires much patience along with hours and hours of trial and error. To help reduce the difficulty in creating such a magazine, I am publishing the source files of my attempt to replicate the New Yorker.

## Using this Repository
The goal of the repository is to provide a template for students to use when creating their magazine. Most students use publishing software such as Microsoft Publisher or Adobe InDesign to create their magazine. When I started this project, I found that Publisher is missing some key features and InDesign has a very steep learning curve. Thus, I stumbled upon Scribus, an open-source publishing software available on Mac, Windows and various flavors of Linux. Scribus had just enough features to suit this assignment and was easy enough that the average person would not be bogged down by the learning curve. The magazine in the project was made with Scribus.

### Files
```
-- ads                | Folder containing all images in the magazine. 
   -- original        | Original files, downloaded from the web.
   -- edited          | Images edited to produce a clearer image. 
-- text               | All text in magazine, grouped by section.
   -- ...             |
-- ScribusPortable    | Copy this directory onto the Desktop and run
                      | ScribusPortable.exe to run Scribus without installation. 
--------------------------------------------------------------------
--Magazine.pdf        | Exported PDF version of magazine. 
--Magazine.sla        | Editable Scribus file. 
--ScribusTutorial.pdf | Tutorial for new Scribus users.

```

## Scribus
Scribus is available for download at https://www.scribus.net/downloads/stable-branch/ . 
### Portable Version
Scribus offers a portable version of the software. This means the software can be run without installation. The `ScribusPortable` directory in this repository is the copy of Scribus I used to create this repository. The fonts used in the Magazine can be found at `ScribusPortable/App/Scribus/share/fonts`
To use the portable version of this software, copy the `ScribusPortable` directory to your Desktop. **You must do this. The software will not run directly off of a flash drive or any other type of removable media**. Once on the Desktop, run `ScribusPortable.exe`.

### Using Scribus
Scribus has a wealth of documentation and tutorial available for learning the software. Here are a few links:

https://wiki.scribus.net/canvas/Scribus
https://wiki.scribus.net/canvas/Scribus_Video_Tutorials
https://www.youtube.com/playlist?list=PLHQhkJ5kqi5T-oWdYaYYa3gLUJ947TCuu
https://www.youtube.com/watch?v=JmmeLoqLhNE

## Magazine.sla
This section will outline how `Magazine.sla` is structured and how you should use it. To open this `Magazine.sla`, open Scribus, then naviagate to `File > Open`. Once you've familiarized yourself with how Scribus works, come back and read this section.
### Page Setup.
Magazine.sla is set up as a Double-Sided document. The page configuration is as follows:

![alt text](https://raw.githubusercontent.com/jayasurya-sridharan/MagazineProject/blob/master/readme_files/setup.PNG)


### Sections

I used sections to make the page numbers begin at page 3 rather than page 1. Because certain pages do not include a page number, I did not include the page numbers in the master page. Rather, I copied and pasted the page numbers and associated text on only the pages that required them. Because Scribus positions elements based on the page it is on, I only had to position the page numbers once. When copying, the postition of the page numbers relative to the page did not change, sparing me the inconvenience of having to reposition the page number on each page.

### Styles

The Magazine only contains a few text types. To make it easier when creating the document, I created Styles for each font type. When I needed to use it, I could simply select the correct character or paragraph style and the appropriate settings were applied. The Styles I created were the following:

**Paragraph Styles**
- Goings On Heading Black
- Goings On Heading Red
- Goings On Small Text
- Goings On Subheading
- New_Yorker_Text_Drop
- New_Yorker_Text_Standard

The definitions of these Styles can be seen in `Edit > Styles`

## Conclusion
I tried my best to create an accurate replica of the magazine, but to err is human. I encourage all users of this repository to check for errors and repair them. Any future students may host their magazine on this repository as well, regardless of which software they used to create it: Publisher, InDesign or Scribus. If that intrests you, just send me your files. For any questions about how I've created this document or even general questions about how to use Scribus, feel free to shoot an email to jayasurya(dot)sridharan(at)gmail(dot)com