> :white_check_mark: *Jeśli będziesz mieć problem z rozwiązaniem tego zadania, poproś o pomoc na odpowiednim kanale na Slacku, tj. `s10e03-gamedev-oop-advanced` (dotyczy [mentee](https://devmentor.pl/mentoring/)) lub na ogólnodostępnej i bezpłatnej [społeczności na Discordzie](https://devmentor.pl/discord). Pamiętaj, aby treść Twojego wpisu spełniała [odpowiednie kryteria](https://devmentor.pl/jak-prosic-o-pomoc/).*

&nbsp;

# `#03` GameDev: Programowanie Obiektowe Część II

## Gra RPG - Część III
To ćwiczenie jest kontynuacją ćwiczenia `Gra RPG - Część II`. Przekopiuj jego cały kod do tego projektu, by móc go rozbudowywać na potrzeby tego ćwiczenia:
1. System ekwipunku
   - Zaimplementuj klasę `Weapon`, która zawiera typ broni (miecz, łuk, kostur magiczny) oraz ilość obrażeń;
   - Zaimplementuj klasę `Armor`, która zawiera typ pancerza (zbroja, ubranie, szata) oraz ilość redukowanych obrażeń;
   - Zaimplementuj klasę CharacterEquipment, która służy do zakładania/zdejmowania broni oraz pancerza z inwentarza;
   - Zaimplementuj zasady ograniczające zakładanie poszczególnych typów broni przez poszczególne klasy postaci (np. rycerz nie może używać kosturu magicznego);
2. System walki
   - Zaimplementuj interfejs `ICombat`, który zawiera metodę `Hit(Character defender)`;
   - Zaimplementuj ten interfejs w klasie Character - wywołanie metody Hit powinno obliczyć ilość zadanych obrażeń (`obrażenia broni - obrona zbroi`) i odjąć odpowiednią ilość punktów zdrowia;
   - Zaimplementuj w klasie `Character` właściwość tylko do odczytu `IsDead`;


&nbsp;

> :no_entry: *Jeśli nie posiadasz materiałów do tego zadania tj. **PDF, projekt + Code Review**, znajdziesz je na stronie [devmentor.pl](https://devmentor.pl/workshop-gamedev-oop-advanced)*

> :arrow_left: [*poprzednie zadanie*](./../02) | [*następne zadanie*](./../04) :arrow_right:
