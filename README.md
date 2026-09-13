# Fatima Guerrero Morales
Matricula: 2630018  
Nombre de la practica: Creación y sincronización de repositorios con Git y GitHub  
## Descripcion  
1. Como primer paso abri una ventana de powershell y user el comando ```cd ~``` para colocarme en la carpeta principal y volvi a usar ```cd ``` para dirigirme a desktop

2. Cree una carpeta con el comando de ```mkdir practica-git-Fatima-Guerrero```  y use de nueco ```cd``` para ir a practica-git-Fatima-Guerrero y usea ```pwd``` para asegurarme
3. Use el comando ```git init``` ara iniciar al repositorio en git
4. Despues use ```git branch -M main``` para darle nombre a la rama principal
5. Desde escritorio cree dos archivos unos llamado datos.txt con un texto inicial y otro llamado README.md y los agregue a mi repositorio
6. Volvi a la powershell y usea el comando  ```git status``` para ver que los archivos estuvieran en la zona de untracked file
7. Desppues user el comando ``` git add .``` para agregar los archivos a la zona de praparacion o stanging area y volvi a usar ```git status``` para ver que estuviera correcto
8. Ya hecho eso hize mi primer commit usando el comando ```git commit -m "Primer commit"``` 
9. El siguiente paso fue hacer el mismo repositorio pero desde github , para eso entre desde google, entre a mi cuenta y me fui a repositorios,le di a new y de nombre le puse el mismo que el repositorio que ya tenia en el escritorio
10. Para enlazarlos use el comando ```git remote add origin URL_DEL_REPOSITORIO``` la url la saque de git de mi repositorio, para checa que estuviera bien echo use el comando ```git remote -v```
11. Para terminar de enlazarlos y enviar mi repositorio local a github use ```git push -u origin main``` y verifique en github que si estuviera 

12. ya que estaba en github estaba mi archivo de datos.txt y lo modifique desde ahi poniendole "este archivo fue modificado desde github " y lo guarde haciendo un commit desde github  
13. Regrese a la power shell y guarde los cambios con el comando de ```git pull origin main ``` y abri mi archivo para ver que estuvieran  
14. Modifique mi archivo datos.txt desde la computadora agregandole un nuevo texto "Este archivo fue modificado desde el repositorio local" y lo guarde  
15. volvi a usar  ```git status``` para ver que estuviera correcto, me salia como modificado y lo mande a staging area con  ``` git add .``` y volvi a usar ```git status``` y si estaba correcto
16. cree un nuevo commit con ```git commit -m "Actualizacion desde repositorio local"``` 
17. con el comando  ```git push```envie los cambios a github 
18. Una vez terminado cheque todos los arvhivos en github y estaban todos, el datos.txt que fue el que estuve modificando y el README.md que no modifique para nada, en total fueron 3 commits, el primero contenia los dos archivos (datos.txt y README.md) el segundo el commit desde github con datos.txt y el tercero el commit desde el repositorio local 
## conclusion 
En conclusion aprender todos estos pasos y ponerlos en practica es tal vez un poco dificil al pprincipio pero nos ayuda a entender mejor los pasos de como se hacen las carpetas desde powershell o como hacer un repositorio vinculado con git, es algo importante saber como se desarollan las cosas y entenderlas aunque hay maneras mas faciles es bueno aprender a hacerlo, github es una pagina muy util para guardar nuestras versiones sin que nuestro codigo este en peligro o que lo perdamos o borremos por accidente y es importante saber usar git como github


 