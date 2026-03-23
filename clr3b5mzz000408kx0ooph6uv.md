---
title: "Jak tworzyć szablony w Logseq?"
datePublished: 2024-01-07T09:45:06.479Z
cuid: clr3b5mzz000408kx0ooph6uv
slug: jak-tworzyc-szablony-w-logseq
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/7ACuHoezUYk/upload/8c90159145ad5e813fdb6fc6a6dfe027.jpeg
tags: logseq, notatki

---

Szablony są popularne w wielu aplikacjach, nie tylko w Logseq. Nie bez przyczyny.

Ciągłe wpisywanie tych samych elementów, i budowanie struktury od zera jest żmudne. A dodatkowo naraża nas na popełnianie błędów, i wprowadza niepotrzebny bałagan. Zabierając nam tym samym cenny czas na prawdziwie użyteczne i kreatywne czynności wymagające większego zaangażowania.

Stosując szablony w Logseq, możemy przygotować strukturę dla różnego typu notatek i projektów. Na przykład spójny szablon do rozmowy z klientem (taki szablon, może zawierać listę pytań czy informacji, które musimy uzyskać od klienta), albo szablon do notatek z zajęć na uczelni, czy listę typu 'krok po kroku' do opublikowania posta na blogu, czy innego wieloetapowego zadania.

Zdecydowanie łatwiej jest być zorganizowanym, kiedy mamy gotowce do wielokrotnego użytku. Bo dzięki jednolitej strukturze, łatwiej później podsumować, porównać czy zebrać informacje.

Poniżej przedstawiam wam, **jak tworzyć, edytować i korzystać z szablonów w Logseq**.

## Jak tworzyć szablony w Logseq?

W Logseq szablony nazywane są templates.

Możemy je **tworzyć w dowolnym miejscu w naszym grafie**, ale pozwólcie, że dla porządku, zasugeruję wam utworzenie osobnej strony o nazwie np. 'Moje Szablony'. Utworzenie osobnej strony przeznaczonej jedynie na szablony pozwoli nam na szybki dostęp do wszystkich naszych gotowców i przyda się podczas ich edycji.

Aby utworzyć stronę, klikamy 'New Page' w lewym dolnym rogu, w lewym panelu, nadajemy naszej stronie dowolną nazwę, a następnie naciskamy enter.

Przechodzimy do nowo utworzonej strony i zabieramy się za tworzenie pierwszego szablonu.

Najpierw wpisujemy nazwę-tytuł naszego szablonu, a następnie **w podblokach dodajemy wszystkie elementy**, które mają się w nim znaleźć. Dla przykładu, utwórzmy prosty szablon do notatek z książek:

![szablon-logseq-1.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1659603882909/8Gu9oPfET.png align="left")

Nie zapomnijmy, że w obrębie elementów szablonu możemy korzystać ze znaczników **markdown**, także możemy dodawać nagłówki, kursywę, czy wytłuścić tekst.

Kiedy jesteśmy zadowoleni z rezultatów i dodaliśmy już wszystkie konieczne elementy i sekcje do naszego szablonu, w Logseq mamy dwa sposoby na jego utworzenie (obie dają identyczny rezultat):

1. opcja 'Make template'
    
2. 'template' property
    

### Sposób 1

Prawym przyciskiem myszy klikamy na indykator bloku nadrzędnego, z listy opcji wybieramy 'Make template'

![make-template-logseq.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1659603257798/XQyJ3qG6_.png align="left")

Następnie dodajemy nazwę nowego szablonu, np. 'notatkiKsiążki'. Musimy jeszcze zadecydować czy chcemy, aby nadrzędny blok wchodził w skład naszego szablonu. W tym celu zaznaczamy, bądź odznaczamy opcję 'Including the parent block in the template?', ja zazwyczaj odznaczam tą opcję, ponieważ nie chcę, aby blok nadrzędny wchodził w skład mojego szablonu.

![szablon-logseq-2.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1659603302905/kpB_ZbEwp.png align="left")

**Gotowe, nasz szablon został utworzony!**

### Sposób 2

Mając kursor na końcu bloku nadrzędnego, naciskamy Shift + Enter i **ręcznie wpisujemy atrybut** 'template:: nazwa-szablonu'

