# Appunti HTML, CSS e JavaScript

**HTML**: scegli che cosa rappresenta un elemento. **CSS**: scegli aspetto e disposizione. **JavaScript**: gestisci azioni e cambiamenti che richiedono codice.

Ogni voce indica a cosa serve e quando sceglierla. I nomi delle nostre classi, come `.assets-title`, sono nomi scelti da noi: il loro comportamento dipende dalle regole CSS.

# HTML

**`<!DOCTYPE html>`**  
Dichiara che la pagina usa HTML moderno. Va all’inizio del documento, prima di `<html>`.

**`<html>`**  
È l’elemento che contiene tutta la pagina: sia `<head>` sia `<body>`.

**`lang="it"`**  
Indica che il contenuto è in italiano. Si mette su `<html>` e aiuta anche la pronuncia dei lettori di schermo.

**`<head>`**  
Contiene le informazioni sulla pagina e i file collegati. Usalo per impostazioni, titolo della scheda, CSS e script.

**`<meta charset="utf-8">`**  
Imposta la codifica del testo, così il browser interpreta correttamente accenti e altri caratteri.

**`<meta name="viewport" content="width=device-width, initial-scale=1">`**  
Fa usare al browser mobile la larghezza del dispositivo per la pagina. Serve insieme al CSS per l’adattamento allo schermo.

**`<title>`**  
Imposta il titolo nella scheda del browser. Per un titolo visibile dentro la pagina usa invece un elemento come `<h1>`.

**`<link rel="stylesheet" href="style.css">`**  
Collega il foglio CSS. Si inserisce nel `<head>`.

**`<script src="script.js" defer></script>`**  
Collega il file JavaScript. `src` indica il percorso del file.

**`defer`**  
Su uno script esterno classico, permette il caricamento durante la lettura dell’HTML e ne rimanda l’esecuzione a quando l’HTML è stato letto.

**`<body>`**  
Contiene gli elementi della pagina: menu, testi, immagini, pulsanti e sezioni.

**`<header>`**  
È l’intestazione della pagina oppure di una sezione. Sceglilo quando raggruppi titolo, introduzione o elementi iniziali.

**`<nav>`**  
Identifica un gruppo importante di collegamenti di navigazione, come il menu con Concept, Sitemap e Assets.

**`<main>`**  
Identifica il contenuto principale della pagina. Nel nostro sito ne usiamo uno, dopo la barra di navigazione.

**`<section>`**  
Raggruppa un argomento riconoscibile, normalmente con un titolo: per esempio Concept o Assets. Sceglilo per una vera sezione di contenuto.

**`<article>`**  
Raggruppa un contenuto che ha senso anche da solo, come una scheda autonoma. Lo abbiamo usato per i singoli blocchi del Concept.

**`<footer>`**  
È la parte conclusiva della pagina o di una sezione. Può contenere autore, collegamenti e ritorno all’inizio.

**`<div>`**  
È un contenitore generico. Sceglilo quando devi raggruppare elementi per il layout, senza identificare una nuova sezione o intestazione.

**`<h1>`**  
È il titolo principale della pagina: nel nostro caso la presentazione di Radici.

**`<h2>`**  
È il titolo di una sezione principale, come Assets. Sceglilo per un argomento direttamente sotto il titolo della pagina.

**`<h3>`**  
È il titolo di una parte dentro una sezione: Palette è una parte di Assets. Scegli il livello per la struttura; la grandezza si regola con CSS.

**`<p>`**  
Contiene un paragrafo. Usalo per una spiegazione o un testo continuo, come l’introduzione della Sitemap.

**`<span>`**  
Raggruppa un breve contenuto dentro una riga. Sceglilo per applicare una classe a una parola o al testo dentro un pulsante.

**`<br>`**  
Inserisce un’interruzione di riga dentro lo stesso testo. Per separare due paragrafi usa due `<p>`; per distanziarli usa CSS.

**`<ul>`**  
Crea una lista in cui l’ordine non esprime una sequenza, come le voci di un menu. Ogni voce va in un `<li>`.

**`<ol>`**  
Crea una lista ordinata, normalmente numerata. Sceglila per passaggi da seguire in sequenza.

**`<li>`**  
È una singola voce di una lista. Si inserisce dentro `<ul>` oppure `<ol>`.

**`<a>`**  
Crea un collegamento verso una pagina, un file o una posizione della pagina. Sceglilo quando l’azione è andare a una destinazione.

**`href`**  
Indica la destinazione di un link. `href="#assets"` cerca l’elemento con `id="assets"`; un URL completo apre quella pagina.

**`<button>`**  
Crea un pulsante per eseguire un’azione, per esempio cambiare scheda. Sceglilo per un controllo interattivo, anziché per un collegamento.

**`type="button"`**  
Indica un pulsante che non invia un modulo. È il tipo usato per i pulsanti delle nostre schede.

