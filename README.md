# Tema2-MN
Titoc Oana-Alexandra
313CA
Tema2-MN
Pentru task-ul 1 am scris o functie care comprima o imagine folosind descompunerea redusa a valorilor
singulare (SVD), returnand matricea Ak (new_X) care reprezinta aproximarea matricei initiale a imaginii.
Pentru task-ul 2 am implementat un algoritm care calculeaza componentele principale ale unei imagini
folosind descompunerea in valori singulare (SVD). Algoritmul normalizeaza imaginea prin scaderea
mediei fiecarui rand, aplica SVD asupra matricei normalizate și selecteaza primele componente
principale. La final se aproximeaza imaginea initiala cu ajutorul acestor componente si se adauga inapoi
media.
Pentru task-ul 3 am implementat un algoritm care calculeaza componentele principale ale unei imagini
folosind matricea de covarianta. Algoritmul normalizeaza imaginea prin scaderea mediei fiecarui rand,
calculeaza matricea de covarianta, obtine vectorii și valorile proprii ale matricei de covarianta, sorteaza
valorile proprii în ordine descrescatoare și selecteaza primele componente principale.
Pentru recunoasterea cifrelor scrise de mana am inceput prin a pregati datele de antrenament (imaginile
si etichetele corespunzatoare). Apoi, am aplicat algoritmul PCA (Principal Component Analysis) pentru
reducerea dimensionalitatii si pentru a extrage componentele principale. Am antrenat modelul de
clasificare prin K-Nearest Neighbors (KNN), utilizând datele de antrenament prelucrate. Am pregatit
imaginea de test. Modelul antrenat l-am folosit pentru a clasifica imaginea de test intr-una din cifrele
posibile.
Observații privind calitatea imaginii:
Calitatea imaginii comprimate depinde de numarul de componente principale alese. Cu cat alegem un
numar mai mic de componente principale, cu atat se pierde mai multa informatie și calitatea imaginii
comprimate scade.
