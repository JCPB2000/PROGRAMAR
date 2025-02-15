 # CREAR REPOSITORIOS
```
# Crear una carpeta para el proyecto
git remote remove origin  
git remote add origin https://github.com/JCPB2000/biblioteca.git  
git remote -v  
git branch -M main  
git pull origin main --rebase  
git push -u origin main  


# Conectar el repositorio local con GitHub
git remote add origin https://github.com/usuario/nombre-del-repositorio.git

# Subir los cambios al repositorio remoto
git branch -M main
git push -u origin main
```

# ACTUALIZAR CAMBIOS

```
git status  # Verifica los cambios realizados
git add .   # Agrega los cambios al área de staging
git commit -m "Descripción de los cambios realizados"  # Guarda los cambios localmente
git pull origin main --rebase  # Sincroniza con el remoto para evitar conflictos
git push origin main  # Sube los cambios al repositorio remoto
```

# Clonar el repositorio
```
git clone https://github.com/JCPB2000/PROGRAMAR.git

# Entrar en la carpeta del repositorio
cd PROGRAMAR

# Abrir el repositorio en Visual Studio Code
code .

```

# PARA ESTRUCTURAR GITHUB
```
https://pandao.github.io/editor.md/en.html
```

# PARA ACTUALIZAR CAMBIOS CUANDO SE MUEVE CARPETAS
```
git add -A
git commit -m "Agregando cambios en el directorio PROGRAMAR"
git pull origin main --rebase
git push origin main

```
