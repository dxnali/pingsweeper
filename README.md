# pingsweeper
A simple bash script for pingsweeping a list of IP addresses. This tool is intended for educational and ethical use only.

# Usage
Clone the git repo:
git clone https://github.com/mfbog/pingsweeper/

Change directory into it:
cd pingsweeper

Create an ip list text file in this layout:
192.168.1.0
192.168.1.1
192.168.1.2
etc...

Save the ip list and execute the tool:
chmod +x pingsweeper
./pingsweeper

When prompted, enter the name of your ip list file:
Enter IP list -> iplist.txt

Then watch the program scan all IP's in the list, telling you which are online and which are offline.

git clone https://github.com/mfbog/pingsweeper && cd pingsweeper && ./pingsweeper