**`<details>`**  
Crea un contenuto apribile e richiudibile con HTML. Sceglilo per le voci Assets o per domande con risposta nascosta.

**`<summary>`**  
È il titolo cliccabile di un `<details>`. Va come primo elemento al suo interno; il testo e l’immagine vengono dopo.

**`open`**  
Su `<details>`, fa partire la voce aperta. Per farla partire chiusa ometti l’attributo: anche `open="false"` è considerato presente.

**`<img>`**  
Mostra un file immagine esterno: PNG, JPG oppure SVG. Sceglilo per fotografie, tavole esportate e immagini salvate nei file del progetto.

**`src`**  
Indica il file da caricare, per esempio `src="assets/images/sitemap.png"`. Negli script indica invece il file JavaScript.

**`alt`**  
Descrive il significato di un’immagine `<img>` per chi non la vede. Usa `alt=""` quando l’immagine è soltanto decorativa.

**`width` e `height` negli attributi HTML**  
Sugli `<img>` indicano le dimensioni e aiutano a riservare spazio con le giuste proporzioni. Il CSS può adattare la dimensione visualizzata.

**`<svg>`**  
Inserisce un disegno vettoriale direttamente nell’HTML. Sceglilo per icone e triangoli da colorare o ruotare con CSS.

**`viewBox`**  
Definisce le coordinate interne di un SVG. `viewBox="0 0 22 22"` descrive un’area di disegno 22 × 22, ridimensionabile con CSS.

**`<path>`**  
Disegna un tracciato dentro un SVG. L’attributo `d` contiene le istruzioni della forma, come quelle del nostro triangolo.

**`<rect>`**  
Disegna un rettangolo dentro un SVG. È adatto a forme semplici, come il piccolo cursore accanto alle etichette.

**`class`**  
Assegna nomi riutilizzabili agli elementi. Sceglila per applicare lo stesso stile a più elementi; puoi assegnare più classi separate da spazi.

**`id`**  
Assegna un identificatore unico nella pagina. Sceglilo per la destinazione di un link, un collegamento accessibile o un elemento specifico in JavaScript.

**`aria-label`**  
Assegna direttamente un nome accessibile, per esempio `aria-label="Apri menu"` a un pulsante con una sola icona.

**`aria-labelledby`**  
Usa il testo di un elemento esistente come nome accessibile. `aria-labelledby="assets-title"` richiama il titolo che ha quell’ID.

**`aria-hidden="true"`**  
Fa ignorare l’elemento ai lettori di schermo, lasciandolo visibile. Sceglilo per decorazioni come il nostro triangolino SVG.

**`tabindex="-1"`**  
Consente di portare il focus sull’elemento tramite codice, senza aggiungere una tappa al percorso con Tab. Lo usiamo sul contenuto principale.

**`popover="auto"`**  
Definisce un pannello a comparsa gestito dal browser, come il menu mobile. Supporta anche la chiusura con Esc e il clic esterno.

**`popovertarget`**  
Collega un pulsante a un popover: il valore è l’ID del pannello, senza `#`.

**`hidden`**  
È l’attributo usato per nascondere un elemento. JavaScript può aggiungerlo o toglierlo tramite la proprietà `.hidden`.

**`<!-- commento -->`**  
Inserisce una nota nel codice HTML. Usalo per spiegazioni e divisioni fra sezioni; il browser non mostra il commento nella pagina.

# CSS

**`*`**  
Seleziona tutti gli elementi. Sceglilo per regole di base comuni, come `box-sizing: border-box` e l’azzeramento degli spazi iniziali.

**`.classe`**  
Seleziona gli elementi con quella classe. È la scelta abituale per gli stili riutilizzabili, come `.assets-title`.

**`#id`**  
Seleziona l’elemento con quell’ID. Sceglilo quando la regola riguarda proprio quell’elemento unico.

**`[attributo]`**  
Seleziona gli elementi che hanno l’attributo indicato. Per esempio `[open]` identifica i `<details>` aperti.

**`[attributo="valore"]`**  
Seleziona gli elementi con un preciso valore dell’attributo. Sceglilo quando la sola presenza dell’attributo non basta.

**`A B`**  
Seleziona tutti i B dentro A, anche a più livelli di profondità. Sceglilo quando possono esserci contenitori intermedi.

**`A > B`**  
Seleziona soltanto i B figli diretti di A. Sceglilo quando la regola deve riguardare il primo livello interno.

**`A + B`**  
Seleziona un B immediatamente dopo un A con lo stesso genitore. Lo usiamo per mettere una linea fra due `.pillar` consecutivi.

**`:root`**  
Seleziona la radice della pagina. Lo usiamo per definire variabili condivise, come colori, spazi e dimensioni dei caratteri.

