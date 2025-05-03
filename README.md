<!---banner--->

<h1 align="center">
 🚀 Printf
</h1>

<p align="center">
 <img src="https://res.cloudinary.com/dzo1cimyr/image/upload/v1746288764/pushswap_yuaoqq.gif"/>
</p>

> **Recréation de la fonction `printf` en C**

Ce projet consiste à réimplémenter la fonction standard `printf` de la bibliothèque C, en respectant les normes de l'école 42. L'objectif est de comprendre la gestion des arguments variables, la manipulation de chaînes, et l'affichage formaté en C.

## ✨ Fonctionnalités

- Gestion des types :
  - `%c` : caractère
  - `%s` : chaîne de caractères
  - `%d` / `%i` : entier signé
  - `%u` : entier non signé
  - `%x` / `%X` : hexadécimal (minuscule/majuscule)
  - `%p` : pointeur
  - `%%` : pourcentage
- Retourne le nombre de caractères affichés (comme l'originale)
- Gestion de l'affichage de `(null)` pour les chaînes NULL

## 🗂️ Structure du projet

```
├── ft_printf.c      # Fonction principale et parsing
├── ft_printf.h      # Header du projet
├── basicf.c         # Fonctions utilitaires (putchar, putstr, putnbr...)
├── fsupp.c          # Fonctions de support (hexa, print_ptr...)
├── Makefile         # Compilation
```

## 🚀 Compilation

```sh
make
```


## 🔥 Utilisation

Inclure le header dans votre projet :
```c
#include "ft_printf.h"
```

Exemple :
```c
ft_printf("Hello %s! You have %d messages.\n", "world", 42);
```

## 🛠️ Technologies & Langages

<p align="center">
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" alt="C"/> <img src="https://img.shields.io/badge/Makefile-000000?style=for-the-badge&logo=gnu&logoColor=white" alt="Makefile"/> <img src="https://img.shields.io/badge/42-000000?style=for-the-badge&logo=42&logoColor=white" alt="42"/>
</p>

---
