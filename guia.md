# Desafíos de Criptografía
El objetivo de estos desafíos es, a partir de un mensaje encriptado, encontrar su significado real, lo que llamaremos "flag".

La obtención en estos desafios de la flag puede ir desde una simple traducción, a tener en cuenta como se almacena la información de usuarios en sistemas UNIX, cracking de contraseñas, entre otros.

En nuestro caso, las flags de los desafios deberán introducirse con el formato:
```
flag{FlagEspecifica}
```

## Utilidades
Para ayudarnos a desencriptar los códigos, usaremos varias páginas webs. Entre ellas:

- [CyberChef](https://gchq.github.io/CyberChef/)

- [dCode](https://www.dcode.fr/), útil por su herramienta que nos indica una aproximación del sistema de encriptación usado. Muy útil cuando no sabemos como se ha encriptado nuestro mensaje.

- [hashes.com](https://hashes.com/en/decrypt/hash), enfocada sólo a Hashes.

## Challenge 1
En primer lugar, descargamos el archivo **challenge1.txt**, cuyo contenido es:

```
4C6120666C61672064656C206368616C6C656E67652065733A200A0A3261633337363438316165353436636436383964356239313237356433323465
```
Este desafío se resuelve traduciendo el contendido del archivo **challenge1.txt** del Hexadecimal.

![[c1_2.png]](/img/c1_2.png)

El resultado es:
```
La flag del challenge es: 

2ac376481ae546cd689d5b91275d324e
```

## Challenge 2

## Challenge 3
Descargamos el archivo **challenge3.txt**, cuyo contenido nos recuerda a como los sistemas UNIX almacenan la información referente a los usuarios del sistema.
![[c3_1.png]](/img/c3_1.png)

Como se nos pide la flag relativa al administrador, desencriptamos su hash.

![[c3_2.png]](/img/c3_2.png)

El resultado es:

```
iloveyou99!
```

## Challenge 4

## Challenge 5
