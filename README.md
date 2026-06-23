# Programa de Formación en Datos

Bienvenidos al programa de formación en análisis y gestión de datos.

El objetivo de este repositorio es desarrollar habilidades prácticas en:

* Git y GitHub
* SQL
* PostgreSQL
* DBeaver
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
* Bases de datos
* Scripts SQL
* Recursos complementarios

**No se deben realizar entregas directamente sobre la rama `main`.**

---

## Ramas de estudiantes

Cada estudiante dispone de una rama exclusiva para sus entregas:

| Estudiante | Rama           |
| ---------- | -------------- |
| Leidy      | Branch_Leidy   |
| David      | Branch_David   |
| Rubiela    | Branch_Rubiela |

Todas las actividades, ejercicios y proyectos deberán publicarse únicamente en su rama correspondiente.

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

## 3. PostgreSQL

No es obligatorio instalar PostgreSQL localmente.

Se proporcionará una base de datos compartida para los ejercicios.

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

Verificar:

```bash
git config --list
```

---

# Clonar el repositorio

Ubicarse en la carpeta deseada.

Ejemplo:

```bash
cd Documentos
```

Clonar:

```bash
git clone URL_DEL_REPOSITORIO
```

Ingresar:

```bash
cd NOMBRE_REPOSITORIO
```

Actualizar información:

```bash
git fetch
```

---

# Cambio a la rama personal

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

La rama activa aparecerá con un asterisco (*).

---

# Base de datos PostgreSQL

Se proporcionarán los siguientes datos:

Servidor:

```text
PENDIENTE
```

Puerto:

```text
5432
```

Base de datos:

```text
PENDIENTE
```

Usuario:

```text
PENDIENTE
```

Contraseña:

```text
PENDIENTE
```

---

# Configuración en DBeaver

Crear nueva conexión:

```text
PostgreSQL
```

Completar:

* Host
* Puerto
* Base de datos
* Usuario
* Contraseña

Probar conexión.

Guardar.

---

# Uso de otros gestores

Si desea utilizar otro gestor de base de datos diferente a DBeaver:

* DataGrip
* pgAdmin
* Azure Data Studio
* Beekeeper Studio
* Otro

Debe solicitar la cadena de conexión al instructor.

---

# Entrega de ejercicios

Cada actividad deberá entregarse en la rama correspondiente.

Ejemplo:

```bash
git add .
```

```bash
git commit -m "Entrega ejercicio joins"
```

```bash
git push origin Branch_Leidy
```

(Modificar el nombre de la rama según corresponda.)

---

# Estructura recomendada para ejercicios

```text
Ejercicio_01/
├── solucion.sql
├── evidencia.png
└── notas.md
```

---

# Reglas del curso

1. No realizar cambios en la rama main.
2. Todas las entregas deben realizarse en la rama personal.
3. Documentar dudas y observaciones.
4. Mantener nombres descriptivos en commits.
5. Subir evidencias cuando se soliciten.
6. Consultar antes de modificar estructuras compartidas.
7. Resolver los ejercicios individualmente.

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

## Módulo 5 - PostgreSQL

* Tipos de datos
* Creación de tablas
* Constraints
* Índices
* Vistas

---

## Módulo 6 - KNIME

* Introducción
* Lectura de archivos
* Transformación de datos
* Integración con PostgreSQL
* Automatización de flujos
* Exportación de resultados

---

## Módulo 7 - Proyecto Final

Desarrollo de una solución completa utilizando:

* PostgreSQL
* SQL
* Git
* GitHub
* KNIME

Simulando un entorno real de trabajo.
