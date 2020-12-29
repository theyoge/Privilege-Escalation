# Privilege-Escalation
Linux Privilege Escalation Scripts


There are many scripts that you can execute on a linux machine which automatically enumerate sytem information, processes, and files to locate privilege escelation vectors. Here are a few:

LinPEAS - Linux Privilege Escalation Awesome Script

wget "https://raw.githubusercontent.com/carlospolop/privilege-escalation-awesome-scripts-suite/master/linPEAS/linpeas.sh" -O linpeas.sh
curl "https://raw.githubusercontent.com/carlospolop/privilege-escalation-awesome-scripts-suite/master/linPEAS/linpeas.sh" -o linpeas.sh
./linpeas.sh -a #all checks - deeper system enumeration, but it takes longer to complete.
./linpeas.sh -s #superfast & stealth - This will bypass some time consuming checks. In stealth mode Nothing will be written to the disk.
./linpeas.sh -P #Password - Pass a password that will be used with sudo -l and bruteforcing other users
