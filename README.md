# Mobiiliprojekti pikkupelit

Mobiiliprojekti on React Native -projekti, joka sisältää useita tunnettuja mobiilipelejä samassa paikassa. 
Projekti on tehty harjoitustyönä ja sen tarkoituksena on harjoitella React Native -sovellusten rakentamista, komponenttien hallintaa ja pelilogiiikan toteuttamista.
Sovelluksen keskiössä on HomeScreen, josta käyttäjä voi helposti valita haluamansa pelin ja asettaa nimimerkkinsä ennen pelaamisen aloittamista. 
Jokaisessa pelissä on omat vaikeustasot ja tulosten tallennus Firebaseen, mikä mahdollistaa henkilökohtaisen kehityksen seuraamisen ja pelien uudelleen pelaamisen.

## Projektin idea & ominaisuudet

- Keskitetty HomeScreen, josta kaikki pelit käynnistetään helposti yhdestä paikasta. Käyttäjä näkee kaikki pelit ja voi valita haluamansa pelin nopeasti
- Nimimerkin asettaminen ennen pelin aloittamista, jotta tulokset ja edistymiset voidaan tallentaa käyttäjäkohtaisesti
- Pelien vaikeustason valinta (Sudoku, Minesweeper ja Connect4 ja TicTacToe singleplayer -pelit), jolloin käyttäjä voi valita haastavuuden omien taitojensa mukaan
- Multiplayer- ja singleplayer-pelejä:
  - Multiplayer-peleissä pelaajat pelaavat vuorotellen samalla laitteella, mikä mahdollistaa ystävien kanssa pelaamisen helposti
  - Singleplayer-peleissä pelaaja pelaa tekoälyä vastaan, tarjoten yksinpelattavaa haastetta ja harjoitusta
- Visuaaliset efektit peleissä, kuten:
  - Animaatiot, jotka tekevät pelien liikkeistä sulavia ja miellyttäviä
  - Confetti-efektit, jotka palkitsevat onnistuneista suorituksista
  - Äänitehosteet, jotka lisäävät pelikokemuksen immersiota ja interaktiivisuutta
- Pelit kattavat eri tyylilajit, kuten:
  - Pulmapelit (Sudoku, Minesweeper)
  - Strategiapelit (Connect4, TicTacToe)
  - Pulma- ja järjestelypeli (ColorSort)
  - Arcade- ja toimintapelit (BubbleShooter, BrickBreaker, FlappyBird)
  - Pähkinäpeli / numeropeli (2048)
  - Firebase-integraatio, jonka avulla tuloksia voidaan tallentaa ja seurata käyttäjäkohtaisesti

## Oma roolini

- Toteutin itse pelit:
  - Sudoku
  - Minesweeper
  - Connect4
  - TicTacToe
  - Osittain ColorSort
- Osallistuin HomeScreenin suunnitteluun ja pelien käyttöliittymiin
- Firebase-integraation toteutus tulosten tallentamiseen
- Custom fonttien ja modaalien lisääminen sovellukseen
  
## Käytetyt teknologiat

- React Native
- Expo
- Firebase
- React Navigation
- Context API nimimerkin hallintaan
  
## Mitä opin

- React Native -sovellusten rakenteen ja komponenttien hallinnan.
- Context API:n käytön nimimerkin ja tilan hallintaan.
- Modaalien ja animaatioiden toteutuksen mobiilisovelluksissa.
- Firebase-integraation perusperiaatteet ja tiedon tallentamisen mobiilisovelluksessa.
- Pelilogiikan suunnittelun ja virheenkäsittelyn käytännön toteutuksen.
- Erilaisten pelityyppien (strategiapelit, pulmapelit, reaaliaikaiset pelit) toteutuksen erityispiirteet.
  
## Video sovelluksen toiminnasta
https://www.youtube.com/watch?v=smlNJxKitC0
