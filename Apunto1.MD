
```markdown
# Informe de Actividades en el Directorio Documents

## Navegación y Operaciones en XYZ

1. **Navegación a Documents:**
   ```bash
   $ cd Documents
```

2. **Creación de Directorios en XYZ:**

   ```bash
   $ cd XYZ
   $ mkdir Prueba
   $ mkdir Test
   ```
3. **Listado de Contenido en XYZ:**

   ```bash
   $ ls
   Archivo.txt  Prueba/  Test/
   ```
4. **Navegación al Directorio Prueba:**

   ```bash
   $ cd Prueba
   ```
5. **Listado de Contenido en Prueba (Vacío):**

   ```bash
   $ ls
   ```
6. **Intento de Navegación a XYZ (Error):**

   ```bash
   $ cd XYZ
   bash: cd: XYZ: No such file or directory
   ```
7. **Retroceso al Directorio Principal de XYZ:**

   ```bash
   $ cd ..
   ```
8. **Listado de Contenido en XYZ:**

   ```bash
   $ ls
   Archivo.txt  Prueba/  Test/
   ```
9. **Vuelta al Directorio Principal:**

   ```bash
   $ cd
   ```
10. **Intento de Navegación a Test (Error):**

    ```bash
    $ cd Test
    bash: cd: Test: No such file or directory
    ```
11. **Listado de Contenido en Documents:**

    ```bash
    $ ls
    ABCDE                  PRO2React.rar
    Arduino               'Plantillas personalizadas de Office'
    CARACTERISTICAS.docx  TodoReact
    'DOP. (1).pdf'        'Virtual Machines'
    ListaTarea             WEB.pdf
    'Mi música'            XYZ
    'Mis imágenes'         desktop.ini
    'Mis vídeos'           index.html
    NetBeansProjects       package-lock.json
    PC.docx                s01_herraminetas.txt
    PFinal                '~$RACTERISTICAS.docx'
    PRO2React
    ```

## Operaciones en XYZ y Configuración Git

12. **Navegación a XYZ:**

    ```bash
    $ cd XYZ
    ```
13. **Listado de Contenido en XYZ:**

    ```bash
    $ ls
    Archivo.txt  Prueba/  Test/
    ```
14. **Eliminación del Directorio Prueba:**

    ```bash
    $ rmdir Prueba
    ```
15. **Intento Incorrecto de Eliminar Archivo.txt:**

    ```bash
    $ mrdir Archivo.txt
    bash: mrdir: command not found
    ```
16. **Intento Incorrecto de Eliminar Archivo.txt (Otra Forma):**

    ```bash
    $ remove Archivo.txt
    bash: remove: command not found
    ```
17. **Regreso al Directorio Principal de Documents:**

    ```bash
    $ cd ..
    ```
18. **Configuración Global de Usuario y Correo en Git:**

    ```bash
    $ git config --global user.name "Gtav"
    $ git config --global user.email "demk@gmail.com"
    ```
19. **Verificación de Configuración de Usuario Git:**

    ```bash
    $ git config user.name
    Gtav
    ```
20. **Verificación de Configuración de Correo Git (Error):**

    ```bash
    $ git config user.email
    fatal: not in a git directory
    ```

```

```
