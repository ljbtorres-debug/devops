# Guía de Comandos Git
## Configuración inicial
```bash
git config --global user.name "Tu Nombre"
git config --global user.email "correo@example.com"
```

## Ver configuración actual:
```bash
git config --list
```
# Crear repositorio
Inicializar Git:
```bash
git init
```
Clonar repositorio:
```bash
git clone URL_DEL_REPOSITORIO
```
# Estado y seguimiento
Ver estado del proyecto:
```bash
git status
```
Agregar archivo específico:
```bash
git add archivo.txt
```
Agregar todos los archivos:
```bash
git add .
```
# Commits
Crear commit:
```bash
git commit -m "mensaje del commit"
```
Agregar y commitear rápidamente:
```bash
git commit -am "mensaje"
```
Ver historial:
```bash
git log
```
Historial resumido:
```bash
git log --oneline
```
# Ramas
Ver ramas:
```bash
git branch
```
Crear rama:
```bash
git branch nombre-rama
```
Cambiar de rama:
```bash
git checkout nombre-rama
```
Crear y cambiar:
```bash
git checkout -b nombre-rama
```
Eliminar rama:
```bash
git branch -d nombre-rama
```
# Sincronización con GitHub
Conectar repositorio remoto:
```bash
git remote add origin URL
```
Ver remotos:
```bash
git remote -v
```
Subir cambios:
```bash
git push 
```
```bash
git push -u origin nombre-rama
```
Bajar cambios:
```bash
git pull 
```
```bash
git pull origin nombre-rama
```
# Actualizar repositorio
Descargar cambios sin fusionar:
```bash
git fetch
```