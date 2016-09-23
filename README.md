
# Event website template

Template per i siti degli eventi AISF.

Al momento ho preso il codice del sito AISF e l'ho modificato per renderlo il più simile possibile ai siti evento passati (lot, papap), che non erano gestiti con jekyll+githubpages.

La maggior parte dei dati "personalizzabili" del sito sta nella cartella \_data, nei vari file .yml. In questo modo, anche chi non mastica html dovrebbe poter riadattare il sito a suo piacimento.

TO DO:
- non funziona il tabs per il programma dettagliato, al momento commentato in programme.html. Il problema è che non so gestire più di 4 tab. Se provo a metterne 5, va a capo. Se li rimpicciolisco, è graficamente osceno;
- non capisco come mai le cars in facilities.html sono full page, quando su schermi tablet+pc dovrebbero essere a mezza pagina;
- alcuni testi sono ancora nei sorgenti html, e andrebbero spostati in \_data;
- sarebbe molto bello poter personalizare i colori in modo semplice. Per fare questo, definirei delle variabili per i due colori principali in \_data/general.yml, li importerei come variabili sass con liquid nel main.scss e poi li userei nel codice. Problema: alcuni colori non sono definiti tramite la proprietà color, ma con classi (es.: indigo). Non ho ancora indagato a fondo nel codice.
