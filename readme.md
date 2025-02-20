# Ejercicio dos
1. **Primer paso**
   - Crear un repositorio remoto, en nuestro caso usaremos github.  
  
2. **Segundo paso paso**
   - Clonar el respositorio remoto en local:
  ![Este contenido se mostrará cuando la imagen no se pueda cargar, como texto alternativo](./img/1.png "Paso 2")
  
3. **Tercer Paso**
    - dirigirnos al repositorio que hemos clonado y abrirlo en *vsCode*.

4. **Cuarto Paso**
   - Crear el archivo readme, añadirlo con *git add*,  realizar el *commit* en local y realizar el *push* al repositorío remoto.
      ![Este contenido se mostrará cuando la imagen no se pueda cargar, como texto alternativo](./img/2.png "Paso 4")

## Tabla de principales comandos de git:

|Comando Git | ¿Qué hace? | lifecycle |
|:--- |:----: |:----:| 
|  **git config --global --list**   | Muestra la configuración global actual |  |
|  **git init**   | Inicializa un nuevo repositorio Git en el directorio actual. | |
|   **git clone**  | Clona un repositorio existente desde una URL. |  |
|   **git status**  | Muestra el estado de los archivos en el directorio de trabajo |  |
|   **git add**  | Agrega un archivo específico al área de preparación. | Staging |
|   **git commit -m**  | Crea un nuevo commit con los cambios en el área de preparación. | Commits |
|   **git add**  | Agrega un archivo específico al área de preparación. | Staging |








Revisión de Historial
Log (Historial)

sh
git log
Muestra el historial de commits del repositorio.

Diferencias

sh
git diff
Muestra las diferencias entre el directorio de trabajo y el área de preparación.

sh
git diff <commit1> <commit2>
Muestra las diferencias entre dos commits.

Sincronización con Repositorio Remoto
Fetch (Obtener)

sh
git fetch
Obtiene los cambios del repositorio remoto sin fusionarlos.

Pull (Actualizar)

sh
git pull
Obtiene y fusiona los cambios del repositorio remoto.

Push (Subir)

sh
