You can follow the steps on PDF to configure the new switch. 
Recommendation would be, before taking out the old switch, first configure the new switch(using an external power source) and download the backup files then replace with the old one.
In case the old switch is completly broken;
Here are the information that you need from old switch when you start the configure the new switch;
Host Name: SW001
Management Interface(Vlan): 1
IP Assignment Mode: Static
IP Address: 192.168.50.209 / 255.255.255.0
Default Gateway:
NTP Server:
Advanced Settings;
Enable CIP VLAN: Yes
CIP VLAN: 1
IP Address: 192.168.50.209 / 255.2555.255.0
Same As Management VLAN: Yes
CIP and Enable Password(leave blank if no change):               /            


For old switch, when you connect through your browser with its IP you will be asked user name and password
User Name: admin
Password: switch

For new switch, when you connect through your browser with its IP you will be asked user name and password
User Name: no name/blank
Password: switch