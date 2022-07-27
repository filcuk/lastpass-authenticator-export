# LastPass Authenticator Export
Exports OTP accounts from the Authenticator with QR codes.  
Forked to provide instructions alongside the script.

## Requirements
- Python 3
- Pyton binaries must be added to `PATH`

## Instructions
1. Install dependencies `python -m pip install PACKAGE_NAME`:  
    `requests`  
    `pycryptodome`  
    `qrcode[pil]`  
    `pyotp`  
2. Invoke `python lastpass-authenticator-export.py -u EMAIL -o OTP_VALUE`  
    Where `OTP_VALUE` is your one time password:  
    https://lastpass.com/otp.php
3. Check `export` folder
