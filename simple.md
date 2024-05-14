# simple
Level: Easy

Description:
```
Yeah yeah, another password cracking challenge, you know what to do here.

2acc5ca392faa9c5c1d3a1200922b07a

What's the password?

Flag format: byuctf{password}
```

## Writeup
Password Cracking challenge. The text is hashed. Copy and paste it into https://hashes.com/en/tools/hash_identifier. It will identify MD5 as the hashing method. Open WSL and enter the hashed text into the hashcat command. For example: `hashcat --show -m 0 2acc5ca392faa9c5c1d3a1200922b07a`. The output will contain the flag.

**Flag** - `byuctf{darth123vader456}`
