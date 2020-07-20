# Utils

Este archivo contendra informacion util para el trabajo colaborativo en la mentoria.

## How we GIT

Lista de comandos utiles para manejar git. Estos comandos son ejecutados desde terminal en ubuntu, bash de git o desde CMD en windows.

- ```git clone https://github.com/bvaldeiglesias/astrodatos_grp_1.git``` clonar el repositorio. "Fork" del repositorio es muy distinto a "clonar" el repositorio. 
- ```git pull``` antes de empezar a programar.
- ```git branch -a``` veo todas las ramas
- ```git checkout -b <Nombre de la rama>``` crea rama y posiciona en la misma
- ```git status``` ver el estado de cambios actuales localmente.
- ```git add <Nombre de archivo a subir a repositorio>``` agregar cambios al "staging". Todo tiene que agregado para poder se commiteado y eventualmente pusheado al repositorio.
- ```git commit -m "<Mensaje>"``` Cometer los cambios agregados con el comando anterior para poder pushearlos. Describir que cambios hicimos con mensaje significativo.
- ```git push ``` llevar cambios a repositorio

IMPORTANTE: Avisar al resto del equipo antes de realizar ```git push```. **NO PUSHEAR** código roto o celdas de python con mensajes de error. Esto ultimo es para que sea legible al ver desde github en un navegador.

- Garantizar que si ejecuto cada celda en el orden que se presentan, el codigo producira siempre el mismo resultado
- No pushear código comentado
- No es necesario crear git branch por persona

![Cheat Sheet](https://qph.fs.quoracdn.net/main-qimg-d151c0543baa145e6252c1ec95199963 "GIT cheet sheet")

## Reglas de nombrado

- Nombre de notebooks deben ser de la forma ```<nro de orden>_<iniciales del autor>_<nomrbre descriptivo>.ipynb``` (No siempre todos los campos seran necesarios).
	- Ejemplos: ```1_rtas_analisis_y_visualizacion.ipynb```, ```1_bv_curacion_de_datos.ipynb```

- Seguimos convencion [PEP-8](https://www.python.org/dev/peps/pep-0008/#id34) para nombrado de variables, clases y funciones.