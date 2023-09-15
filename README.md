# HTMLBUILD_COBOL
Ten program jest prostym generatorem kodu HTML, który pozwala użytkownikowi wprowadzać znaczniki HTML i tworzyć kod HTML na podstawie wprowadzonych poleceń. Oto opis programu:

IDENTIFICATION DIVISION: W tej sekcji znajdują się informacje identyfikacyjne programu, takie jak tytuł programu i autor.

DATA DIVISION: W tej sekcji definiowane są zmienne i dane potrzebne do działania programu.

OPERATOR: Zmienna przechowująca wprowadzone przez użytkownika polecenia (np. "h1", "p", "E" itp.).
CODEM: Zmienna przechowująca aktualny kod HTML, który jest generowany.
KODSKOM: Zmienna pomocnicza.
Zmienne H1, H2, H3, H4, H5, H6, P, M, BT, HR, BR, AUTO1, AUTO2: Przechowują gotowe fragmenty kodu HTML do wstawienia w odpowiednich miejscach.
ILE: Zmienna przechowująca liczbę.
PROCEDURE DIVISION: W tej sekcji znajduje się główna logika programu.

OPIS_PROGRAMU: Wyświetla informacje o programie i prośbę o wprowadzanie poleceń.

Html: Ta sekcja odpowiedzialna jest za generowanie kodu HTML w zależności od wprowadzonych poleceń. Program oczekuje na wprowadzenie polecenia przez użytkownika i następnie do kodu HTML dodawany jest odpowiedni fragment HTML zdefiniowany wcześniej w zmiennych H1, H2, P, itp. Jeśli użytkownik wprowadzi "E", program kończy działanie.

Koniec: Ta procedura jest wywoływana, gdy użytkownik wprowadzi "E" i służy do zakończenia programu.

Na końcu program generuje kod HTML między AUTO1 a AUTO2 i wyświetla go na konsoli.

Ten program jest prostym przykładem, który ilustruje podstawy programowania w COBOL i generowania kodu HTML na podstawie poleceń użytkownika.

Przykład kodu:
____________
h1
h2
bt
hr
br
E
____________
E jest końcem kodu!
