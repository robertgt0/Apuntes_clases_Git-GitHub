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
👉 Revisa la evolución de un proyecto.  
👉 Identifica cuándo se introdujeron ciertos cambios.  
👉Restaura versiones anteriores en caso de errores o problemas.   

### 👇Seguridad 🔒  
👉Controla quién puede ver o modificar ciertos archivos.  
👉 Protege información sensible o crítica.  
👉 Mantiene la integridad del proyecto frente a cambios no autorizados.  

### 👉FLEXIBILIDAD 🌱  
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
Los tenemos en nuestro ordenador  
## REPOSITORIOS REMOTOS 🦎
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

 ```diff
 ! CLASE 3 
```
## FUSIONAR RAMAS 🌳  
Los cambios en la rama se integran en otra rama  
## ELIMINAR RAMAS 🌴  
Las ramas tienen un proposito corto y unico ademas es de una buena practica.  
## CONFLICTOS EN GIT  
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

No necesariamente debe ser la rama main.  
***git push <nombre_repo_remoto> <rama_a_subirse>  
## Clonar repositorios  
Para clonar con HTTPS:  
***git clone <url_repo_HTTPS>***  
Para clonar cpn SSH:  
git clone <url_repo_SSH>  
## GIT PULL  
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



 ```diff
 + CLASE 2  
```



