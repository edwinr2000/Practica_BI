# Ejercicios de Datos

Bienvenidos a esta práctica de datos.

Este repositorio será el espacio central para el desarrollo de ejercicios, consultas, material de estudio y proyectos prácticos relacionados con análisis de datos.

El objetivo de este repositorio es desarrollar habilidades prácticas en:

* Git y GitHub
* SQL
* DBeaver
* Visual Studio Code
* KNIME
* Buenas prácticas de documentación
* Trabajo colaborativo

---

# Estructura del repositorio

## Rama principal

La rama `main` contendrá:

* Material de estudio
* Guías
* Ejemplos
* Soluciones de referencia
* Scripts SQL
* Recursos complementarios
* Proyecto de conexión para DBeaver

**No se deben realizar entregas directamente sobre la rama `main`.**

A medida que avance el programa, se irán agregando nuevos recursos, ejercicios y material de apoyo a esta rama.

---

## Ramas para cargue de ejercicios

Cada persona dispone de una rama exclusiva para cargar sus ejercicios, desde donde serán revisados.

| Nombre  | Rama           |
| ------- | -------------- |
| Leidy   | Branch_Leidy   |
| David   | Branch_David   |
| Rubiela | Branch_Rubiela |

Todas las actividades, ejercicios y proyectos deberán tener su commit únicamente en la rama correspondiente.

---

# Instalación de herramientas

## 1. Git

### Windows

Descargar e instalar Git:

https://git-scm.com/download/win

Verificar instalación:

```bash
git --version
```

### Ubuntu

```bash
sudo apt update
sudo apt install git -y
```

Verificar:

```bash
git --version
```

---

## 2. DBeaver

Descargar:

https://dbeaver.io/download/

Instalar según el sistema operativo.

---

## 3. Visual Studio Code (Recomendado)

Descargar:

https://code.visualstudio.com/

Instalar según el sistema operativo.

Visual Studio Code será utilizado para:

* Edición de archivos SQL
* Edición de archivos Markdown (.md)
* Revisión de scripts
* Gestión de repositorios Git
* Documentación de ejercicios


---

## 4. KNIME

Descargar:

https://www.knime.com/downloads

Instalar según el sistema operativo.

KNIME será utilizado posteriormente para procesos ETL y automatización de flujos de datos.

---

# Configuración inicial de Git

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

# Acceso al repositorio

Antes de comenzar, debes enviarme el correo electrónico asociado a tu cuenta de GitHub.

Puedes verificar el correo configurado en Git ejecutando:

```bash
git config --global user.email
```

Una vez me compartas ese correo, te otorgaré permisos de colaboración sobre este repositorio para que puedas clonar, actualizar y cargar tus ejercicios en la rama asignada.

Si aún no tienes una cuenta de GitHub, deberás crear una antes de continuar.

---

# Clonar el repositorio

Ubicarse en la carpeta deseada.

Ejemplo:

```bash
cd Documentos
```

Clonar repositorio:

```bash
git clone URL_DEL_REPOSITORIO
```

Ingresar al repositorio:

```bash
cd NOMBRE_REPOSITORIO
```

Actualizar referencias:

```bash
git fetch
```

---

# Cambio a la rama asignada

## Leidy

```bash
git checkout Branch_Leidy
```

## David

```bash
git checkout Branch_David
```

## Rubiela

```bash
git checkout Branch_Rubiela
```

Verificar rama actual:

```bash
git branch
```

La rama activa aparecerá marcada con un asterisco (*).

---

# Configuración de DBeaver

Dentro de la rama `main` encontrarás una carpeta con el proyecto de DBeaver previamente configurado.

Pasos:

1. Clonar el repositorio.
2. Abrir DBeaver.
3. Seleccionar:

```text
File > Import
```

4. Importar el proyecto suministrado en la rama `main`.
5. Finalizar la importación.

El proyecto ya contiene la configuración necesaria para conectarse al entorno de prácticas.

Cuando se publiquen actualizaciones del proyecto o nuevas conexiones, bastará con actualizar la rama `main`.

---

# Uso de otros gestores

Si prefieres utilizar otro cliente de base de datos como:

* Beekeeper Studio
* DataGrip
* Azure Data Studio
* pgAdmin
* Otro

Comunícate conmigo para revisar la configuración correspondiente.

---

# Actualizar material desde la rama main

Antes de iniciar un nuevo ejercicio es recomendable actualizar el material disponible en la rama principal.

Cambiar a la rama main:

```bash
git checkout main
```

Actualizar:

```bash
git pull origin main
```

Regresar a tu rama:

```bash
git checkout Branch_Leidy
```

> Reemplaza el nombre de la rama según corresponda.

---

# Entrega de ejercicios

Cada actividad deberá entregarse únicamente en la rama asignada.

Agregar cambios:

```bash
git add .
```

Crear commit:

```bash
git commit -m "Entrega ejercicio joins"
```

Enviar cambios:

```bash
git push origin Branch_Leidy
```

Modificar el nombre de la rama según corresponda.

---

# Estructura recomendada para ejercicios

```text
Ejercicio_01/
├── solucion.sql
├── evidencia.png
└── notas.md
```

Ejemplo:

```text
Ejercicio_05_Joins/
├── solucion.sql
├── evidencia.png
└── notas.md
```

### Descripción de archivos

**solucion.sql**

Contiene la solución SQL desarrollada para el ejercicio.

**evidencia.png**

Captura de pantalla mostrando el resultado obtenido.

**notas.md**

Comentarios, observaciones o explicación de la solución implementada.

---

# Observaciones

1. No realizar cambios directamente sobre la rama `main`.
2. Solo cargar ejercicios en la rama asignada.
3. Mantener nombres descriptivos para carpetas y archivos.
4. Realizar commits con mensajes claros.
5. Antes de iniciar un nuevo ejercicio, actualizar los cambios desde la rama `main`.
6. Mantener actualizado el acceso a GitHub.
7. Verificar que el correo configurado en Git corresponda a la cuenta de GitHub utilizada.
8. Revisar periódicamente la rama `main`, ya que allí se publicarán nuevos ejercicios, material de apoyo y recursos adicionales.

---

# Temario General

## Módulo 1 - Git y GitHub

* ¿Qué es Git?
* ¿Qué es GitHub?
* Repositorios
* Clone
* Pull
* Push
* Commit
* Branches
* Resolución básica de conflictos
* Buenas prácticas

---

## Módulo 2 - SQL Básico

* SELECT
* WHERE
* ORDER BY
* LIMIT
* DISTINCT
* Funciones básicas
* Alias

---

## Módulo 3 - SQL Intermedio

* GROUP BY
* HAVING
* CASE
* JOIN
* UNION
* Subconsultas

---

## Módulo 4 - SQL Avanzado

* CTE
* Window Functions
* Optimización básica
* Modelado relacional
* Integridad referencial

---

## Módulo 5 - Bases de Datos

* Tablas
* Relaciones
* Llaves primarias
* Llaves foráneas
* Índices
* Vistas
* Buenas prácticas de modelado

---

## Módulo 6 - KNIME

* Introducción
* Lectura de archivos
* Transformación de datos
* Integración con bases de datos
* Automatización de flujos
* Exportación de resultados

---

## Módulo 7 - Proyecto Final

Desarrollo de una solución completa utilizando:

* SQL
* Git
* GitHub
* DBeaver
* Visual Studio Code
* KNIME

Simulando un entorno real de trabajo.

**Tema:** To be defined.
