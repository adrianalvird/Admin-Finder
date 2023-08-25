# Admin-Finder
All possible Admin panel directory and subdomain lists

# This list can find all possible admin panel 

# Tools : 
Use Any Fuzzing Tool like Dirbuster , Gobuster , FFuF  etc ..

# Usage : [ FFuF ]
//** this FUZZ will replace with the each wordlist character **//
//** -mc 200 will check the status code 200 **//

# Directory Finding
ffuf -u "<URL>/FUZZ" -w admin-directory.txt -mc 200
ffuf -u "https://www.target-site.com/FUZZ" -w admin-directory.txt -mc 200 

# Subdomain Finding
ffuf -u "FUZZ.<URL>" -w admin-subdomain-list.txt -mc 200
ffuf -u "https://FUZZ.target-site.com" -w admin-subdomain-list.txt -mc 200
