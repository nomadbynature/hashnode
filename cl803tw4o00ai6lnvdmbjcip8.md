---
title: "Pokaż światu swoje portfolio w 10 minut z Notion"
datePublished: 2022-08-22T21:00:00.000Z
cuid: cl803tw4o00ai6lnvdmbjcip8
slug: pokaz-swoje-portfolio-z-notion-darmowa-strona-internetowa
cover: https://cdn.hashnode.com/res/hashnode/image/unsplash/gREi-9tI5Mg/upload/v1663343662442/zeRtgqbtm.jpeg
tags: notion, vercel, midjourney

---

Ostatnio zachwyciło mnie Midjourney AI.

To sztuczna inteligencja, tworząca niesamowite obrazy i grafiki na podstawie twoich instrukcji. Spójrzcie sami na jedną z moich prac:

![nomadbynature-yurt-1.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1663067468286/Grp-5LPFR.png align="left")

Od razu chciałam podzielić się najlepszymi obrazami z przyjaciółmi!
Ale wysyłać im zdjęcie po zdjęciu...to nie ma sensu. Przyszedł mi na myśl Instagram, ale nie chcę tworzyć nowego konta.

Wtedy przypomniałam sobie, że mogę skorzystać z Notion! Błyskawicznie zbudować i opublikować prostą stronę internetową pokazującą moje prace.

Darmowe portfolio, które mogę przygotować i pokazać światu w 10 minut!

Już wcześniej pisałam jak zrobić darmową stronę internetową z Notion, ale ostatnio pojawiło się nowe, łatwiejsze i zupełnie darmowe rozwiązanie na stronę ze schludnym adresem internetowym.

Autorem rozwiązania jest [Jotzilla](https://jotzilla.net/), a darmową subdomenę (twój-adres.vercel.app) lub darmowe przekierowanie strony Notion pod domenę, którą już masz, oferuje Vercel.

Zaprezentuję więc jak stworzyć stronę internetową, portfolio z Notion tym nowym sposobem.

# Co będzie ci potrzebne?

Zanim opublikujesz swoją darmową stronę internetową, potrzebne ci będzie:

- konto GitHub (darmowe)
- konto [Vercel](https://vercel.com/) (darmowe, możesz zalogować się przez konto GitHub)
- konto Notion (darmowe)
- publiczna strona Notion (z twoim portfolio)
- własny adres internetowy (opcjonalnie)

**10 minut start!**

# Darmowe portfolio krok po kroku

## Skopiuj repozytorium

Będąc zalogowanym na GitHub, skopiuj repozytorium (tzw. fork) [minimal-notion-blog](https://github.com/jotzilla/minimal-notion-blog/fork).

![notion_blog_1.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1663067595281/i_jO7XAEr.png align="left")

## Zmień site.config.js

Skopiuj numer swojej wcześniej przygotowanej, upublicznionej strony Notion (aby to zrobić, **w Notion przejdź do opcji 'Share'** w prawym górnym rogu strony, a następnie 'Copy web link'):

![publiczna-strona-notion.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1663067704103/1YfQdmZSf.png align="left")

Wróć do skopiowanego repozytorium w GitHub i podmień dane w pliku **site.config.js**:

![notion_strona_darmowa.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1663067737350/owo5IRP64.png align="left")
Zmień 'rootNotionPageId' na numer widoczny na końcu skopiowanego przez ciebie w Notion adresu strony.

Następnie możesz również zmienić 'social usernames'.


## Przejdź do Vercel

Po wprowadzeniu zmian, przejdź do strony [https://vercel.com/new](https://vercel.com/new) zaloguj się i zaimportuj swoje nowe repozytorium (minimal-notion-blog).

![notion_blog_3.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1663067789221/crqZYdn0A.png align="left")
Po zaimportowaniu, nadaj projektowi nazwę i naciśnij **'Deploy'**.

**Poczekaj parę minut i gotowe**, twoja strona jest już online!

## Pretty URL

Ale to jeszcze nie koniec, na razie twoja strona jest dostępna pod przypadkowo wygenerowanym, trudnym do zapamiętania adresem. Tego nie chcemy!

Aby to zmienić, przejdź do '**Dashboard'** projektu, przejdż do ustawień **'Settings'**, a następnie zakładki domeny **'Domains'**:

![notion_darmowa_strona.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1663067889289/2lzkpOLAS.png align="left")

Zmień nazwę subdomeny, na taką która ci odpowiada. Dla siebie wybrałam [nomadbynature.vercel.app](https://nomadbynature.vercel.app/). Miałam szczęście, że subdomena była jeszcze dostępna :)

**Dziel się swoim portfolio ze światem!**

# Strona pod własnym adresem internetowym

Proste portfolio, czy CV możesz z powodzeniem wyświetlać z subdomeną Vercel, ale jeśli zależy ci na prowadzeniu strony pod własnym adresem, również masz taką możliwość.

W sekcji 'Domains' możesz dodać własny adres internetowy, a Vercel poda ci dane A record i CNAME, DNS Record, które musisz następnie wprowadzić (zmienić), u swojego dostawcy domeny (np. NameSilo).

# Edycja i wygląd strony

Elementy i treści na swojej stronie edytujesz, dodajesz, czy odejmujesz na poziomie Notion. Także, aby dodać zdjęcie, czy tekst do strony zaloguj się do Notion i tam modyfikuj swoje portfolio. Zmiany będą widoczne dla odwiedzających stronę praktycznie od razu.

Jeśli natomiast chcesz zmodyfikować elementy takie jak favicon, footer, czy CSS musisz to zrobić w twoim 'minimal-notion-blog' repozytorium na GitHub (modyfikacja plików). 

---
Przydały ci się informacje zawarte w artykule? Chcesz wspomóc mojego bloga? Możesz to zrobić [stawiając mi kawę](https://buycoffee.to/nomadbynature).

%%[buycoffee]