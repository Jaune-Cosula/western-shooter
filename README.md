# Villin Lännen Revolverisankari

Pieni retrotyylinen selainpeli: alaspäin scrollaava western-maisema, revolverisankari alareunassa ja rosvoja, siviilejä sekä bonuksia ylhäältä satavina.

## Pelaaminen

Avaa `index.html` selaimessa — tai pelaa julkaisun jälkeen GitHub Pagesissa.

| Toiminto | Näppäin |
|---|---|
| Liiku | Nuolinäppäimet tai A / W / S / D |
| Ammu | Väilyönti |
| Tauko | P |
| Aloita / aloita uudelleen | Enter |

## Säännöt

- **Rosvot:** ampu niistä → pisteitä. Kovat rosvot (huppupäinen) ja konekivääriläjät kestävät useampia osumia ja ampuvat kovempaa.
- **Siviilit:** älä ammu (-300 pistettä) äläkä törmää (-1 elämä).
- **Törmäykset:** törmäys rosvoon tai siviiliin vie yhden elämän; lyhyt suojattu aika sen jälkeen. Bandiittien luodit vievät kestopisteitä (HP); HP:n nollauduttua menetät elämän.
- **Suojat:** radalle vierii tynnyreitä, puulaatikoita ja kiviä, jotka pysäyttävät sekä sinun että rosvoluodit — piiloudu niiden taakse hetkeksi pommisateelta.
- **Tasot:** joka 1000 pisteestä taso nousee — lisää rosvoja, nopeammin liikkeellä, kovempia aseita. Ensimmäisillä tasoilla rosvot ampuvat suoraan alaspäin, myöhemmin ne tähtäävät sinuun.
- **★-laatikko:** apulaisseriffi apuun + tuplatulivoima 12 sekunniksi.
- **+-laatikko:** +30 HP.

Vaikeustaso nousee maltillisesti: taso 1 on pidättyväinen (harvat, hitaat rosvot, lievät vahingot) ja kiristyy vasta tasojen myötä.

## Tekniikka

- Yksi tiedosto (`index.html`): HTML5 canvas, pikseligrafiika piirretty proseduraalisesti, äänet WebAudio-synteesillä. Ei riippuvuuksia, ei palvelinta, ei buildia.