**`--nome-variabile`**  
Definisce un valore riutilizzabile: `--spacing-24: 24px`. Le variabili possono essere ridefinite in un tema, componente o media query.

**`var()`**  
Richiama una variabile: `padding: var(--spacing-24)`. Sceglilo quando vuoi utilizzare un valore già definito nel progetto.

**`@font-face`**  
Definisce un font e il file da cui caricarlo. Per applicarlo agli elementi si usa poi `font-family`.

**`src` dentro `@font-face`**  
Indica il percorso del file del font, per esempio un file `.woff2` nella cartella `assets/fonts`.

**`format()`**  
Indica il formato della risorsa del font, per esempio `format("woff2")`. Fa parte della dichiarazione `src`.

**`font-display`**  
Regola la visualizzazione durante il caricamento del font. `swap` permette di mostrare prima un font di ripiego.

**`font-family`**  
Sceglie il carattere, come Mona Sans. Usalo quando cambia il tipo di font, non la sua grandezza o il suo peso.

**`font-size`**  
Sceglie la dimensione del testo. Nel nostro sito richiama le variabili dei titoli e dei paragrafi.

**`font-weight`**  
Sceglie lo spessore del carattere: `400` normale, `500` medio, `700` grassetto. Usa le variabili già disponibili per questi valori.

**`font`**  
È una forma abbreviata per più proprietà del carattere. `font: inherit` fa riprendere al pulsante lo stile del testo del genitore.

**`line-height`**  
Regola l’altezza delle righe. `1.5` significa una volta e mezza la dimensione del carattere; serve alla leggibilità dei paragrafi.

**`letter-spacing`**  
Regola lo spazio fra le lettere. Sceglilo per modificare la spaziatura di etichette o titoli.

**`font-feature-settings`**  
Controlla caratteristiche tipografiche del font. Per esempio `"liga" 0` disattiva le legature, quando la regola è supportata e applicata.

**`-webkit-font-smoothing`**  
Regola la resa dei contorni del testo nei sistemi che lo supportano, soprattutto macOS. Non modifica la dimensione dichiarata del font.

**`text-align`**  
Allinea il testo dentro il contenitore: `left`, `center` o `right`. Per centrare il contenitore stesso servono regole di layout.

**`text-transform`**  
Cambia la presentazione delle lettere: `uppercase` mostra le maiuscole. Il testo scritto nell’HTML rimane quello originale.

**`text-decoration`**  
Controlla decorazioni come la sottolineatura. Usa `underline` per aggiungerla oppure `none` per rimuoverla.

**`text-wrap`**  
Controlla la distribuzione delle righe del testo. `balance` cerca righe equilibrate ed è utile per i nostri titoli.

**`color`**  
Imposta il colore del testo e il valore di `currentColor`. Sceglilo per scritte e per icone che usano quel colore.

**`fill`**  
Imposta il riempimento delle forme SVG. Nel nostro progetto `fill: currentColor` fa seguire alle icone il loro colore CSS.

**`currentColor`**  
È un valore che riprende la proprietà `color` dell’elemento. Usalo per collegare il colore di riempimenti o bordi al colore del testo.

**`background`**  
È la forma abbreviata per più proprietà dello sfondo. Quando lo usi, può reimpostare anche proprietà dello sfondo dichiarate prima.

**`background-color`**  
Cambia soltanto il colore di fondo. Sceglilo quando vuoi conservare le altre impostazioni dello sfondo, come l’immagine.

**`background-image`**  
Imposta un’immagine di sfondo, per esempio nella hero. Per un’immagine che fa parte del contenuto usa un `<img>` con descrizione.

**`color-mix()`**  
Mescola due colori. Sceglilo per ricavare una variante di un colore esistente, per esempio per uno stato al passaggio del mouse.

**`padding`**  
È lo spazio interno, fra contenuto e bordo. Sceglilo per dare respiro dentro una sezione, scheda o pulsante.

**Valori di `padding` e `margin`**  
Un valore: tutti i lati. Due: sopra/sotto e destra/sinistra. Tre: sopra, lati, sotto. Quattro: sopra, destra, sotto, sinistra.

**`margin`**  
È lo spazio esterno al bordo. Sceglilo per distanziare un elemento da ciò che gli sta intorno.

**`margin-top`**  
Regola soltanto lo spazio esterno sopra l’elemento. Usalo quando vuoi aumentare la distanza da ciò che lo precede.

**`margin-bottom`**  
Regola soltanto lo spazio esterno sotto l’elemento. Nel nostro sito separa l’immagine dalle voci che vengono dopo.

**`margin-left`**  
Regola il margine sinistro. Insieme a `margin-right: auto` può centrare un blocco che ha una larghezza limitata.

**`margin-right`**  
Regola il margine destro. Usa entrambi i margini laterali `auto` per distribuire ai lati lo spazio libero di un blocco.

