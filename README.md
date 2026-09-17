# TK Lokomotiva Karlovy Vary — návrhy nového webu

Redesign webu **teniskv.cz**. Tři varianty, všechny ve stejném rozsahu obsahu.

## Soubory

| Soubor | Varianta | Charakter |
|---|---|---|
| `index.html` | rozcestník | galerie všech tří variant |
| `01-indigova-noc.html` | Indigová noc | tmavý luxus, Playfair Display + Inter, v hero velký klubový znak |
| `02-porcelan.html` | Porcelán | krémová lázeňská elegance, Cormorant Garamond + Jost, zlaté linky |
| `03-centrkurt.html` | Centrkurt | čistá bílá, Archivo, dělený hero, běžící pás, ostrý grid |
| `img/logo-ltk-znak.png` | — | nový 3D klubový znak, vyklíčované pozadí, přebarvený do indigové palety webu |
| `img/logo-ltk-znak-modry.png` | — | totéž v původních modro-bronzových barvách (záloha) |
| `img/logo-ltk-kv.png` | — | staré ploché logo z teniskv.cz (už se nepoužívá) |
| `img/areal-kurty.jpg` | — | pohled na antukové dvorce (z teniskv.cz, 1200×750) |
| `img/areal-hala.jpg` | — | zimní přetlaková hala zvenku (zatím nepoužito) |
| `img/areal-kurty-2.jpg` | — | kurty u opěrné zdi (zatím nepoužito) |

## Klubové barvy (odvozené z loga)

- indigová `#18006A` — štít v logu
- limetková `#ABFF00` — míček v logu
- bílá `#FFFFFF`

Varianta 02 přidává zlatou `#B08D3F` jako lázeňský akcent.

## Logo

Nové 3D logo přišlo v modro-bronzovém provedení (štít `#234261`, bronz `#7B5946`, míček `#C3CF45`). Aby ladilo s návrhy, je **přebarvené do indigové palety** — štít posunutý do `#18006A`, míček do syté limetky `#ABFF00`, bronzový rám ponechaný jako luxusní akcent. Původní modrá verze zůstává ve složce `img/` jako záloha.

Obrys znaku pochází z verze očištěné přes remove.bg, kterou dodal klient; obrazová data jsou z velkého renderu (verze z remove.bg má jen poloviční rozlišení). Znak funguje na tmavém, světlém i barevném podkladu.

## Odlišnost varianty 01

V hero má místo karty „Areál v číslech“ **velký klubový znak** s jemnou září. Údaje o areálu (7 antuka, 2 tvrdý povrch, 2 v hale, zeď) zůstávají v sekci *O klubu*, ceny v *Ceníku*.

## Použití fotky areálu

Fotka antukových dvorců je v každé variantě jinak, podle jejího charakteru:

- **01 Indigová noc** — podklad celého hero pod tmavým indigovým závojem
- **02 Porcelán** — obrazový pás v sekci *O klubu*, v tenkém rámu s popiskem
- **03 Centrkurt** — podklad sekce *Rezervace* pod indigovým závojem

Fotka má 1200×750 px, což na celoobrazovkový podklad stačí jen díky závoji. **Pro ostrý web je potřeba originál ve vyšším rozlišení** — ideálně 2400 px na šířku.

## Struktura každé varianty

hero → čísla areálu → o klubu + povrchy → tenisová škola → trenéři → ceník → historie + odchovanci → aktuality → **partneři** → rezervace → kontakt + mapa → patička

## Partneři

Členění do tří úrovní je převzaté z ltkliberec.cz — bílé boxy s logy, největší u hlavních partnerů. Loga stažená z teniskv.cz, odkazy vedou na weby partnerů.

| Úroveň | Partneři |
|---|---|
| Hlavní partneři | Město Karlovy Vary, Karlovarský kraj, ALFABYT |
| Partneři | Národní sportovní agentura, Babolat, Safeguard Service |
| Svazy a instituce | Český tenisový svaz, Česká unie sportu, Spolufinancováno EU |

**Zařazení do úrovní je odhad** — současný web partnery neřadí, všechny uvádí v jedné řadě. ALFABYT je mezi hlavními proto, že dává jméno klubovému turnaji. Pořadí i úrovně je potřeba potvrdit s klubem.

## Obsah převzatý z teniskv.cz

- **Klub:** Tenisový klub Lokomotiva Karlovy Vary z.s., IČ 63554615, Bečovská 1811/11, 360 01 Karlovy Vary (areál Tuhnice)
- **Areál:** 7 antukových kurtů, 2 s tvrdým povrchem, tréninková zeď za centrkurtem, zimní přetlaková hala se 2 antukovými dvorci
- **Historie:** 1952 první dva kurty na Růžovém Vrchu (14 členů) → 1964 Stanislav Birner a Jaroslav Kolář zakládají klub v Tuhnicích → 1972 centrální kurt, exhibice Jan Kodeš vs. František Pála → 1985 samostatný subjekt → 2023 vedení Tomáš Kasík, hlavní trenér Štěpán Rinko → 2024 postup z divize do 2. ligy
- **Odchovanci:** Stanislav Birner ml. (Davis Cup), Jiří Havel, Luděk Šleis, Milan Birner
- **Tenisová škola:** školička do 7 let, škola 8—9 let, žactvo 10—14 let, dorost 15—18 let, rekreační tenis, příměstské tábory 6—16 let; přihlášky celoročně
- **Trenéři:** Martin Tofi (šéftrenér, 602 298 502), Štěpán Rinko (hlavní trenér, 725 307 413), Zuzana Horská (728 794 255), Patrik Abeldinov (728 688 179)
- **Ceník pronájmu (léto):** antuka 200 Kč/hod, tvrdý povrch 120 Kč/hod, člen + host 50 %
- **Ceník tréninků (od 6. 10. 2025, za hráče/hod, venku / hala):** 1 hráč 500/890, 2 hráči 300/490, 3 hráči 230/310, 4 hráči 190/270, 5+ hráčů 150/250
- **Rezervace kurtů:** +420 775 655 091 (předseda Ing. Josef Bauer)
- **Facebook:** facebook.com/tklokomotivakarlovyvary

## Ověřeno

- diakritika ve všech velkých nadpisech (kontrolní render, háčky a kroužky celé)
- responzivní chování na 390 px — žádné vodorovné přetečení v žádné variantě
- rendery přes headless Edge (Chrome na tomto stroji zlobí)

## Co ještě chybí pro ostrý web

- fotografie z areálu (návrhy zatím používají grafické plochy místo fotek)
- online rezervační systém (nyní jen telefon)
- členské příspěvky, stanovy, družstva, turnaje, galerie, Erasmus — podstránky
