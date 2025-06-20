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
$ git checkout -b rama/nombredelalumno

# 3. Edita plantilla.md y añade tu nombre en tu grupo
# Por ejemplo si estas en DAW y eres del grupo Koala, en plantilla.md añade tu nombre y grupo (Koala) en el apartado de DAW

# 4. Añade y haz commit de los cambios
$ git add plantilla.md
$ git commit -m "Añadida presentación de Nombre Apellido (DAW)"

# 5. Sube tu rama a GitHub
$ git push origin rama/nombredelalumno

# 6. Abre un Pull Request y haz merge a main
1. Ve al repositorio en GitHub.
2. GitHub te mostrará un botón para comparar y crear un Pull Request ("Compare & pull request"). Haz clic ahí.
3. Asegúrate de que estás comparando tu rama con `main`.
4. Añade un título claro y una descripción si lo deseas.
5. Haz clic en "Create pull request".
6. Una vez creado el Pull Request, haz clic en el botón verde "Merge pull request".
7. Confirma haciendo clic en "Confirm merge".
```

---

## Notas importantes

- No modifiques otras partes del archivo.
- Mantén el orden alfabético por grupo.
- Espera a que el profesor revise y apruebe tu PR.

---

Buena suerte
