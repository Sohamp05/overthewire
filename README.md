# overthewire
Level 0: ssh bandit.labs.overthewire.org -p2220 -lbandit0
Level 0->1: -ls then -cat readme, copy the password, exit the server, and again ssh and paste the password(NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL)
Level 1->2: -cat ./- because cat- has a different function, password(rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi)
Level 2->3: -cat "spaces in this filename" as it has spaces password(aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG)
Level 3->4: first, cd to /inhere, then as it is hidden, do ls -a to get even . .. and .hidden, then cat .hidden to get the password(2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe)
Level 4->5: go to directory inhere, cat out all files individually to get the password in file07 password(lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR)
Level 5->6:
