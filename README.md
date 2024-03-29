# wiresharkhelper

This works with the mobile app, get it from https://www.txthinking.com/wireshark.html

### Install via [nami](https://github.com/txthinking/nami)

```
nami install wiresharkhelper
```

### Usage

```
NAME:
   nami - Capture all mobile TCP&UDP and decrypt TLS into desktop Wireshark. All protocols supported by Wireshark. SSL/TLS certificates for interception are generated on the fly.

USAGE:
   nami [global options] command [command options] [arguments...]

VERSION:
   20221019

AUTHOR:
   Cloud <cloud@txthinking.com>

COMMANDS:
   help, h  Shows a list of commands or help for one command

GLOBAL OPTIONS:
   --ip value                                             Listen IP, usually lan ip
   --dns value                                            DNS Server (default: "8.8.8.8:53")
   --ipv value                                            4: query A only, 6: query AAAA only, 46: query A first, if no then query AAAA, only connect to one ip (default: 4)
   --bypass value, -b value [ --bypass value, -b value ]  Bypass domain, suffix match mode, repeated. Example: -b apple.com -b icloud.com
   --help, -h                                             show help (default: false)
   --version, -v                                          print the version (default: false)

COPYRIGHT:
   https://www.txthinking.com/wireshark.html
```
