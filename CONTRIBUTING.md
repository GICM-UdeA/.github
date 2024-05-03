# Contribuir a los proyectos 🛠️
:+1: Primero que todo, gracias por leer está guía para realizar tus contribuciones! :+1: 

Ya sea que esté comenzando un **nuevo proyecto** o que quiera **unirse a uno** que ya esté avanzado, la idea es seguir una metodología clara para la publicación de su contribución y tratar de mantener la información y avance de cada proyecto accesible y entendible para todos los miembros de la organización. Por ello, en la medida de lo posible, trate de mantener sus desarrollos en repositorios donde las tareas a desarrollar se organicen como **issues**([Guía](https://medium.com/nyc-planning-digital/writing-a-proper-github-issue-97427d62a20f)) a resolver y trabajar sobre diferentes **ramas**([Guía](https://medium.com/@jmz12/recomendaciones-para-el-manejo-de-ramas-5dd4b5a23c91)) para ir resolviendo cada uno. La metodología recomendada es crear un issue, crear una rama para trabajar en el issue, hacer los **commits**([Guía](https://medium.com/@jmz12/buenas-pr%C3%A1cticas-para-commits-5eb4c86b9a47)) y push necesarios y finalmente integrarlos mediante un **pull request**([Guía](https://styde.net/pull-request-en-github/)). De esta forma, se pueden mezclar las diferentes versiones de cada participante del proyecto sin generar conflictos entre sus publicaciones y la historia del proyecto será trazable para quien desee enterarse o unirse.

Revise las los enlaces que se han marcado como "Guía" si no está muy familiarizado con esos conceptos en github, o si simplemente quiere reforzar las buenas prácticas. A continuación, se dejan unas pautas generales para realizar sus contribuciones en alguno de los proyectos del grupo:

#### Tabla de contenidos
1. [¿Encontró algún Bug o tienes alguna pregunta? ](#Bug?)
2. [Lineamiento para resolver un issue](#issue)
3. [Finalizar sus contribuciones](#after)

### <a name="Bug?"></a> ¿Tiene una propuesta, encontró algún Bug o tienes alguna pregunta? 
Abra un `issue` qué describa el problema lo mejor posible y asigne trate de asignar las etiquitas adecuadas( https://github.com/GICM-UdeA/.github-private/labels/bug, https://github.com/GICM-UdeA/.github-private/labels/enhancement, https://github.com/GICM-UdeA/.github-private/labels/documentation, https://github.com/GICM-UdeA/.github-private/labels/question, etc. De esta forma se podrán analizar las prioridades para tratar de dar solución lo antes posible.

### <a name="issue"></a> Lineamiento para resolver un issue
Con base al `issue` relacionado cree una nueva rama, anteponiendo al nombre de la rama la etiqueta correspondiente. Si usted es miembro de la organización **no es necesario hacer Fork al repositorio**, solo debería tener presente:
* No publicar los cambios directamente en la rama principal.
* Comentar apropiadamente sus implementaciones.
* Si sus cambios afectan directamente las aplicaciones existentes, actualice o añada la documentación relevante.
* Publique los commits con mensajes descriptivos.

Eso es todo, ¡Gracias por su contribución!

### <a name="after"></a> Finalizar sus contribuciones
Después de que su pull request sea aceptado y mezclado con la rama principal, borre su rama del repositorio central.

* Cambie a la rama principal:
```bash
git checkout master -f
```
* Borre la rama localmente:
```bash
git branch -D my-fix-branch
```
* Actualice su rama principal con los últimos cambios del upstream
```bash
git pull --ff origin master
```

[contributors]: CONTRIBUTORS
