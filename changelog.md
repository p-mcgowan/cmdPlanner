###v0.2.0 - Sept, 2014  
Added:  
  \- sort, -o: Prints lines matching 'date' in order, from today's date +[0,24]  
Changed:  
  \- Revised push, -p and find, -f methods to accomodate file parsing  
 
###v0.3.0 - Sept, 2014
Added:  
  \- rep, -r: Replaces a substring in a file. Previously, this only replaced full lines.  
Changed:  
  \- rep, -r is now replace single substring. For previous full line replacement, use repl or -rl.  
Upcoming:  
  \- sort, -o will print unmatched string after the sorted list.  
  \- Increasing speed of searching algorithms.  
  \- Restructure file storage, possibly consolidating files into one.  
  \- Implementing config files and optional file creating and deletion file for more reusable implementation.  
  
###v1.0.0 - Sept, 2014
Finalization patches, implementations. Released as version 1.0.0  
Added:  
  \- sort, -o prints unmatched strings, minor optimizations made.  
Upcoming:  
  \- Restructure file storage, possibly consolidating files into one.  
  \- Implementing config files and optional file creating and deletion file for more reusable implementation.  

###v1.0.1 - Oct, 2014
Hotfix - sort, -o duplicate output in unmatched  
Changed:  
  \- sort, -o no longer prints duplicates, but requires date format at end of line  
Upcoming:  
  \- Restructure file storage, possibly consolidating files into one.  
  \- Implementing config files and optional file creating and deletion file for more reusable implementation.  

###v1.0.2 - Oct, 2014
Fix - sort does not print duplicates  
Changed:  
  \- sort actually no longer prints duplicates.  
Upcoming:  
  \- Implementing config files and optional file creating and deletion file for more reusable implementation.  
Notes:  
  \- Restructure pushed back, may revisit if necessary.  

###v1.0.3 - Oct, 2014
Fix - Octal numbers in date (ie. 08) caused errors  
Changed:  
  \- Slightly tweaked sort for loop  
Upcoming:  
  \- Implementing config files and optional file creating and deletion file for more reusable implementation.  
  \- Possibly implementing a count for a more verbose search record  

