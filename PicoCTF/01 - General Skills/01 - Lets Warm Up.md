# Lets Warm Up
---
# Descripción
If I told you a word started with 0x70 in hexadecimal, what would it start with in ASCII?

---
# Solución
## Solución 1 (Cyberchef)
Se ingresa el hexadecimal **0x70** en cyber chef, se selecciona la receta **from hex** ya que vamos transformar de hexadecimal, esto nos resuta en la letra *p*
[Solución con cyberchef]([Solución con cyberchef](https://gchq.github.io/CyberChef/#recipe=From_Hex('Auto')&input=MHg3MA))
## Solución 2 (Python)
Se realiza la transformación de hexadecimal a decimal, entonces se busca el carácter del número decimal (que representa su valor en la tabla ascii).
```
# Transformación de hexadecimal a decimal
hex_num = 0x70
decimal = int(hex_num)
print("Valor decimal del hexadecimal: ", decimal)

# Búsqueda del caracter
letra = chr(decimal)
print(letra)
```

**Flag:** picoCTF{p}

---
# Notas adicionales

Hay otras formas de resolver esto, se puede indagar en más formas de resolverlo.

---
# Referencias

