# Nombre del reto
>timer

---
# Descripción
>You will find the flag after analysing this apk
>Download [here](https://artifacts.picoctf.net/c/449/timer.apk).

---
# Solución
Aplicamos lo siguiente
`$ unzip timer.apk`

`$ grep -rw picoCTF .`
  `grep: ./classes3.dex: binary file matches`

`$ strings -t x classes3.dex | grep picoCTF`
  `160f *picoCTF{........redacted........}`

---
# Flag del reto
>picoCTF{t1m3r_r3v3rs3d_succ355fully_17496}

---
# Notas adicionales

---
# Referencias