![szablony-logseq-notatki-3.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1659605064365/hozTDqiS3.png align="left")

Możemy również dodać atrybut 'template-including-parent:: false' (albo true), w zależności od tego czy chcemy, aby blok nadrzędny znalazł się w szablonie.

Efekt jest dokładnie taki sam, jak przy pierwszym sposobie, tyle, że atrybuty musieliśmy dodać samodzielnie, a nie za pomocą opcji 'Make template'.

## Tworzenie szablonów z Logseq - video

Jak tworzyć i korzystać z szablonów w Logseq pokazuję na [kanale Połącz Myśli](https://www.youtube.com/channel/UCuo27x4w65c_coFgtDkbNtQ):

<iframe width="560" height="315" src="https://www.youtube.com/embed/TNWptm3ia78"></iframe>

## Jak korzystać z szablonów w Logseq?

Wywołanie szablonu jest bardzo proste.

Wystarczy, że w dowolnym miejscu naszego systemu, grafu wpiszemy ukośnik '/' i wybierzemy opcję 'Template', a następnie konkretny szablon z listy dostępnych.

![wstawianie-szablonu-logseq.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1659603372837/hHUixznTo.png align="left")

Po kliknięciu, elementy szablonu zostaną wstawione, a my możemy zacząć je dalej uzupełniać konkretnymi informacjami.

![szablony-logseq-6.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1659603393276/iZlarGYfl.png align="left")

## Jak edytować szablony w Logseq?

Edycja szablonów w Logseq jest również bardzo prosta.

Szczególnie, jeśli trzymamy wszystkie szablony na jednej podręcznej stronie (jak zasugerowałam na początku). Jeśli nie, zawsze możemy szybko odnaleźć wszystkie szablony korzystając z zapytania: {{ query (property template) }}

Aby wprowadzić zmiany w szablonie, **przechodzimy do oryginału szablonu**, a następnie modyfikujemy, dodajemy, lub usuwamy jego elementy. Możemy również zmienić nazwę szablonu, przez zmodyfikowanie atrybutu 'template:: zmieniona nazwa'.

Pamiętaj, że zmiany nie zostaną wprowadzone, tam gdzie już wcześniej użyto szablonu.

Jeśli chcemy usunąć szablon, wystarczy, że skasujemy jego blogi, lub usuniemy atrybut 'template::' z bloku nadrzędnego.

## Turbodoładowanie szablonów atrybutami

Nawet podstawowe szablony zawierające jedynie tekst są bardzo użyteczne.

Ale w Logseq możemy **połączyć siłę szablonów z innymi opcjami dostępnymi w tej aplikacji**. W szablonie możemy umieszczać połączenia (linki), tagi, albo nawet dynamicznie wstawić datę lub czas.

![dzisiejsza-data-logseq.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1659623086883/mln7uNlEZ.png align="left")

![data-logseq.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1659623072625/1mK21yBXa.png align="left")

Myślę, że szczególnie użyteczne będzie dodanie **properties (atrybutów)** do naszych szablonów. Zaletą korzystania z atrybutów jest to, że mogą być one wykorzystywane przy konstruowaniu zapytań (queries).

Dzięki wykorzystaniu atrybutów i zapytań, możemy stworzyć listę przeczytanych materiałów, listę aktualnych projektów, itp.

Atrybuty dodajemy poprzez dodanie :: (podwójnego dwukropka), nazwa atrybutu:: wartość.

## Kiedy i dlaczego używać szablonów w Logseq?

Szablony dają moc.

* oszczędzają nam czas i wysiłek
    
* dodają jednolitości i przejrzystości naszym notatkom
    
* zmniejszają ryzyko pojawienia się błędów
    
* są dobrym punktem startowym, instrukcją przy wykonywaniu wieloetapowych zadań
    

Pamiętaj jednak, żeby nie tworzyć ich na zapas, a w miarę potrzeby. Dla czynności, elementów, które faktycznie powtarzasz.

Szablony mają zmniejszyć nasz nakład pracy i wysiłku, a nie nam ich dodać!

Jeśli szukasz dodatkowych informacji na temat szablonów w Logseq, odwiedź ich [oficjalną dokumentację](https://docs.logseq.com/#/page/templates).