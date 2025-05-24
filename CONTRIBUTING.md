# Guía de contribuciones

### Clases

Como se describió en el `README.md` se tiene que toda clase hace parte de un mini curso semestral, solo se aceptaran contribuciones de clases nuevas que hagan parte de uno de estos cursos semestrales y que sean subidas por miembros del semillero o externos autorizados. 

Toda clase subida tiene que tener la siguiente estructura de carpetas

```
clases/[año-semestre] Nombre de la Clase/
    latex/
        notas_de_clase.tex
        presentación.tex
    notas_de_clase.pdf
    notebook_de_aplicación.ipynb
    presentación.pdf
    README.md
```

Un ejemplo sería el siguiente:

```
clases/[2025-1] Maquinas de Soporte Vectorial/
    latex/
        SVM.tex
    notas_SVM.pdf
    svm_lineales.ipynb
    svm_kernelizadas.ipynb
    presentacion_svm.pdf
    README.md
```

En este ejemplo la presentación no se hizo con latex así que solo se subió el pdf de esta.

Tenemos los siguientes requerimientos por cada elemento dentro de la carpeta:

- **Presentación**: Formato horizontal, la última hoja debe de tener todas las referencias usadas. Se puede usar cualquier herramienta para hacer la presentación, lo único obligatorio será que esta se suba en formato pdf.
- **Notas de clase**: Notas con datos extra que no entraron en la presentación, o que van más allá de lo abarcado en esta, como demostraciones u otras aplicaciones. Se necesita que estas se hagan con un editor de ecuaciones como LaTex o equivalente, no se aceptan archivos de Microsoft Word.
- **Notebook de Aplicación**: En caso de usar otro lenguaje o herramienta para el código que no sean notebooks de Jupyter, se deberá crear una carpeta llamada "codigo" que tenga las instrucciones de como ejecutarlo. Se necesita que todo el código que se suba esté comentado y sea legible, todo código espagueti será rechazado.
- **README.md**: En este archivo se tiene que poner el titulo de la presentación, el autor, el enlace a la grabación de la clase en caso de que exista y el curso al que pertenece esta clase.

### Guías

Estas guías se toman como conocimiento base para las clases del semillero, se usarán como guía para que miembros nuevos se puedan poner al día con los contenidos. Se necesita que estén hechas con un editor de ecuaciones como LaTex o equivalente, toda guía subida debe contener una hoja de portada con:

- Titulo.
- Autores.
- Ultima fecha de modificación o version.
- Indice de contenidos.

Al final de la guía se tiene que tener de forma obligatoria una tabla de referencias bibliográficas usadas en la guía.

> No hay restricciones para quien puede subir las guías, se aceptan guías de externos que estén bien documentadas.

La estructura de carpetas para las siguiente:

```
guias/Tema/
    latex/
        tema.tex
    guia.pdf
```

Un ejemplo sería el siguiente:

```
guias/Maquinas de Soporte Vectorial/
    latex/
        SVM.tex
    SVM.pdf
```

## Proceso de Pull Request

Al crear el PR asegúrate de que haces lo siguiente:

1. Cumples con todo los requisitos dados en la sección anterior para el tipo de aporte.
2. Marcar como reviewer a una o dos personas que estén en la lista de mantenedores del repositorio que está en el `README.md`.
3. Ponerle la etiqueta correspondiente al aporte al pull request.
4. Cumples con el código de conducta descrito en `CODE_OF_CONDUCT.md` en tu aporte.

> Si el pull request va a editar algo que ya está en el repositorio, asegúrate de primero crear un issue en el que se discuta ese cambio antes de enviar un pull request.

Solo se aceptaran pull requests que cumplan esas condiciones y que cumplan las reviews dadas por los mantenedores.
