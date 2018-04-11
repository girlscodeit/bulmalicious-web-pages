# Bulmalicious Web Pages :sparkles:
Di Samantha Baita & Daniela Bolza

## Cosa serve per iniziare?
- [ATOM](https://atom.io/)
- Per evitare di salvare il file tutte le volte, puoi impostare l'autosalvataggio


## Impostare autosave su Atom (Windows)
Per Windows:
1. File ![1.File](/Screen/Windows/1_Settings.png)
2. Settings
3. Packages
4. Scrivi nella barra di ricerca "autosave" e premi invio ![2.Packages](/Screen/Windows/2_Packages.png)
5. Nel riquadro di Core Packages clicca "settings"
6. Nella nuova schermata metti la spunta in Settings su "Enabled" ![3.Autosave](/Screen/Windows/3_Autosave.png)

##Impostare autosave su Atom (MacOS)

Per Apple:
1. Atom ![1.File](/Screen/MacOS/1_Settings.png)
2. Preferences
3. Packages
4. Scrivi nella barra di ricerca "autosave" e premi invio ![2.Packages](/Screen/MacOS/2_Packages.png)
5. Nel riquadro di Core Packages clicca "settings"
6. Nella nuova schermata metti la spunta in Settings su "Enabled" ![3.Autosave](/Screen/MacOS/3_Autosave.png)



## Cos'è Bulma?
- [BULMA](https://bulma.io/)
- È uno strumento che serve per creare pagine web.
- Immaginati una cassetta degli attrezzi dalla quale puoi prendere quello che ti serve

## Obiettivo di oggi
- Creare la propria pagina professionale con gli strumenti che ti mette a disposizione Bulma

## Let's start
- Puoi aprire ATOM
- Crea un nuovo file e salvalo con l'estensione HTML
- Adesso puoi andare su Bulma e copiarti lo "Starter Template"
- Puoi incollarlo sul nuovo file appena creato
- Per vedere il tuo risultato vai nella cartella dove hai salvato il file, clicca con il tasto dx e seleziona "Apri con Google Chrome"

## Dai un titolo al tuo documento
- Nel file puoi inserire un titolo a tuo piacimento
- Puoi aprire il file su Chrome o aggiornare la pagina per verificare il risultato

## Se vuoi puoi inserire un sottotitolo
- All'interno del file puoi cambiare la descrizione già esistente oppure puoi cancellare quello che non ti serve
- Puoi aprire il file su Chrome o aggiornare la pagina per verificare il risultato

## La struttura di Bulma
- La struttura è basata su sezioni chiamate _section_
- In ogni sezione vi è un contenitore chiamato _container_.

#### Quindi le varie sezioni saranno così strutturate:
```
<section class="section">
  <div class="container">
    //Qui puoi inserire i vari elementi
  </div>
</section>
```
#### Per inserire del contenuto testuale:
- Quando vuoi aggiungere del testo all'interno del tuo documento puoi aggiungere un _div_ con la classe _content_

```
<div class="content">
  // Qui puoi inserire il tuo testo
</div>
```


## Come utilizzare gli elementi di Bulma
- Per utilizzare i vari elementi e componenti puoi cercare quello che ti serve sulla documentazione di Bulma
- Copiarlo e incollarlo all'interno del tuo codice :blush:
- Puoi aprire il file su Chrome o aggiornare la pagina per verificare il risultato

## Puoi utilizzare le colonne per organizzare i vari elementi

```
    <div class="columns">
      <div class="column">
        //contenuto della prima colonna
      </div>
      <div class="column">
        //contenuto della seconda colonna
      </div>
    </div>

```
## Puoi aggiungere la tua foto
- Puoi andare su Bulma e cercare l'elemento che ti permette di aggiungere l'immagine
- Puoi copiarlo ed inserirlo nel tuo file
- Per personalizzare l'immagine puoi sostituire il contenuto della classe ```src``` in due modi:
  - inserendo il percorso di una tua immagine che è già salvata sul tuo computer
  - copiando ed incollando il link di un'immagine trovata su internet
- Puoi aprire il file su Chrome o aggiornare la pagina per verificare il risultato


## Puoi inserire le tue informazioni personali
- Puoi mettere:
  - Nome e cognome
  - Telefono
  - Email
  - Nazionalità
- Puoi aprire il file su Chrome o aggiornare la pagina per verificare il risultato

![](/Screen/informazioni_personali.png)

## Formazione
- Puoi inserire la tua carriera scolastica
- Puoi aprire il file su Chrome o aggiornare la pagina per verificare il risultato

![](/Screen/Formazione.png)

## Esperienza lavorativa
- Puoi aggiungere la tua carriera lavorativa
- Puoi aprire il file su Chrome o aggiornare la pagina per verificare il risultato

![](/Screen/esperienza_lavorativa.png)

## Capacità e competenze personali
- Puoi inserire  una lista delle tue Competenze
- Puoi aprire il file su Chrome o aggiornare la pagina per verificare il risultato

![](/Screen/capacitaecompetenze.png)

## Competenze Linguistiche
- Puoi inserire le tue conoscenze linguistiche
- Puoi aprire il file su Chrome o aggiornare la pagina per verificare il risultato

![](/Screen/competenze_linguistiche.png)

## Aggiungi un pò di colore
- Per inserire del colore all'interno del tuo documento puoi sostituire la prima _section_ con un _hero_

```
<section class="hero is-light is-medium">
  <div class="hero-body">
    <div class="container">
      // Qui rimane il contenuto delle tue informazioni personali
    </div>
  </div>
</section>
```
- Successivamente inserisci il tag _style_ come ultimo elemento del tag _head_ per personalizzare il colore
```
<style type="text/css">
.hero.is-light {
  background-color:lightpink;
}
</style>
```


## Soluzione

La soluzione con il tutto il codice è disponibile [qui](Soluzione/index.html)
