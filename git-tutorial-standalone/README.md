# Git & GitHub Tutorial - Versione Standalone

Un sito web **statico** per imparare Git e GitHub, creato appositamente per studenti di 3° ITIS che hanno studiato HTML e CSS.

## 🎯 Caratteristiche

- **Nessuna installazione richiesta**: Non serve Node.js, npm o altri strumenti
- **Solo HTML, CSS e JavaScript**: Tecnologie che già conosci
- **Aprilo e basta**: Doppio click su `index.html` e sei pronto
- **Guida Completa**: Tutorial passo-passo su Git e GitHub
- **Interattivo**: Copia i comandi Git con un click
- **Design Moderno**: Interfaccia responsive e professionale

## 📁 Struttura del Progetto

```
git-tutorial-standalone/
├── index.html      # Pagina principale - Pubblicare su GitHub
├── clone.html      # Pagina secondaria - Clonare da GitHub
├── styles.css      # Tutti gli stili CSS del sito
├── script.js       # JavaScript per interattività
└── README.md       # Questo file
```

## 🚀 Come Usare Questo Progetto

### Metodo 1: Apertura Diretta (Più Semplice)

1. **Scarica** o **clona** questo progetto sul tuo computer
2. **Apri** la cartella `git-tutorial-standalone`
3. **Doppio click** sul file `index.html`
4. Il sito si aprirà nel tuo browser predefinito!

### Metodo 2: Trascina nel Browser

1. Apri il tuo browser preferito (Chrome, Firefox, Edge)
2. Trascina il file `index.html` nella finestra del browser
3. Il sito sarà visualizzato immediatamente!

## 📚 Cosa Imparerai

### Pagina 1: Pubblicare su GitHub (`index.html`)
- Cos'è Git e GitHub
- Come creare un repository Git locale
- Come configurare GitHub
- Come pubblicare il tuo progetto su GitHub
- Workflow Git completo

### Pagina 2: Clonare da GitHub (`clone.html`)
- Cos'è il cloning
- Come scaricare progetti da GitHub
- Come lavorare su progetti clonati
- Come sincronizzare le modifiche

## 🛠️ Tecnologie Utilizzate

- **HTML5**: Struttura delle pagine
- **CSS3**: Stili, layout responsive, animazioni
- **JavaScript (Vanilla)**: Interattività senza librerie esterne
- **Font Awesome**: Icone
- **Google Fonts**: Font Inter

## ✨ Funzionalità JavaScript

Il file `script.js` include:

- **Menu Mobile**: Hamburger menu per dispositivi piccoli
- **Copy to Clipboard**: Copia i comandi Git con un click
- **Smooth Scrolling**: Navigazione fluida tra sezioni
- **Notifiche**: Feedback visivo per le azioni
- **Animazioni**: Elementi che appaiono durante lo scroll
- **Progress Bar**: Barra di progresso durante la navigazione

## 🎓 Per Studenti ITIS

Questo progetto è perfetto per te se:

- ✅ Hai studiato HTML e CSS
- ✅ Vuoi imparare Git e GitHub
- ✅ Non hai ancora studiato Node.js o framework complessi
- ✅ Vuoi un progetto pratico da pubblicare su GitHub

## 📝 Esercizi Pratici

### Esercizio 1: Pubblicare Questo Progetto
1. Segui la guida in `index.html`
2. Crea un repository Git locale
3. Pubblica il progetto sul tuo account GitHub
4. Condividi il link con i tuoi compagni!

### Esercizio 2: Personalizzare il Sito
1. Modifica i colori in `styles.css` (cerca `:root`)
2. Cambia il titolo in `index.html`
3. Aggiungi una nuova sezione
4. Fai commit delle modifiche
5. Pusha su GitHub

### Esercizio 3: Clonare e Modificare
1. Chiedi a un compagno il link del suo repository
2. Clona il suo progetto seguendo `clone.html`
3. Esplora il codice
4. Suggerisci miglioramenti

