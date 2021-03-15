```
░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
████████████████████████████████
██▄░░░░░░░░░░░░░░░░░░░░░░░░░░▄██
████▄░░░░░░░░░░░░░░░░░░░░░░▄████
██░▀██▄░░░░░░░░░░░░░░░░░░▄██▀░██
██░░░▀██▄░░░░░░░░░░░░░░▄██▀░░░██
██░░░░░▀██▄░░░░░░░░░░▄██▀░░░░░██
██░░░░░░░▀██▄░░░░░░▄███░░░░░░░██
██░░░░░░▄██▀██▄░░▄██▀▀██▄░░░░░██
██░░░░▄██▀░░░▀████▀░░░░▀██▄░░░██
██░░▄██▀░░░░░░░░░░░░░░░░░▀██▄░██
██▄██▀░░░░░░░░░░░░░░░░░░░░░▀████
███▀░░░░░░░░░░░░░░░░░░░░░░░░░▀██
██▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄█
▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀
░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░

Email Generator/Permutator by Juan Cruz Tommasi - Base4 Security - www.base4sec.com
```

# **Email Generator/Permutator**
#### Generate 50 possible mails from domain with a name

#### No extra dependency needed

### **ARGS**
```
-f --firstname
-l --lastname
-m --middlename (Optional)
-d --domain
```

## **EXAMPLES**:

> Search in github taking each line of the t.txt as search pattern with a time of 5 seconds between api calls:  
> `python3 mailgen.py -f john -l doe -m francis -d gmail.com`  

Expected output:
```bash
john@gmail.com
doe@gmail.com
johndoe@gmail.com
john.doe@gmail.com
jdoe@gmail.com
j.doe@gmail.com
johnd@gmail.com
john.d@gmail.com
jd@gmail.com
j.d@gmail.com
doejohn@gmail.com
doe.john@gmail.com
doej@gmail.com
doe.j@gmail.com
djohn@gmail.com
d.john@gmail.com
dj@gmail.com
d.j@gmail.com
john-doe@gmail.com
j-doe@gmail.com
john-d@gmail.com
j-d@gmail.com
doe-john@gmail.com
doe-j@gmail.com
d-john@gmail.com
d-j@gmail.com
john_doe@gmail.com
j_doe@gmail.com
john_d@gmail.com
j_d@gmail.com
doe_john@gmail.com
doe_j@gmail.com
d_john@gmail.com
d_j@gmail.com
johnfrancisdoe@gmail.com
john.francis.doe@gmail.com
john-francis-doe@gmail.com
john_francis_doe@gmail.com
jfdoe@gmail.com
jf.doe@gmail.com
johnfdoe@gmail.com
john.f.doe@gmail.com
jf-doe@gmail.com
john-f-doe@gmail.com
jf_doe@gmail.com
john_f_doe@gmail.com
```
