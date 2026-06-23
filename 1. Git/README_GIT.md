# README_GIT.md

# Git y GitHub

Este documento contiene los conceptos y comandos fundamentales de Git que utilizaremos durante la práctica.

El objetivo es aprender a trabajar con repositorios, ramas, cambios y control de versiones de forma similar a un entorno profesional.

---

# ¿Qué es Git?

Git es un sistema de control de versiones que permite:

* Registrar cambios en archivos.
* Mantener un historial de modificaciones.
* Trabajar en equipo sin sobrescribir el trabajo de otras personas.
* Recuperar versiones anteriores de un proyecto.

---

# ¿Qué es GitHub?

GitHub es una plataforma que permite almacenar repositorios Git en la nube.

Utilizaremos GitHub para:

* Compartir ejercicios.
* Descargar material.
* Entregar actividades.
* Mantener versiones de nuestro trabajo.

---

# Configuración inicial

Configurar nombre:

```bash
git config --global user.name "Nombre Apellido"
```

Configurar correo:

```bash
git config --global user.email "correo@ejemplo.com"
```

Verificar configuración:

```bash
git config --list
```

---

# Flujo básico de trabajo

## 1. Verificar estado

```bash
git status
```

Permite conocer qué archivos han sido modificados.

---

## 2. Agregar archivos

Agregar todos los cambios:

```bash
git add .
```

Agregar un archivo específico:

```bash
git add archivo.sql
```

---

## 3. Crear commit

```bash
git commit -m "Entrega ejercicio 01"
```

Un commit representa un punto de control en el historial del proyecto.

---

## 4. Enviar cambios

```bash
git push
```

O:

```bash
git push origin Branch_Leidy
```

---

## 5. Descargar cambios

```bash
git pull
```

---

# Trabajando con ramas

Ver ramas disponibles:

```bash
git branch
```

Cambiar de rama:

```bash
git checkout Branch_Leidy
```

Cambiar a main:

```bash
git checkout main
```

---

# Flujo recomendado para los ejercicios

1. Actualizar material desde `main`.
2. Cambiar a tu rama.
3. Resolver ejercicio.
4. Ejecutar:

```bash
git add .
git commit -m "Entrega ejercicio XX"
git push
```

5. Esperar revisión.

---

# Comandos más utilizados

## Estado actual

```bash
git status
```

## Ver historial

```bash
git log
```

Versión resumida:

```bash
git log --oneline
```

## Ver diferencias

```bash
git diff
```

## Ver ramas

```bash
git branch
```

## Descargar referencias remotas

```bash
git fetch
```

## Actualizar repositorio

```bash
git pull
```

---

# Buenas prácticas

✅ Realizar commits pequeños y frecuentes.

✅ Utilizar mensajes descriptivos.

✅ Mantener actualizada la rama principal.

✅ Revisar los cambios antes de realizar commit.

✅ Mantener organizada la estructura de carpetas.

---

# Ejercicios prácticos

## Ejercicio 1

Crear una carpeta llamada:

```text
Ejercicio_Git_01
```

Crear un archivo:

```text
README.md
```

Agregar una breve presentación personal.

Realizar commit y push.

---

## Ejercicio 2

Modificar el archivo anterior agregando:

* Ciudad
* Profesión
* Hobbies

Realizar commit y push.

---

## Ejercicio 3

Crear una carpeta:

```text
Ejercicio_Git_03
```

Agregar:

```text
notas.md
```

Escribir 5 comandos Git aprendidos.

Realizar commit y push.

---

## Ejercicio 4

Consultar el historial del repositorio utilizando:

```bash
git log --oneline
```

Tomar evidencia y guardarla como:

```text
evidencia_historial.png
```

Subir a la rama correspondiente.

---

# Recursos recomendados

## Learn Git Branching

Plataforma interactiva para aprender Git visualmente.

https://learngitbranching.js.org

Permite practicar:

* Commits
* Branches
* Merge
* Rebase
* Cherry-pick

Muy recomendada para comenzar.

---

## Git Practice

Ejercicios interactivos tipo laboratorio.

https://git-practice.com

Incluye más de 20 retos prácticos con validación automática.

---

## GitLearn

Curso gratuito con lecciones progresivas y simulador visual.

https://www.gitlearn.online

Muy útil para reforzar conceptos después de practicar los comandos básicos.

---

# Meta del módulo

Al finalizar este módulo deberás ser capaz de:

* Clonar un repositorio.
* Crear commits.
* Actualizar tu repositorio.
* Subir cambios.
* Trabajar en tu rama asignada.
* Entender el flujo básico de trabajo con Git y GitHub.
