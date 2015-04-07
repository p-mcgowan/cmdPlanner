#v1.3.7 - Apr, 2015  
  \- Formatting and typo bug fix  

#v1.3.6 - Mar, 2015  
  \- Added config making option if config file not found  
  \- Changed -rl to -z  

#v1.3.5 - Mar, 2015  
  \- Multiple refactoring and format changes 

#v1.3.4 - Mar, 2015  
  \- Added -C, --conf to print config settings  
  \- Large formatting restructure, long options now prepended with -- to comply with standards  

#v1.3.3 - Mar, 2015
  \- Fixed error in calculating target file with multiple calling conventions  

#v1.3.2 - Mar, 2015  
  \- Fix and clean config loading  

#v1.3.1 - Feb, 2015  
  \- String replace hotfix, now works for quoted input (eg cnotes -r course "param param param" "replacement param")  

#v1.3.0 - Feb, 2015
  \- Added config file and config loading options for easily modifiable courses and files  

#v1.2.0 - Feb, 2015
  \- Sort and calendar functionality changed  
    \- Date format for searching now uses 3 char format (eg mar for March) to fix dates being sorted improperly  
  \- Slight optimizations and cleanup  

#v1.1.5 - Jan, 2015
  \- Added touch to fix empty directory errors  
  \- Reformat changelog.md  

#v1.1.4 - Jan, 2015
  \- Calendar fix for start of line dates  

#v1.1.3 - Nov, 2014
  \- Optimizations in sort  
  \- Formatting changes  

#v1.1.2 - Oct, 2014
  \- minor sort output formatting  

#v1.1.1 - Oct, 2014
  \- -a, append strong quotations in sed were fixed  

#v1.1.0 - Oct, 2014
Calendar sort - sort option prints calendar.  
  \- -o, sort now has additional -c parameter which prints this month and next months calendar with date marking based on formatted sort input.  
  \- Minor code cleanup  
  \- Strong and weak quoting for grep and sed fixes  

#v1.0.6 - Oct, 2014
Fix - clear was not deleting lines with spaces, added quotes  
  \- Quick fix - added quotes around message to grep for in clear, -c  

#v1.0.5 - Oct, 2014
Fix - 1.0.4 fix broke matching and printing. Hopefully this fixes it  
  \- Changed sort to output temp file to parse so that it can remove matched strings  

#v1.0.4 - Oct, 2014
Fix - Unmatched not printing certain strings  
  \- Added quotes around grep cmd in sort for whole string  

#v1.0.3 - Oct, 2014
Fix - Octal numbers in date (ie. 08) caused errors  
  \- Slightly tweaked sort for loop  

#v1.0.2 - Oct, 2014
Fix - sort does not print duplicates  
  \- sort actually no longer prints duplicates.  

#v1.0.1 - Oct, 2014
Hotfix - sort, -o duplicate output in unmatched  
  \- sort, -o no longer prints duplicates, but requires date format at end of line  

#v1.0.0 - Sept, 2014
Finalization patches, implementations. Released as version 1.0.0  
  \- sort, -o prints unmatched strings, minor optimizations made.  

#v0.3.0 - Sept, 2014
  \- rep, -r: Replaces a substring in a file. Previously, this only replaced full lines.  
  \- rep, -r is now replace single substring. For previous full line replacement, use repl or -rl.  

#v0.2.0 - Sept, 2014  
  \- sort, -o: Prints lines matching 'date' in order, from today's date +[0,24]  
  \- Revised push, -p and find, -f methods to accomodate file parsing  
