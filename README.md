# 📚 Libft – Mi primera librería en C

Libft es una librería personalizada escrita en C como parte de mi primer proyecto en 42.
Implementa funciones esenciales que amplían las capacidades de la librería estándar de C,
facilitando la manipulación de cadenas, memoria y listas enlazadas.

## 🚀 Características
- Funciones de manipulación de strings (`ft_strlen`, `ft_strcpy`, `ft_strdup`...).
- Manejo de memoria (`ft_memset`, `ft_memcpy`, `ft_memalloc`...).
- Funciones matemáticas y de conversión (`ft_atoi`, `ft_isalpha`, `ft_tolower`...).
- Listas enlazadas (`ft_lstnew`, `ft_lstadd`, `ft_lstdelone`...).

## 🛠️ Compilación e instalación
Para compilar la librería, ejecuta:
```bash
make
```
Esto genera un archivo libft.a que puedes incluir en tus proyectos con:
```C
#include "libft.h"
