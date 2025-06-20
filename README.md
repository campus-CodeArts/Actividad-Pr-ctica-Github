# Actividad práctica: Presentaciones vía Pull Request

## Objetivo
Cada alumno aprenderá a:
- Clonar un repositorio desde GitHub
- Crear una nueva rama
- Hacer cambios en un archivo de plantilla
- Subir los cambios con `git push`
- Crear un Pull Request
- Ver sus cambios integrados en `main`

---

## Archivos del repositorio

### `README.md`

```md
# Presentaciones de alumnos – Curso de prácticas

Este repositorio está destinado a practicar Git y GitHub mediante la creación de ramas y pull requests.

Cada alumno debe:

1. Clonar este repositorio
2. Crear una rama con su nombre
3. Añadir su presentación en el archivo `plantilla.md`
4. Subir los cambios y crear un Pull Request

---

Recuerda añadirte en tu grupo correspondiente y en orden alfabético por nombre.
```

### `plantilla.md`

```md
# Presentaciones de alumnos

## DAW
<!-- Añade aquí tu nombre si estás en DAW -->

## DAM
<!-- Añade aquí tu nombre si estás en DAM -->

## SMR
<!-- Añade aquí tu nombre si estás en SMR -->

## ASIR
<!-- Añade aquí tu nombre si estás en ASIR -->
```

---

## Instrucciones paso a paso para los alumnos

```bash
# 1. Clona el repositorio
$ git clone https://github.com/<tu-org>/presentaciones.git
$ cd presentaciones

# 2. Crea tu rama personal
$ git checkout -b presentacion-tu-nombre

# 3. Edita plantilla.md y añade tu nombre en tu grupo

# 4. Añade y haz commit de los cambios
$ git add plantilla.md
$ git commit -m "Añadida presentación de Nombre Apellido (DAW)"

# 5. Sube tu rama a GitHub
$ git push origin presentacion-tu-nombre

# 6. Abre un Pull Request desde GitHub
```

---

## Notas importantes

- No modifiques otras partes del archivo.
- Mantén el orden alfabético por grupo.
- Espera a que el profesor revise y apruebe tu PR.

---

Buena suerte
