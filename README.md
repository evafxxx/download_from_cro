# Stahovani ze stranek CRo



tento script je urcen pro zjednoduseni prace se stahovanim audio-souboru ze stranek CRo


**doporucene browsery:**

    Chrome
    Safari
    Edge

proste vsechny, ktere umoznuji ukladat js scripty do Snippets (Firefox umoznuje pracovat se snippet, ale neumi jej ukladat, takze se script musi kopirovat do FF snippetu po kazdym refresh stranky)
Snippets se v Chrome nazyvaji **"Fragmenty"**

**Jak pracovat se scriptem (napr.v Chrome)**
- na strance Ceskeho rozhlasu otevrete devTools (**Ctrl+Shift+J**)
- ( nebo nabidka->dalsi nastroje->nastroje pro vyvojare) 
- ( nebo klik na strance  pravym  tlacitkem mysi; volba Prozkoumat)
  


v nastrojich pro vyvojare kliknete na "Zdroje" (=sources) 1. a pote, pokud nevidite zalozku "Fragmenty"(=Snippets) kliknete na 2. a zvolte "Fragmenty"

![Annotation 2024-01-14 153907](https://github.com/evafxxx/download_from_cro/assets/156581982/1206f0f5-24b2-4094-b219-e6636f0c9140)

Zalozte novy fragment (=new Snippet)

![obrazek](https://github.com/evafxxx/download_from_cro/assets/156581982/de0897da-847a-461b-8e53-dc4ba888da56)

a prejmenujte jej napr. na "Rozhlas CRo"

![Annotation 2024-01-14 153907b](https://github.com/evafxxx/download_from_cro/assets/156581982/8a102856-7ba3-48f3-a5e0-4bd85defc363)

do tohoto noveho fragmentu zkopirujte obsah souboru [rozhlas_cro.js](https://github.com/evafxxx/download_from_cro/blob/main/rozhlas_cro.js)

![Annotation 2024-01-14 153907c](https://github.com/evafxxx/download_from_cro/assets/156581982/b7026835-1e4e-47f2-b073-00eabac3373b)

a pro sichra ulozte pomoci **Ctrl + S**

zavrete okno nastroje pro vyvojare


Nyni mate vse pripravene, abyste kdykoli mohli stahovat mp3 ze stranek rozhlasu ci ziskali vsechny odkazy na stream:


### Priklad mp3:

Chcete stahnout **"Mizeni"**

na dane strance stisknete **Ctrl+Shift+J**

![Annotation 2024-01-14 153907g](https://github.com/evafxxx/download_from_cro/assets/156581982/f444959c-ab42-4437-a76c-0eb63b1daf07)

a nalistujete zalozku **Zdroje** ; **Fragment "Rozhlas CRo"**

Fragmenty se spousti pomoci klavesove zkratky **Ctrl + Enter** (nebo klepnutim na Ctrl+Enter tlacitko ve spodni casti okna fragmentu)

V pripade, ze jsou audio-soubory ulozene ve formatu mp3 (= muzete je stahnout na svuj pocitac), signalizuje vam to i ikona


![Annotation 2024-01-14 153907h](https://github.com/evafxxx/download_from_cro/assets/156581982/5e6439f7-7906-4b13-b136-c9525a5a5b15)

Klepnutim na ikonu inicializujete stahovani (pokud je souboru vice, chvili to trva)

![Annotation 2024-01-14 153907i](https://github.com/evafxxx/download_from_cro/assets/156581982/8e76e303-2b19-4aa3-9af8-42f5c477f6e1)


### Priklad stream:

Chcete stahnout **"Let do nebezpeci"**

na dane strance stisknete **Ctrl+Shif+J**

![Annotation 2024-01-14 153907e](https://github.com/evafxxx/download_from_cro/assets/156581982/155f207b-942c-427a-818a-737c8a3a1482)

a nalistujete zalozku **Zdroje** ; **Fragment "Rozhlas CRo"**

Fragmenty se spousti pomoci klavesove zkratky **Ctrl + Enter** (nebo klepnutim na Ctrl+Enter tlacitko ve spodni casti okna fragmentu)

V pripade, ze se jedna o streamy, pak ty nemuzete jednoduse stahnout na svuj pocitac. Nicmene existuji nastroje (vetsinou offline), pomoci nichz si muzete prekonvertovat stream do mp3.

Nejcasteji je pro tyto ucely pouzivan program **youtube-dl**, pomoci nehoz lze z prikazove radky provest zadanou konverzi. (youtube-dl existuje i v grafickem provedeni youtube-dl-GUI)

Ze se jedna o stream, opet signalizuje ikona

![Annotation 2024-01-14 153907j](https://github.com/evafxxx/download_from_cro/assets/156581982/3d8be3f3-7309-4387-bea7-55da58b17880)

Klepnutim na ikonu se vam zobrazi seznam url, ktery podstrcite jako parametr youtube-dl ( ci jinemu konvertoru)


![Annotation 2024-01-14 153907k](https://github.com/evafxxx/download_from_cro/assets/156581982/4b66bdca-ba1f-4e8e-82af-8d3a62fa3312)


*Je mozne, ze na stankach rozhlasu se vyskytuji i jine formaty pro prehravani audia, ktere jsem nezaregistrovala(nenavstevuji jej a neco mi mohlo uniknout) a proto nejsou podchycene ve scriptu*
