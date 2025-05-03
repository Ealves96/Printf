<div align="center">
  <img src="https://raw.githubusercontent.com/ayogun/42-project-badges/main/covers/cover-ft_printf.png" alt="ft_printf banner" width="600"/>
  <br>
  <a href="https://profile.intra.42.fr/users/ealves" target="_blank">
    <img alt="42" src="https://img.shields.io/badge/42-Paris-black?style=flat&logo=42&logoColor=white"/>
  </a>
  <img src="https://img.shields.io/badge/score-125%20%2F%20100-success?color=%2312bab9&style=flat" />
  <img src="https://img.shields.io/badge/status-finished-brightgreen?style=flat" />
  <img src="https://img.shields.io/github/languages/top/ealves/ft_printf?style=flat" />
</div>

---

# ft_printf

> **Recréation de la fonction `printf` en C**

Ce projet consiste à réimplémenter la fonction standard `printf` de la bibliothèque C, en respectant les conventions de l'école 42. L'objectif est de comprendre la gestion des arguments variables, la manipulation de chaînes, et l'affichage formaté en C.

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

Cela génère la librairie statique `libftprintf.a`.

Pour nettoyer les fichiers objets :
```sh
make clean
```
Pour tout nettoyer (objets + librairie) :
```sh
make fclean
```
Pour recompiler :
```sh
make re
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

## 🧪 Tests

Vous pouvez tester la fonction avec vos propres fichiers ou en utilisant des outils comme [Francinette](https://github.com/xicodomingues/francinette).

## 📚 Ressources
- [Man printf(3)](https://man7.org/linux/man-pages/man3/printf.3.html)
- [va_list documentation](https://en.cppreference.com/w/c/variadic)

---

## 🛠️ Technologies & Langages

<p align="center">
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" alt="C"/>
  <img src="https://img.shields.io/badge/Makefile-000000?style=for-the-badge&logo=gnu&logoColor=white" alt="Makefile"/>
  <img src="https://img.shields.io/badge/42-000000?style=for-the-badge&logo=42&logoColor=white" alt="42"/>
</p>

---

<div align="center">
  <img src="https://raw.githubusercontent.com/ayogun/42-project-badges/main/badges/ft_printfe.png" alt="ft_printf badge" width="120"/>
</div> 