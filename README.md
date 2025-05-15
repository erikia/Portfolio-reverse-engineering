# Reverse Engineering Projects Portfolio
My portfolio of reverse engineering projects. This repository contains detailed write-ups of binaries I've reversed. Each project folder contains a report of my analysis and the tools used.

## Projects 

| Project Name            | Description                                       | Tools Used                  | Difficulty    |
| ----------------------- | ------------------------------------------------- | --------------------------- | ------------- |
| `001-easy-crackme`      | Basic password verification crackme               | Ghidra, x64dbg              |               |
| `002-android-login.apk` | Android APK with login logic analysis             | JADX, Frida, MobSF          |               |
| `003-trojan-sample.exe` | Windows malware exhibiting persistence mechanisms | Ghidra, PEStudio, Wireshark | ([GitHub][1]) |

---> Smaller the prefix number, newer the report. This way, the newest (and most relevant) will be at the top.

##  Tools & Techniques

* **Static Analysis**: Ghidra, JADX, PEStudio
* **Dynamic Analysis**: x64dbg, Frida, Wireshark
* **Android Analysis**: MobSF, apktool
* **Malware Analysis**: Sandboxing, IOC extraction([GitHub][2])

## Notes
- Difficulties listed in reports are taken from the site at the time of writing the report
