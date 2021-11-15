# Harjoitus 3
 
## Tehtävä Z 
- Markdown on helppo tapa formatoida tekstiä, joka näyttää hyvältä
kaikilla laitteilla.
- Huomioi että merkin jälkeen pitää aina laittaa välilyönti
- Lista: * tai -
- Otsikko: #, kakkostason otsikko ##
- Kappalejako: tyhjä rivi (tehdään tässä)
 
Kappale alkaa tässä
ja jatkuu täällä, mutta loppuu tässä
 
Uusi kappale 
- Sisennys: >, välilyönti lopettaa sisennyksen
>sisennetty 
- Linkki: [linkin teksti](https://www.google.fi)
- Kuva:

 ![image](https://quiksite.com/wp-content/uploads/2016/09/Linux_Tux-300x300.png)

## Tehtävä A
- Tee tehtävä Markdownina

## Tehtävä B
Luotiin kansio testikansio ja sinne tekstia.txt, johon lisättiin muutama
rivi tekstiä. Lisätään vielä yksi tekstitiedosto projektin juureen.

![image](https://linuxpalvelimet2021syksy.files.wordpress.com/2021/11/tehtavab1.png)

Kansion sisältö on nyt seuraavanlainen.

![image](https://linuxpalvelimet2021syksy.files.wordpress.com/2021/11/tehtavatab2.png)

Lisätään commit-viestiin mitä tehtiin.

![image](https://linuxpalvelimet2021syksy.files.wordpress.com/2021/11/tehtavab3.png)

Ajetaan komento, joka lisää kaiken kansion sisällön gittiin (add), lisää kommentin mitä tehty
(commit), vetää vanhan projektin (push), mikäli siihen olisi tehty päivityksiä välissä ja
ajaa päivitykset (push).

![image](https://linuxpalvelimet2021syksy.files.wordpress.com/2021/11/tehtavab4.png)

Muutokset näkyvät git repositoriossa.

![image](https://linuxpalvelimet2021syksy.files.wordpress.com/2021/11/tehtavab5.png)

## Tehtävä C
Git log näyttää järjestyksessä edelliset versiot, commitit, tekijän, päivämäärän ja kellonajan.

![image](https://linuxpalvelimet2021syksy.files.wordpress.com/2021/11/tehtavac1-1.png)

Git diff näyttää eron viimeisimmän version ja nyt tehtyjen muutosten välillä. Vihreällä
näkyy mitä uutta on lisätty.

![image](https://linuxpalvelimet2021syksy.files.wordpress.com/2021/11/tehtavac2.png)

Git blame näyttää tietyn tiedoston muokkaushistorian. Tässä ajettu komento 

git blame tehtava3.md

Ensimmäiset rivit

![image](https://linuxpalvelimet2021syksy.files.wordpress.com/2021/11/tehtavac3.png?w=1024)

Viimeiset rivit

![image](https://linuxpalvelimet2021syksy.files.wordpress.com/2021/11/tehtavac4.png?w=1024)

## Tehtävä D
Lisätään pupputekstiä testitiedosto.txt-tiedostoon. Lisätään muutokset uuteen versioon
komennolla

git add .

Tarkistetaan status komennolla 

git status

![image](https://linuxpalvelimet2021syksy.files.wordpress.com/2021/11/tehtavad1.png)

Testitiedosto.txt:n sisältö on nyt seuraavanlainen.

![image](https://linuxpalvelimet2021syksy.files.wordpress.com/2021/11/tehtavad2.png)

Ajetaan komento

git reset --hard

Komento palauttaa gitin tilan edelliseen versioon ja ilmottaa siitä. Tarkistetaan vielä
Gitin status ja testitiedoston sisältö. Huomataan, että tiedosto ja versio ovat muutosta
edeltävässä tilassa.

![image](https://linuxpalvelimet2021syksy.files.wordpress.com/2021/11/tehtavad3.png)
