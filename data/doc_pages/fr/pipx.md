Afin de ne pas polluer son système avec des différents utilitaires python que nous sommes amenés à utiliser.


Pipx permet de considérer ces paquets comme des binaires sans polluer son environnement python avec les dépendances, comme un virtualenv, mais pipx s'occupe de tout !

https://pipxproject.github.io/pipx/

installation:
```
python3 -m pip install --user pipx
python3 -m userpath append ~/.local/bin
```

puis, si vous voulez installer black:
```
pipx install black
```
