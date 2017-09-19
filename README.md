# Platzom

Platzom es un idioma inventado para el [Curso de Fundamentos de JavaScript](https://platzi.com/js) de [Platzi](https://platzi.com).

## Descripción del Idioma

- Si la palabra termina en "ar", se le quitan esos dos caracteres
- Si la palabra inicia con z, se le añade "pe" al final
- Si la palabra traducida, tiene 10 o más letras,
se debe partir a la mitad y unir con un guión medio.
- Si la palabra original es un palíndromo,
ninguna regla anterior cuenta y de devuelve la misma palabra intercalando mayusculas y minusculas

## Instalación

```
npm install platzom
```
import platzom from 'platzom'

platzom("Programar") // Program
platzom("Zorro") // Zorrope
platzom("Zarpar") // Zarppe
platzom("abecedario") // abece-diario
platzom("sometemos") // SoMeTeMoS
```

## Créditos
- Edgar Arce

## Licencia
[MIT](https://opensource.org/licenses/MIT)
