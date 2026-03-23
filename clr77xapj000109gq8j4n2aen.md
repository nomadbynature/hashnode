---
title: "Lista książek przeczytanych i do przeczytania w Logseq"
datePublished: 2024-01-10T03:25:43.159Z
cuid: clr77xapj000109gq8j4n2aen
slug: lista-ksiazek-przeczytanych-i-do-przeczytania-w-logseq
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/7ACuHoezUYk/upload/7e5713a854b276c7ff286423e2747d3d.jpeg
tags: logseq

---

Aby skutecznie wykorzystać Logseq i utworzyć tracker książek, będzie nam potrzebna znajomość: szablonów, atrybutów oraz zapytań w tej aplikacji.

### Szablony (Templates)

Szablony pozwalają na wielokrotne wykorzystanie tych samych elementów. Przydadzą się wszędzie tam, gdzie mamy do czynienia z powtarzalnymi czynnościami (np. powtarzalna struktura do notatek ze spotkania, czy wykłdów, formularz do wypełnienia, notatki z książek...)

Szablon w Logseq tworzymy przez dodanie atrybutu **template**.

### Atrybuty (Properties)

Atrybuty nadają dodatkowych cech naszym notatkom - blokom lub stronom.

W Logseq mamy kilka domyślych atrybutów (np. icon), ale możemy dodawać również własne Jak zobaczymy przy tworzeniu naszego trackera, **atrybuty tworzą nagłówki kolumn w tabelce w wynikach naszych zapytań**.

### Zapytania (Queries)

Zapytania możemy przyrównać do zaawansowanego wyszukiwania.

A do tego, wyniki zapytań w Logseq **zmieniają się dynamicznie** (wraz ze zmianami w naszych notatkach), o czym również zaraz się przekonamy.

## Tworzymy tracker krok po kroku

### Stwórzmy szablon

Szablon będzie nam potrzebny, ponieważ chcemy, aby wszystkie materiały (w tym wypadku książki), **miały te same metadane**. Dzięki temu, później będą jednolicie prezentowały się w wynikach zapytania (query).

Szablon możemy utworzyć w dowolnym miejscu naszego grafu, ale myślę, że najlepiej będzie **utworzyć osobną stronę**, na której będziemy umieszczać wszystkie nasze przyszłe szablony - wtedy najłatwiej je odnaleźć i w razie potrzeby edytować.

Na nowo utworzonej stronie np. 'Szablony', **utwórzymy nowy szablon**, zawierający wszystkie elementy, które mają wspomagać nasze notatki z lektury.

Możemy dodać takie elementy jak np.:

![szabln-logseq.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1662199884881/u4Lxexe88.png align="left")

Pamiętajmy, że w obrębie szablonu, możemy również **korzystać z markdown** - także możemy dodać nagłówki, wytłuszczenia, itp. Oraz zastosować **dynamic variables** (dynamiczne zmienne).

W przypadku naszego książkowego szablonu, chcemy dodać również atrybuty - nasze metadane. Mogą się tu znaleźć takie pozycje jak: tytuł, autor, rok wydania, ocena, typ, okładka...

Jeśli chcecie dodać okładkę, podaję wam formułę do wstawiania obrazu:

```plaintext
![image](){:height 86, :width 49}
```

Co ważne atrybuty dodajemy w pierwszym podbloku naszego szablonu, aby przeskoczyć do następnego wiersza, a nie następnego bloku musmy nacisnąć Enter, przytrzymując Shift (Shift + Enter). Atrybuty dodajemy poprzez dodanie podwójnego dwukropka, w takiej formule:

nazwa\_atrybutu:: wartość\_atrybutu

**Uwaga!** To jakie elementy będzie zawierał wasz szablon, będzie zależało od was. **Nie możemy zapomnieć jednak o dodaniu atrybutu typ:: książka**. To ten atrybut będziemy wykorzystywać przy konstruowaniu zapytania do wygenerowania naszej listy.

