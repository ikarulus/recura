# recura
Recura is a simple CLI tool for ARP Poisoning in Python. It is using the scapy library.
## Getting started
### Requirements
* python2.7
* scapy

### Exec
`./recury.py`

## Usage
```
recura.py [-h] -i INTERFACE -v VICTIM -r ROUTER [-f]usage: recura.py [-h] -i INTERFACE -v VICTIM -r ROUTER [-f]
Careful ARP-Poisoning tool
optional arguments:
  -h, --help            show this help message and exit
  -i INTERFACE, --interface INTERFACE
                        Your interface
  -v VICTIM, --victim VICTIM
                        The victim's IP
  -r ROUTER, --router ROUTER
                        The gateway's IP
  -f, --forwarding      Enable forwarding to sniff packages
```
