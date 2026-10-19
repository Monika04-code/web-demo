# Ukážkový e-shop: Zlatý knôt

Frontendová ukážka e-shopu s ručne vyrábanými sviečkami. Vytvorená v čistom HTML, CSS a JavaScripte, bez knižníc a bez servera. Značka, produkty a ceny sú vymyslené.

## Čo ukazuje
- Prémiový tmavý dizajn so zlatým akcentom, responzívny pre mobil aj počítač
- Zoznam produktov s ilustráciami (SVG), popisom vôní a cenou
- Funkčný košík: pridanie, zmena množstva, odstránenie položky
- Výpočet medzisúčtu, dopravy a celkovej sumy v eurách so slovenským formátom
- Doprava zadarmo od 50 € s informáciou, koľko do nej chýba
- Košík sa uchová aj po obnovení stránky (localStorage)
- Prístupnosť: natívne dialógové okno košíka, popisky tlačidiel, viditeľné zvýraznenie pri ovládaní klávesnicou

## Čo to nie je
Je to ukážka predného rozhrania (frontendu). Neobsahuje platobnú bránu, databázu ani správu objednávok, takže tlačidlo „Pokračovať k objednávke" len zobrazí informáciu. Nejde o e-shop na platforme Shopify ani WooCommerce.

## Ako ho otvoriť
Stiahni `index.html` a otvor ho v prehliadači. Nič ďalšie nie je potrebné.

## Úprava
- Produkty sú v poli `PRODUCTS` v časti `<script>`. Pridaj nový objekt s názvom, vôňou, cenou a farbou.
- Hranica dopravy zadarmo a cena dopravy sú v premenných `FREE_FROM` a `SHIPPING`.
- Farby sú na začiatku súboru v `:root`.

## Autorka
Monika. Ukážka mojej práce s webom a JavaScriptom.