**`gap`**  
Imposta la distanza fra i figli di un contenitore flex o grid. Sceglilo per spazi regolari fra più elementi dello stesso gruppo.

**`width`**  
Imposta la larghezza dell’elemento. `100%` lo fa seguire alla larghezza del suo contenitore, rispettando le altre regole di dimensionamento.

**`height`**  
Imposta l’altezza. Per le immagini responsive `height: auto` mantiene le proporzioni quando cambia la larghezza.

**`max-width`**  
Imposta un limite massimo alla larghezza. Sceglilo per un contenitore che deve restringersi sul telefono ma restare contenuto sul desktop.

**`min-width`**  
Imposta un limite minimo alla larghezza. `min-width: 0` permette a un elemento flex o grid di restringersi oltre il minimo automatico del contenuto.

**`max-height`**  
Limita l’altezza. Con `overflow-y: auto` permette a un pannello lungo di scorrere al suo interno.

**`box-sizing: border-box`**  
Include padding e bordi dentro `width` e `height`. Il margine resta esterno; lo usiamo come regola generale.

**`border`**  
Imposta spessore, tipo e colore di tutti i bordi: per esempio `1px solid black`.

**`border-top`**  
Imposta soltanto il bordo superiore. Sceglilo per una linea sopra una voce o una sezione.

**`border-bottom`**  
Imposta soltanto il bordo inferiore. Sceglilo per chiudere visivamente una lista o separare il contenuto successivo.

**`border-left`**  
Imposta soltanto il bordo sinistro. Nel Concept desktop lo usiamo per separare le colonne.

**`border-right`**  
Imposta soltanto il bordo destro. Sceglilo quando la linea deve comparire esclusivamente su quel lato.

**`border-inline`**  
Nel nostro testo orizzontale imposta insieme i bordi laterali. È la proprietà usata per le due linee ai lati del contenitore.

**`border-block`**  
Nel nostro testo orizzontale imposta insieme il bordo sopra e quello sotto. Sceglilo per delimitare un blocco verticalmente.

**`border-color`**  
Cambia il colore dei bordi già impostati. Sceglilo quando vuoi mantenere il loro spessore e il loro tipo.

**`border-radius`**  
Arrotonda gli angoli. Si usa su pulsanti, schede o immagini quando il disegno richiede angoli arrotondati.

**`display: block`**  
Dispone normalmente l’elemento su una riga propria. Sceglilo per un contenitore o un’immagine da trattare come blocco.

**`display: inline`**  
Fa scorrere l’elemento insieme al testo. Sceglilo per frammenti di una riga; sui normali elementi inline larghezza e altezza non funzionano come sui blocchi.

**`display: inline-block`**  
Mantiene l’elemento nella riga, permettendo di assegnare larghezza e altezza. Sceglilo per piccoli blocchi affiancati al testo.

**`display: none`**  
Nasconde l’elemento e toglie il suo spazio dal layout. Lo usiamo per i testi delle schede non selezionate.

**`display: flex`**  
Dispone i figli lungo un asse principale. Sceglilo per una fila di pulsanti, una colonna di contenuti o titolo e triangolo affiancati.

**`flex-direction`**  
Sceglie l’asse principale: `row` per una riga, `column` per una colonna. Cambia anche il significato degli allineamenti flex.

**`flex-wrap`**  
Con `wrap` permette ai figli flex di andare su più righe quando manca spazio. Con `nowrap` restano sulla stessa riga.

**`flex-shrink`**  
Regola quanto un figlio flex può restringersi. `0` impedisce il restringimento: lo usiamo per mantenere riconoscibili le icone.

**`align-items`**  
Allinea tutti i figli sull’asse trasversale di flex: con `row` è verticale, con `column` è orizzontale. In grid allinea i figli verticalmente nelle celle.

**`align-self`**  
Modifica quell’allineamento per un solo figlio. Sceglilo quando un elemento deve avere un allineamento diverso dagli altri.

**`justify-content`**  
In flex allinea lungo l’asse principale: `center` centra; `space-between` mette spazio fra gli elementi. Con `row` agisce orizzontalmente, con `column` verticalmente.

**`display: grid`**  
Crea una griglia di righe e colonne. Sceglilo per i dati del corso in due o quattro colonne, oppure per tre schede uguali.

**`grid-template-columns`**  
Definisce le colonne di una griglia. `repeat(2, minmax(0, 1fr))` crea due colonne uguali; richiede un contenitore grid.

**`repeat()`**  
Ripete una definizione di colonne o righe. `repeat(3, 1fr)` è una forma compatta di `1fr 1fr 1fr`.

**`minmax()`**  
Imposta una dimensione minima e massima di una traccia grid. `minmax(0, 1fr)` permette alla colonna di restringersi con un minimo di zero.

