# boost
Rez package to build boost

# Requirements
*Python 2.7 - you may need to install python-devel (sudo dnf install python-devel)

# Notes
This rez package relies on an existing file (downloaded from internet).
Rez will try to find this file inside the directory pointed by the environment variable named REZ_REPO_PAYLOAD_DIR.
Usually, this variable points to a main directory where all payloads can be found. Example: ~/rezpayload
From there, it will find the sub-directory named boost and the file within.
See CMakeLists.txt for more details.
