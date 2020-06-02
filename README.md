# STEGANOGRAFIA

## INTRODUZIONE

***Che cos’è?***

La steganografia è una tecnica che si prefigge di nascondere la comunicazione tra due interlocutori. Il termine è composto appunto dalle parole greche στεγανός (coperto) e γραφία (scrittura). 

A differenza della crittografia, consente di nascondere il messaggio attraverso un vettore che viaggia senza destare alcun sospetto. 


***Il primo utilizzo***

Il primo utilizzo registrato del termine fu nel 1499 da Johannes Trithemius nella sua Steganographia, un trattato sulla crittografia e la steganografia, mascherato come un libro sulla magia. L'opera incominciò a circolare e suscitò reazioni così allarmate che l'autore decise di non pubblicarla e ne distrusse molte copie ritenendo che non avrebbero mai dovuto vedere la luce.  

Continuò comunque a circolare in forma di minuta e fu pubblicata nel 1606. 


***I primi riferimenti nella storia ***

Tuttavia, tracce della steganografia si trovano già nell’antica Grecia quando Erodoto nelle sue storie narrò di Demarato di Sparta, che per avvisare i compatrioti di una possibile invasione scrisse su una tavoletta di cera il messaggio di allarme, coprendola poi con un'altra tavoletta con un messaggio innocuo. 

Erodoto narrò anche di Istieo che rasando la testa al suo servo, scrisse tramite un tatuaggio indelebile un messaggio sulla sua testa, poi ricoperto con la ricrescita dei capelli, con un’istruzione chiara ‘’quando arriverai a Mileto, dì ad Aristagora di rasarti i capelli’’. 


***La steganografia nella storia moderna ***

Ci sono esempi anche nella storia moderna: 

Durante entrambe le guerre mondiali le spie femminili utilizzavano il lavoro a maglia per inviare dei messaggi lasciando imperfezioni volontarie nel tessuto. 

Durante la seconda guerra mondiale furono usati dei vetri fotosensibili, un progetto dichiarato top secret, usato per mandare messaggi agli alleati. 

Jeremiah Denton ha ripetutamente battuto le palpebre in codice morse, scandendo la parola ‘’torture’’ nel 1966 in una conferenza stampa, con l’obiettivo di far capire agli americani che i prigionieri di guerra venivano torturati dai vietnamiti.  


## IL FUNZIONAMENTO DELLA STEGANOGRAFIA 

Con lo sviluppo della tecnologia digitale la steganografia ebbe un maggior utilizzo. La tecnica prevede che il “messaggio” che si deve trasferire vada inserito all’interno di un “contenitore” attraverso una “funzione” steganografica. A questo punto otterremo un “frammento stego”, il quale contiene l’informazione. Il ricevente, utilizzando poi la funzione di estrazione corretta, stabilita in precedenza con il mittente, otterrà il messaggio dal frammento stego. 


***La chiave di sicurezza ***

Per aumentare la sicurezza nella trasmissione di un messaggio venne introdotto l’utilizzo di una “chiave” di sicurezza, per l’autenticazione a 2 fattori. La suddetta chiave è di conoscenza sia da parte del mittente che del destinatario, in modo che chi riceve il contenitore con al suo interno l’informazione, oltre alla funzione di estrazione debba anche possedere la chiave d’accesso. 


***Il Meccanismo di Funzionamento ***

Questo è il meccanismo di funzionamento: 

