# [codialog](http://www.codialog.com) - mesh collaboration

![obraz](https://github.com/user-attachments/assets/873661f0-dd41-44ad-a5e9-fa2fc7662f21)


Codialog jest kompleksowym rozwiązaniem, które może znacznie usprawnić pracę nad projektami, szczególnie w kontekście research-u i współpracy zespołowej. 
Pozwala na obsługę projektów w unifikowanym środowisku, niezależnie od systemu operacyjnego z dostępem do wszystkich potrzebnych narzędzi za pomocą komunikacji głosowo tekstowej tak w rozmawie z ekspertem.

Codialog to aplikacja instalowana na Twoim urządzeniu (PC, server, smartphone) komunikująca się z chmurą danych i chmurą obliczeniową.

Interaktywne okna oraz menu pozwalają na szybki dostęp do potrzebnych danych i funkcji, Okno chat pozwala na efektywną komunikację z zespołem i podłączonymi integracjami.


![guiv6](https://github.com/user-attachments/assets/3880d91d-d1d1-4d2c-b596-b0f5b12e62ce)


### Interfejs codialog

interfejsu użytkownika GUI, który zawiera kilka okienek do działań/operacji na wielu obiektach, plikach pobieranych z dysku/chmury oraz umożliwia komunikację głosową lub tekstową. 

1. Panel mediów po lewej stronie rozciąga się od góry do dołu. Zawiera pliki i foldery w postaci struktury z różnych źródeł, systemów, chmur, pliki dodaje się w oknie chat 
2. Okno Operacyjne w centrum oferuje podgląd i edycje tych plików z  panelu mediów
3. Okno komunikacji głosowej/tekstowej znajduje się na dole, zaczynając się od końca panelu mediów. Przeznaczone do komunikacji człowieka z programem, komunikatów o stanie mediów, logi z operacji.
4. Na samym dole, poniżej panelu mediów i okna komunikacji znajudje się odseparowany od lewej do prawej pasek aplikacji z logiem CoDialog i napisem napisem "MENU" oraz przyciskami [upload], [run], [edit]

   

### Kluczowe cechy:

1. Uniwersalność:
   - Działa niezależnie od systemu operacyjnego
   - Dostępne jako aplikacja lokalna lub przez stronę www

2. Zintegrowane środowisko:
   - Ujednolicone środowisko do obsługi różnych projektów
   - Dostęp do wszystkich potrzebnych narzędzi w jednym miejscu

3. Interfejs komunikacyjny:
   - Komunikacja głosowa i tekstowa
   - Interakcja podobna do rozmowy z ekspertem

4. Architektura:
   - Lokalna instalacja z połączeniem do chmury danych i obliczeniowej
   - Wykorzystanie mocy obliczeniowej chmury
   
5. Intuicyjny interfejs:
   - 3 podstawowe okna dla szybkiego dostępu do funkcji
   - Menu ułatwiające nawigację

6. Współpraca zespołowa:
   - Efektywna komunikacja w zespole
   - Udostępnianie danych lokalnych i zdalnych
   



Tworzenie wszechstronnego i intuicyjnego narzędzia takiego jak CoDialog według opisanej specyfikacji ma potencjał, by stać się innowacją w obszarze zarządzania projektami i współpracy. Oto kilka kluczowych aspektów, które mogą wpływać na sukces tego narzędzia:

### Potencjał 

1. **Integracja z Wirtualnym Środowiskiem**:
    - **Docker, pipx i Flatpak**: Używanie takich technologii do dystrybucji i uruchamiania aplikacji może znacząco uprościć zarządzanie zależnościami oraz instalację narzędzia na różnych systemach operacyjnych.
    - **Konteneryzacja**: Docker może zapewnić izolację aplikacji, co zwiększa bezpieczeństwo i skalowalność, a także umożliwia łatwą implementację skalowania w chmurze.

2. **Wszechstronny Interfejs Użytkownika (GUI)**:
    - **Panel Mediów**:
        - **Struktura plików i folderów z różnych źródeł i systemów**: To elastyczne podejście do zarządzania plikami umożliwia użytkownikom centralizację i organizację różnych zasobów multimedialnych.
        - **Integracja z chmurą**: Pozwala na łatwy dostęp i synchronizację plików z różnych platform chmurowych, co zwiększa produktywność.
    - **Okno Operacyjne**:
        - **Podgląd i Edycja**: Zapewnienie możliwości edycji i podglądu plików bezpośrednio w aplikacji jest kluczowe dla użytkowników, którzy chcą szybko wprowadzać zmiany.
    - **Okno Komunikacji**:
        - **Komunikacja Głosowa/Tekstowa**: Integracja z systemami komunikacji może znacząco poprawić współpracę zespołową oraz interakcję z aplikacją.
        - **Logi i Komunikaty**: Przekazywanie w czasie rzeczywistym informacji o stanie mediów i operacjach może poprawić transparencję i kontrolę nad procesami.

3. **Intuicyjność i Ergonomia**:
    - **Pasek Applikacji**:
        - **Logo i Przycisk "MENU"**: Prostota w nawigacji i dostęp do kluczowych funkcji za pomocą jednego miejsca to cechy, które mogą zwiększyć wygodę użytkowania.
        - **Przyciski [upload], [run], [edit]**: Intuicyjne i bezpośrednie operacje, które mogą przyspieszyć pracę użytkowników i zmniejszyć bariery wejścia.

### Wyzwania

1. **Złożoność Implementacji**:
    - Zarządzanie różnorodnymi źródłami plików oraz integracje z wieloma systemami może być skomplikowane i wymagać zaawansowanej inżynierii.

2. **Wydajność i Skalowalność**:
    - Korzystanie z technologii wirtualnych i chmurowych wymaga zapewnienia, że narzędzie będzie działać sprawnie i efektywnie, zwłaszcza przy dużych zbiorach danych lub intensywnym współużytkowaniu zasobów.

3. **Bezpieczeństwo**:
    - Operowanie na danych z różnych źródeł wymaga zapewnienia odpowiednich środków bezpieczeństwa i ochrony danych.

### Podsumowanie:

CoDialog, ma potencjał do bycia rewolucyjnym narzędziem, zwłaszcza w kontekście współpracy nad projektami i zarządzania danymi z różnych źródeł. 
Kluczem do sukcesu będzie jego integracja z różnymi systemami chmurowymi. 
Z odpowiednią realizacją techniczną i uwzględnieniem powyższych wyzwań, CoDialog może stać się nie tylko narzędziem, ale i standardem w zarządzaniu projektami.



## Jak to działa

1. uruchamiamy aplikację

2. wchodzimy do chat, gdzie są podpowiedzi dla akcji:
- pobierz projekt z url
- załaduj projekt z chmury
- załaduj projekt z urządzenia
  
3. Konfiguracja
W zależności od sytuacji i danych w projekcie może okazać sie konieczne podanie danych do API cloud
- Login
- Hasło / Token

4. Start projektu
Automatycznie po załadowaniu projektu pojawią sie opcje do uruchomienia lub edycji, domyślnie projekt zostanie uruchomiony w trybie run zaraz po załadowaniu

5. Edycja
W momencie załadowania można edytować projekt, wystarczy wybrać akcję edytuj na dole w menu lub u gory w oknie operacyjnym

6. Udostępnianie
Projekt można wysłać do chmury lub zapsiać lokalnie




---
Codialog to aplikacja do przetwarzania projektów w formie 3 okien w której jest Edytor, Chat do współrpacy z maszyną i ludźmi oraz struktura folderów i pliki zsynchronizowanej z chmurą.