**`fr`**  
Divide lo spazio disponibile della griglia in quote. `1fr 1fr` dà due quote uguali; `2fr 1fr` assegna una quota doppia alla prima.

**`position: relative`**  
Mantiene l’elemento nel flusso normale e lo rende un riferimento per figli assoluti. Sceglilo sul contenitore di una decorazione posizionata.

**`position: absolute`**  
Toglie l’elemento dal flusso normale e lo posiziona rispetto al suo riferimento, spesso un genitore `relative`. Lo usiamo per linee e aree sovrapposte.

**`position: fixed`**  
Normalmente posiziona l’elemento rispetto alla finestra e lo mantiene fermo durante lo scorrimento. Sceglilo per un controllo che deve restare visibile.

**`top`**  
Su un elemento posizionato regola la distanza dal lato superiore del suo riferimento.

**`bottom`**  
Su un elemento posizionato regola la distanza dal lato inferiore del suo riferimento.

**`left`**  
Su un elemento posizionato regola la distanza dal lato sinistro del suo riferimento.

**`right`**  
Su un elemento posizionato regola la distanza dal lato destro del suo riferimento.

**`inset`**  
Abbrevia `top`, `right`, `bottom` e `left`. Con `position: absolute` e `inset: 0` un elemento può coprire tutta l’area del riferimento.

**`z-index`**  
Regola l’ordine di sovrapposizione all’interno del contesto di sovrapposizione dell’elemento. Lo usiamo per mostrare il menu sopra il contenuto.

**`overflow`**  
Gestisce il contenuto che supera il contenitore: `visible` lo mostra, `hidden` lo taglia, `auto` permette lo scorrimento quando serve.

**`overflow-y`**  
Gestisce soltanto il superamento verticale. Scegli `auto` per un menu o pannello che deve scorrere quando è troppo alto.

**`transform`**  
Applica trasformazioni visive tramite funzioni come `rotate()` o `translateY()`. Non ridispone gli elementi vicini come farebbe un nuovo margine.

**`translateY()`**  
Sposta visivamente un elemento in verticale. Sceglilo per un piccolo spostamento senza modificare la disposizione degli altri elementi.

**`rotate()`**  
Ruota un elemento. `rotate(180deg)` capovolge il triangolo; `rotate(0deg)` lo mostra nella direzione originale del disegno.

**`scaleY()`**  
Moltiplica la dimensione visiva verticale. `scaleY(2)` permette di mostrare una linea con spessore doppio senza cambiare il layout.

**`transform-origin`**  
Sceglie il punto di riferimento della trasformazione. `top` fa partire dall’alto una trasformazione come `scaleY()`.

**`opacity`**  
Regola la trasparenza da `0` a `1`. A zero l’elemento conserva spazio e può ancora ricevere interazioni; scegli `display: none` per toglierlo dal layout.

**`::before`**  
Crea una parte aggiuntiva prima del contenuto dell’elemento. Lo usiamo per una linea decorativa sopra una scheda.

**`::after`**  
Crea una parte aggiuntiva dopo il contenuto. Può essere posizionata sopra tutta la scheda per estendere l’area del suo pulsante.

**`content`**  
Definisce il contenuto di `::before` e `::after`. `content: ""` crea una parte vuota, da disegnare con le altre proprietà CSS.

**`::marker`**  
Seleziona il pallino di una lista o il triangolo nativo di un `<summary>`. Usalo per cambiarne il colore o il contenuto.

**`::-webkit-details-marker`**  
Seleziona il triangolo nativo di `<summary>` nei browser che supportano questa forma. Lo nascondiamo quando inseriamo il nostro triangolo SVG.

**`:has()`**  
Seleziona un elemento in base a una relazione con altri elementi. Nel nostro caso controlla se il componente contiene una voce `.is-selected`.

**`:not()`**  
Esclude gli elementi che soddisfano una condizione. `.breakdownTabs-item:not(.is-selected)` identifica le voci non selezionate.

**`:hover`**  
Identifica l’elemento sotto il puntatore. Sceglilo per uno stile al passaggio del mouse.

**`:focus`**  
Identifica l’elemento che ha il focus, ottenuto con tastiera, clic o codice. Serve quando vuoi reagire al focus in generale.

**`:focus-visible`**  
Identifica il focus per cui il browser ritiene utile un indicatore visibile, tipicamente durante l’uso della tastiera. Sceglilo per il nostro contorno di focus.

**`:popover-open`**  
Identifica un elemento popover attualmente aperto. Lo usiamo per cambiare lo stato visivo e l’etichetta del menu.

**`outline`**  
Disegna un contorno che non occupa spazio nel layout. Sceglilo per rendere visibile il focus, mantenendo i bordi del componente.

**`outline-offset`**  
Regola la distanza del contorno dall’elemento. Un valore positivo lo allontana, uno negativo lo sposta verso l’interno.

