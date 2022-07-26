# pycrack

### pycrack is an easy to use password cracking tool that don't rely on GPU.  


#### Usage:
```
./pycrack [hash] [wordlist] [wordlist lenght] [workers]

```

### Example: 
```bash
./pycrack d2141cf615dfb57d04c4d27913948056 \
/lab/wordlists.d/crackstation.txt \
1212356398 \
12
```

![alt text](./images/potato21.png)



So far pycrack can deal only with md5 hashs.  
However as we are using hashlib. 
We could potentialy crack a couple of other hashs as well.
Maybe I'll add more options later on.
But feel free to modify the script to suit your needs.
Any pool request will be welcome. 


Number of workers should be the same as the number of cores
in your machine. If your using linux you can try 'nproc'.
Also wordlist lenght can be found with 'wc -l /path/to/wordlist.txt'


