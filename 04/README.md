> :white_check_mark: *Jeśli będziesz mieć problem z rozwiązaniem tego zadania, poproś o pomoc na odpowiednim kanale na Slacku, tj. `s10e04-gamedev-oop-advanced` (dotyczy [mentee](https://devmentor.pl/mentoring/)) lub na ogólnodostępnej i bezpłatnej [społeczności na Discordzie](https://devmentor.pl/discord). Pamiętaj, aby treść Twojego wpisu spełniała [odpowiednie kryteria](https://devmentor.pl/jak-prosic-o-pomoc/).*

&nbsp;

# `#04` GameDev: Programowanie Obiektowe Część II

## Gra RPG - Część IV
To ćwiczenie jest kontynuacją ćwiczenia `Gra RPG - Część III`. Przekopiuj jego cały kod do tego projektu, by móc go rozbudowywać na potrzeby tego ćwiczenia:
1. System handlu
   - Zaimplementuj interfejs `ITrade`, który zawiera metody `TryBuy(Item item)`, `TrySell(Item item)`, który dziedziczy po `IInventory`;
   - Zaimplementuj nową klasę postaci: handlarz - `Merchant`, oraz klasę `MerchantBuilder`, która umożliwia łatwe i wygodne stworzenie handlarza z konkretnymi przedmiotami i ich ilościami;
   - Zaimplementuj nową klasę przedmiotu: `Gold`, która zawiera właściwość `Amount` i domyślnie znajduje się w inwentarzu każdej postaci z ilością `0`;
   - Zaimplementuj w klasie `Character` interfejs `ITrade` - czyli funkcjonalność handlu;
2. System doświadczenia
   - Zaimplementuj system zbierania doświadczenia (wartości liczbowej) poprzez wykonywanie akcji, takich jak wygranie walki, czy sprzedaż przedmiotu;
   - Po osiągnięciu progu doświadczenia (np. `100`, zwiększony zostaje poziom postaci, co zwiększa jego bazowe wartości zdrowia, siły i magii o 10%;
   - Każdy kolejny próg jest dwa razy większy od poprzedniego;

&nbsp;

> :no_entry: *Jeśli nie posiadasz materiałów do tego zadania tj. **PDF, projekt + Code Review**, znajdziesz je na stronie [devmentor.pl](https://devmentor.pl/workshop-gamedev-oop-advanced)*

> :arrow_left: [*poprzednie zadanie*](./../03) | [*następne zadanie*](./../05) :arrow_right:
