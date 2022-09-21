# my-button

A __Static Site Generator__(_SSG_) for __OSD600__

This repo introduces a __JavaScript__ program that convert __.txt file__ or __.md file__ into a __HTML file__
# Installation 
First install via:
`npm install`

check if yargs is installed and if not run the following in your terminal:
`npm i yargs`
# Commands
`node server.js --input  Convert a text file to HTML file.`
After installation of yargs. You can simply run the program by the command:

`node server.js -i '.\Silver Blaze.txt'` or `node server.js -i Silver-Blaze.md`
Which will generate a __HTML__ file for the __'Silver Blaze.txt'__ file or __'Silver-Blaze.md'__ into the __/dist__ folder.

__Or__

`node server.js -i .\Sherlock-Holmes-Selected-Stories\` 
Which will generate __HTML__ files for the __Sherlock-Holmes-Selected-Stories directory__ into the __/dist__ folder.
# Options
Options:

 ` -h, --help     Show help                                             [boolean]`
 
 ` -v, --version  Show version number                                   [boolean]`

 ` -i, --input    convert .txt file to html file              [string] [required]`
 
 # Test Site
 https://my-button-ssg.vercel.app/ 
 # License
 [__MIT License__](https://choosealicense.com/licenses/mit/)
 
