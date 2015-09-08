# Respuestas Ejecicio 1

**¿Qué comando usaste en el paso 11?**

*git reset --hard HEAD~1*

**¿Porque?**

*Se usó git reset para mover el puntero HEAD y el puntero de la rama htmlify al commit anterior. Como se pedía perder todos los cambios se ha usado el modificador --hard. Por último, HEAD~1 indica el commit anterior, que es donde se quería volver.*

**¿Qué comandos o comandos utilizaste en el paso 12?**

*git reflog*

*git reset --hard b6995d7*

**¿Porqué?**

*El primer comando (git reflog) se ha usado para poder buscar la referencia del último commit. El segundo comando (git reset) se ha utilizado para volver al commit cuya referencia se ha obtenido en el paso anterior y se ha usado el modificador --hard para dejar el working area como estaba antes de deshacer el cambio.*

*También habría sido podible volver a hacer un nuevo commit, pero se ha optado por esta opción para no dejar commit sueltos.*

**El merge del paso 13, ¿causó algún conflicto?**

*El merge no ha causado ningún conflicto*

**¿Porqué?**

*Porque no existían dos modificaciones del mismo archivo en la misma línea para que se puediera causar un conflicto. Además la rama htmlify ya contenía todos los cambios de la rama master.*

**El merge del paso 19, ¿causó algún conflicto?.¿Porqué?**

*Este merge ha causado conflictos debido a que existen modificaciones en el fichero poem.md en las ramas htmlify y matrix que afectan a las mismas líneas.*

**El merge del paso 21, ¿causó algún conflicto?. ¿Porqué?**

*Este merge no ha causado conflictos ya que la rama master contenía todos los cambios que se habían producido en la rama htmlify más los suyos propios. De hecho, el merge que se ha llevado a cabo es de tipo Fast-forward y solamente ha actualizado el puntero de la rama htmlify a master*

**¿Qué comando o comandos utilizaste en el paso 25?**

*git log --graph --decorate --pretty=oneline*

**El merge del paso 26, ¿podría ser fast forward? ¿Porqué?**

*Este merge no podría ser fast forward ya que existían cambios de title que no se encontraban en master, lo que hacía que el grafo de commits no formase una lista y por ello este merge no era fast forward.*

**¿Qué comando o comandos utilizaste en el paso 27?**

*git reset HEAD~1*

**¿Qué comando o comandos utilizaste en el paso 28?**

*git reset --hard HEAD*

**¿Qué comando o comandos utilizaste en el paso 29?**

*git branch -d title*

**¿Qué comando o comandos utilizaste en el paso 30?**

*git reflog*

*git reset f6f0de2*

**¿Qué comando o comandos utilizaste en el paso 32?**

*git checkout bd9ca96*

**¿Qué comando o comandos utilizaste en el paso 33?**

*git checkout f6f0de2*



