# masteruah
## 1. Commit inicial <br />
- git clone https://github.com/bingchilling01/masteruah/
- git add README.md 
- git commit -m "commit inicial"
- git push 
## 2. Fichero 1.txt 
- git add "fichero 1.txt" 
- git commit -m "añadir fichero 1" 
- git tag v0.1 
- git push --tags 
## 3. Rama v0.2 
- git branch v0.2 
- git checkout v0.2 
- git add "fichero 2.txt"
- git commit -m "añadiendo fichero 2"
- git push -u origin v0.2
## 4. Fusionar rama principal con v0.2
- git checkout main
- git merge v0.2
## 5. Fusión conflictiva
- git add "fichero 1.txt"
- git commit -m "añadir fichero 1 con conflictos"
- git checkout v0.2
- git add "fichero 1.txt"
- git commit -m "añadir fichero 1 con conflictos adios"
- git checkout main
- git merge v0.2
## 6. Listar ramas fusionadas y no fusionadas
- git branch --merge
- git branch --no-merge
## 7. Solucionar conflicto
- git status
- nano "fichero 1.txt"
- git branch --merge
- git commit -m "conflicto arreglado"
- git status
## 8. Tag v0.2
- git tag v0.2
## 9. Eliminar rama v0.2
- git branch -d v0.2
## 10. Listar cambios
- git log --oneline --decorate --all

