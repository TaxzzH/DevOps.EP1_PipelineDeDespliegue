# DevOps.EP1_PIPELINEDEDESPLIEGUE

Repositorio para EP1 de Ingeniería DevOps

## Instrucciones de instalación

Para instalar este proyecto, ejecuta el siguiente comando:
\`\`\`bash
git clone [https://github.com/TaxzzH/DevOps.EF1_FundamentosGit.git]

## Desarrollo del proyecto

* Repostiorio creado directamente desde github y poseriormente clonado dentro de VSC.

* Se ha seleccionado la estrategia "GitFlow" debido a que personalmente encuentro que es la mas ordenada al momento
de desarrollar un proyecto, pese a que las formas trabajar moviendose entre ramas son un poco mas complejas que trunk-based.

* Aparte de este README, se creó un archivo CHANGELOG para llevar un mejor seguimiento de los cambios y commits hechos dentro del proyecto.
Y un archivo SECURITY para dejar instrucciones sobre que hacer ante fallos y/o bugs encontrados por usuarios.

* Creacion desde la terminal con el comando "git checkout -b" las respectivas ramas del proyecto
    * main
    * develop
    * feature/automatizacion
    * hotfix/correcciones

* Se ha creado la carpeta github/workflows junto al archivo de automatizacion para la revision de documentos .md que interactuan directamente
con github, junto a su correspondiente archivo "markdownlint.json", los cuales en conjunto se aseguran de que la sintaxis de estos archivos 
esté escrita correctamente.