Kiedy jesteśmy już zadowoleni z efektów i dodaliśmy wszystkie sekcje oraz atrybuty (~metadane), teraz do bloku nadrzędnego dodajemy domyślny atrybut szablon - tworząc tym samym szablon (więcej o tym [jak utworzyć szablon](https://polaczmysli.com/jak-tworzyc-szablony-w-logseq)).

### Dodajmy pozycje książkowe z wykorzystaniem szablonu

Od teraz, za każdym razem kiedy dodajemy w Logseq nową książkę i notatki na jej temat, możemy korzystać z przygotowanego szablonu.

Wszystkie nasze notatki na temat przeczytanych lektur będą miały jednolitą strukturę, co na pewno się przyda przy ich podsumowywaniu, porównywaniu, czy przeglądzie.

Ja dla każdej przeczytanej książki dodaję osobną stronę w Logseq, a następnie wstawiam na niej szablon, poprzez wpisanie '/' (ukośnika), a następnie opcji 'template' i wyboru odpowiedniego szablonu z listy:

![wstawiamy-szablon-logseq.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1662201321972/QIdagLAMj.png align="left")

![szablon-logseq-książki.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1662201335144/ooGXQNJ8s.png align="left")

Po wstawieniu szablonu, **uzupełniamy dane**:

![notaki-ksiazki-logseq.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1662201482266/hiyi1ruoh.png align="left")

![notatki-z-ksiazek-logseq.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1662201493702/iEH_1M7dC.png align="left")

Linki do zdjęć okładek, możecie skopiować ze strony np. [GoodReads](https://www.goodreads.com/).

Aby stworzyć listę, najlepiej dodać co najmniej parę pozycji książkowych w naszym grafie. Czy to tych przeczytanych, czy jeszcze do przeczytania.

### Napiszmy zapytanie, aby śledzić przeczytane książki

Ostatni etap to napisanie zapytania (query), które pokaże nam wszystkie pozycje książkowe, w ramach jednej, schludnej listy.

Najpierw, za pomocą ukośnika '/' wywołujemy opcję query, a następnie konstruujemy zapytanie pokazujące wszystkie strony z atrybutem 'książka'.

Zapytanie będzie wyglądało następująco:

```plaintext
{{query (page-property typ "książka")}}
```

**Tracker gotowy!**

![lista-książęk-śledzik-tracker-logseq.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1662204417997/7UaNPiWMS.png align="left")

**Teraz możemy zauważyć, że atrybuty (properties) odpowiadają nagłówkom kolumn w tabelce z wynikami!**

Wygląd takiej tabeli możemy zmienić, pozbywając się niechcianych kolumn, lub zmieniając ich kolejność. W tym celu klikamy 'Set Properties' i korzystamy z suwaków do włączania/wyłączania poszczególnych atrybutów (kolumn).

![set-properties-logseq.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1662204740874/UopV62knv.png align="left")

![kolumny-lista-ksiazek.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1662204759246/jQuYM04rh.png align="left")

Aby zmienić kolejność kolumn, musimy najpierw odznazyć widocznośc wszystkich kolumn (oprócz przynajmniej jednej), a następnie pozaznaczać je w kolejności, w jakiej chcemy, aby wyświetlały się w tabeli z wynikami.

Oczywiście, zapytanie możemy modyfikować i uszczegóławiać, np. wyświetlić tylko książki, które mamy jeszcze do przeczytania - tworząc tym samym listę pozycji do przeczytania. Oczywiście pod warunkiem, że dodaliśmy atrybut, np. status:: do przeczytania.

Wtedy zapytanie będzie wyglądało następująco:

```plaintext
{{query (and (page-property typ "książka") (page-property status "do przeczytania"))}}
```

![lista-tracker-ksiazek-do-przeczytania.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1662204457478/iEAvoBdiR.png align="left")

Pamiętajmy, że **raz napisane zapytanie będzie zmieniać się dynamicznie**, wraz ze zmianami w naszym systemie notatek. Jeśli dodamy notatki na temat nowych książek, pojawią się one w wynikach query. Jeśli usuniemy jakieś książki (a dokładniej, usuniemy atrybut typ:: książka), znikną one z wyników.

Dlatego query różnią się znacząco od prostego wyszukiwania (za pomocą paska wyszukiwania), czy nawet filtrów w sekcji linked references - wystarczy napisać je raz, a wyniki będą widoczne cały czas.

## Nagranie YouTube już na kanale Połącz Myśli

W nagraniu pokazuję, jak zrobić śledzik (tracker) książek:

<iframe width="560" height="315" src="https://www.youtube.com/embed/GDYutx3co80"></iframe>

## Jak jeszcze wykorzystać funkcje Logseq?

Znajomość wykorzystania szablonów, atrybutów i zapytań w Logseq, daje nam duże możliwości.

Oprócz śledzenia (inwentaryzacji) książek, możemy stworzyć tacker PDF-ów, listę aktualnych projektów, własny ranking ulubionych filmów, gier czy seriali. Tracker przyda się przy wieloetapowych zadaniach, np. przy nagrywaniu video na YT, przy tworzeniu treści na social media, pisaniu bloga...

Wystarczy dobrze poznać możliwości Logseq, a to w jaki sposób je wykorzystacie, będzie już zależało od waszych zainteresowań i celów.

%%[buycoffee]