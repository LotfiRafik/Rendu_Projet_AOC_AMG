#################### Contenu de l'archive ###################

Ce dossier contient les différents executables de notre code en version séquentielle ainsi que la version parallele:

1-version sequentielle:
  *le nom de l'executable:
  
  *description: cette executable représente la version séquentielle sans aucunne optimisation.
  
  *Compilation  :       make
  
  *d'autres options:    make clean     (suprimer les fichier .o ) 
                        make veryclean (suprimer les fichier .o, les bibliothéques et les éxécutables)
  
  *Execution: mpirun -n 1 ./amg -n 200 200 200 -P 1 1 1
  
  
  

2-version optmiser:

  *le nom de l'executable: 
 
  *description: cette executable représente la version séquentielle sans aucunne optimisation.
  
  *Compilation  :       make
  
  *d'autres options:    make clean     (suprimer les fichier .o ) 
                        make veryclean (suprimer les fichier .o, les bibliothéques et les éxécutables)
  
  
  *Execution: mpirun -n 1 ./amg -n 200 200 200 -P 1 1 1
 
 
 
 3- note:
 -pour manipuler les flags de compilations, ouvrez le fichier Makefile.include 
 
 -"-n 200 200 200" manipuler la taille de la grid.
 -"-p 1 1 1" manipuler le nombre de processus mpi sur les demension de la grid
  
