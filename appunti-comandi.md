### HTML

**`<!DOCTYPE html>`**  
Indica che il documento usa HTML moderno.

**`html` · `lang`**  
Contiene la pagina; `lang="it"` indica la lingua italiana.

**`head` · `meta` · `title`**  
Contengono impostazioni, codifica, adattamento allo schermo e titolo della scheda.

**`link`**  
Collega il file CSS.

**`script` · `defer`**  
Collega JavaScript; `defer` lo esegue dopo la lettura dell’HTML.

**`body`**  
Contiene ciò che appare nella pagina.

**`header` · `main` · `section` · `footer`**  
Identificano intestazione, contenuto principale, sezioni e parte finale.

**`nav`**  
Identifica un gruppo di collegamenti di navigazione.

**`div`**  
Raggruppa elementi in un contenitore.

**`h1` · `h2`**  
Titolo principale e titoli delle sezioni.

**`p`**  
Contiene un paragrafo.

**`span`**  
Raggruppa una parte di testo o contenuto dentro una riga.

**`br`**  
Manda il testo a capo.

**`ul` · `li`**  
Creano una lista e le sue singole voci.

**`a` · `href`**  
Creano un collegamento; `href="#concept"` porta all’elemento con quell’ID.

**`button` · `type="button"`**  
Creano un pulsante per un’azione nella pagina, senza inviare un modulo.

**`img` · `src` · `alt`**  
Mostrano un’immagine; `src` indica il file, `alt` la descrizione alternativa.

**`width` · `height`**  
Indicano larghezza e altezza, anche per riservare spazio alle immagini.

**`svg` · `viewBox` · `path` · `rect`**  
Creano grafica vettoriale: area del disegno, tracciati e rettangoli.

**`class` · `id`**  
Assegnano classi riutilizzabili e identificatori unici agli elementi.

**`aria-label` · `aria-labelledby` · `aria-hidden`**  
Danno un nome accessibile, lo collegano a un titolo o nascondono elementi decorativi ai lettori di schermo.

**`tabindex="-1"`**  
Permette di spostare il focus con JavaScript senza aggiungere una tappa al percorso Tab.

**`popover` · `popovertarget`**  
Definiscono un pannello a comparsa e il pulsante che lo apre.

**`hidden`**  
Nasconde un elemento.

**`<!-- commento -->`**  
Scrive una nota che non appare nella pagina.

### CSS

**`*` · `.classe` · `#id` · `[attributo]`**  
Selezionano tutti gli elementi, una classe, un ID o un attributo.

**`A B` · `A > B`**  
Selezionano elementi dentro A oppure soltanto i suoi figli diretti.

**`:root` · `--variabile` · `var()`**  
Definiscono e richiamano valori riutilizzabili.

**`@font-face` · `src` · `format()` · `font-display`**  
Caricano i font e regolano la visualizzazione durante il caricamento.

**`font-family` · `font-size` · `font-weight` · `font`**  
Impostano carattere, dimensione, peso o più proprietà insieme.

**`line-height` · `letter-spacing`**  
Regolano distanza fra le righe e fra le lettere.

**`font-feature-settings` · `-webkit-font-smoothing`**  
Regolano caratteristiche del font e resa del testo nei browser compatibili.

**`text-align` · `text-transform` · `text-decoration` · `text-wrap`**  
Regolano allineamento, maiuscole, sottolineature e distribuzione delle righe.

**`color` · `fill` · `currentColor`**  
Impostano il colore del testo e degli SVG; `currentColor` riprende il colore dell’elemento.

**`background` · `background-color` · `background-image`**  
Impostano sfondo, colore e immagine di fondo.

**`color-mix()`**  
Mescola colori, per esempio al passaggio del mouse.

**`padding`**  
Spazio interno, fra contenuto e bordo.

**`margin` · `margin-top` · `margin-bottom` · `margin-left` · `margin-right`**  
Spazio esterno; i margini laterali `auto` possono centrare un blocco.

**`gap`**  
Distanza fra elementi di un contenitore flex o grid.

**`width` · `height` · `max-width` · `min-width` · `max-height`**  
Impostano dimensioni e relativi limiti.

**`box-sizing: border-box`**  
Include padding e bordi nelle dimensioni dichiarate.

**`border` · `border-top` · `border-bottom` · `border-left` · `border-right`**  
Disegnano tutti i bordi o un singolo lato.

**`border-inline` · `border-block` · `border-color` · `border-radius`**  
Regolano bordi laterali, sopra/sotto, colore e angoli arrotondati.

**`display: block / inline / inline-block / none`**  
Regola la disposizione di base oppure nasconde l’elemento.

**`display: flex`**  
Dispone i figli lungo una riga o una colonna.

**`flex-direction` · `flex-wrap` · `flex-shrink`**  
Regolano direzione, ritorno a capo e restringimento degli elementi flex.

**`align-items` · `align-self` · `justify-content`**  
Allineano gli elementi del contenitore o un singolo elemento.

