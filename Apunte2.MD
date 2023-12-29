Entiendo, aquí tienes un informe de los comandos utilizados y una breve descripción de sus acciones:

---

# Informe de Actividades en el Repositorio WebTools

## Creación y Configuración Inicial del Repositorio

1. **Creación del Directorio WebTools:**

   ```bash
   mkdir WebTools
   cd WebTools
   git init
   ```

   Se crea un directorio llamado WebTools y se inicializa un repositorio Git dentro de él.
2. **Configuración del Nombre de Usuario Global:**

   ```bash
   git config --global user.name "NIIIC7"
   ```

   Se configura el nombre de usuario global para los commits.
3. **Configuración del Correo Electrónico Global:**

   ```bash
   git config --global user.email "U21318040@UTP.EDU.PE"
   ```

   Se configura el correo electrónico global para los commits.
4. **Configuración del Editor de Texto para Commits:**

   ```bash
   git config --global core.editor "code --wait"
   ```

   Se configura Visual Studio Code como el editor para mensajes de commit.
5. **Cambio del Nombre de la Rama Predeterminada a "main":**

   ```bash
   git config --global init.defaultBranch main
   ```

   Se cambia el nombre de la rama predeterminada de "master" a "main".
6. **Creación de Archivos y Primer Commit:**

   ```bash
   git add *
   git commit -m "archvio de respaldo"
   ```

   Se crean archivos y se realiza el primer commit.

## Conexión con Repositorio Remoto en GitHub

7. **Configuración del Repositorio Remoto en GitHub:**

   ```bash
   git remote add origin https://github.com/NIIIC7/WebTools.git
   ```

   Se establece la conexión con un repositorio remoto en GitHub.
8. **Push Inicial al Repositorio Remoto:**

   ```bash
   git push -u origin master
   ```

   Se envían los commits iniciales al repositorio remoto.

## Gestión de Commits y Ramas

9. **Creación de Nuevos Archivos y Commits Adicionales:**

   ```bash
   git add *
   git commit -m "frm"
   git add *
   git commit -m "xxx"
   ```

   Se crean nuevos archivos y se realizan commits adicionales.
10. **Reversión de Commits Locales:**

```bash
   git reset --soft HEAD~1
```

   Se revierten los últimos commits locales manteniendo los cambios en el directorio de trabajo.

11. **Push de Cambios Revertidos al Repositorio Remoto:**

```bash
   git push -u origin master
```

   Se envían los cambios revertidos al repositorio remoto.

## Creación de Informe de Actividades

12. **Generación de Informe de Actividades:**

```
   git log
```

   Se muestra el historial de commits para incluir en el informe.

13. **Adición de Archivo para el Informe:**

```bash
   touch xvid.txt
   git add xvid.txt
   git commit -m "GAAAAAAAAAAAA"
```

   Se crea un archivo y se realiza un commit para incluir en el informe.

14. **Edición de Commit Anterior:**

```bash
   git commit --amend -m "LUCHOTOOTTOTOTOOTOGT"
```

   Se realiza una edición al commit anterior.

---

Este informe resume las principales acciones realizadas en el repositorio WebTools hasta el momento. Puede imprimirse o presentarse según sea necesario.
