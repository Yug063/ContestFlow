# ContestFlow
A Codeforces parser for a specific contest identified by **contest-id**. Can be used for uninterrupted and smooth participation in a virtual contest, upsolving a practice contest or even a live contest.

# What it does
* You are prompted the contest-id of the Codeforces contest you want to upsolve
    * You **enter** the contest-id
* You are prompted for the preferred coding language from a list of options
    * You **enter** the option no.
* The script starts scraping the desired contest
* A Folder is created having the format ( name-of-the-contest)
    * Each folder has individual folders for each problem (A to F)
        * Each such sub-folder has 3 files (Assuming the problem is A)
            * A.cpp (Assuming you code in cpp)
            * A.txt (The i/o file)
            * input.txt 
    * A stats.txt and a stats.png file is also created having showing the problem vs accepted ratio.It helps the user gauge the difficulty of each problem and the contest as a whole.
   
# Starter code to be placed in template.txt (I have used my personal template)

## Requirements
* Modules
    * os
    * sys
    * requests
    * re
    * bs4 (BeautifulSoup)
    * time
    * matplotlib

* User Requiremets
    * codeforces-contest-id of any contest

* Python Version
    * 3 or above

* Active internet when py - script runs

* The terminal (required for input) shows log as the script runs


