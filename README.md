# cmail-file-grabbing

The web server fails to check whether requested files fall outside its document tree (by using ".." in the URL). 
Therefore attackers can retrieve files in the same drives as the ones that the software is on if they know or can get it's filename.
http://www.example.com:8002/../spool/username/mail.txt
