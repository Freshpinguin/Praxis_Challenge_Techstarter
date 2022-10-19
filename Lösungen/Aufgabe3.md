### a)
```console
grep -o Hobbit Herr_der_Ringe_1.txt |  wc -l
grep -o Ork Herr_der_Ringe_1.txt |  wc -l
```

### b)
```console
grep Hobbit Herr_der_Ringe_1.txt | grep Auenland | wc -l
grep Ork Herr_der_Ringe_1.txt | grep Mordor | wc -l
```
