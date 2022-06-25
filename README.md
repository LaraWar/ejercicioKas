# ejercicioKas
11- Utilicé git reset --hard HEAD virgulilla(si pongo el símbolo el README me tacha el texto) 1 para que retrocediese el puntero head sin guardar los cambios en el working copy.
12- Usé reflog para ver el ID del commit al que hacer otro reset hard.
13- Causó conflicto porque main es padre de styled y no deja mergearlo, absorbí styled haciendo checkout desde main.
19- No causó conflicto pero en vez de mergearlo hice un reset --hard para que el commit creado en htmlify no se tuviera en cuenta y se quedaran las 2 ramas en el commit de Modifico poema con los cambios de styled.
21- No causó conflicto pero hice lo mismo que en el punto 19.
25- Git log --graph
26- Hice un merge--no-f.
27- Hice un git reset HEAD~1.
28- Git restore para descartar los cambios.
29- Utilicé git branch -D.
30- Usé un reflog e hice checkout a el commit del MNFF, moviendo solamente HEAD a ese commit y creé la rama con un git branch "title", después hice otro checkout a
title para situar HEAD en esa rama.
32- Hice un git reflog para copiar el ID del primer commit e hice un reset hard a ese commit.
33- Utilicé  un git reflog para copiar el ID del commit del merge NFF para volver al estado final.
