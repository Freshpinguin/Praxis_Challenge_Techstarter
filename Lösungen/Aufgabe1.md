### a)
Benutze *head* um die ersten 10 Zeilen von "pokemon.txt" zu betrachten.
```console
head pokemon.txt
```
Man kann sehen, dass die erste Zeile beschreibt, was die Werte in den darauf folgenden Zeilen bedeuten.

### b)

```console
head -n 1 pokemon.txt > water_pokemon.txt
```

### c)
```console
grep Water pokemon.txt >> water_pokemon.txt
```

### d)
```console
wc -l water_pokemon.txt
```

### e)
```console
grep Fire pokemon.txt >> fire_pokemon.txt
wc -l fire_pokemon.txt
```

### f)
```console
grep Fire water_pokemon.txt > fire_water_pokemon.txt
wc -l fire_water_pokemon.txt
```
