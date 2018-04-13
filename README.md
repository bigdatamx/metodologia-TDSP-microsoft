# metodologia-TDSP-microsoft
Metodología TDSP de Microsoft


Versiones utilizadas: 

 3.4.4 de R 

 1.1.442 Rstudio 

 Ubuntu 16.04


Para la herramienta de IDEAR de microsoft, se ha compilado en Rstudio el archivo de run-IDEAR.R el cual ha se han obtenido algunos errores de los cuales se corrigió uno: 
Comentar las líneas de script.dir y la de setwd(script.dir) y se cambia solo por la linea setwd()

#script.dir <- dirname(sys.frame(1)$ofile)
#setwd(script.dir)
setwd()	

Se corre el archivo IDEAR-MRS.rmd, tarará un tiempo de entre 3 min a 5 min en compilar el archivo, pero al momento que se selecciona un archivo .yml y al intentar leerlo manda el siguiente error: 
Error in config$RLogFilePath : objeto de tipo 'closure' no es subconjunto

Por lo que se consultó en la siguiente pág: https://github.com/Azure/Azure-TDSP-Utilities/issues?page=2&q=is%3Aissue+is%3Aclosed

Para conocer los errores y no se ha encontrado solución a esta. 



 

