# Zadanie projektowe nr 3

### Polecenie

Na podstawie zbioru danych HBO Max Movies and TV Shows opracuj raport na temat oferty platformy strumieniowej HBO Max.

### Zbiór danych

Zbiór danych dotyczy zawartości biblioteki oferowanej przez HBO Max w marcu 2023 roku.

### Opis kolumn

ID: identyfikator,
Title: tytuł,
Type: rodzaj oferowanej treści,
Release Year: rok premiery,
Age Certification: kategoria wiekowa,
Runtime: czas trwania w minutach[1],
Genres: lista gatunków filmowych,
Countries: lista krajów będących producentami,
Seasons: liczba sezonów[2],
IMDb Score: ocena użytkowników portalu IMDb,
IMDb Votes: liczba ocen użytkowników portalu IMDb,
TMDb Popularity: popularność na portalu TMDb,
TMDb Score: ocena użytkowników portalu TMDb.

[1] Wartość oznaczająca czas trwania filmu albo odcinka serialu (w zależności od rodzaju oferowanej treści).
[2] Wartość podana jedynie w przypadku seriali.

### Ogólne zasady

- nie można modyfikować danych przed ich zaimportowaniem do programu Power BI,
- można modyfikować nazwy kolumn (w tym także dokonywać ich tłumaczenia),
- można tworzyć nowe miary, kolumny i tabele,
- można korzystać z wizualizacji niestandardowych,
- można dowolnie personalizować raport (w tym także zamieszczać grafiki).

### Wymagania funkcjonalne

raport powinien przedstawiać ofertę HBO Max z podziałem na filmy i seriale, +
raport powinien przedstawiać łączną liczbę produkcji, +
raport powinien przedstawiać średnią ocenę użytkowników portalu TMDb[3], +
raport powinien przedstawiać średnią ocenę użytkowników portalu IMDb[3], +
raport powinien przedstawiać łączną liczbę ocen użytkowników portalu IMDb[3], +
raport powinien przedstawiać pięć filmów o największej popularności na portalu TMDb posortowanych malejąco po tej wartości[4],
raport powinien przedstawiać udział krajów będących producentami w łącznej liczbie filmów[5],
raport powinien przedstawiać liczbę filmów w zależności od czasu ich trwania[6][7],
raport powinien przedstawiać pięć seriali o największej liczbie ocen użytkowników portalu IMDb posortowanych malejąco po tej wartości[4],
raport powinien przedstawiać udział kategorii wiekowych w łącznej liczbie seriali[5],
raport powinien przedstawiać liczbę seriali w zależności od liczby ich sezonów[7][8],
raport powinien umożliwiać jednoznaczną identyfikację produkcji na podstawie jej tytułu[9],
raport powinien umożliwiać filtrowanie danych względem kategorii wiekowej[10][11],
raport powinien umożliwiać filtrowanie danych względem kraju będącego producentem[10][12],
raport powinien umożliwiać filtrowanie danych względem gatunku filmowego[10][12],
raport powinien umożliwiać filtrowanie danych względem roku premiery[10],
raport powinien umożliwiać filtrowanie danych względem tytułu produkcji[10][13].

[3] Wizualizacja nie powinna wyświetlać wartości pustej w przypadku braku danych, tylko wartość "N/A".
[4] Wizualizacja powinna wyświetlać także wartości kryterium sortowania.
[5] Wizualizacja powinna wyświetlać tylko pięć pierwszych wartości (o największym udziale).
[6] Wizualizacja powinna graficznie obrazować rozkład wartości.
[7] Wizualizacja nie powinna uwzględniać działania jakichkolwiek fragmentatorów.
[8] Wizualizacja powinna uwzględniać tylko te liczby sezonów, które dotyczą chociaż jednego serialu.
[9] Jeżeli tytuł produkcji nie jest niepowtarzalnym identyfikatorem, to na jego końcu należy zamieścić w nawiasie datę premiery (w innym przypadku nie).
[10] Filtr powinien dopuszczać możliwość wyboru więcej niż jednej wartości jednocześnie.
[11] Filtr nie powinien dopuszczać możliwości wyboru wartości pustych.
[12] Filtr nie powinien dopuszczać możliwości wyboru zestawów wartości, tylko pojedynczych wartości.
[13] Filtr powinien dopuszczać możliwość wyszukania tytułu poprzez jego ręczne uzupełnienie.

### Wymagania niefunkcjonalne

raport powinien składać się z dwóch stron,
raport powinien zapewniać nawigację pomiędzy stronami,
raport powinien zawierać nagłówek, który w jednoznaczny sposób będzie identyfikować jego treść,
raport powinien być czytelny i przejrzysty[14],
raport powinien być intuicyjny i łatwy w obsłudze[14].

[14] Nie narzucam Państwu miar oceny tych kryteriów, ale strona wizualna również będzie podlegać ocenie, co w przypadku raportów jest oczywiste.
