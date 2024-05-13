# Mano-Python

**Programa vis dar kurimo stadijoje, todel ne visos funkcijos veikia (pazymeta). Kai kurios funkcijos veikia nestabiliai (pazymeta).** 

Norint paleisti programą "Kursinis" naujoje aplinkoje, prieš tai paleisti "Kursisnis prep".

"Kursisnis prep" sukuria nedidelę failų sistemą ir pradinius (įskaitant ir būtinus) failus, iskaitant kelis vartotojus ([Sandra, pass: 4321, user], [Paulius, pass 1234 , user], [Pitas, pass: 626827, admin], [m, pass: 1, admin]

Taip par sukuriami keli ".f_data.txt" failai skirtingose lokacijose, apibreziantys tuose aplnkuose esanciu failu/aplanku prieigos teises. (move/copy/delete kol kas su sita funkcija neveikia) 

Programa naudoja Vartotojai1.txt faila autentifikuoti vartotojams. Siuo metu prisijungti gali tik aprasyti vartotojai, sveciai negali.

Prisijungiama ivedus Vartotojo varda ir slaptazodi. Ju paparasoma is karto paleidus programa.
Jei per 30 sekundziu ivyksta 5 nesekmingi prisijungimai, prisijungimo junkcija uzrakinama 30 sekundziu. Pasibaigus laikui sistema grizta i iprasta rezima.

Komanda ir jos argumentas (pvz. open "folder name") rasomi atskirai

Ivedus komanda "comlist" gaunamas komandu sarasas

Ju paaiskinimai:
- exit               iseiti
- active_user_list   gauti prisijungusiu vartotoju sarasa
- back               grizti i tevini aplanka
- comlist            komandu sarasas
- copy               kopijuoti
- create             _#neveikia_
- delete             istrinti failus ir aplankus (pasiremkama atsidarius "select")
- dir_list           perziureti darbine direktorija
- dir_list_full      perziureti pilna darbines direktorijos medi
- move               perkelti failus/aplankus (pasiremkama atsidarius "select") _(veikia nestabiliai)_
- open               atidaryti faila (kol kas dar neveikia) arba direktorija (veikia)
- perm_check         grazina vartotojo teises
- rename             _#neveikia_

Pasirenkant failus (select metodas)(aktyvuojams move/copy/delete atvejais) ivedamas failo/aplanko pavadinimas.
"-" reiskia nepasirinktus failus/aplankus,
"*" - pasirinktus
