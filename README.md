### Purpose
bfuzz is an experimental boundary value checker.
It sends packets described in a cfg file where this
configuration file describes the headers and data and
how to assemble the packets described.  It has support
for automated length and CRC calculations.

### Requirements:
        Python 3.6 or higher
        Permission to create a raw socket

### Installation:

        Assuming Python is installed you can run the script from anywhere
        the configuration file and bfuzz program is installed.

### Usage
        python bfuzz.py -f sample.cfg

### Ethics
_Do not use this for nefarious purposes._ If you do, I don't want to know about it, I am not and will not be responsible for your lack of common decency and/or foresight. However, if you find a clever non-evil use for this, by all means, share.

### Use Cases
These are a few examples of ways this tool could be used:

**Ethical**
 * Testing Server protocols for boundary condition vulnerabilities
 * Notifying owners of vulnerable software and with techniques and tools used for discovery.

**Unethical**
 * Sending packets to exploit known or discovered vulnerabilities without first notifying the owners of vulnerable software.
 * Publicizing security vulnerabilities without first notifying owners.

### License
The source of this project is licensed under Affero GPL v3.0. According to [http://choosealicense.com/licenses/agpl-3.0/](http://choosealicense.com/licenses/agpl-3.0/) you may:

#### Required:

 * **Disclose Source:** Source code must be made available when distributing the software. In the case of LGPL, the source for the library (and not the entire program) must be made available.
 * **License and copyright notice:** Include a copy of the license and copyright notice with the code.
 * **Network Use is Distribution:** Users who interact with the software via network are given the right to receive a copy of the corresponding source code.
 * **State Changes:** Indicate significant changes made to the code.

#### Permitted:

 * **Commercial Use:** This software and derivatives may be used for commercial purposes.
 * **Distribution:** You may distribute this software.
 * **Modification:** This software may be modified.
 * **Patent Grant:** This license provides an express grant of patent rights from the contributor to the recipient.
 * **Private Use:** You may use and modify the software without distributing it.

#### Forbidden:

 * **Hold Liable:** Software is provided without warranty and the software author/license owner cannot be held liable for damages.
 * **Sublicensing:** You may not grant a sublicense to modify and distribute this software to third parties not included in the license.

### Feedback
If you have any general questions or feedback leave a comment below. For bugs, feature suggestions and anything directly relating to the program itself, submit an issue in github.