**`display: grid` · `grid-template-columns`**  
Creano una griglia e definiscono le colonne.

**`repeat()` · `minmax()` · `fr`**  
Ripetono colonne, ne definiscono i limiti e dividono lo spazio disponibile.

**`position: relative / absolute / fixed`**  
Regola il posizionamento rispetto alla posizione normale, a un contenitore o alla finestra.

**`top` · `left` · `right` · `inset` · `z-index`**  
Regolano posizione e ordine di sovrapposizione.

**`overflow` · `overflow-y`**  
Gestiscono il contenuto che supera il contenitore e lo scorrimento.

**`transform` · `translateY()` · `rotate()` · `scaleY()`**  
Spostano, ruotano o ridimensionano visivamente un elemento.

**`transform-origin`**  
Imposta il punto da cui parte una trasformazione.

**`opacity`**  
Regola la trasparenza.

**`::before` · `::after` · `content`**  
Creano elementi decorativi tramite CSS, come linee e aree cliccabili.

**`:has()` · `:not()`**  
Selezionano in base al contenuto oppure escludono una condizione.

**`:hover` · `:focus` · `:focus-visible` · `:popover-open`**  
Selezionano elementi sotto il mouse, con focus o pannelli aperti.

**`outline` · `outline-offset`**  
Disegnano il contorno di focus e la sua distanza dall’elemento.

**`cursor` · `pointer-events` · `list-style`**  
Regolano il cursore, la ricezione dei clic e i pallini delle liste.

**`@media` · `min-width` · `max-width`**  
Applicano regole soltanto a determinate larghezze.

**`hover` · `pointer` · `prefers-reduced-motion`**  
Controllano capacità del dispositivo e preferenze sui movimenti.

**`transition` · `animation` · `@keyframes`**  
Gestiscono cambiamenti graduali e animazioni.

**`anchor-name` · `position-anchor` · `anchor()` · `anchor-size()`**  
Posizionano il pannello del menu rispetto al suo pulsante.

**`calc()`**  
Calcola misure combinando valori.

**`inherit` · `auto` · `!important`**  
Riprendono il valore dal genitore, lasciano il calcolo al browser o danno priorità alla dichiarazione.

**`px` · `em` · `%` · `dvh`**  
Misure in pixel, relative al carattere, al contenitore o all’altezza della finestra.

**`/* commento */`**  
Scrive una nota nel CSS.

### JavaScript

**`const` · `let`**  
Dichiarano variabili: `const` non viene riassegnata, `let` può cambiare.

**`document.querySelector()`**  
Trova il primo elemento che corrisponde al selettore.

**`document.querySelectorAll()`**  
Trova tutti gli elementi corrispondenti, nell’ordine dell’HTML.

**`NodeList` · `.length` · `[indice]`**  
Rappresentano un elenco, il suo numero di elementi e una posizione precisa.

**`function` · parametri**  
Definiscono un’azione riutilizzabile e le informazioni che riceve.

**`for` · `i++`**  
Ripetono operazioni, aumentando l’indice a ogni giro.

**`if / else` · `return`**  
Scelgono cosa eseguire e interrompono una funzione.

**`===` · `!==` · `<`**  
Confrontano uguaglianza, differenza e valori più piccoli.

**`&&` · `||` · `!` · `in`**  
Combinano condizioni, le negano o controllano se una proprietà esiste.

**`condizione ? valore1 : valore2`**  
Sceglie fra due valori in base a una condizione.

**`classList.add()` · `classList.remove()`**  
Aggiungono e tolgono classi, come `is-selected`.

**`addEventListener()` · `click` · `change` · `toggle`**  
Collegano una funzione a clic, cambi di condizione o apertura/chiusura del pannello.

**`window.matchMedia()` · `.matches`**  
Controllano una media query e restituiscono se è vera.

**`CSS.supports()` · `HTMLElement.prototype`**  
Aiutano a verificare il supporto delle funzionalità del browser.

**`setAttribute()` · `removeAttribute()` · `.hidden`**  
Impostano o eliminano attributi e nascondono elementi.

**`matches()` · `closest()` · `contains()`**  
Controllano un selettore, cercano un antenato o verificano se un elemento ne contiene un altro.

**`getElementById()`**  
Trova un elemento tramite il suo ID.

**`event.target` · `event.defaultPrevented`**  
Indicano l’origine dell’evento e se la sua azione predefinita è stata annullata.

**`ctrlKey` · `metaKey` · `shiftKey` · `altKey`**  
Controllano quali tasti modificatori sono premuti durante il clic.

**`.hash` · `.slice()`**  
Leggono il frammento del collegamento e ne estraggono una parte.

**`document.activeElement` · `.focus()`**  
Individuano l’elemento con focus e spostano il focus su un altro.

**`.textContent`**  
Legge o modifica il testo di un elemento.

**`.hidePopover()`**  
Chiude il pannello a comparsa.

**`// commento`**  
Scrive una nota nel JavaScript.