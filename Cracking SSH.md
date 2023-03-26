

Cracking SSH Key Passwords with John

```
ssh2john id_rsa > id_pass.txt
john --wordlist=/usr/share/wordlists/rockyou.txt id_pass.txt
```
