# Panorama

Escritura de espacios libres e inmersivos para el performance audiovisual.

Marianne Teixido, Dorian Sotomayor y Emilio Ocelotl 

[Texto Completo](https://github.com/piranhalab/panoramaArticulo/blob/main/panorama.pdf)

### Resumen

El confinamiento provocado por la pandemia de COVID-19 obligó a artistas, gestores, instituciones públicas e industrias a replantear maneras de compartir flujos co-presenciales y hacer performance audiovisual en vivo.

El presente artículo describe *Panorama*, un conjunto de módulos de código y software que permiten realizar conciertos en espacios virtuales tridimensionales alojados en la web. De manera complementaria, enuncia discusiones que surgieron durante la activación del espacio sobre materialidad, virtualidad, descentralización, distribución, espacio público, arqueologías del cyberespacio, entre otros.                       

## Estructura

- **Resumen**
- **Ecosistema.-** Introducción, antecedentes, proyectos y tecnologías similares.
- **Diseño y Escritura.-** Elementos del diseño de *Panorama*. Enunciación y descripción breve de las tecnologías implicadas.
- **Notas y Pruebas.-** Primera parte que describe resultados. Casos elegidos: *Notas de Ausencia* y *Pruebas proféticas*
- **EDGES y Contemplación.-** Segunda parte que describe resultados. Casos elegidos: *EDGES* y *La contemplación del Fin del Mundo*
- **Three y 4nt1.-** Tercera parte que describe resultados. Casos elegidos: *threecln* (en proceso) y *4nt1* (en proceso) 
- **Conclusiones.-** ¿Se cumplió la premisa/hipótesis descrita en Diseño y Escritura? ¿Qué otras cosas surgieron?
- **Notas.-** El artículo usa notas al final del texto. Aquí aparecen hipervínculos y conceptos de apoyo. 
- **Referencias.-** Referencias bibliográficas y repositorios en Git como referencias en la web. 

## Requisitos para compilar el documento

- Compilador y editor latex
- Instalar Endnotes

## Ejecución provisional

Para compilar el documento en pdf

`pdflatex -halt-on-error -output-directory out panorama.tex`

Para compilar el texto como html sin problemas de caracteres en español 

`make4ht -x panorama.tex`

Agregar el estilo manualmente 

## Por hacer

- [ ] Pasar de html a texto plano para compartir en algún lado.
- [ ] Escribirle a lxs de ecosistemas.
- [ ] Descripciones menos genéricas para las piezas.    
- [ ] Cuestionario de Pruebas Proféticas como un anexo en el repositorio  
- [ ] Recopilar recursos multimedia
- [ ] Fundir casos 

## Propuestas

- Mini taller de latex. 

## Referencias

- [latex-demo](https://github.com/rexmalebka/latex-demo) 
- [Modelo IMRyD](https://www.lluiscodina.com/modelo-imryd) 
- [Academic writing](https://www.unaminternacional.unam.mx/academic-writing)
- [How do you cite a Github repository](https://academia.stackexchange.com/questions/14010/how-do-you-cite-a-github-repository) 
