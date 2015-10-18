# Fase 1: Costruiamo il primo prototipo di germinatoio (fase 1)

[Alcune foto del CoderDojo Milano del 17-10-2015](CoderDojo20151017/README.md)

## Elenco del materiale

- 1 Scatola (rettangolare, 55.5cm x 39cm x 19cm)
- 24 Vasetti (rettangolare, _cm x _cm x _cm )
- X m. striscia illuminazione LED colore ROSSO
- Y m. striscia illuminazione LED colore BLU
- W g. terriccio
- N*coeff. semi

## Fasi salienti
### Di che cosa hanno bisogno i Lithops, da giovani
Come spesso accade, anche agli umani, le esigenze degli adulti non coincidono esattamente con quelle dei _bambini_. Se gli adulti tollerano condizioni più difficili, grazie alla loro forza o esperienza (o non potendo fare diversamente...), i _bambini_ non sono ancora pronti ad affrontare le asprezze della vita reale. Allo stesso modo: **un Lithops appena uscito dal suo minuscolo seme** non ha ancora la capacità di sopportare neppure un centesimo della siccità che invece non darebbe alcun fastidio ad una pianta di Lithops adulta.

Se, come è sempre opportuno fare, qualcuno si chiedesse come possono allora vivere i Lithops in natura, come possono riprodursi nei loro luoghi di origine aridi, la risposta sarebbe duplice: da un lato i luoghi aridi non sono tali per tutto il tempo dell'anno; dall'altro **i semi stessi dei Lithops non germinano durante tutto l'anno ma aspettano la breve (a volte _brevissima_) stagione umida per germinare**. Ci sono addirittura alcune piante, come la Lapidaria, uno stretto parente del Lithops, che aprono le loro capsule seminifere (cioè il contenitore dei semi che si forma alla base del fiore ormai seccato), soltanto quando sono colpite dalle gocce di pioggia. Il significato di questo adattamento è ovvio: i semi non si fidano del calendario per sapere quando è arrivata la stagione umida, ma rimangono protetti fino a quando sentono la prima goccia di pioggia sulla loro testa prima di rilasciare il loro preziosissimo carico di semi.

Noi che cosa dovremmo quindi realizzare, per i nostri semi?: niente di che, semplicemente il paradiso. Cioè, diversamente da quanto succede in natura, in cui per ogni mille semi, uno solo diventerà adulto, noi punteremo, avendo a disposizione solo decine di semi e non tutta questa pazienza, al massimo del risultato. Quindi dovremo realizzare le migliori condizioni possibili per la germinazione, trascurando che queste siano _innaturali_. Queste condizioni consistono in:
- umidità costante per i primi 10-20 giorni; dopodiché alternanze sempre più prolungate di secco e umido;
- temperatura fra i 15 e i 25 °C (meglio se più fresco di notte e più caldo di giorno);
- luce adeguata, almeno dopo che i semi sono germinati;
- assenza di predatori (quest'ultima condizione, come vedremo, non è banale come potrebbe sembrare)

Per realizzare tutte queste condizioni, nasce l'idea della scatola delle semine, cioè del **germinatoio**

### Acqua, tanta acqua, anzi no, non troppa
I Lithops hanno puntato tutto sull'adattamento a un ambiente caldo e arido. Sanno sopravvivere al freddo, al caldo, al caldo terrificante. Sanno aspettare pazientemente per mesi che cada loro in testa un goccio d'acqua, prima di _muoversi_. Ma, a causa della loro predilezione per l'estrema siccità, hanno dovuto pagare un prezzo: **hanno infatti perduto la capacità di sopportare ristagni d'acqua**. Lasciateli in _ammollo_ troppo a lungo (ci vuol poco: basta non svuotare il sottovaso dopo un acquazzone...) e saranno fortemente a rischio di marcire.
Per questo nel germinatoio dobbiamo prevedere delle ventole: per estrarre l'aria umida e far entrare aria che possa sì essere più fresca ma soprattutto meno umida. L'eccessiva umidità è utile solo ai funghi e alle muffe, che troverebbero non solo un clima favorevole ma anche delle vittime (le nostre plantule di Lithops), praticamente senza difese.

D'altra parte troppa poca acqua porta semplicemente alla disidratazione. Le piante appena nate dal seme, se si eccettua la prima settimana di crescita inarrestabile (quasi _magica_), allungano la loro radice solitaria alla ricerca d'acqua. Non hanno ancora potuto sviluppare la loro personale riserva, cosa che faranno solo con il tempo; e quindi occorre loro non essere mai in un ambiente completamente secco. **La situazione ideale per una giovane pianta di Lithops** è avere una radice che raggiunge zone sotterranee umide e di essere appoggiata su terra il più possibile secca (facile a dirsi!), con una leggera brezza che impedisca l'umidità eccessiva. Un aiuto, in questa situazione quasi irrealizzabile, è data... dai Lithops stessi. In particolare, quando si hanno a disposizione centinaia di semi, invece che decine, la crescita delle giovani piante strettamente appiccicate le une alle altre porta ad avere una sorta di separazione fra il fondo umido e l'aria superficiale e ha un effetto benefico sulla salute dell'intera colonia. Come dire: i giovani Lithops sono decisamente _social..._


### La luce e la regola del contrario
Di che colore sono le piante, nella loro maggioranza? La risposta è semplice: verdi. Quindi di quale colore, nella gamma delle lunghezze d'onda possibili, hanno più bisogno? Personalmente sarei stato dell'idea di dire "verde"... Ma sbaglierei. Il colore che vediamo nelle foglie, nei fusti, nelle parti molli delle piante, questo colore così facilmente associato alla natura stessa, corrisponde esattamente alla lunghezza d'onda che *non* serve alle piante per la fotosintesi. E che quindi restituiscono; sono altri i colori, e quindi le lunghezze d'onda, che assorbono.

Questo spiega la ragione dell'apparente contraddizione nel fatto di immaginare un germinatoio con luce rossa e blu. Come accennato, la contraddizione è solo apparente, dato che in realtà rosso e blu sono proprio le lunghezze d'onda che le piante assorbono (e che quindi non vanno a costituire il colore dei tessuti fotosintetizzanti). Per essere più precisi il rapporto stesso fra le due luci dovrebbe essere di circa 4 a 1 a vantaggio delle luci rosse. Tra l'altro è per questa ragione che si trovano in rete molte immagini di germinatoi travestiti apparentemente da discoteche anni '70.

## Realizzazione

### Dimensionamento

La scatola ha una lunghezza di circa 55.5cm ed una profondità di 39cm. Considerando un po' di "scarto", la superficie utile del coperchio per l'installazione delle striscioline di illuminazione dovrebbe ricoprire un'area di 1.440cmq, pari ad una potenza di irragiamento di circa 138W (per i dettagli di calcolo [guarda qui](https://docs.google.com/spreadsheets/d/1xajgQuW4uSA6tnMqnAGUhpJfXqwB1AFufzQxHgO6zJg/edit?usp=sharing)).

### L'assemblamento della scatola

Come facciamo a bloccare i vasetti?
L'idea è quella di creare un reticolo, forando opportunamente la scatola e facendo poi passare del filo (nylon?)...


## Suggerimenti e trucchetti

### Sì, ma quanto mi costa?
Informazioni di dettaglio di tutti i costi del materiale comprato fin qui...
