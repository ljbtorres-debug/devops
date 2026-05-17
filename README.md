# Guía de Comandos Git
## Configuración inicial
```bash
git config --global user.name "Tu Nombre"
git config --global user.email "correo@example.com"
```
Ver configuración actual:

git config --list (Sirve para ver que es lo que tenemos configurado)

Crear repositorio
Inicializar Git:

git init (Inicializar el repositorio) 1

Clonar repositorio:

git clone URL_DEL_REPOSITORIO
Estado y seguimiento
Ver estado del proyecto:

git status
Agregar archivo específico:

git add archivo.txt  (Sirve capturar los cambios que deseo subir de un solo archivo)
Agregar todos los archivos:

git add . (Captura de todos los cambios de todos los archivos) 2
Commits
Crear commit:

git commit -m "mensaje del commit" (Este da un comentario) 4
Agregar y commitear rápidamente:

git commit -am "mensaje"
Ver historial:

git log
Historial resumido:

git log --oneline
Ramas
Ver ramas:

git branch
Crear rama:

git branch nombre-rama
Cambiar de rama:

git checkout nombre-rama
Crear y cambiar:

git checkout -b nombre-rama
Eliminar rama:

git branch -d nombre-rama
Sincronización con GitHub
Conectar repositorio remoto:
git remote add origin URL  (Especifica y se conecta con el repo) 3
Ver remotos:

git remote -v
Subir cambios:

git push (Subir cambios a la rama en la que me encuetra) 
git push -u origin nombre-rama (Me actualiza una rama especifica/ en caso de no tener una rama el push original no a funcioar y usamos este) 5
Bajar cambios:

git pull 
git pull origin nombre-rama
Actualizar repositorio
Descargar cambios sin fusionar:

git fetch
Fusionar ramas:

git merge nombre-rama
