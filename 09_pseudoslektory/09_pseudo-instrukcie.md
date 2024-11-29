
# Inštrukcie

Dokončite kód a upravte vzhľad stránky podľa nasledovných bodov:

### 1. Menu položky - hover efekt:

- Pri prechode myšou nad jednotlivými položkami menu (`li a`), zmeňte pozadie na tmavší odtieň (#D90368) a pridajte podčiarknutie textu.
- Použite pseudotriedu `:hover` na tento efekt.

### 2. Pseudoelementy - prvý nadpis:

- Pomocou pseudoelementu `::before` pridajte pred nadpis v hlavičke (`h1`) symbol "💻".
- Nastavte symbol na rovnakú farbu ako text nadpisu a uistite sa, že má dostatočný odstup od textu.

### 3. Efekt na tlačidlo:

- Keď používateľ prejde myšou nad tlačidlo (`.cta-button`), zmeňte jeho farbu pozadia na tmavší odtieň žltej (#FFC300) a pridajte jemný efekt tieňa.
- Použite pseudotriedu `:hover`.

### 4. Prvý odstavec - zvýraznenie prvého písmena:

- Upravte prvý odstavec (`.description`) tak, aby jeho prvé písmeno bolo väčšie a odlíšené inou farbou (použite pseudoelement `::first-letter`).

### 5. Výber textu:

- Pridajte štýl pre vybratý text na celej stránke (`::selection`), zmeňte farbu pozadia vybraného textu na svetložltú (#FFD700) a farbu textu na tmavosivú (#2E294E).

### 6. Skrytý odkaz na Kontakt:

- Skryte poslednú položku v navigácii (Kontakt) na mobilných zariadeniach pomocou pseudotriedy `:last-child` a media queries (použite šírku obrazovky pod 600px).

@media (max-width: 600px) {
    dopň kód
    }


### 7. Formátovanie tlačidla - disabled stav:

- Vytvorte nový štýl pre tlačidlo (`button:disabled`) s nastavením svetlosivej farby a neaktívneho vzhľadu. Potom skúste tlačidlo v HTML na chvíľu vypnúť (atribút `disabled`).
"""


