# Wydania dodatku Warsztat MM do Outlooka

Dodatek **Warsztat MM — korespondencja** wysyła zaznaczone w Outlooku maile
razem z załącznikami do Korespondencji programu Warsztat MM.

Działa w klasycznym Outlooku na Windows (Outlook 2016, 2019, 2021, Microsoft 365
zainstalowany na komputerze), z każdym kontem pocztowym. Nie działa w „nowym
Outlooku”, w przeglądarce ani na telefonie.

Kod źródłowy jest w osobnym, prywatnym repozytorium. Tutaj leżą wyłącznie pliki
do pobrania, żeby dodatek mógł sam sprawdzać aktualizacje bez żadnego tokenu.

## Instalacja

Pobierz `WarsztatMM-Outlook-<wersja>.exe` z [najnowszego wydania](../../releases/latest)
i uruchom go (uprawnienia administratora nie są potrzebne). Jeśli Windows ostrzeże
przed plikiem z internetu: **Więcej informacji → Uruchom mimo to**.

Potem uruchom ponownie Outlooka. Na karcie **Narzędzia główne** jest przycisk
**Do programu**: przy pierwszym użyciu wpisz adres programu i zaloguj się swoim kontem.

## Aktualizacje

Dodatek sam sprawdza plik `latest.json` z najnowszego wydania (numer wersji,
adres paczki i jej skrót SHA-256) i przygotowuje nowszą wersję; Outlook używa jej
od następnego uruchomienia. Połączenie z programem i ustawienia zostają.

## Odinstalowanie

Przy zamkniętym Outlooku: **Ustawienia Windows → Aplikacje → Warsztat MM — dodatek
do Outlooka → Odinstaluj**.
