Test per nuovo sito https://theradiostars.com

da lanciare con 
hugo server -D
(in questo modo carica le pagine ancora in draft)
il tema e' papermod: qua la documentazione
https://github.com/adityatelange/hugo-PaperMod

Fork del tema
https://github.com/massimobarbieri/hugo-PaperMod-radiostars

Dopo aver clonato il repo git del sito è necessario scaricare, sempre con git, il tema del sito.

Questo primo comando non è necessario se stiamo clonando:

`git submodule add --depth=1 https://github.com/adityatelange/hugo-PaperMod.git themes/PaperMod`

Il comando seguente è necessario

`git submodule update --init --recursive # needed when you reclone your repo (submodules may not get cloned automatically)`

Per aggiornare

`git submodule update --remote --merge`
