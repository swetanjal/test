# IIITH-VPN
A handful of bash scripts written to automate the entire process of setting up openvpn to connect to IIITH VPN, connect and disconnect to IIITH VPN endless number of times and uninstall it if not required.
(This is only for IIITH students)

# INSTRUCTIONS TO USE:

# I. SETTING UP OPENVPN
1. Open Terminal
2. Go to home directory by typing the following command: cd ~/
3. Type: git clone https://github.com/swetanjal/IIITH-VPN.git
4. Type: sudo bash IIITH-VPN/iiit_vpn_setup.sh
# II. CONNECTING AND DISCONNECTING TO IIITH VPN
1. Open Terminal
2. Go to home directory by typing the following command: cd ~/
3. Type: sudo bash IIITH-VPN/iiit_vpn_setup.sh
4. You are now connected to IIITH VPN.
5. If you want to use the terminal for some work, open a new terminal window as you would be required to keep this terminal window open to remain connected to IIITH VPN.
6. Press CTRL+C to disconnect from IIITH VPN.
# III. UNINSTALL
*Please note that this would only remove the files required to connect to IIITH VPN.*
1. Open Terminal
2. Go to home directory by typing the following command: cd ~/
3. Type: sudo bash IIITH-VPN/uninstall.sh
4. If you want to remove openvpn as well, type: sudo update-rc.d -f openvpn  remove
5. Finally type: rm -rf IIITH-VPN/

