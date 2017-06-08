# Remember-Gmail-Password

<img src="images/gmail.png" width="10%" />


## Overview
Script that helps you to remember forgotten password to **Gmail** account.


## How to use
Put all emails and possible passwords in **list.txt** in format : **email:password** .
Example of **list.txt**:
```
sample@gmail.com:password123
sample2@gmail.com:123123123
```
Script will only work ***if account has SMTP connection enabled***.

## Usage example
```bash
python2 main.py
```

### Output
For each pair email:password from **list.txt** you'll get the response, **was it successfull or not.**
