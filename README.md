# OPENVPNConfigfiles


Steps before using the .ovpn files.

1. Go to the linux terminal and install openvpn as:
sudo apt install openvpn
2. Go to this website: https://www.freeopenvpn.org/en/logpass/netherlands.php
3. You can also download various other country .ovpn files
4. Once you download go to the downloads as:
  cd ~/Downloads
5. Then, go to the terminal and enter:
   sudo openvpn --config Netherlands_freeopenvpn_tcp.ovpn  (For example I am using vpn from Netherland)
6. Once you do that you will need to enter the username and password which you will find on the same website.
  (But, remember the password changes twice a day.)
7. Once you do that the vpn will start working.
8. To check whether you are connected or not open new tab on terminal as ctrl+shift+T and type ifconfig, you will see you have been connected to new extra network. 
9. You have successfully accessed the VPN network.

For any questions and problems email at: prajwollamichhane11@gmail.com