**`cursor`**  
Sceglie la forma del puntatore. `pointer` mostra la mano sui controlli cliccabili; l’azione è gestita dall’HTML o da JavaScript.

**`pointer-events`**  
Regola se l’elemento può essere il bersaglio del puntatore. `none` è utile per una decorazione che deve lasciare passare i clic.

**`list-style`**  
Regola i marcatori delle liste. `none` rimuove pallini o numeri: è la scelta usata per il menu e per la lista delle schede.

**`@media`**  
Racchiude regole che valgono soltanto quando una condizione è vera. Sceglilo per adattare la pagina allo schermo o alle capacità del dispositivo.

**`@media (max-width: 800px)`**  
Attiva le regole quando la finestra è larga al massimo 800px, inclusi. Nel nostro sito è la soglia scelta per gli schermi piccoli.

**`@media (min-width: 1000px)`**  
Attiva le regole da 1000px in su, inclusi. Nel nostro sito gestisce il passaggio alla disposizione desktop.

**`(hover: hover)`**  
Verifica che il dispositivo di puntamento principale permetta il passaggio sopra un elemento. Serve a limitare gli effetti hover ai dispositivi adatti.

**`(pointer: fine)`**  
Verifica che il dispositivo di puntamento principale sia preciso, come un mouse. Lo combiniamo con `hover` per gli effetti sulle schede.

**`(prefers-reduced-motion: reduce)`**  
Verifica la preferenza dell’utente per movimenti ridotti. Serve per ridurre o eliminare animazioni quando sono presenti.

**`transition`**  
Rende graduale il passaggio fra due valori di una proprietà, per esempio quando cambia un colore al passaggio del mouse.

**`animation`**  
Applica una sequenza di animazione, anche ripetuta. Sceglila per una sequenza definita con `@keyframes`, anziché per un semplice cambio di stato.

**`@keyframes`**  
Definisce le tappe di una sequenza animata. Per eseguirla su un elemento serve anche una proprietà `animation` che la richiami.

**`anchor-name`**  
Assegna un nome CSS a un elemento che deve fare da riferimento di posizione, come il pulsante del menu.

**`position-anchor`**  
Indica quale riferimento usare per un elemento posizionato. Collega il pannello al nome definito con `anchor-name`.

**`anchor()`**  
Usa la posizione di un lato del riferimento. Per esempio `top: anchor(bottom)` posiziona il pannello a partire dal bordo inferiore del pulsante.

**`anchor-size()`**  
Usa una dimensione del riferimento. `anchor-size(width)` permette di ricavare la larghezza dal pulsante collegato.

**`calc()`**  
Calcola una misura: `calc(64px - var(--hero-content-gap))`. Sceglilo quando devi combinare dimensioni e variabili con un calcolo.

**`inherit`**  
Fa riprendere una proprietà dal genitore. Sceglilo per uniformare un pulsante al testo circostante, per esempio con `font: inherit`.

**`auto`**  
Lascia il calcolo al browser, con effetti diversi secondo la proprietà. `height: auto` mantiene le proporzioni dell’immagine; i margini laterali `auto` possono centrare un blocco.

**`!important`**  
Contrassegna una dichiarazione come importante nella cascata CSS. Per le modifiche normali del progetto preferisci intervenire sulla regola e sull’ordine appropriati.

**`px`**  
È un’unità in pixel CSS. Nel nostro progetto la usiamo per gli spazi condivisi dei contenitori, richiamati tramite variabili.

**`em`**  
Per spazi e dimensioni si basa sul font dell’elemento; dentro `font-size` si basa sul font del genitore. Sceglilo per misure che devono seguire il testo.

**`%`**  
È una misura relativa, il cui riferimento dipende dalla proprietà. Per `width`, ad esempio, `100%` segue la larghezza del contenitore.

**`dvh`**  
È una quota dell’altezza dinamica della finestra: `100dvh` corrisponde a tutta l’altezza disponibile, aggiornata anche con le barre del browser mobile.

**`/* commento */`**  
Inserisce una nota nel CSS. Sceglilo per spiegare una regola o dividere le categorie del foglio.

# JavaScript

**`const`**  
Dichiara un riferimento che non riassegni, per esempio il pulsante trovato nella pagina. Puoi comunque modificare l’elemento a cui si riferisce.

**`let`**  
Dichiara una variabile che può cambiare, come l’indice di un ciclo. Nel nostro `for`, ogni giro mantiene il proprio indice per il gestore del clic.

**`document.querySelector()`**  
Trova il primo elemento corrispondente a un selettore CSS. Sceglilo per un contenitore o pulsante specifico; se non trova nulla restituisce `null`.

