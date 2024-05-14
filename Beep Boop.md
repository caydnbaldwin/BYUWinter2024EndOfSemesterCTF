# Beep Boop
Level: Easy

Description:
```
beepbeepbeepboop boopboopbeepboopbeepboopbeep boopboopboop boopbeepbeepbeep boopboopboop boop

https://chall4.csa.cyberjousting.com/
```

## Writeup
Web Exploitation challenge. The link takes you to a robot themed website. The webpage theme hints you to look at the `robots.txt` page. This can be done by adding `/robots.txt` to the end of the URL. For example: `https://chall4.csa.cyberjousting.com/robots.txt`. There is one disallowed file present. Replace the end of the URL `/robots.txt` with the file name `/secrets`. For example: `https://chall4.csa.cyberjousting.com/secrets/`. The page will contain the flag.

**Flag** - `byuCTF{I_f0und_th3_r0b0t!!}`
