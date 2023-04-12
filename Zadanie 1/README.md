# Zadanie projektowe nr 1

### Polecenie

Na podstawie zbioru danych Winter Sports opracuj raport, którego głównym elementem będzie wykres Gantta.

### Zbiór danych

Zbiór danych dotyczy mistrzostw świata, które mają odbyć się w 2023 roku we wszystkich olimpijskich sportach zimowych.

### Opis kolumn

- Federation: federacja odpowiedzialna za organizację mistrzostw świata,
- Sport: sport albo dyscyplina, w której odbywają się zawody,
- Sex: płeć, która jest uprawniona do startu w zawodach[1],
- Start Date: pierwszy dzień zawodów,
- End Date: ostatni dzień zawodów,
- Country: kraj albo kraje będące gospodarzami mistrzostw świata,
- Ceremony: rodzaj ceremonii (otwarcia albo zamknięcia)[2].

[1] Wartość podana jedynie wtedy, gdy nie są to wspólne mistrzostwa.

[2] Wartość podana jedynie wtedy, gdy ceremonia nie odbywa się w czasie trwania zawodów.

### Ogólne zasady

- nie można modyfikować danych przed ich zaimportowaniem do programu Power BI,
- można modyfikować nazwy kolumn (w tym także dokonywać ich tłumaczenia),
- można tworzyć nowe miary, kolumny i tabele,
- można korzystać z wizualizacji niestandardowych,
- można dowolnie personalizować raport (w tym także zamieszczać grafiki).

### Wymagania funkcjonalne

- raport powinien przedstawiać terminy mistrzostw świata w każdym z olimpijskich sportów zimowych, +
- raport powinien zawierać alfabetyczną listę sportów albo dyscyplin, +
- raport powinien zawierać liczbę wierszy odpowiadającą liczbie unikalnych sportów albo dyscyplin, +
- raport powinien przedstawiać listę sportów albo dyscyplin w taki sposób, aby wszystkie były widoczne jednocześnie[3],+
- raport powinien zawierać oś czasu w skali tygodniowej,
- raport powinien przedstawiać ceremonie otwarcia i zamknięcia w postaci kamieni milowych,+
- raport powinien przedstawiać zawsze aktualny procent ukończenia danych zawodów[4],
- raport powinien zawierać legendę, która będzie rozróżniać mistrzostwa świata w zależności od federacji odpowiedzialnej za ich organizację, +
- raport powinien wyświetlać informację o kraju albo krajach będących organizatorami mistrzostw świata po najechaniu kursorem na dane zawody, +
- raport powinien umożliwiać filtrowanie danych względem federacji[5],
- raport powinien umożliwiać filtrowanie danych względem kraju[5],
- raport powinien umożliwiać filtrowanie danych względem płci[5][6],
- raport powinien umożliwiać filtrowanie danych względem zakresu dat[7].

[3] Raport nie powinien zmuszać użytkownika do korzystania z pionowego paska nawigacji.

[4] Procent ukończenia zawodów stanowi iloraz minionych dni zawodów i czasu ich trwania, tzn. w przypadku zawodów rozgrywanych od 1 do 4 marca procent ich ukończenia 1 marca wynosi 0%, 3 marca wynosi 50%, a 5 marca wynosi 100%.

[5] Filtr powinien dopuszczać możliwość wyboru więcej niż jednej wartości jednocześnie.

[6] Filtr powinien dopuszczać jedynie dwie wartości, tzn. w przypadku wyboru zawodów mężczyzn powinny wyświetlić się wszystkie zawody, w których mogli oni uczestniczyć (analogicznie dla kobiet).

[7] Filtr powinien uwzględniać jednocześnie datę początku i końca zawodów, tzn. powinny wyświetlić się wszystkie zawody, których chociaż jeden dzień mieści się w podanym zakresie.

### Wymagania niefunkcjonalne

- raport powinien składać się wyłącznie z jednej strony,
- raport powinien zawierać nagłówek, który w jednoznaczny sposób będzie identyfikować jego treść,
- raport powinien być czytelny i przejrzysty[8],
- raport powinien być intuicyjny i łatwy w obsłudze[8].

[8] Nie narzucam Państwu miar oceny tych kryteriów, ale strona wizualna również będzie podlegać ocenie, co w przypadku raportów jest oczywiste.
