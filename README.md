MR BUGGY 7 – Testing Project

Opis projektu
Projekt zawiera zestaw manualnych przypadków testowych dla formularza rejestracji administratora.  
Został przygotowany w celu pokazania podejścia do testowania walidacji danych oraz projektowania testów w oparciu o wymagania.



Zakres testów

Testy obejmują:

- walidację pustych pól  
- walidację pola username (minimalna i maksymalna długość)  
- walidację hasła:
  - minimalna długość  
  - maksymalna długość  
  - brak cyfry  
  - brak znaku specjalnego  
- zgodność pól password i confirm password  
- przypadki graniczne (np. dokładnie 5 znaków, 6 znaków, 20 znaków)  
- różne sposoby wprowadzania danych (wpisywanie z klawiatury, wklejanie)  
- poprawne przejście formularza (happy path)  



Podejście

Podczas tworzenia testów zwrócono uwagę na:

- testowanie wartości granicznych  
- rozdzielenie przypadków tak, aby każdy test sprawdzał jedną regułę  
- unikanie sytuacji, w których jeden test może maskować kilka błędów  
- czytelność i prostotę scenariuszy  



Narzędzia

- TestRail – do zarządzania przypadkami testowymi  



Struktura

Repozytorium zawiera:

- przypadki testowe  
- opis testowanego zakresu  



Cel

Celem projektu jest pokazanie umiejętności:

- projektowania testów manualnych  
- analizy wymagań  
- identyfikowania edge case’ów  
- myślenia w kategoriach QA  



Możliwe rozszerzenia

- automatyzacja testów  
- testy API  
- testy wydajnościowe  
- testy bezpieczeństwa  
