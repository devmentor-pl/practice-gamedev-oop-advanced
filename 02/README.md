> :white_check_mark: *Jeśli będziesz mieć problem z rozwiązaniem tego zadania, poproś o pomoc na odpowiednim kanale na Slacku, tj. `s10e02-gamedev-oop-advanced` (dotyczy [mentee](https://devmentor.pl/mentoring/) lub na ogólnodostępnej i bezpłatnej [społeczności na Discordzie](https://devmentor.pl/discord). Pamiętaj, aby treść Twojego wpisu spełniała [odpowiednie kryteria](https://devmentor.pl/jak-prosic-o-pomoc/).*

&nbsp;

# `#02` GameDev: Programowanie Obiektowe Część II

## Gra RPG - Część II
To ćwiczenie jest kontynuacją ćwiczenia `Gra RPG - Część I`. Przekopiuj jego cały kod do tego projektu, by móc go rozbudowywać na potrzeby tego ćwiczenia:
1. System przedmiotów
   - Zaimplementuj klasę abstrakcyjną `Item`, która zawiera nazwę, wartość (ilość monet) oraz masę (w kg) danego przedmiotu, oraz metodę abstrakcyjną `Use(Character character)`;
   - Zaimplementuj klasę `Potion`, która w zależności od ustawionej wartości typu enumeratywnego, podczas użycia przywraca postaci punkty zdrowia, siły lub magii;
2. System inwentarza
   - Zaimplementuj interfejs `IInventory`, który zawiera metody `Add(Item item)`, `Remove(Item item)` oraz `GetAll()` i stanowi bazę pod poszczególne implementacje inwentarza;
   - Zaimplementuj klasę `Chest`, która implementuje interfejs `IInventory` (przechowuje przedmioty) i zawiera funkcjonalność otwarcia i zamknięcia na trzycyfrową kombinację - gdy skrzynia jest zamknięta, próba wywołania dowolnej metody z interfejsu `IInventory` powinna skutkować wyjątkiem;
   - Klasa `Character` też powinna zawierać swoją implementację `IInventory` (personalny ekwipunek gracza);

&nbsp;
> :no_entry: *Jeśli nie posiadasz materiałów do tego zadania tj. **PDF, projekt + Code Review**, znajdziesz je na stronie [devmentor.pl](https://devmentor.pl/workshop-gamedev-oop-advanced)*

> :arrow_left: [*poprzednie zadanie*](./../01) | [*następne zadanie*](./../03) :arrow_right:
