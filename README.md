# pdrozd-ssg

pdrozd-ssg is a static site generator created in python

# Features
 * Creates an index based on your html files created
 * Added JSON config file support 
 * Complete Markdown Support with the Help of [Python-Markdown/markdown](https://github.com/Python-Markdown/markdown)

# Requirements

Python 3

# How to Install

go to https://pypi.org/project/pdrozd-ssg/ or simply run the command `pip install pdrozd-ssg` 
to run use the command `pdrozd [with the command you want]`

# How to Upgrade

If theirs a new version run the command `pip install pdrozd-ssg --upgrade`

# Commands

The commands of pdrozd-ssg are
* -h or --help this will display to the user the options they have

* -c or --config this will specify a config file which contains arguments for SSG to read.

* -v or --version this will display to the user the current verison of pdrozd-ssg

* -i or --input this with a combanation of .txt or .md file or directory will output your files as a Static Site
  to use put in the format. e.g. <br>
   ```pdrozd -i or --input [file.txt\text.md] or [directory\]``` 

* -l or --lang this at the end of the input command will allow the default language of the HTML files to change. e.g.<br>
   ```pdrozd -i or --input [file.txt\text.md] or [directory\] -l or --lang [language]```

# Config File
Config files should be in legal JSON format with a similar format like
``` 
{
    "input":"./Sherlock-Holmes-Selected-Stories",
    "lang":"fr"
} 
```