## 🎨 Personalizzazione

### Cambiare i Colori

Apri `styles.css` e modifica le variabili CSS all'inizio del file:

```css
:root {
    --primary-color: #0366d6;    /* Blu principale */
    --secondary-color: #28a745;  /* Verde secondario */
    --dark-color: #24292e;       /* Grigio scuro */
    --light-color: #f6f8fa;      /* Grigio chiaro */
}
```

### Aggiungere Nuove Sezioni

1. Copia una sezione esistente in `index.html`
2. Modifica il contenuto
3. Aggiungi un link nel menu di navigazione
4. Salva e ricarica la pagina!

## 🌐 Pubblicare Online

Dopo aver imparato Git e GitHub, puoi pubblicare questo sito gratuitamente su:

### GitHub Pages (Consigliato)
1. Pubblica il progetto su GitHub
2. Vai su Settings → Pages
3. Seleziona il branch `main`
4. Il tuo sito sarà online su `https://tuonome.github.io/git-github-tutorial`

### Netlify Drop
1. Vai su [netlify.com/drop](https://netlify.com/drop)
2. Trascina la cartella del progetto
3. Il sito sarà online in pochi secondi!

## 🔍 Differenze con il Progetto Originale

Questo progetto è una versione **semplificata** del progetto originale:

| Caratteristica | Progetto Originale | Questa Versione |
|----------------|-------------------|-----------------|
| Server | Node.js + Express | Nessun server |
| Installazione | `npm install` richiesto | Nessuna installazione |
| Avvio | `npm start` | Doppio click su HTML |
| Dipendenze | package.json | Nessuna dipendenza |
| Complessità | Media | Bassa |
| Ideale per | Sviluppatori | Studenti ITIS |

## 💡 Suggerimenti

- **Usa un editor di codice**: VS Code, Notepad++, o Sublime Text
- **Apri la console del browser**: F12 per vedere eventuali errori
- **Sperimenta**: Modifica il codice e vedi cosa succede!
- **Fai backup**: Usa Git per salvare le tue modifiche
- **Chiedi aiuto**: Collabora con i compagni di classe

## 🐛 Risoluzione Problemi

### Il sito non si apre
- Assicurati di aprire `index.html` con un browser web
- Controlla che tutti i file siano nella stessa cartella

### Le icone non si vedono
- Verifica la connessione internet (Font Awesome è online)
- Controlla la console del browser (F12)

### Il JavaScript non funziona
- Apri la console del browser (F12)
- Cerca eventuali errori in rosso
- Verifica che `script.js` sia nella stessa cartella

### I link non funzionano
- I link tra `index.html` e `clone.html` sono relativi
- Assicurati che entrambi i file siano nella stessa cartella

## 📖 Risorse Aggiuntive

- [Git - Documentazione Ufficiale](https://git-scm.com/doc)
- [GitHub Docs](https://docs.github.com)
- [Learn Git Branching](https://learngitbranching.js.org) - Tutorial interattivo
- [Pro Git Book](https://git-scm.com/book/it/v2) - Libro gratuito in italiano

## 🤝 Contribuire

Hai idee per migliorare questo tutorial?

1. Fai un fork del repository
2. Crea un branch per le tue modifiche
3. Fai commit delle modifiche
4. Apri una Pull Request

## 📄 Licenza

Questo progetto è distribuito sotto licenza MIT - sentiti libero di usarlo per imparare e insegnare!

## 👨‍🏫 Per i Docenti

Questo progetto è ideale per:

- Introdurre Git e GitHub agli studenti
- Esercitazioni pratiche di HTML/CSS/JS
- Progetti di gruppo
- Verifiche pratiche

Gli studenti possono:
- Pubblicare il progetto così com'è
- Personalizzarlo e renderlo unico
- Usarlo come portfolio su GitHub

---

**Creato con ❤️ per gli studenti ITIS**

Buon apprendimento e buon coding! 🚀
