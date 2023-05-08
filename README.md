# File Thingie 2.5.7 - RCE

Arbitary File Upload discovered by Cakes: https://www.exploit-db.com/exploits/47349. This PoC exploits the discovered vulnerability and generates and uploads a webshell.

## Usage

```bash
usage: filethingieRCE.py [-h] -t TARGET -u USERNAME -p PASSWORD -L LHOST -P LPORT

options:
  -h, --help            show this help message and exit
  -t TARGET, --target TARGET
                        Target URL to ft2.php
  -u USERNAME, --username USERNAME
                        File Thingie username
  -p PASSWORD, --password PASSWORD
                        File Thingie password
  -L LHOST, --LHOST LHOST
                        Local listener ip
  -P LPORT, -LPORT LPORT
                        Local listener port
```
