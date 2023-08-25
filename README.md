# Admin-Finder
All possible Admin panel directory and subdomain lists

# This list can find all possible admin panel 

# Tools : 
Use Any Fuzzing Tool like Dirbuster , Gobuster , FFuF  etc ..

# Usage : [ FFuF ]
ffuf -u "<URL>/FUZZ" -w admin-directory.txt -mc 200
ffuf -u "FUZZ.<URL>" -w admin-subdomain-list.txt -mc 200
