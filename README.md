# Bash command line organizer

A simple bash script command line planner, mainly for fun. Built and used on android devices, designed with portability in mind, GNU and non-GNU platforms, and uses utilities which are standard to all distros, including the limited range of utils on Android command line.

Feel free to use, revise, or comment on any part of the script.

## Usage
`cnotes [-acCDfhlprRuz] [-o [-c]] [FILE] [ARGS]...`  

| Options                        | Description |
|                             ---|--- |
|  -a, --add FILE LINE STR       | Append STR to the first line containing LINE in FILE  |
|  -c, --clear FILE STR          | Delete first line containing STR from FILE, temporarily storing it in working_dir/deleted/lastline  |
|  -D, --del FILE                | Delete contents of FILE, storing a backup in working_dir/deleted/  |
|  -f, --find [FILE] STR         | Print FILE or all file lines containing STR  |
|  -p, --push FILE STR           | Append STR to FILE  |
|  -l, --list [FILE]             | Print FILE or print all files  |
|  -r, --rep FILE STR REPLACE    | Replace first occurence of STR with REPLACE in FILE  |
|  -z, --repl FILE STR REPLACE   | Like -r, but replaces the whole line  |
|  -R, --rest FILE               | Swap deleted FILE file with one in working_dir/deleted  |
|  -o, --sort [-c]               | Print tasks in chronological order if the have monthDay appended to them (eg nov15 or sep17). With -c supllied, prints this and next month calendars, highlighting tasks  |
|  -u, --undo FILE               | Append most recently cleared line to FILE  |
|  -C, --conf                    | Print config settings  |
|  -h, --help                    | Show this menu |  |

Feel free to use or modify the code - any suggestions on improvements are welcome
