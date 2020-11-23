# Bootcamp-Data-Science-SQL
### Podstawy SQL - Projekt

1. Stwórz Bazę „Sklep odzieżowy”
2. Utwórz tabelę „Dostawca” z kolumnami:
- Id producenta
- Nazwa producenta
- Adres producenta
- Nip producenta
- Data podpisania umowy z producentem
Do każdej kolumny ustaw odpowiedni „constraint” 

3. Utwórz tabelę „Produkt” z kolumnami:
- id produktu
- nazwa producenta
- nazwa produktu
- opis produktu
- cena netto zakupu
- cena brutto zakupu
- cena netto sprzedaży
- cena brutto sprzedaży
- procent VAT sprzedaży
Do każdej kolumny ustaw odpowiedni „constraint” 

4. Utwórz tabelę „Zamówienie” z kolumnami:
- Id zamówienia
- Id klienta
- Id produktu
- Data zamówienia
Do każdej kolumny ustaw odpowiedni „constraint”

5. Utwórz tabelę „Klient” z kolumnami:
- Id klienta
- Id zamówienia
- Imię
- Nazwisko
- adres
Do każdej kolumny ustaw odpowiedni „constraint”

6. Każdą tabelę uzupełnij danymi wg:
- Tabela „Dostawca” – 4 pozycje
- Tabela „Produkt” – 20 pozycji
- Tabela „Zamówienie” – 10 pozycji
- Tabela „Klient” – 10 pozycji

7. Połącz kolumny ze Sobą aby tabele ze sobą się Komunikowały
- Produkt – Dostawca
- Produkt – Zamówienie
- Zamówienie - Klient 

8. Wyświetl wszystkie produkty z wszystkimi danymi od dostawcy który
znajduje się na pozycji 1 w tabeli „Dostawca” 

9. Posortuj te produkty po Nazwie od A-B 

10. Wylicz średnią cenę za produktu od tego dostawcy

11. Wyświetl dwie grupy produktów tego dostawcy:
- Połowa najtańszych to grupa: „Tanie”
- Pozostałe to grupa: „Drogie”

12. Wyświetl produkty zamówione, wyświetlając nazwę,

13. Wyświetl wszystkie produkty zamówione –ograniczając do wyświetlonych 5 pozycji

14. Policz wartość wszystkich zamówień

15. Wyświetl wszystkie zamówienia wraz z produktami sortując je wg daty
od najstarszego do najnowszego

16. Sprawdź czy w tabeli produkty mają uzupełnione wszystkie dane –
wyświetl pozycje dla których brakuje danych

17. Wyświetl produkty najczęściej sprzedawane wraz z ich ceną

18. Znajdź dzień w którym najwięcej zostało złożonych zamówień

Odpowiedzi prześlij do mentora. Powodzenia!
