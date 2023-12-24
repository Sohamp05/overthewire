# overthewire
Level 0: ssh bandit.labs.overthewire.org -p2220 -lbandit0
Level 0->1: -ls then -cat readme, copy the password, exit the server, and again ssh and paste the password(NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL)
Level 1->2: -cat ./- because cat- has a different function, password(rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi)
Level 2->3: -cat "spaces in this filename" as it has spaces password(aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG)
Level 3->4: first, cd to /inhere, then as it is hidden, do ls -a to get even . .. and .hidden, then cat .hidden to get the password(2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe)
Level 4->5: go to directory inhere, cat out all files individually to get the password in file07 password(lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR)
Level 5->6: do find -size 1033c to get the file which has the password(P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU)
Level 6->7: do find -user bandit7 -group bandit6 see through the permission denied list a /var/lib/dkpg/info/bandit7.password file is there cat to get the password(z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S)
Level 7->8: just grep "millionth" data.txt to get the password(TESKZC0XvTetK0S9xNwm25STk5iWrBvP)
Level 8->9: first sort the text then use unique with -u to get the unique line which is the password(EN632PlfYiZbn3PhVK3XOGSlNInNE00t)
Level 9->10: get the strings using cat data.txt|string | grep == and use grep to get the password which would be random so(G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s)
Level 10->11: just decode the file using base64 data.txt -d command with(-d) to get the password(6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM)
Level 11->12: using the translate function to solve the rot13 using cat data.txt | tr "A-Za-z" "N-ZA-Mn-za-m" to get the solved password(JVNBBFSmZwKKOP0XbFXOoW8chDz5yVRv)
Level 12->13: first make a temp dir don't use temp use /tmp/randome to not get permission denied, do xxd -r data.txt to copied file to this directory, then uncompress  till you get ASCII text file if gz file then put extension .gz and gunzip filename, if bzip2 then extension .bz2 and bzip2 -d filename, and if tar then extension .tar and tar -xf filename. use mv to rename and file command to know the type of file. At data8 txt file there will be password(wbWdlBxEir4CaE8LaPhauuOo6pwRmrDw).
Level 13->14: use ssh -i sshkey.private bandit14@localhost -p 2220 , don't forget -p 2220, to get to the server and then cat /etc/bandit_pass/bandit14 to get the password(fGrHPx402xGC7U7rXKDaxiWFTOiF0ENq)
Level 14->15: just use nc localhost 30000 and submit the current level's password to get the next password(jN2kgmIXJ6fShzhT2avhotn4Zcka6tnt)
