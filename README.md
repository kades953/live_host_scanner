# 🕵️‍♂️ Live Host Scanner

This is a super simple Bash script I put together to scan a local subnet and find which hosts are alive. It's basically a quick `ping` sweep tool — nothing fancy, just fast and functional.

## 💡 What It Does

You give it a base IP like `192.168.1`, and it loops through all the addresses from `192.168.1.1` to `192.168.1.254`, pinging each one. If a host replies, it prints the IP. Done.

Handy for small network recon, CTFs, or when you just wanna know who else is on your Wi-Fi 👀

## 🛠️ How to Use It

Make sure the script is executable and run it as:

```bash
chmod +x ipsweep.sh
./ipsweep.sh 192.168.1
