Zaktualizuj dane klienta
```
Załóżmy, że klient o id=1 zmienił numer telefonu na '999-999-999'
```
Zaktualizuj cenę wynajmu dla konkretnego modelu samochodu
```
Załóżmy, że cena wynajmu samochodu marki 'Toyota' i modelu 'Corolla' zostanie zmieniona na 170.00
UPDATE samochody 
SET model=Toyota model=Colla+170.00;
```
Zaktualizuj dostępność samochodu po wypożyczeniu
Załóżmy, że samochód o id=6 został wypożyczony, więc jego dostępność powinna być ustawiona na 0
Oznacz samochód jako dostępny po jego zwrocie
Załóżmy, że samochód o id=6 został zwrócony przez klienta i jego dostępność zostanie ustawiona na 1
Przedłuż czas wypożyczenia samochodu dla konkretnego klienta
Załóżmy, że klient o id=2 chce przedłużyć wypożyczenie samochodu o id=4 do nowej daty zwrotu '2024-04-25'
Zmniejsz dostępność samochodów wypożyczalni o 1, gdy samochód zostanie wypożyczony
Załóżmy, że samochód o id=3 został wypożyczony, więc jego dostępność zostanie zmniejszona o 1

UPDATE samochody 
SET model=Toyota model=Colla+170.00;
