# Priprema za vežbe  

## Jupyter Notebook  

Na vežbama ćemo raditi sa **Jupyter Notebook**-ovima, jednom komponentom [Project Jupyter](https://jupyter.org/)-a.  
**Jupyter Notebook** je *open source* web aplikacija koja omogućava rad sa dokumentima koji sadrže izvorni kod, jednačine, vizuelizacije i objašnjavajući tekst. Ova aplikacija dolazi instalirana u svim okruženjima za potrebe nastave.

Dokumentacija **Jupyter Notebook**-a se nalazi na sledećem [linku](https://jupyter-notebook.readthedocs.io/en/stable/).


### Pokretanje  

**Jupyter Notebook** server u *default web browser*-u pokrećemo tako što se u terminalu pozicioniramo u željeni folder i izvršimo komandu `jupyter notebook`:  
```bash
cd v0-priprema/

jupyter notebook
```
Željeni *web browser* se može specificirati pomoću `--browser`:
```bash
jupyter notebook --browser firefox
```

Nakon što se server pokrene, u *web browser*-u će se automatski otvoriti stranica sa sadržajem foldera. Željeni *notebook* se u novom *tab*-u otvara dvoklikom.  

### Stopiranje  

Pokrenuti *notebook* se gasi opcijom **File > Close and Shut Down Notebook**.
**Jupyter Notebook** server se gasi opcijom **File > Shut Down** ili komandom `CTRL + c` u terminalu u kom "trči".
