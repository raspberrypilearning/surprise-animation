## Dodaj niespodziankę!

Teraz musisz dodać niespodziankę. Co może się stać z obiektem?
- Czy zamieni się w inny przedmiot?
- Czy zmieni się w postać?
- Czy zniknie i odsłoni kolejnego duszka?

Ty decydujesz! Utwórz **trzecią część** swojej animacji.

![Taśma filmowa z 3 klatkami. Trzecia klatka jest podświetlona. Ramka przedstawia scenę, w której postać wygląda na zaskoczoną obiektem.](images/surprise.png)

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
Czy napisałeś historię z niespodzianką lub zwrotem akcji? Oglądałeś program lub czytałeś książkę z niespodziewanym zakończeniem? Możesz użyć tych samych metod podczas tworzenia cyfrowej opowieści lub animacji. 
</p>

### Kiedy nastąpi niespodzianka?

--- task ---

Wybierz 🎂🎾🎁 **interesujących obiektów** duszka. Dodaj skrypt, aby niespodzianka zaczęła się, kiedy chcesz.

Musisz wybrać opóźnienie, które będzie pasować do Twojego projektu. Jeśli masz postać, która spędza dużo czasu na zaciekawienie, będziesz musiał wybrać dłuższe opóźnienie.

```blocks3
when flag clicked
wait (5) seconds // zmień liczbę, aby utworzyć opóźnienie czasowe
```

--- /task ---

### Teraz stwórz niespodziankę!

--- task ---

Obiekt może `zagrać dźwięk`{:class="block3sound"}, `zmienić kostium`{:class="block3looks"}, `zmienić efekty graficzne`{:class="block3looks"} lub `zmienić rozmiar`{:class="block3looks"}.

Można dodać zaskakujący strój do duszka, aby później mógł `zmień kostium`{:class="block3looks"}, aby go odsłonić.

![Tło pustyni ze skałą jiggling tam i z powrotem.](images/bat.gif)

[[[scratch3-add-costumes-to-a-sprite]]]

Możesz sprawić, by duszek zmienił się w innego duszka — aby to zrobić, `ukryj`{:class="block3looks"} 🎂🎾🎁 **interesujący obiekt** duszek w tym samym czasie, gdy `pokaż`{:class="block3looks"} inny duszek.

--- collapse ---
---
title: Ukryj i pokaż duszki
---

🎂🎾🎁 **interesujący obiekt** sprite:
```blocks3
when flag clicked
show
wait (5) seconds
hide
```

🎷👻⚡**obiektów niespodzianek** sprite:
```blocks3
when flag clicked
hide
wait (5) seconds
show
```

**Wskazówka:** Jeśli stworzysz 🎷👻⚡**obiekt-niespodziankę** duszek `pokaż`{:class="block3looks"}, będziesz musiał to zrobić `ukryj`{:class="block3looks"} `po kliknięciu zielonej flagi`{:class="block3events"}.

--- /collapse ---

--- /task ---

--- task ---

**Test:** Kliknij zieloną flagę. Czy niespodzianka zdarza się we właściwym czasie? Czy animacja resetuje się prawidłowo?

--- /task ---

--- task ---

**Debugowanie:**

Jeśli chcesz, aby duszek znajdował się przed lub za innym duszkiem, możesz użyć warstw:

[[[scratch3-positioning-with-layers]]]

Jeśli niespodzianka wydarzy się w niewłaściwym czasie, możesz to naprawić:

--- collapse ---
---
title: Niespodzianka zaczyna się w złym momencie
---

Być może będziesz musiał zmienić czas w niektórych lub wszystkich blokach `czekaj`{:class="block3control"} lub dodać więcej bloków `czekaj`{:class="block3control"}, aby uzyskać właściwy czas.

--- /collapse ---

--- /task ---