**`document.querySelectorAll()`**  
Trova tutti gli elementi corrispondenti, nell’ordine dell’HTML. Sceglilo per raccogliere tutte le voci o tutti i pulsanti del componente.

**`NodeList`**  
È un elenco di elementi, come quello restituito da `querySelectorAll()`. Puoi contarli e raggiungerli tramite indice.

**`.length`**  
Restituisce il numero di elementi dell’elenco. Sceglilo per sapere quante volte deve ripetersi il ciclo sulle voci.

**`[indice]`**  
Raggiunge una posizione nell’elenco: `[0]` è la prima, `[1]` la seconda, `[2]` la terza.

**`function`**  
Definisce un’azione riutilizzabile. La funzione viene eseguita quando viene chiamata, per esempio `selectBreakdownTab(2)`.

**Parametri di una funzione**  
Sono le informazioni che la funzione riceve. `selectedIndex` indica quale voce scegliere; passando `2` chiediamo la terza voce.

**`for`**  
Ripete un blocco di istruzioni. Sceglilo per controllare tutte le voci o assegnare un gestore a tutti i pulsanti.

**`i++`**  
Aumenta `i` di uno. Nel ciclo fa passare dalla posizione corrente alla successiva.

**`if`**  
Esegue un blocco quando una condizione è vera. Lo usiamo per riconoscere la voce con l’indice richiesto.

**`else`**  
Esegue il blocco alternativo quando la condizione dell’`if` è falsa. Nel nostro ciclo toglie la selezione alle altre voci.

**`return`**  
Termina la funzione corrente e può restituire un risultato. Sceglilo anche per uscire subito quando non ci sono le condizioni per continuare.

**`===`**  
Confronta uguaglianza di valore e tipo. `i === selectedIndex` controlla se siamo sulla voce richiesta; `1` e `"1"` non sono uguali con questo confronto.

**`!==`**  
È il confronto di disuguaglianza corrispondente a `===`. Sceglilo quando devi verificare che due valori non coincidano per tipo e valore.

**`<`**  
Confronta se un valore è minore dell’altro. Nel ciclo `i < elenco.length` permette di usare tutti gli indici disponibili.

**`&&`**  
Combina condizioni che devono essere tutte vere. Lo usiamo quando una funzionalità richiede più supporti contemporaneamente.

**`||`**  
Combina condizioni per cui basta che una sia vera. Lo usiamo per riconoscere più motivi alternativi per interrompere un gestore.

**`!`**  
Nega una condizione. `!target` è vero quando non abbiamo trovato una destinazione valida.

**`in`**  
Controlla se una proprietà esiste in un oggetto, anche tramite il suo prototipo. Lo usiamo per verificare la presenza di `popover`.

**`condizione ? valore1 : valore2`**  
Sceglie un valore: il primo se la condizione è vera, il secondo se è falsa. È utile per assegnare “Chiudi menu” oppure “Apri menu”.

**`classList.add()`**  
Aggiunge una classe a un elemento. Sceglilo per attivare uno stato definito nel CSS, come `.is-selected`.

**`classList.remove()`**  
Toglie una classe. Lo usiamo per rimuovere `.is-selected` dalle voci che non devono essere selezionate.

**`addEventListener()`**  
Collega una funzione a un evento. La funzione viene eseguita quando l’evento avviene, per esempio al clic sul pulsante.

**`click`**  
È l’evento di attivazione del controllo. Su un vero `<button>` viene generato anche attivandolo da tastiera con Invio o Spazio.

**`change`**  
Dipende dall’oggetto che lo emette. Su `matchMedia()` segnala che la condizione è passata da vera a falsa o viceversa, non ogni ridimensionamento.

**`toggle`**  
Segnala il cambio fra aperto e chiuso di elementi come popover e `<details>`. Lo usiamo per aggiornare l’etichetta del menu.

**`window.matchMedia()`**  
Crea un oggetto che controlla una media query. Sceglilo quando JavaScript deve reagire al passaggio tra mobile e desktop.

**`.matches` sull’oggetto di `matchMedia()`**  
È un valore vero/falso: `desktopMedia.matches` indica se la finestra soddisfa adesso la condizione desktop.

**`CSS.supports()`**  
Verifica se il browser supporta una dichiarazione CSS. Sceglilo per controllare il supporto prima di attivare una funzionalità che ne dipende.

**`HTMLElement.prototype`**  
È l’oggetto con le funzionalità comuni degli elementi HTML. L’espressione `'popover' in HTMLElement.prototype` verifica la presenza di quella proprietà.

**`setAttribute()`**  
Imposta un attributo HTML. Sceglilo per aggiornare valori come `aria-label` o `popovertarget`.

**`removeAttribute()`**  
Elimina un attributo HTML. Nel menu desktop lo usiamo per togliere `popover` e `popovertarget`.

