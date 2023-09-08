Primero inicio git local: $git init

Creo el archivo readme.md: $cat >readme.md

Añado el archivo al String Area: $git add readme.md (o en este caso tmb podria ser git add .)

Miro el estado actual del git: $git status (me sale el archivo en SA)

Hago un snapshot: $git commit -m "Creo archivo readme.md"

Miro el estado actual del git: $git status (me sale que no tengo nada más que commitear)

Finalmente creo el repo en gitHub y lo subo:
git remote add origin https://github.com/LiaPuigmi/repo01.git
git branch -M main
git push -u origin main