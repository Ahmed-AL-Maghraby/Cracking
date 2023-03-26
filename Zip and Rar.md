

Zip Files Using John

```
zip2john zipfile.zip > secure.txt
john --wordlist=/usr/share/wordlists/rockyou.txt secure.txt
```

RAR File Using John

```
rar2john rarfile.rar > rarPass.txt
john --wordlist=/usr/share/wordlists/rockyou.txt rarPass.txt
```
