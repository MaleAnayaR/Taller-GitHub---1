# Taller-GitHub---1
Práctica de lo aprendido con Jullie Allen
Marzo 10 del 2026
1. Abrimos una cuenta en GitHub
2. Descargamos GitBash
3. Creamos un token de seguridad
4. Conectamos nuestra cuenta de GitHUb con la cuenta de GitBash
5. Hicimos una mini actividad para aprende del terminal
Marzo 17 del 2026
1. git --version: es para ver la versión en la q esta el computador
2. En caso de q no aparezca la version:
      git is /usr/local/bin/git
      git is /usr/bin/git
Estas son las diferentes carpetas donde esta git. La primera línea es la q automáticamente se usa, 
esa es la versión q se esta usando. En caso tal de q no sea la reciente, descarguela:
      https://git-scm.com/download/win
Instalarlo con las opciones por defecto. (Si	ya	descargó	la	última	versión,	
pero	aún	su	computador	no	la	está	utilizando	como	primera	
opción,	ayúdese	de	ChatGPT	para	lograrlo)

3. Para confirmar si está configurar su cuenta de git en el computador:
     git config --global --list
 Si no lo esta, utilizar lo siguiente:
     git config --global user.name "..."
     git config --global user.email "..." 
4. Para normalizar los saltos de línea automáticamente:
     git config --global core.autocrlf true
 Ahora para confirmar la configuración de este:
     git config --global --list

5. Para clonar el repositorio en el computador:
   - Entrar a GitHub, estar dentro del repositorio, hacer click en "Code" y copiar el URl
   - Se pega: 
     git clone https://..... (Esto descarga el repositorio en el pc)
6. Para entrar en el, se utiliza:
     cd "Nombre del repositorio.git"
7. Para abrir el archivo en el terminal: 
     nano README.md


