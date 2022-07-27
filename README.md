<<<<<<< Updated upstream
# lastpass-authenticator-export
Forked to provide instructions, which are missing on the original repo, and minor qol improvements to the script.

## Requirements
- Python 3
- Pyton binaries must be added to `PATH`

## Instructions
1. Install dependencies from `requirements.txt` (to be merged into the script)  
  Alternatively: `pip install PACKAGE_NAME`
3. Invoke `python lastpass-authenticator-export.py -u EMAIL -o OTP_VALUE`
4. See folder `export`
=======
# LastPass Authenticator Export
Exports list of accounts from the Authenticator with QR codes.

# Requirements
- Python 3

# Instructions
1. Install dependencies:
    requests
    pycryptodome
    qrcode[pil]
    pyotp

    `python -m pip install PACKAGE_NAME`
1. Invoke `python lastpass-authenticator-export.py -u EMAIL -o OTP_VALUE`
    Where `OTP_VALUE` is your one-time LastPass password:
    https://lastpass.com/otp.php
1. See `export` folder
>>>>>>> Stashed changes
