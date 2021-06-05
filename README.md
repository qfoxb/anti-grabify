# anti-grabify
A hosts list based on https://github.com/Konnor88/anti-grabify. Blocks IP Grabbers.
# Installation Instructions 
# Pi-Hole
Head on over to [pi.hole](http://pi.hole/admin/) (or the ip address of your pi)
Press on Group Management and then Click on Adlists [or this handy link here!](http://pi.hole/admin/groups-adlists.php) 
Paste ```https://raw.githubusercontent.com/qfoxb/anti-grabify/master/hosts``` as the Address of the Adlist
Then, press add. Now, on the Terminal of your pi, run ```pihole -g```
# Windows
**WARNING: I am not responsible for damages caused by modifying System Files**
In a Command Prompt (As Administrator)
Run ```notepad.exe %SystemRoot%\System32\drivers\etc\hosts```.
At the very bottom of this file, paste the contents of [this file.](https://raw.githubusercontent.com/qfoxb/anti-grabify/master/hosts)
Press save, and restart your computer.
# macOS/Linux
**WARNING: I am not responsible for damages caused by modifying System Files**
In a Terminal,
Run ```sudo nano /etc/hosts``` (Or your preferred text editor!)
At the very bottom of this file, paste the contents of [this file.](https://raw.githubusercontent.com/qfoxb/anti-grabify/master/hosts)
Save the file (On nano, it's Ctrl + X, then strike the Y key, and then press enter.)
You should be kicked back out into the terminal. 
Restart your computer.

