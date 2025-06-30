> :white_check_mark: *Jeśli będziesz mieć problem z rozwiązaniem tego zadania, poproś o pomoc na odpowiednim kanale na Slacku, tj. `s10e01-gamedev-oop-advanced` (dotyczy [mentee](https://devmentor.pl/mentoring/)) lub na ogólnodostępnej i bezpłatnej [społeczności na Discordzie](https://devmentor.pl/discord). Pamiętaj, aby treść Twojego wpisu spełniała [odpowiednie kryteria](https://devmentor.pl/jak-prosic-o-pomoc/).*

&nbsp;

# `#01` GameDev: Programowanie Obiektowe Część II

## Gra RPG - Część I
Zaimplementuj prosty kreator postaci do gry RPG (np. jak w Baldur's Gate 3). Funkcjonalności:
1. Abstrakcyjna klasa `Character`
   - Powinna zawierać statystyki postaci, takie jak punkty zdrowia, siły i magii, oraz możliwość dodawania kolejnych;
   - Powinna zawierać aktualny stan postaci, takie jak aktualna ilość punktów zdrowia i magii;
   - Powinna zawierać abstrakcyjną metodę `UseSpecialAbility()`, która docelowo ma wyświetlić komunikat o wykonywanej czynności i odjąć punkty siły lub magii za jej użycie;
2. Zaimplementuj kilka klas postaci, np. rycerz, łucznik, mag; każda z nich powinna mieć unikalną implementację metody `UseSpecialAbility()`;
3. Cechy postaci i `CharacterBuilder`
   - Do klasy `Character` dodaj co najmniej pięć stałych cech danej postaci - np. wzrost, rasa, płeć;
   - Korzystając ze wzorca projektowego Builder, zaimplementuj klasę `CharacterBuilder`, która umożliwia wygodne nadawanie tych cech nowo tworzonej postaci;



&nbsp;
> :no_entry: *Jeśli nie posiadasz materiałów do tego zadania tj. **PDF, projekt + Code Review**, znajdziesz je na stronie [devmentor.pl](https://devmentor.pl/workshop-gamedev-oop-advanced)*

> :arrow_left: ~~*poprzednie zadanie*~~ | [*następne zadanie*](./../02) :arrow_right:
