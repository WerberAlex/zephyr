## Configuration
D'abord trouver le docker file décrivant le docker. 
Puis lancer : 
```
docker run --rm -it -p 2222:22 -p 8800:8800 -v "${PWD}\workspace:/workspace" -w /workspace env-zephyr-espressif
```
Créer un localhost dans Visual Studio pour se connecter en ssh : 
```
root@localhost:2222
```
Une fois connectée, rentrer le mot de passe et TADAM on est dedans. 
