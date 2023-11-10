# Este es mi primer proyecto de Git

## Este es un titulo de ejemplo

[Esto es un enlace a las recetas de la Nonna](https://lanonnarecipes.onrender.com/)

![Esto es una imagen con enlace](https://hips.hearstapps.com/hmg-prod/images/hand-dipping-turkish-flatbread-into-hummus-royalty-free-image-1637582505.jpg?crop=1xw:0.49976xh;center,top&resize=1200:*)

Esto es una lista ordenada

1. Primer elemento
2. Segundo elemento
3. Tercer elemento

Y esto es un codigo  de Powershell
`Get-Process -Select notepad.exe`

commit 5dbc0ca37f63f19c009ea6cb3a9a9c3b55e55d2e (HEAD -> master)
Author: Orflo <lual.antonelli@gmail.com>
Date:   Mon Oct 30 16:01:06 2023 +0100

    Añadido readme.md

Cambios para hacer un git diff

### Ejercicio 6: Visualizando Diferencias

    diff --git a/readme.md b/readme.md
    index e8e973a..afd8d07 100644
    --- a/readme.md
    +++ b/readme.md
    @@ -19,4 +19,6 @@ commit 5dbc0ca37f63f19c009ea6cb3a9a9c3b55e55d2e (HEAD -> master)
    Author: Orflo <lual.antonelli@gmail.com>
    Date:   Mon Oct 30 16:01:06 2023 +0100

    -    Añadido readme.md
    \ No newline at end of file
    +    Añadido readme.md
    +
    +Cambios para hacer un git diff

### Ejercicio 6 etiqueta v2.o.checkout v1.0.log
    git diff 89ed97e 61ee0cf
    diff --git a/readme.md b/readme.md
    index ed66dce..e8e973a 100644
    --- a/readme.md
    +++ b/readme.md
    @@ -15,22 +15,8 @@ Esto es una lista ordenada
    Y esto es un codigo  de Powershell
    `Get-Process -Select notepad.exe`

    -git checkout 5dbc0ca37f63f19c009ea6cb3a9a9c3b55e55d2e
    -Note: switching to '5dbc0ca37f63f19c009ea6cb3a9a9c3b55e55d2e'.
    +commit 5dbc0ca37f63f19c009ea6cb3a9a9c3b55e55d2e (HEAD -> master)
    +Author: Orflo <lual.antonelli@gmail.com>
    +Date:   Mon Oct 30 16:01:06 2023 +0100

    -You are in 'detached HEAD' state. You can look around, make experimental
    -changes and commit them, and you can discard any commits you make in this
    -state without impacting any branches by switching back to a branch.
    -
    -If you want to create a new branch to retain commits you create, you may
    -do so (now or later) by using -c with the switch command. Example:
    -
    -  git switch -c <new-branch-name>
    -
    -Or undo this operation with:
    -
    -  git switch -
    -
    -Turn off this advice by setting config variable advice.detachedHead to false
    -
    -HEAD is now at 5dbc0ca Añadido readme.md
    \ No newline at end of file
    +    Añadido readme.md
    \ No newline at end of file

Modificaciones para subir este archivo en un commit