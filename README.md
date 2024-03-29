Usage:

This script will embed a hidden and encrypted message into a specified output PNG file.  

```
$ python tuckerenc.py --input demo.png --output steg.png --message "Hi there! It's me!"
ENTER PASSPHRASE:
[+] Saving image to: steg.png
 
```

This script will also extract the hidden message, decrypt it, and then print it.  

```
$ python tuckerenc.py --input steg.png --getmessage                             
ENTER PASSPHRASE:
Hi there! It's me!

```


Note:  

This script may not work under Windows because of the way input for the passphrase is accepted.

You will most likely need to use Cygwin on Windows, or Windows Subsystem for Linux, or Linux.