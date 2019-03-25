# Documentación
Todos los datos útiles para la comprensión de archivos y además datos sobre el avance en nuevos y antiguos proyectos, documentarlos acá.

# paquete bib2gls
El documento presenta el paquete `glossaries-extra` con tree, lo que provoca que sea necesario compilar como sigue:
```bash
pdflatex nombreDocumento or pdflatex --jobname=<dir>\<doc_name_ppal> Vpython_Documentacion.tex
```
```bash
bib2gls nombreDocumento or bib2gls <dir>\<doc_name_ppal>.aux 
```
```bash
pdflatex nombreDocumento or pdflatex --jobname=<dir>\<doc_name_ppal> Vpython_Documentacion.tex
```
