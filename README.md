# NOTES GIT
---

Algunes notes d'interés sobre Git.

[Link de llibre de Git en castellà](http://git-scm.com/book/es)

[Link de sintaxis markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

### ÍNDEX

1. [Bàsic](https://github.com/ricardpanades/notes-git#basic)
2. [Branches](https://github.com/ricardpanades/notes-git#branches)

<a rel="license" href="http://creativecommons.org/licenses/by-nc/3.0/deed.es_CO"><img alt="Licencia Creative Commons" style="border-width:0" src="http://i.creativecommons.org/l/by-nc/3.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">Notes Git</span> por <a xmlns:cc="http://creativecommons.org/ns#" href="http://ricardpanades.com" property="cc:attributionName" rel="cc:attributionURL">Ricard Panadès Nadal</a> se encuentra bajo una <a rel="license" href="http://creativecommons.org/licenses/by-nc/3.0/deed.es_CO">Licencia Creative Commons Atribución-NoComercial 3.0 Unported</a>.<br />Basada en una obra en <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/ricardpanades/notes-git" rel="dct:source">https://github.com/ricardpanades/notes-git</a>.



## Bàsic
---

Crear una repo nova:
```
$ git init
```

Agregar a un commit:
```
$ git add <nom-arxiu>
```
Per agregar arxius amb una mateixa extensió:
```
$ git add "*.extensió"
```
Per agregar tot:
```
$ git add .
```

Per a fer un commit:
```
$ git commit -m "missatge descriptiu per a el commit"
```

Per a pujar el/s commit/s al servidor:
```
$ git push
```



## Branches
---

Crear una nova branca:
```
$ git branch <nom-de-la-branca>
```

Pujar la nova branca al servidor:
```
$ git push origin <nom-de-la-branca>
```

Canviar de branca:
```
$ git checkout <nom-de-la-branca>
```

Veure les branques creades:
```
$ git branch
```

Borrar una branca local:
```
$ git branch -d <nom-de-la-branca>
```

Borrar una branca del servidor:
```
$ git push origin --delete <nom-de-la-branca>
```
```
$ git push origin :<nom-de-la-branca>
```


