# htmlcss-responsive-layout

## Descrizione
Riproduzione di una pagina di un vero sito in modalità responsive.
Partiamo dal realizzare la struttura base del nostro tema solo con i blocchi colorati senza inserire i veri testi, img etc. o pensare al dettaglio.
L'approccio utilizzato per il responsive è mobile first.
Partiamo sempre dall'individuare il layout generale e poi iniziamo dall'alto verso il basso. Non passiamo ad una sezione successiva se la precedente non funziona.

## Tasks:
1. guardare i video e prendere appunti
2. questa volta imparare a usare Metodo BEM per la nomenclatura delle classi

## Parte "complicata":
2/3 colonne

## MEGAPROBLEMA.
in query media 576 px, il layout calcoli stranissimi
    .cards__card.cards__card--two-thirds  {
        width: calc((100% / 3* 2) - 6.5px);
    }
    .cards__card.cards__card--one-thirds{
        width: calc((100% / 3) - 13.5px);
        flex-grow: 1;
    }
    Funziona funziona. fa cagare pero.
    

    