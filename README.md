# pycrack

### pycrack is an easy to use password cracking tool that don't rely on GPU.  

### Algorithms supported
* blake2b  
* blake2s
* md5  
* sha1  
* sha224  
* sha256  
* sha384  
* sha3_224  
* sha3_256  
* sha3_384  
* sha3_512  
* sha512  
* shake_128  
* shake_256


#### Usage:
```
./pycrack [hash] [algorithm] [wordlist] [wordlist lenght] [cores]

```

### Example: 
```bash
./pycrack 028b7e429c7e056704dd8cd383a1a361 \
md5 \
/lab/wordlists.d/crackstation.txt \
1212356398 \
12
```

![alt text](./images/potato21.png)

SHA512 can take a tad longer but still feasible.
![alt text](./images/sha512.png)

On linux you can use nproc to figure out how may cores you have.
```bash
nproc
```

![alt text](./images/cpus.png)


Also you could count the lines with the fallowing command.
```bash
wc -l /path/to/wordlist.txt
```

![alt text](./images/wc.png)


I use crackstation.txt on my labs. You can download it from the link.
[crackstation.txt](https://crackstation.net/crackstation-wordlist-password-cracking-dictionary.htm)

#### We are using GPLv3. Feel free to modify this script as much as you want...
