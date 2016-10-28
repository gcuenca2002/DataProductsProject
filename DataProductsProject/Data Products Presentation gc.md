Data Products Presentation gc
========================================================
author: GCuenca
date: Fri Oct 28 16:14:08 2016
autosize: true

My APP_PLAT
========================================================

APP_PLAT shows some carcteristics about structures with a fator like high and position coordinates,
SUBS gca.cvs is file that suppport this app.
Some other inpts could be add in future.

- Name of each structure
- dates
- weigth

File (R Code) 
========================================================


```r
df <- read.csv("App_Plat/data/TRABAJO SUBS gca.csv", stringsAsFactors = FALSE)
head(df)
```

```
       NOMBRE TIRANTE INICIOINST FINALINST NUMDIAS PESO   COORDX  COORDY
1       MAY-B    12.2  09-nov-04 08-dic-04      29  650 545010.5 2068011
2       MAY-A    14.1  01-oct-04 28-oct-04      27  727 542768.3 2069881
3 PP-TSIMIN-D    14.4  01-jun-14 01-jul-14      30 1230 531863.8 2067914
4    PP-XUX-A    14.9  02-nov-12 29-nov-12      27  949 526964.0 2066672
5 PP-TSIMIN-B    16.5  04-feb-12 22-feb-12      18 1553 533506.8 2070193
6 PP-TSIMIN-C    16.6  13-mar-13 23-may-13      71 1420 531401.0 2069901
  DESN RANGO
1   20     1
2  114     1
3   73     1
4   20     1
5   84     1
6   79     1
```

APP_PLAT
========================================================

Using Shiny

This APP_PLT is in:

https://gcuenca2002.shinyapps.io/App_Plat/

APP_PLAT GITHUB
========================================================

Using Github

Files Project are:

https://github.com/gcuenca2002/DataProductsProject
