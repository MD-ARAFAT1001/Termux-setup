pkg update && pkg upgrade
pkg install git
pkg install python
rm -rf Termux-setup
git clone https://github.com/MD-ARAFAT1001/Termux-setup
cd Termux-setup
python fullsetup_enc.py
