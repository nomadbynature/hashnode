---
title: "Więcej funkcji z wtyczkami Logseq (plugins)"
datePublished: 2024-01-10T03:17:35.025Z
cuid: clr77mu29000409jphhvkcekm
slug: wiecej-funkcji-z-wtyczkami-logseq-plugins
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/PbgY3ptgA4A/upload/4e3212ed8f86e48bf06b4c06c258ac4d.jpeg
tags: logseq

---

Plugins czyli wtyczki poszerzają funkcjonalność aplikacji. Pozwalają na zgrabne ominięcie niedociągnięć, czy dopełnienie brakujących funkcji.

Podobnie jak w przypadku aplikacji [Obsidian.md](https://nomadbynature.xyz/aplikacja-obsidian-jak-zaczac-uzywac) i w Logseq wtyczki często tworzone są przez prężną społeczność i entuzjastów aplikacji.

Najlepsze jest to, że wtyczki możemy dobierać samodzielnie i do własnych potrzeb. Choć trzymałabym się tutaj raczej zasad [cyfrowego minimalizmu](https://nomadbynature.xyz/cyfrowy-minimalizm-cal-newport-sposob-na-uzaleznienie-od-smartphona) - nie wszystkie pluginy jak leci i przeładowany interface, tylko przemyślany wybór.

Nie wszystkie opcje są potrzebne każdemu z nas! Zanim dodacie daną wtyczkę, zadajcie sobie pytania: **Czy jest mi ona potrzebna? Czy to tylko nieprzydatny bajer?**

W poście przedstawiam wam parę fajnych i popularnych wśród logseqowców/logseqerów? ;P wtyczek. Może i wam coś się z tej listy przyda.

# Jak dodać/zainstalować wtyczki w Logseq?

Aby dodać wtyczki w aplikacji Logseq, przechodzimy do ustawień (...)--&gt; Plugins --&gt; zakładka Marketplace. Następnie możemy przeglądać dostępne wtyczki, lub wyszukać tą, która nas interesuje.

![instalacja-wtyczek-logseq.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1663584343636/H90ov_mFr.png align="left")

![plugins-logseq-dodaj.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1663584358573/u6zpLhuwo.png align="left")

Aby wtyczki działały prawidłowo, nie możemy zapomnieć o ich aktualizacji. Od czasu do czasu, zajrzyjmy, więc do zainstalowanych wtyczek, przechodząc do ustawień (...) --&gt; Plugins (zakładka Installed), i sprawdzając ich status.

![aktualizacja-wtyczki-logseq.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1663584402428/6Tn2SbnPX.png align="left")

Dodatkowo, niektóre wtyczki mają własne ustawienia. Do ustawień konkretnych wtyczek, możemy dostać się poprzez:

1. ustawienia (...) --&gt; Settings --&gt; zakładka Plugin Settings lub
    

![ustawienia-logseq.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1663584778602/2H-5gsxNd.png align="left")

![zakładka-plugin-settings-logseq.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1663584795837/Wk925FDkN.png align="left")

1. ustawienia (...)--&gt; Plugins --&gt; ustawienia poszczególnych wtyczek (zębatka)
    

![ustawienia-wtyczek-logseq.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1663584816576/Bn4CBUZm1.png align="left")

## Jak usunąć/odinstalować wtyczkę w Logseq?

Podobnie jak przy aktualizacji, przechodzimy do ustawień (...) --&gt; Plugins (zakładka Installed). Następnie klikamy na małą zębatkę w lewym dolnym rogu kafelka wtyczki, którą chcemy odinstalować, i wybieramy opcję 'Uninstall'.

![odinstalowanie-wtyczki-logseq.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1663585033643/TlwvxWfeY.png align="left")

# Lista przydatnych wtyczek

## Journals Calendar

Obawiam się, że bez tej wtyczki się nie obędziecie.

Jest to wtyczka, którą polecam zainstalować każdemu, zaraz po instalacji samego Logseq. Znacznie ułatwia ona pracę z aplikacją i poruszanie się pomiędzy dziennikami na poszczególne dni oraz błyskawiczne tworzenie stron dziennika na przyszłe dni.

![calendar-logseq.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1663585548902/Kg2FG6gLi.png align="left")

Domyślnie, to niedziela jest ustawiona, jako pierwszy dzień tygodnia. Możemy to zmienić przechodząc do ustawień wtyczki i zmieniając firstDayOfWeek na cyfrę '2' (jeśli, chcemy, aby poniedziałek wyświetlał się jako pierwszy).

![poniedziałek-pierwszy-dzien-logseq.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1663585566372/NXwHVgeCL.png align="left")

**Pro Tip** Nie jest to co prawda wskazówka dotycząca wtyczek, ale skoro jestem już przy dniach tygodnia, to wspomnę o tym, jak zmienić pierwszy dzień tygodnia (z niedzieli na poniedziałek), w samym kalendarzu Logseq. Wiem, że dla Europejczyków jest to dość irytująca kwestia!

Przechodzimy do ustawień (...) --&gt; Settings --&gt; otwieramy **'Edit config.edn'** --&gt; na końcu pliku (wewnątrz nawiasu klamrowego) dodajemy \*\* :start-of-week 0\*\* --&gt; zamykamy plik --&gt; re-index graph (w lewym panelu bocznym, w menu grafu). Jeśli w pliku config.edn jest już opcja :start-of-week, to nic nie dodajemy, a jedynie zmieniamy cyfrę na 0.

Tydzień będzie już zaczynał się od poniedziałku :)

## Bullet Threading

Ta opcja jest domyślna w niektórych motywach - np. w Developer Theme, którego używam. Ale jeśli korzystacie z motywu, który nie ma domyślnego bullet threading, to warto pomysleć o tej wtyczce.

Znacząco poprawia pracę z narzędziem, ponieważ **wyraźnie pokazuje, na którym poziomie (gałęzi), twojego outline'u jesteś** (gdzie jest kursor). Tak, żeby się łatwo nie pogubić, przy pracy z wieloma długimi notatkami i skomplikowanym outlinem.

Ciężko, to wytłumaczyć, najlepiej pokazać na zrzucie ekranu, jak wygląda bullet threading:

![brak-bullet-threading-logseq.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1663585895873/mqxpgfrwa.png align="left")

![bullet-threading-logseq.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1663585905268/6qmKFL7x-.png align="left")

W ustawieniach tej wtyczki możecie zmienić kolor linii, lub jej grubość.

## Logseq Anki Sync

Wtyczka dla miłośników fiszek, i/lub uczących się np. języków.

Logseq co prawda ma wbudowaną opcję fiszek i SR (spaced repetition), ale takie podstawowe fiszki mogą nie spełnić waszych oczekiwań. Ja sama na początku używałam domyślnych fiszek do nauki chińskiego, (i nadal przydają mi się do zdań), ale wolę jednak korzystać z bardziej wyspecjalizowanych aplikacji (Pleco, Skritter).

Anki to znana od lat i bardzo rozbudowana aplikacja do tworzenia i powtarzania fiszek. Dzięki wtyczce w Logseq połączycie możliwości obu aplikacji i dodacie nowe fiszki z Logseq do Anki i odwrotnie. Wtyczka daje również możliwość tworzenia odwróconych fiszek, co nie jest automatycznie możliwe w przypadku domyślnej funkcji fiszek.

Aby, korzystać z tego plugin'u trzeba mieć na komputerze zainstalowany program [Anki](https://apps.ankiweb.net/) z AnkiConnect. Po więcej informacji, jak zsynchronizować wasze fiszki, zajrzyjcie do dokumentacji pluginu Logseq Anki Sync.

## Todoist (Logseq Todoist Plugin)

Kolejna integracja ze znaną aplikacją, tym razem do zarządzania zadaniami - [Todoist](https://todoist.com/home).

Jeśli korzystacie z Todoist i/lub chcecie otrzymywać powiadomienia na telefonie (lub innych urządzeniach) o nadchodzących zadaniach do wykonania, czy liście zakupów, to ta wtyczka jest dla was.

**Łatwo stworzycie zadania w Logseq, które możecie następnie wysłać na wasze konto Todoist**, które możecie podglądać na telefonie i w biegu. Tak samo, zadania utworzone w Todoist, możecie synchronizować do Logseq.

Sama nie korzystam z tej wtyczki, bo nie mam konta Todoist, ale ponieważ jak na razie Logseq nie ma sync, ani alertów, może być to przydatna opcja dla zabieganych.

Sama przy zarządzaniu zadaniami eksperymentuję z plugin'em Agenda, a ostatnio, po przerwie wróciłam też do [GTD w Notion](https://nomadbynature.xyz/jak-zaczac-z-aplikacja-notion-poradnik-dla-poczatkujacych?x-host=nomadbynature.xyz).

## Swap Blocks

To prosty plugin pozwalający na zamianę miejsca bloku &lt;--&gt; odniesienia do bloku (block reference) oraz szybkie dodanie podbloków do odniesienia.

Usprawnia łączenie i pracę nad informacjami, którymi akurat się zajmujemy (przyspieszony dostęp do oryginalnej notatki i jej podbloków).

![swap-block-plugin-logseq.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1663595743742/uhYsdLIJU.png align="left")

![zamiana-logseq-aplikacja.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1663595754449/SPEEy6gQb.png align="left")

Opcje wtyczki, dostępne są w menu bloku (kliknij prawym przyciskiem myszy na indykator bloku).

![swap-ref-logseq.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1663595723544/nl_US2ibR.png align="left")

## Tabs

Tabs, czyli zakładki. Odpowiedź na pytanie, co robi ta wtyczka, mamy w jej nazwie. Pozwala na tworzenie zakładek w Logseq, na wzór zakładek w przeglądarce internetowej.

Wypróbowałam dla was ten plugin, ale mi się nie do końca spodobał, ponieważ za duża ilość zakładek mnie rozprasza. Wolę mieć jedno okno w którym pracuję, szczególnie, że Logseq ma pomocny prawy panel boczny, do którego mogę zrzucić przydatne strony i bloki.

Kolejne zakładki otwieramy przytrzymując ctrl (lub cmd na Mac) i klikając na stronę, lub blok, który chcemy otworzyć.

![tabs-logseq-wtyczka.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1663596791325/OeqQaY2mC.png align="left")

Choć ja wolę akurat nie korzystać z Tabs, plugin na pewno przyda się niektórym z was.

## Focus Mode

Z tym plugin'em możesz błyskawicznie przeskoczyć do trybu 'bez rozproszeń'.

Przydaje się, przy pisaniu, zwłaszcza dłuższych form tekstowych, kiedy musimy bardziej się skupić. Plugin chowa takie elementy, jak panele boczne i przełącza aplikację w tryb pełnoekranowy (choć dokładne ustawienia zależą od was).

Po instalacji, przejdźcie do ustawień wtyczki, wprowadźcie pożądane zmiany, i jeśli jesteście już zadowoleni z nowych ustawień, zrestartujcie Logseq. Domyślnie, skrót 'ff' przełączy was do trybu 'bez rozproszeń' (focus mode).

![focus-logseq-aplikacja.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1663597707335/J0yV2dlJw.png align="left")

## Link Preview

Bardzo prosta, acz przydatna wtyczka - wyświetla mały podgląd linków zewnętrznych, kiedy najedziemy na jeden z nich kursorem.

![podglad-linku-logseq.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1663598821164/K6-xM-vl6.png align="left")

Po wywołaniu komendy /Convert link to a link card, przekształci link tekstowy w 'link card'.

![convert-link-to-card-logseq.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1663598859988/j6Ibp--wa.png align="left")

![logseq-link-card.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1663598843946/lx-ivFAAg.png align="left")

## Logseq Smartblocks

Wtyczka oryginalnie powstała dla [RoamResearch](https://nomadbynature.xyz/aplikacje-do-robienia-notatek-i-zarzadzania-wiedza-zrob-porzadek-w-swoich-notatkach), ale została zaadoptowana na potrzeby Logseq.

Dodaje ona nowe możliwości przy tworzeniu [templates (szablonów)](https://www.youtube.com/watch?v=TNWptm3ia78) i pozwala na ich szybkie wstawianie za pomocą 'templater button' przycisku.

Na razie za wiele na jej temat nie powiem, bo dopiero ją zainstalowałam i testuję.

## Wygeneruj spis treści

Do wygenerowania spisu treści (na podstawie nagłówków i/lub poziomów w naszym outlinie), znajdziemy w Logseq Marketplace dwa popularne plugin'y:

* TOC Generator
    
* Logseq TOC Plugin (real-time generation)
    

(TOC - Table of Contents)

Oba plugin'y przydadzą się przy nawigacji po długim outlinie, albo np. do wygenerowania spisu treści do e-booka, broszury, itp.

## Omnivore

Ostatnio odkryłam tą wtyczkę (i samą aplikację Omnivore), i od razu bardzo mi się spodobała!

Omnivore to alternatywa dla np. [Pocket](https://getpocket.com/en/), czy innych aplikacji typu read-later, pozwalających na zbieranie ciekawych linków i materiałów napotkanych w sieci i zachowanie ich do późniejszego przeczytania.

Omnivore to również wygodny czytnik, pozwalający na zakreślanie (robienie highlightów) w czytanych przez nas artykułach.

Po połączeniu z Logseq, highlighty i komentarze, które zrobimy podczas czytania w aplikacji Omnivore, będą automatycznie dodane jako notatki w Logseq.

Jest to szczególnie przydatne, jeśli przeglądacie internet i czytacie na różnych urządzeniach (np. na iPadzie, laptopie).

Omnivore + Logseq krok po kroku

1. załóż konto na [Omnivore.app](https://omnivore.app/auth/email-signup)
    
2. dodaj Omnivore extension do swojej przeglądarki internetowej
    
3. ściągnij czytnik Omnivore na swoje urządzenie, np. iPad (z AppSore)
    
4. zainstaluj wtyczkę Omnivore w Logseq
    
5. stwórz i skopiuj [klucz do Omnivore API](https://omnivore.app/settings/api)
    
6. wklej skopiowany klucz w ustawieniach wtyczki Omnivore w Logseq
    

Gotowe! Twoje highlighty będą synchronizowane.

---

Logseq ma jeszcze wiele innych plugin'ów. Zachęcam was do samodzielnego przejrzenia Marketplace i wypróbowania dostępnych opcji. Czy macie inne, ulubione wtyczki, o których nie wspomniałam? A może macie pomysł na zupełnie nową, która dopełniłaby wasz workflow?

Dajcie mi znać w komentarzu.

---

Przydały ci się informacje zawarte w artykule? Chcesz wspomóc mojego bloga? Możesz to zrobić [stawiając mi kawę](https://buycoffee.to/nomadbynature).

%%[buycoffee]