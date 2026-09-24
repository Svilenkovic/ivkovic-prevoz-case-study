<a href="https://ivkovicprevoz.rs/"><img src="media/cover.jpg" alt="Ivković Prevoz, naslovna strana na laptopu i telefonu" width="100%"></a>

# Ivković Prevoz

Sajt na jednoj strani za firmu iz Leskovca koja prodaje ogrevno drvo, vozi robu i šlepuje vozila, sa deset linkova za poziv i bez kontakt forme.

**[ivkovicprevoz.rs](https://ivkovicprevoz.rs/)** · [Studija slučaja](https://svilenkovic.rs/radovi/ivkovic-prevoz) · [English](README.md)

> [!NOTE]
> Klijentski projekat. Izvorni kod pripada klijentu i čuva se u privatnom repozitorijumu. Ova stranica opisuje šta sam uradio i kako.

<table>
  <tr><td><b>Klijent</b></td><td>Ivković Prevoz</td></tr>
  <tr><td><b>Delatnost</b></td><td>Ogrevno drvo, kamionski prevoz robe i šlepovanje vozila</td></tr>
  <tr><td><b>Lokacija</b></td><td>Leskovac</td></tr>
  <tr><td><b>Vrsta</b></td><td>Sajt na jednoj strani</td></tr>
  <tr><td><b>Moj deo posla</b></td><td>Dizajn, izrada, SEO, hosting i održavanje</td></tr>
  <tr><td><b>Tehnologije</b></td><td>PHP 8.3, nginx, JSON-LD, Consent Mode v2</td></tr>
</table>

## O projektu

Ivković Prevoz iz Leskovca radi tri posla koja nemaju mnogo zajedničkog. Prodaje ogrevno drvo (bukvu, hrast i grab) na metar, sa dostavom i istovarom, vozi robu kamionom po celoj Srbiji i šlepuje vozila po Leskovcu, Lebanu i okolnim mestima. Svaku uslugu ljudi traže drugim rečima i u drugo doba godine, a sve tri se dogovaraju telefonom.

Zato sam stranu napravio bez kontakt forme i bez ijednog polja za unos. Umesto nje ima deset mesta za poziv, a na telefonu traka sa brojem stoji pri dnu ekrana. Čovek kome je auto stao na putu neće da čeka odgovor na mejl. Nema ni fotografija: pozadina prvog ekrana je vektorska ilustracija upisana u CSS, pa se strana brzo otvara i na slabom mobilnom signalu.

## Šta sam uradio

- Po jedna puna celina za svaku uslugu, a u kontaktu područje rada posebno za drvo, prevoz i šlepovanje
- Sekcija o šlepovanju podeljena po situacijama (kvar na putu, auto kupljen u drugom gradu, kombiji), jer se isti posao traži na više načina
- Deset linkova za poziv i traka sa brojem na telefonu; forme nema, pa automati nemaju šta da popune
- Fontovi i ikone sa sopstvenog domena, a nginx kešira gotovu stranu i daje poslednju ispravnu verziju ako PHP zakaže
- Sedam JSON-LD blokova, u kojima je šlepovanje izdvojeno kao posebna usluga za pet mesta
- Popravljene kartice koje su na telefonu ostajale nevidljive posle skoka iz menija: prag je sada nula, a sve što je već ostalo iznad odmah se prikazuje

## Merenja

| | Performanse | Pristupačnost | Dobre prakse | SEO |
| :-- | :-: | :-: | :-: | :-: |
| Telefon | 91 | 100 | 100 | 100 |
| Desktop | 99 | 100 | 100 | 100 |

PageSpeed Insights, laboratorijsko merenje živog sajta, septembar 2026. Sigurnosna zaglavlja: 6 od 6. HTML validator: bez grešaka. axe provera pristupačnosti: bez prekršaja. Strukturisani podaci: `LocalBusiness`.

## Snimci ekrana

<table>
  <tr>
    <td width="68%" valign="top"><img src="media/desktop.webp" alt="Ivković Prevoz, naslovna strana na ekranu širine 1440 px"></td>
    <td width="32%" valign="top"><img src="media/mobile.webp" alt="Ivković Prevoz, naslovna strana na telefonu"></td>
  </tr>
</table>

<img src="media/inner-1.webp" alt="Naše usluge: prodaja ogrevnog drveta, kamionski prevoz i šlepovanje vozila">
<sub>Naše usluge: prodaja ogrevnog drveta, kamionski prevoz i šlepovanje vozila</sub>

<img src="media/inner-2.webp" alt="Vrste ogrevnog drveta: bukva, hrast i grab, svaka sa svojim opisom">
<sub>Vrste ogrevnog drveta: bukva, hrast i grab, svaka sa svojim opisom</sub>

---

<sub>Izrada: [D. Svilenković](https://svilenkovic.rs).</sub>
