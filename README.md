# overthewire
Level 0: ssh bandit.labs.overthewire.org -p2220 -lbandit0
Level 0->1: -ls then -cat readme, copy the password, exit the server, and again ssh and paste the password(NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL)
Level 1->2: -cat ./- because cat- has a different function, password(rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi)
Level 2->3: -cat "spaces in this filename" as it has spaces password(aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG)
Level 3->4: first, cd to /inhere, then as it is hidden, do ls -a to get even . .. and .hidden, then cat .hidden to get the password(2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe)
Level 4->5: go to directory inhere, cat out all files individually to get the password in file07 password(lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR)
Level 5->6: do find -size 1033c to get the file which has the password(P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU)
Level 6->7: do find -user bandit7 -group bandit6 see through the permission denied list a /var/lib/dkpg/info/bandit7.password file is there cat to get the password(z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S)
Level 7->8: 
