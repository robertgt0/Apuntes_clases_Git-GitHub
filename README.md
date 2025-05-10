# <ins>Apuntes_Clases_Git/GitHub 📚</ins>
>Se vera los apuntes de cada clase avanzada de la etapa 2 de los postulantes de la SCESI
#
 ```diff
 - CLASE 1  
```
## CONTROL DE VERSIONES⏳     
Sistema que registra cada cambio en el codigo fuente que funciona como un historial.    
## LA IMPORTANCIA DEL CONTROL DE VERSIONES   

### 👇Historial 📃  
![image](https://github.com/user-attachments/assets/04d3f41f-83e8-4a86-b8bf-4ce496ab2b02)

👉 Revisa la evolución de un proyecto.  
👉 Identifica cuándo se introdujeron ciertos cambios.  
👉Restaura versiones anteriores en caso de errores o problemas.   

### 👇Seguridad 🔒  
![image](https://github.com/user-attachments/assets/0194a63f-2158-4bff-b2ea-0d7ae70754a2)

👉Controla quién puede ver o modificar ciertos archivos.  
👉 Protege información sensible o crítica.  
👉 Mantiene la integridad del proyecto frente a cambios no autorizados.  

### 👉FLEXIBILIDAD 🌱  
![image](https://github.com/user-attachments/assets/eacdce82-d107-413b-9bb6-68e42c7f3514)

👉Integrar cambios de varios colaboradores sin conflictos.  
👉Facilidad para entender la evolución del proyecto.  
👉El seguimiento de qué cambios se incluyen en cada versión.  
***
## GIT  
Es un sistema distribuido donde aloja una copia de repositorio en cada maquina local  
## ¿QUE ES UN REPOSITORIO?📔
Es una carpeta donde se almacena las diferentes versiones de los ficheros de un proyecto y su historial  
Estos mismos repositorios pueden ser locales o remotos  
## REPOSITORIO LOCAL 🖥️  
![image](https://github.com/user-attachments/assets/9790eb47-cad0-4c5f-b8f7-3a5e3cc80081)

Los tenemos en nuestro ordenador  
## REPOSITORIOS REMOTOS 🦎  
![image](https://github.com/user-attachments/assets/8533263e-82ce-43a9-9d5d-0a0f4fa176de)

Estan en un servidor externo  
###
## COMANDOS  
Proyecto desde cero📁    
|git init nuevo-proyecto |crea un nuevo repositorio  |  
|------------------------|---------------------------|  
|cd nuevo-proyecto       |para cambiar de directorio |  

Proyecto con carpeta ya existente📂  
|cd <directorio del proyecto que ya existe>|cambio de direcctorio|  
|------------------------------------------|---------------------------|
|git init                                  |inicia un nuevo repositorio|

***
 ```diff
 + CLASE 2  
```
## LOS 3 ESTADOS DE GIT  
### Modified📜  
El archivo fue creado, eliminado o contiene cambios.  
### Staged 📋  
El archivo fue marcado para confirmar en el repositorio local.  
### Commited 📘  
El archivo fue grabado en el repositorio local.  
***

## ¿QUE ES UN COMMIT? 📌  
![image](https://github.com/user-attachments/assets/b3040179-b1df-4f2b-b362-7240c74ff94b)

***Es una de las piezas mas importantes para GIT***  
Sirven para el registro de los cambios de los repositorios.  
__Como guardar una partida en un videojuego__

## ¿QUE ES UNA RAMA? 🌳  
Es un nuevo apuntador hacia una de las confirmaciones  
## FUNCIONES DE LAS RAMAS  
Permiten realizar un desarollo no lineal y colaborativo.  


## COMANDOS  
Comandos Realizados en la segunda clase📁    
|git status              |Es para ver el estado actual del proyecto          |  
|------------------------|---------------------------------------------------|  
|git add README.md       | Es para incluir este archivo                      |  
|git commit              |Guarda los cambios                                 |   
|git commit -m           | Confirma los cambios                              | 
|git log --help          |Abre la documentacion de git mostrando los comandos|    
|git log --oneline       |Muestra el nombre del commit                       |  
|git switch              |Para cambiar de rama                               |  
|git switch rama_javacrip|Estoy cambiando a la rama de javascript            |
|git branch rama_d rama-c|Crea la rama y la cambia                           | 
|&&                      |Sirve para concatenar comandos                     |
***
 ```diff
 ! CLASE 3 
```
## FUSIONAR RAMAS 🌳  
![image](https://github.com/user-attachments/assets/e0d31b68-aa3e-49ed-b83f-c979057a38dc)

Los cambios en la rama se integran en otra rama  
## ELIMINAR RAMAS 🌴  
![image](https://github.com/user-attachments/assets/ba7f64c7-0d4e-45ee-a9c1-28427b1733bf)

Las ramas tienen un proposito corto y unico ademas es de una buena practica.  
## CONFLICTOS EN GIT  
![image](https://github.com/user-attachments/assets/ada35fd6-92af-45e6-99ba-e7f020ff473d)

Si fusionamos dos ramas, la del destino realiza cambios en la misma linea de un fichero que los que queremos fusionar  
***TENEMOS CONFLICTO***  

|git merge                      |indicamos a que rama me quiero aderir                      |  
|-------------------------------|-----------------------------------------------------------|  
|git merge --no commit          | evita que se haga commit automaticamente                  |         
|git merge --edit               | Abre el editor antes de hacer el commit                   |
|git merge --abor               | Cancela una operacion de fusion                           |
|git log --oneline --graph      | Puedes ver el historial de los commit                     |
|git switch main                | Cambia la rama actual a la rama main                      |
|git branch                     |Para crear ramas, visualizar, borrara ramas y relacionados |
|git brach -d no_rama           | Elimina la rama                                           |
|git brach <nombreRama> --no_ff | Se crea el commit sin hacer el fast forward               |

***

 ```diff
 -CLASE 4 
```
## GIT Y GITHUB  
Git es un control de versiones  
Github aloja en la nube fuentes basadas en el sistema de control de versiones que git ofrece manejar repositorio  
***  
## REPOSITORIOS REMOTOS  
Estan hospedados en un servidor y que servira de punto de sincronizacion.  


## Sincronizando repositorios  
Usaremos un nuevo comando llamado git push, nos permite sincronizar nuestros cambios del repositorio local a nuestro repositorio remoto.  
## NUEVO REPOSITORIO  

![image](https://github.com/user-attachments/assets/b1b2fe7e-8ceb-4476-9cb8-e90e9c307d2e)  
Vamos a la pestana create new y elegimos new repositoty
![image](https://github.com/user-attachments/assets/a9bfa8d0-c23c-4a5d-bf30-fc73280db35d)
Llena los datos  
![image](https://github.com/user-attachments/assets/bc0f74f8-2199-40c7-94c7-dcc424263f4e)


No necesariamente debe ser la rama main.  
***git push <nombre_repo_remoto> <rama_a_subirse>  
## Clonar repositorios  
Para clonar con HTTPS:  
***git clone <url_repo_HTTPS>***  
Para clonar cpn SSH:  
git clone <url_repo_SSH>  
## GIT PULL  
![image](https://github.com/user-attachments/assets/9e969aed-6e94-4b35-a908-ff833cf5a4db)

Sirve para jalar o descargar los cambios del repositorio remoto al repositorio local  
***
##EXPERIMENTOS CON GIT PULL  
Treaernos cambios de otras ramas a la actual  
Traernos cambios de varias ramas a una sola  
***  
## TIPS PARA UNA BUENA PR  
Enfoca tu codigo en una sola cosa  
Explica tu pull request  
##REVISAR UNA PR  
Proporcionar siempre feedback positivo  
Concrecion y claridad  
Entiende el contexto 


## COMANDOS  
Comandos Realizados en la cuarta clase📁    
|git pull       | Te trae los cambios que se hicieron       |  
|------------------------|---------------------------------------------------|  
|git remote add origin <url>       |   Agrega repositorio remoto a tu proyecto de GIT locas    |  
|git remote -v        | Muestra los repositorios remotos configurados          |  
|git remote prune origin |Elimina referencias locales a ramas que ya no existen|  
|git fetch | Descargas los cambios de los repositorios remotos | 
|git push origin <rama> | Envia los commit de tu rama local al repositorio remoto|  
|git clone <url_repositorio> | Copia un repositorio remoto completo a tu maquina local| 

***

 ```diff
 + CLASE 5
```
## GITFLOW  

1. Main: contener el codigo de produccion  
 ![image](https://github.com/user-attachments/assets/a1c4c322-b976-4294-a73d-599e26c5be19)
2. Develop: Codigo de produccion que todavia tienen que ser probadas
![image](https://github.com/user-attachments/assets/bbaee5a8-26d3-4813-ae26-b1432ca45309)

3. Feature: Caracteristicas nuevas
4. Release: Cambios de ultimo momento
5. Hotfix: Parches
   

## SHIP/SHOW/ASK  
1. Ship: Se fucionan en la rama principal
2. Show: Abre una peticion de cambios para  que sean revisados
3. Ask: Abre una PR para discutir los cambios antes de fusionarlos
   
***
 ```diff
 - CLASE 6
```   

## BUENAS PRACTICAS 🐐  
1. Es un estandar manejado en la mayoria de equipos de desarollo
2. Resolver conflictos o problemas durante el desarollo es mas facil
3. Tu historial de commits es mas legible

## CADA CUANTO HACER COMMIT?  
***A menudo***  
Hacer commit a menudo no significa que debes hacer commits sin sentido  
Usa prefijo para tus commits para hacerlos mas semanticos  
![image](https://github.com/user-attachments/assets/217fa7b7-40b7-4cd6-8108-ce034f8ad7c5)

## ESCRIBIR UN BUEN NOMBRE DE RAMA  
1. Se consistente al nonmbrar tus ramas
2. Usa el nombre de la accion que se realiza en la rama
![image](https://github.com/user-attachments/assets/ce27e478-e4ae-4e7f-a3a3-9cfad664f128)

3. Usa los IDS de JIRA o el sistema de tickets que usas
   ![image](https://github.com/user-attachments/assets/d92acf7b-2c18-48ed-885c-6dd77f7cd9c0)
***  
 ```diff
 - CLASE 7
```  
## EN QUE CASOS DESHACEMOS CAMBIOS?🚩  
1. Dejo de funcionar el proyecto
2. Queremos recuperar una parte del codigo que eliminamos
3. Queremos recuperar archivos que eliminamos

## COMANDOS DESTRUCTIVOS🔨  
Los comandos destructivos afectan el historial de commits realizados, los comandos no destructivos trabajan en base al historial sin efectarlo.  

## GIT RESET  
SOFT: Mantiene los cambios que ocurrieron antes de hacer commit desde donde apuntaba  
HARD: Descarta los cambios  
## GIT REVERT  
Revierte los cambios que un commit introdujo y crea un nuevo commit con los cambios revertidos  
**git revert edba**  




***
 ```diff
 - CLASE 8
```
## QUE ES UN HOOKS💡  
1. Un hook de enganche es la posibilidad de ejecutar una accion o scrip cada vez que ocurre un evento determinado de GIT
2. Hooks del lado del cliente
3. Hooks del lado del servidor

## HOOKS DEL LADO DEL CLIENTE👤  
![image](https://github.com/user-attachments/assets/81f40b27-6eb3-4588-91fa-451d75a33991)  
### Pre-commit  
Podrias comprobar si se esta intentando hacer un commit de demasiados archivos  
Puede ser un buen sitio para ejecutar el linter sobre los archivos que han sido modificados  
### Prepare-commit-msg  
Para modificar el mensaje del commit  
### Post-commit  
Se usa para notificar por Slack  
### Pre-push  
Para ejecutar una bateria de test  
### post-checkout y post-merge  
Permite limpiar el directorio del trabajo tras realizar un checkout  

##¿Como añado un hook a mi repositorio local?  
Primero: Deberemos ir a la carpeta de nuestro proyecto y habilitar la visualización de archivos ocultos.  

![image](https://github.com/user-attachments/assets/17a7c6a8-55fa-4c17-872d-33f0beebf6da)  

Segundo: Entraremos en la carpeta .git, esta carpeta es crucial para la integridad de tu proyecto asi que te ruego no tocar cosas que no sabes.  

![image](https://github.com/user-attachments/assets/b7f5b307-51fa-45f1-b86d-9a6b4c9c852b)  

Tercero: Abre la carpeta hooks aqui encontraras varios hooks de muestra.  

![image](https://github.com/user-attachments/assets/aaf344f6-c5c0-42b3-897d-e13b49951072)  

Cuarto: Crea una copia del .sample y cambia el nombre de tu copia a un tipo de hook que tu desees. Abre el hook con un edito de codigo y posteriormente crea el codigo necesario para tu hook  

![image](https://github.com/user-attachments/assets/a135635b-15ba-46e6-ac25-de705bafedd3)  

Quinto: Quitale el .sample a tu archivo  
## TRUCOS EN GIT  
Garda tus cambios temporales:  
git stash  
git stash -u  
git stash pop  
Aplicar cambios de commits en especifico:  
git cherry-pick<SHA>  
Detectar que commits es el que ha introducido un bug:  
git bisect  
git bisect start
git bisect bad
git bisect good  
git bisect reset  
![image](https://github.com/user-attachments/assets/e856cd71-3dcb-4515-8129-339011051eca)

