ExSize - Rewards and Tasks System 🎮🎯🎉
Cel i grupa docelowa

ExSize to aplikacja motywująca dzieci do wykonywania obowiązków domowych poprzez system grywalizacji oparty na zadaniach, nagrodach w postaci monet i punktach VIP oraz personalizacji awatarów.

    Grupa docelowa:
        Dzieci: Wykonują zadania, zdobywają monety i punkty VIP, personalizują awatary. Brak określonego przedziału wiekowego – aplikacja ma być uniwersalna.
        Rodzice: Tworzą i zarządzają zadaniami dla dzieci, zatwierdzają ich wykonanie, nadzorują konta dzieci.

Platforma

    Aplikacja składa się z:
        Strony internetowej (responsywnej – desktop i mobile).
        Aplikacji mobilnej (iOS).
    Wymagana synchronizacja danych między platformami za pomocą backendu.

Size Pass 🎟️

    Opis: Specjalny karnet odblokowujący dodatkowe funkcje, w tym zakładkę Osiągnięcia (Achievements).
    Cena: 30 USD na sezon (2 miesiące).
    Darmowy Size Pass: Można go zdobyć po roku regularnego wykonywania zadań – minimum 5 zadań dziennie przez 365 dni (ciągłość wymagana).
    Ważność: 2 miesiące (sezon). Po wygaśnięciu:
        Użytkownicy tracą dostęp do zakładki Osiągnięcia, chyba że odnowią Size Pass w ciągu 7 dni od wygaśnięcia.
        Brak wpływu na monety czy inwentarz.

Monety (Coins) 💰

    Zasady zdobywania:
        Monety zdobywane są za ukończenie zadań i misji.
        Rodzice ustawiają nagrody w monetach za zadania (zatwierdzają ich wykonanie).
        Rodzaje zadań i nagrody:
        Rodzaj zadania	Maks. ilość/dzień	Nagroda w monetach	Nagroda w punktach VIP (dla Size Pass)
        Zwykłe	30	0-100 💵	0-100 VIP
        Trudne	15	100-300 💵	100-300 VIP
        Duże	5	300-500 💵	300-350 VIP
        Ekstremalne	1	500-1000 💵	350-500 VIP
    Misje i nagrody (Missions and rewards):
        Przykłady: „Zrób dziś 20 zadań” – nagroda: 1000 monet.
        Definiowane przez autora systemu, dostępne w określonych sezonach.
    Przechowywanie: Monety nie zerują się – są przechowywane bezterminowo.

Sklep (Store) 🎨

    Warianty:
        General: Stała oferta przedmiotów.
        Event: Limitowane czasowo przedmioty (dostępne przez 2 tygodnie w trakcie sezonu).
    Przedmioty:
        Avatary, dekoracje awatarów, ramki do awatarów (tylko kosmetyczne, bez wpływu na funkcjonalność).
    Liczba kopii:
        Przedmioty 0-100 monet: 50 sztuk.
        Przedmioty 100+ monet: 10 sztuk.
    Zmiana przedmiotów: Bez dodatkowych opłat za zmianę zakupionego przedmiotu.

Osiągnięcia (Achievements) 🏅

    Dostępność: Zakładka dostępna tylko dla posiadaczy Size Pass (zablokowana bez karnetu).
    Różnice od misji: Długoterminowe cele definiowane przez autora systemu, losowo przypisywane użytkownikom.
    Przykłady:
        „Wydaj 10 000 monet w tydzień” – nagroda: 20 000 monet.
        „Zbierz 500 monet”.
    Przechowywanie: Postępy zerują się po 24 godzinach od przypisania osiągnięcia.

Misje (Missions) 📅

    Kategorie:
        Codzienne: Losowane co dzień, max 10 misji.
        Cotygodniowe: Losowane co tydzień, max 10 misji.
        Coroczne: Losowane co rok, max 10 misji.
    Nagrody:
        Codzienne: 10-30 monet.
        Cotygodniowe: 40-70 monet.
        Coroczne: 70-1000 monet.
    Odświeżanie:
        Koszt: 100 monet za odświeżenie kategorii.
        Limity:
            Codzienne: 2x/dzień.
            Cotygodniowe: 2x/tydzień.
            Coroczne: 2x/rok.

Ekwipunek i personalizacja awatara

    Ekwipunek:
        Przechowuje wszystkie zakupione przedmioty.
        Brak limitu liczby przedmiotów.
    Personalizacja:
        Zmiana wyglądu awatara (avatar, dekoracje, ramki) – bez opłat.

Interfejs użytkownika (UI)

    Dashboard (po zalogowaniu):
        Kafelki:
            Size Pass (duży kafelek).
            Misje.
            Osiągnięcia.
            Zadania.
            Przyjaciele.
            Sklep.
        Menu górne:
            Ustawienia (w tym włączanie/wyłączanie powiadomień).
            Przełączenie między sekcją rodzica/dziecka.
            Powiadomienia.
            Profil.
            Link do strony twórcy (www).
    Konta:
        Rodzice: Oddzielne konto z panelem do dodawania/zarządzania zadaniami i przypisywania kont dzieci (wyszukiwanie konta dziecka i oznaczenie go).
        Dzieci: Oddzielne konto z dostępem do Dashboardu i funkcji grywalizacji.
    Responsywność: Aplikacja działa na desktopach, tabletach i telefonach.

Techniczne wymagania

    Backend:
        Wymagany do synchronizacji danych między stroną internetową a aplikacją mobilną.
        Przechowywane dane:
            Konta użytkowników (rodzice i dzieci).
            Monety i punkty VIP.
            Zadania, misje, osiągnięcia.
            Inwentarz i historia zakupów.
        Sugerowana baza: Firebase.
    Logowanie:
        Przez konta Google (autoryzacja via Firebase Authentication).
    Weryfikacja zadań:
        Dziecko zgłasza ukończenie zadania, rodzic zatwierdza je z poziomu swojego konta.

Powiadomienia

    Funkcjonalność:
        Przypomnienia o zadaniach.
        Informacje o wygaśnięciu Size Pass.
    Ustawienia: Włączanie/wyłączanie w sekcji Ustawienia.

Licencja

    Projekt jest licencjonowany na licencji MIT (patrz plik LICENSE).

Kontakt

    Email: crystalgamesstudio9@gmail.com

Uwagi dla programisty

    Tech stack: Next.js (frontend), TypeScript, Firebase (backend i autoryzacja).
    Struktura:
        Komponenty dla Dashboardu, kafelków, sklepu, misji itd.
        Oddzielne widoki/panele dla rodziców i dzieci.
    API:
        Synchronizacja danych użytkownika (monety, zadania, inwentarz).
        Zarządzanie relacją rodzic-dziecko (przypisywanie kont).
    Responsywność: Mobile-first design z dostosowaniem do desktopów.
