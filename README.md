# RenamePDFsBasedOnTitle
Written in Python 3.7.7 for Windows 10 <br/>
Makes use of PyPDF2 and os <br/>
At present can only be run through and IDE, or Python via command line

Asks the user for a folder path which can be pasted from explorer <br/>
For PDFs in the folder, renames them based on the Title metadata

Does not work with PDFs lacking metadata or those that are protected <br/>
Also may incorrectly rename the file if metadata is inaccurate

