# Libft - Mi Primera Librería en C

## 🔮 Descripción
Libft es una librería personalizada escrita en C que implementa una serie de funciones esenciales que serán de gran utilidad a lo largo del cursus. Este proyecto te ayudará a comprender mejor el funcionamiento de las funciones estándar de C, a implementarlas y a utilizarlas eficientemente.

## 📖 Instrucciones Generales
- El proyecto debe estar escrito en **C**.
- Debe seguir la **Norma** estrictamente.
- No se permiten **segfaults, memory leaks, ni comportamientos inesperados**.
- Toda la memoria asignada en el heap debe liberarse adecuadamente.
- Se debe entregar un **Makefile** con las siguientes reglas:
  - `$(NAME)`, `all`, `clean`, `fclean`, `re`.
- El Makefile debe compilar los archivos con las flags:
  ```sh
  -Wall -Werror -Wextra
  ```
- Se debe utilizar `ar` para generar la librería (`libft.a`). **El uso de libtool está prohibido**.
- Se recomienda crear programas de prueba para verificar el funcionamiento de las funciones.

## 🔨 Estructura del Proyecto
```
/
├── Makefile
├── libft.h
├── ft_*.c
├── bonus/
│   ├── ft_*.c
│   ├── ft_*.h
```

## 💡 Consideraciones Técnicas
- **No se permiten variables globales**.
- Si una función es muy compleja, divídela en funciones auxiliares marcadas como `static`.
- No se deben entregar archivos no utilizados.
- Si el proyecto permite el uso de Libft en otros proyectos, se debe incluir su código fuente en un directorio `libft/` con su propio Makefile.

## 🌟 Bonus
Para entregar los bonus del proyecto, se debe incluir una regla `bonus` en el Makefile. Los archivos de bonus deben estar en archivos separados y con la nomenclatura `*_bonus.{c/h}`.

## 📝 Entrega
- El proyecto se debe subir al repositorio Git asignado.
- Solo el contenido del repositorio será evaluado.
- Deepthought podrá evaluar el trabajo después de la evaluación entre compañeros.

---
🚀 **Comienza tu viaje en C con Libft y mejora tus habilidades!**

