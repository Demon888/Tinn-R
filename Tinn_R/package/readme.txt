Building R packages in Windows

 - https://www.biostat.wisc.edu/~kbroman/Rintro/Rwinpack.html
 - https://stevemosher.wordpress.com/ten-steps-to-building-an-r-package-under-windows/

Em s�ntese, ap�s instalar Rtools.exe:
- R CMD check mypackage
- R CMD build mypackage
- R CMD INSTALL --build mypackage.tar.gz