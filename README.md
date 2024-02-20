- [😎 Sintaxis de Markdown](#-sintaxis-de-markdown)
    - [Caracteres especiales:](#caracteres-especiales)
    - [Tablas:](#tablas)
    - [El resultado será el siguiente:](#el-resultado-será-el-siguiente)
  - [|3. Row| aligned | centered | aligned  |](#3-row-aligned--centered--aligned--)
    - [Imágenes con enlace: existe la posibilidad de combinar imágenes y enlaces de la siguiente manera:](#imágenes-con-enlace-existe-la-posibilidad-de-combinar-imágenes-y-enlaces-de-la-siguiente-manera)
  - [](#)
    - [Líneas separadoras o regla horizontales: Nos permiten separar un contenido de otro. Vamos a ver un ejemplo:](#líneas-separadoras-o-regla-horizontales-nos-permiten-separar-un-contenido-de-otro-vamos-a-ver-un-ejemplo)
      - [Líneas separadoras escrita sin espacios (se verá igual que la otra)](#líneas-separadoras-escrita-sin-espacios-se-verá-igual-que-la-otra)
      - [Líneas separadoras escrita con espacios (se verá igual que la otra)](#líneas-separadoras-escrita-con-espacios-se-verá-igual-que-la-otra)

# 😎 Sintaxis de Markdown


### Caracteres especiales:  
Si queremos escribir los conodios como caracteres especiales como son:  
`  acento invertido  
\*  asterisco  
_  guión bajo  
{} llaves  
[] corchetes  
() paréntesis  
\#  almohadilla  
\+  símbolo de suma    
\-  guión  
.  punto  
!  exclamación

---

### Tablas:
A parte de las tabla de contenido que acabamos de ver también podemos realizar tablas sin que estás seas de contenido. Vamos a ver un ejemplo:
```
|Header |Column 1 | Column 2 | Column 3  |
|:--- |:---- |:----:| ----:|
|1. Row| is | is | is  |
|2. Row| left | nicely | right  |
|3. Row| aligned | centered | aligned  |
```
---
### El resultado será el siguiente:
---
|Header |Column 1 | Column 2 | Column 3  |
|:--- |:---- |:----:| ----:|
|1. Row| is | is | is  |
|2. Row| left | nicely | right  |
|3. Row| aligned | centered | aligned  |
---
### Imágenes con enlace: existe la posibilidad de combinar imágenes y enlaces de la siguiente manera:
---
```
[![a](https://www.google.es/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png)](www.google.es)
```
---

[![a](https://www.google.es/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png)](www.google.es)
---

### Líneas separadoras o regla horizontales: Nos permiten separar un contenido de otro. Vamos a ver un ejemplo:
```
## Líneas separadoras escrita sin espacios (se verá igual que la otra)
Contenido 1
*** 
Contenido 2
---
Contenido 3
___
## Líneas separadoras escrita con espacios (se verá igual que la otra)
Contenido 1
* * *
Contenido 2
- - -
Contenido 3
_ _ _
```
#### Líneas separadoras escrita sin espacios (se verá igual que la otra)

Contenido 1
*** 

Contenido 2

---

Contenido 3
___

#### Líneas separadoras escrita con espacios (se verá igual que la otra)

Contenido 1
* * *

Contenido 2
- - -

Contenido 3
_ _ _