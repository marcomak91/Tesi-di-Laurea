# Tesi di Laurea
Relazione finale sullo stage univeritario

## Istruzioni per compilazione 

Per includere **Glossario** e **Acronimi** nel documento:
 * compilare una prima volta il file *tesi.tex*;
 * eseguire il comando: *makeindex -s tesi.ist -t tesi.glg -o tesi.gls tesi.glo*;
 * eseguire il comando: *makeindex -s tesi.ist -t tesi.alg -o tesi.acr tesi.acn*;
 * compilare due volte il file *tesi.tex*.

(**Attenzione**: nel caso dovessero mancare alcuni termini ripetere nuovamente il passaggio e il problema dovrebbe risolversi)

Per includere la **Bibliografia** nel documento:
 * compilare una prima volta il file *tesi.tex*;
 * eseguire il comando: *biber tesi*;
 * compilare ancora una volta il file *tesi.tex*.
