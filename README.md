# anti-grabify
A hosts list based on https://github.com/Konnor88/anti-grabify. Blocks IP Grabbers.
# Installation Instructions 
# Pi-Hole
Head on over to [pi.hole](http://pi.hole/admin/) (or the ip address of your pi)
Press on Group Management and then Click on Adlists [or this handy link here!](http://pi.hole/admin/groups-adlists.php) 
Paste https://raw.githubusercontent.com/qfoxb/anti-grabify/master/hosts as the Address of the Adlist
Then, press add. Now, on the Terminal of your pi, run ```pihole -g```.
