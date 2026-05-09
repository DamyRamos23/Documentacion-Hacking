# Nombre del reto
>Picker I

---
# Descripción
>This service can provide you with a random number, but can it do anything else?
>Connect to the program with netcat:
>$ nc saturn.picoctf.net 54469
>The program's source code can be downloaded [here](https://artifacts.picoctf.net/c/515/picker-I.py).

---
# Solución
Al entrar al programa con netcat, colocamos win, lo cual nos dará un conjunto de hexadecimales los cuales [transformaremos](https://toolbox.itsec.tamu.edu/#recipe=From_Hex('Auto')&input=MHg3MCAweDY5IDB4NjMgMHg2ZiAweDQzIDB4NTQgMHg0NiAweDdiIDB4MzQgMHg1ZiAweDY0IDB4MzEgMHgzNCAweDZkIDB4MzAgMHg2ZSAweDY0IDB4NWYgMHgzMSAweDZlIDB4NWYgMHgzNyAweDY4IDB4MzMgMHg1ZiAweDcyIDB4MzAgMHg3NSAweDY3IDB4NjggMHg1ZiAweDYzIDB4NjUgMHgzNCAweDYyIDB4MzUgMHg2NCAweDM1IDB4NjIgMHg3ZA) para obtener la flag.

---
# Flag del reto
>picoCTF{4_d14m0nd_1n_7h3_r0ugh_ce4b5d5b}

---
# Notas adicionales

---
# Referencias