**`.hidden`**  
Gestisce l’attributo `hidden` con un valore booleano: `true` lo aggiunge, `false` lo rimuove. Lo usiamo sul pulsante del menu.

**`element.matches()`**  
Verifica se un elemento soddisfa un selettore CSS, per esempio `navigationPanel.matches(':popover-open')`. È un metodo dell’elemento, distinto dalla proprietà `desktopMedia.matches`.

**`closest()`**  
Cerca l’elemento stesso e poi risale ai suoi antenati fino alla prima corrispondenza. Sceglilo per risalire dall’icona cliccata al link che la contiene.

**`contains()`**  
Controlla se un elemento contiene un altro, considerando valido anche il caso in cui coincidano. Lo usiamo per capire se il focus è nel menu.

**`getElementById()`**  
Trova un elemento tramite il suo ID, senza scrivere `#`. Sceglilo per cercare la destinazione di un collegamento interno.

**`event.target`**  
Indica l’elemento da cui arriva l’evento. Può essere l’icona dentro un pulsante o link, quindi a volte bisogna risalire con `closest()`.

**`event.defaultPrevented`**  
Indica se il comportamento predefinito dell’evento è già stato annullato. Lo controlliamo prima di gestire la navigazione del link.

**`event.ctrlKey`**  
Indica se durante l’evento è premuto Ctrl. Lo controlliamo per rispettare le azioni speciali dell’utente sui collegamenti.

**`event.metaKey`**  
Su Mac indica se è premuto Comando. Lo controlliamo, per esempio, per rispettare il clic che apre un collegamento in un’altra scheda.

**`event.shiftKey`**  
Indica se è premuto Maiusc. Lo usiamo insieme agli altri modificatori per riconoscere un clic con un comportamento speciale.

**`event.altKey`**  
Indica se è premuto Alt, chiamato Opzione su Mac. Anche questo può modificare il comportamento del clic secondo il browser.

**`.hash`**  
Legge la parte del collegamento che inizia con `#`, per esempio `#concept`. Sceglilo per ricavare la destinazione interna di un link.

**`.slice()`**  
Estrae una parte di una stringa. Nel nostro codice `link.hash.slice(1)` restituisce `concept` togliendo il primo carattere, cioè `#`.

**`document.activeElement`**  
Indica l’elemento che ha attualmente il focus. Lo usiamo prima di cambiare disposizione del menu per conservarne una posizione utile.

**`.focus()`**  
Porta il focus su un elemento che può riceverlo. Sceglilo per il collegamento “Vai al contenuto” o per gestire il passaggio fra menu e pulsante.

**`.textContent`**  
Legge o sostituisce il testo dentro un elemento. Lo usiamo sull’etichetta del menu per mostrare “Apri menu” o “Chiudi menu”.

**`.hidePopover()`**  
Chiude un popover. Nel nostro menu viene chiamato quando il collegamento punta a una sezione realmente presente nella pagina.

**`// commento`**  
Inserisce una nota fino alla fine della riga JavaScript. Sceglilo per spiegare i passaggi del codice.

## Scelte frequenti nel nostro sito

**Devo andare in un’altra sezione?**  
Usa `<a href="#nome">` e assicurati che la destinazione abbia `id="nome"`.

**Devo eseguire un’azione?**  
Usa un `<button type="button">`; collega JavaScript quando l’azione lo richiede.

**Devo aprire e chiudere testo e immagine?**  
Usa `<details>` e `<summary>`, come negli Assets: l’apertura e la chiusura sono già gestite dall’HTML.

**Devo aggiungere spazio dentro un elemento?**  
Usa `padding`. Per lo spazio esterno usa `margin`; per distanze regolari fra figli flex o grid usa `gap`.

**Devo affiancare un titolo e un triangolo?**  
Usa `display: flex`, `align-items: center` e `justify-content: space-between` sul loro contenitore.

**Devo creare due o tre colonne uguali?**  
Usa `display: grid` con `grid-template-columns: repeat(2, minmax(0, 1fr))`, cambiando `2` con `3` quando servono tre colonne.

**Devo rendere il testo più grande oppure più spesso?**  
Usa `font-size` per la dimensione e `font-weight` per lo spessore. Richiama le variabili del progetto.

**Devo nascondere qualcosa?**  
Per toglierlo dal layout usa `display: none` o l’attributo `hidden`. Per una decorazione SVG da ignorare soltanto durante la lettura assistita usa `aria-hidden="true"`.

**Devo trovare un elemento oppure un elenco?**  
Usa `querySelector()` per il primo elemento corrispondente e `querySelectorAll()` per raccoglierli tutti.

**Devo descrivere un’immagine?**  
Su `<img>` usa `alt`. Per un SVG informativo scritto nell’HTML usa un nome accessibile, per esempio con `<title>` o `aria-label`; per un SVG decorativo usa `aria-hidden="true"`.
