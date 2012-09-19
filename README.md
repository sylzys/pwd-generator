pwd-generator
------------

pwd-gen is a simple password generator. It can generate a password with letters, digits and symbols, and encrypt them with MD5 or SHA1.

User can choose password length (default length is 8), password encryption, and if password will contain digits and/or symbols.



<b>Usage: ./pwd-gen [options]</b>
*    -l, --length [LENGTH]            Length of the desired password
*    -d, --no-digit                   Do not include digits in password
*    -s, --no-symbol                  Do not include symbols in password
*    -e, --encrypt [md5|sha1]         Encryption type of the desired password
