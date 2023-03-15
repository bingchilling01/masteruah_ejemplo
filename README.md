# Práctica GIT
## _1. Commit inicial_
- git clone https://github.com/bingchilling01/masteruah/
- git add README.md 
- git commit -m "commit inicial"
- git push 
## _2. Fichero 1.txt_
- git add "fichero 1.txt" 
- git commit -m "añadir fichero 1" 
- git tag v0.1 
- git push --tags 
## _3. Rama v0.2_
- git branch v0.2 
- git checkout v0.2 
- git add "fichero 2.txt"
- git commit -m "añadiendo fichero 2"
- git push -u origin v0.2
## _4. Fusionar rama principal con v0.2_
- git checkout main
- git merge v0.2
## _5. Fusión conflictiva_
- git add "fichero 1.txt"
- git commit -m "añadir fichero 1 con conflictos"
- git checkout v0.2
- git add "fichero 1.txt"
- git commit -m "añadir fichero 1 con conflictos adios"
- git checkout main
- git merge v0.2
## _6. Listar ramas fusionadas y no fusionadas_
- git branch --merge
- git branch --no-merge
## _7. Solucionar conflicto_
- git status
- nano "fichero 1.txt"
- git branch --merge
- git commit -m "conflicto arreglado"
- git status
## _8. Tag v0.2_
- git tag v0.2
## _9. Eliminar rama v0.2_
- git branch -d v0.2
## _10. Listar cambios_
- git log --oneline --decorate --all

