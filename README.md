# Creare un repository
## Passo per passo
> Passaggi:

- 1 Creare il *repository*
- 2 Configurarlo su *Visul Studio Code*
- 3 Creare il branch e aggiungere l'origine dei *commit*
- 4 Lanciare il comando per *caricare* i contenuti

**1**- Il primo passaggio si effettua così:
Sulla tendina del profilo github scegliere Your Repository>New, quindi creare un repository nuovo.

**2**- Creare su Visual Studio Code una cartella con lo stesso nome del repository e , al suo interno, un file "README.md"

**3**- Nel terminale di Visual Studio, all'interno della cartella creata, seguire questi passaggi:
``` 
git init

git add README.md

git commit -m "first commit"

git branch -m main

git remote add origin http://git.hub.com/username/repositoryname.git
```

**4**- Infine lanciare il comando per caricare i contenuti con:
```
git push -u origin main
```