Assumendo che E sia il messaggio segreto da nascondere e C sia il contenitore nel quale si nasconderà il messaggio, avremo una chiave K, conosciuta dal mittente (A) e dal destinatario (B). fₖ (C, E) sarà la funzione steganografica che nasconde E in C utilizzando la chiave K, mentre C’ è il frammento stego contenente l’informazione, il quale è sato ottenuto attraverso la funzione f. Infine, sfruttando la chiave K e il frammento C’, si sarà in grado di estrarre E. Tutto ciò grazie alla funzione inversa di f: fₖ-1 (C') 


## LE VARIE TECNICHE DELLA STEGANOGRAFIA

Nel tempo il bisogno di camuffare messaggi è sempre stato presente, difatti, non solo nel periodo dell’antica Grecia avveniva ciò, ma anche nei secoli successivi, per esempio, nel 1550 era diffuso il metodo della griglia di Cardano, che era un metodo per la scrittura di messaggi segreti inventato dal matematico italiano Girolamo Cardano.  


***Griglia Di cardano *** 

Questo metodo si basava sull’utilizzo di un foglio di carta, in cui venivano opportunatamente ritagliate delle aperture, attraverso le quali si scriveva un messaggio su un foglio sottostante e a questo punto, rimossa la griglia, si completavano le porzioni del messaggio terminando lo scritto, inserendo del testo di senso compiuto, fino ad ottenere un messaggio all’apparenza normale. Questa griglia era costituita da un foglio di carta spessa, oppure una pergamena o un sottile foglio metallico, possibilmente a righe per facilitare il ritaglio delle caselle, che venivano posizionate in maniera arbitraria sul foglio, senza nessuna precisa regola.  


***Cosa Fa Il Mittente?  ***

Il mittente del messaggio collocava la griglia su un foglio di carta bianco e scriveva il suo messaggio attraverso le aperture, inserendo in ogni finestrella una lettera, una sillaba o parole intere secondo la dimensione delle aperture. Quando aveva terminato la scrittura del messaggio, toglieva la griglia e completava il messaggio, scrivendo del testo con o senza significato collegato ai frammenti del testo da nascondere. Un consiglio che dava Cardano, era quello di ripassare il testo tre volte, in modo da smussare ogni irregolarità che potesse rivelare la presenza delle parole nascoste.  


***Cosa Fa Il Destinatario?  ***

A questo punto il destinatario del messaggio doveva essere in possesso di una griglia identica a quella utilizzata dal mittente, e per leggere il messaggio non doveva far altro che disporla sul foglio ricevuto e leggere il testo che filtrava dalle aperture.  

Oltre al metodo di Cardano c’era ed è ancora presente, il metodo acrostico, che è un metodo che utilizza una poesia o un testo qualunque e tramite una logica, si può ricavare il significato, per esempio, prendendo la prima lettera di ogni capoverso, si ottiene un messaggio di senso compiuto, oppure, prendendo un testo generico e tramite una combinazione pensata e scelta, per ogni parola si estraggono tutte le lettere che formeranno poi il messaggio nascosto. 

Per il funzionamento di ciò è sufficiente che mittente/i e destinatario/i abbiano concordato la particolarità del messaggio.  


***Esempio Metodo Acrostico Nel Poker***

Un altro esempio di metodo acrostico è la famosa frase che si dice spesso nel Poker, “Come Quando Fuori Piove”, dove la “C” identifica il simbolo “Cuori”, la “Q” identifica il simbolo “Quadri”, la “F” “Fiori” e la “P” “Picche”.  


***A Troppe Informazioni Diventa complicato  ***

La tecnica degli acrostici è una tecnica di memoria limitata ad un certo numero di informazioni memorizzabili, infatti questa tecnica diventa impegnativa nel momento in cui aumenta il volume di informazioni da dover memorizzare. 


***Camuffamento di Immagini ***

Un altro mezzo molto usato per nascondere le informazioni è quello di inserirle all’interno di un’immagine (dipinto o fotografia) in modo da nascondere dati e informazioni senza dare nell’occhio. In passato venivano utilizzati i dipinti, ma al giorno d’oggi questo metodo viene utilizzato prevalentemente ritoccando le immagini. 

Vengono inseriti nell’immagine alcuni dettagli che soltanto il destinatario sarà in grado di comprendere. 

Durante la Seconda Guerra Mondiale, il direttore dell’FBI inventò la tecnica dei micropunti fotografici, la quale consiste nel ridurre alla dimensione di un piccolissimo punto un’immagine. Questa verrà poi inserita all’interno di un’altra immagine e quando il ricevente ingrandirà il punto otterrà l’immagine di buona qualità con al suo interno l’informazione. 

Inoltre, esiste un metodo molto più complesso, che è quello di inserire delle sequenze di bit (messaggio) in un’immagine digitalizzata. A prima vista non si noterà alcuna differenza, in quanto l’immagine può al massimo risultare un po’ sporca rispetto all’originale. Per fare uso di queste tecniche esistono programmi abbastanza sofisticati. Ad esempio, prendendo come spunto una immagine rappresentante un paesaggio, sulla sinistra avremo un frammento di immagine nel quale i pixel sono messi in modo da descrivere il numero pi (pigreco). 


## LE VARIE TECNICHE DELLA STEGANOGRAFIA NELL’INFORMATICA 

La steganografia comprende l'occultamento di informazioni all'interno di file di computer.  

Nella steganografia digitale, le comunicazioni elettroniche possono includere la codifica steganografica all'interno di un livello di trasporto, ad esempio un file di documento, un file di immagine, un programma o un protocollo. 

I file multimediali sono ideali per la trasmissione steganografica a causa della loro grande dimensione. Ad esempio, un mittente potrebbe inviare un file di immagine innocuo e regolare il colore di un pixel ogni cento, per farlo corrispondere a un carattere alfabetico. La modifica è così sottile che qualcuno che non la cerca in modo specifico è improbabile che la noti. 

Esistono innumerevoli tecniche stenografiche e sono divise in due principali categorie: 

***La steganografia iniettiva***

La steganografia iniettiva, la quale consiste nell’inserire un messaggio all’interno di un contenitore già esistente modificandolo in modo tale che risulti all’occhio umano praticamente indistinguibile dall’originale. 

***La steganografia generativa ***

L'altra categoria è la steganografia generativa consiste nel prendere il messaggio segreto e costruirgli un opportuno contenitore in modo tale da nascondere il messaggio nel miglior modo possibile. 


Adesso che abbiamo analizzato le due principali categorie, passiamo alle tecniche più comunemente utilizzate, esse sono principalmente tre: 

***La steganografia sostitutiva ***
La stenografica sostitutiva è la tecnica più diffusa in quest’ambito. Alla base di questa tecnica è presente il concetto che qualsiasi tipo di segnale porta con sé un disturbo (o rumore), il quale può capitare che alteri il segnale stesso. 

Alterando tale disturbo e sostituendolo con il nostro messaggio, possiamo avere un contenuto praticamente indistinguibile dall’originale ma allo stesso tempo contenete un messaggio nascosto. 

***Facciamo un esempio ***

Applicare questa tecnica nell’ambito informatico è abbastanza semplice, prendiamo come esempio una foto. Modificando i bit meno significativi (LSB) di questo file possiamo nascondere un messaggio. Dato che questo tipo di bit sono spesso soggetti ad errore è più difficile che tale messaggio venga riconosciuto. 

In un'immagine i bit meno significativi sono la parte finale del codice del colore RGB di un pixel. Inserendo in ogni pixel una parte del messaggio è possibile modificare questa immagine in modo impercettibile all’occhio umano, poiché il valore dell’ultimo bit di un codice RGB è poco influente sul colore effettivo. 

Volendo si può modificare il codice di un solo colore (per esempio il blu), in modo da avere un effetto ancora meno percepibile a discapito, però, della lunghezza del messaggio. 

La stessa tecnica può essere applicata ai file audio andando a modificare il rumore di fondo e inserendoci il messaggio. 

In entrambi i casi, qualsiasi tipo di alterazione portata al file (es. Compressione), andrà a cancellare l’informazione contenuta all’interno. 


***Steganografia selettiva ***

Un'altra tecnica è la steganografia selettiva, questa tecnica ha un uso meno diffuso rispetto alla precedente, data la più complessa e laboriosa esecuzione. Per esempio, si fissi una semplice funzione Hash che vale 1 se il contenitore contiene un numero dispari 1, e 0 se ne contiene un numero pari. Nel caso in cui si voglia trasmettere come informazione un bit dal valore 0 si cercherà un contenitore con numero pari di 1 e lo si invierà. Il vantaggio di questo metodo è che i contenitori non vengono alterati. 


***Steganografia costruttiva ***

L’ultima tecnica è quella della steganografia costruttiva, questa tecnica è molto simile alla precedente, l’unica differenza è l’approccio al problema. Mentre precedentemente si provava a creare un pacchetto su misura, con questa tecnica si prova a modificare un pacchetto già esistente in modo che rispetti alcuni criteri. Il difetto di questo metodo risiede nel fatto che non è facile costruire un modello del rumore. 