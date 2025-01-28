# CREAR REPOSITORIOS

# Crear una carpeta para el proyecto
mkdir nombre-del-proyecto
cd nombre-del-proyecto

# Inicializar un repositorio local
git init

# Crear un archivo README (opcional)
echo "# Mi nuevo repositorio" >> README.md

# Agregar los archivos al área de staging
git add .

# Crear el commit inicial
git commit -m "Primer commit: Inicialización del repositorio"

# Conectar el repositorio local con GitHub
git remote add origin https://github.com/usuario/nombre-del-repositorio.git

# Subir los cambios al repositorio remoto
git branch -M main
git push -u origin main


# ACTUALIZAR CAMBIOS

'''
git status  # Verifica los cambios realizados
git add .   # Agrega los cambios al área de staging
git commit -m "Descripción de los cambios realizados"  # Guarda los cambios localmente
git pull origin main --rebase  # Sincroniza con el remoto para evitar conflictos
git push origin main  # Sube los cambios al repositorio remoto


'''

# Clonar el repositorio
git clone https://github.com/JCPB2000/PROGRAMAR.git

# Entrar en la carpeta del repositorio
cd PROGRAMAR

# Abrir el repositorio en Visual Studio Code
code .


