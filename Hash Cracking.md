
# Hash Cracking

## Online Tools

+ Password Hash Cracker : https://crackstation.net/

+ MD5 and SHA1 : https://hashtoolkit.com/

+  MD5, SHA1, MySQL, NTLM, SHA256, SHA512 hashes : https://hashes.com/en/decrypt/hash

+ Hash analyzer : https://www.tunnelsup.com/hash-analyzer/

## CLI Tools


Hash analyzer
```
$ hashid '00000'
```

### Crack with HashCat

Hash modes

```
hashcat --help | grep 'HashType'    
```

Crack

```
$ hashcat -m <hash mode> hash.txt wordlist.txt --force
```











