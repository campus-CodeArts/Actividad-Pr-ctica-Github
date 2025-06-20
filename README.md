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

## Instrucciones paso a paso

```bash
# 1. Clona el repositorio
$ git clone git@github.com:campus-CodeArts/Actividad-Pr-ctica-Github.git
$ cd Actividad-Pr-ctica-Github

# 2. Crea tu rama personal con tu nombre
$ git checkout -b nombredelalumno

# 3. Edita plantilla.md y añade tu nombre en tu grupo
# Por ejemplo si estas en DAW y eres del grupo Koala, en plantilla.md añade tu nombre y grupo (Koala) en el apartado de DAW

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
