# LEUBNT
Lets Encrypt For UBNT Edge Router 1.9.7 HF1

Based on and adapted from [rholmboe](https://github.com/rholmboe/ubnt-letsencrypt)

Disclaimer:
> This can totally knacker the web interface on your edgerouter, read the scripts understand what it does, it is likely buggy and will break.  Use at your own risk.

## Installation

SSH into your EdgeRouter and issue following command

```
curl https://raw.githubusercontent.com/ghostseven/LEUBNT/master/install.sh | sudo bash
```
*Important* is to enter your external FQDN
