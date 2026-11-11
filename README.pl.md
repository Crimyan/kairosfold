# Kairosfold

**Aplikacje o pracę, CV składane z biblioteki klocków i timery ogłoszeń – w jednym miejscu, na Twoim komputerze.**

**[⬇ Pobierz Kairosfold 1.5.0 dla Windows](https://github.com/Crimyan/kairosfold/releases/download/v1.5.0/Kairosfold_1.5.0_x64-setup.exe)** · [Wszystkie wydania](https://github.com/Crimyan/kairosfold/releases) · [English version](README.md)

> Działa bez internetu, bez konta i chmury. Twoje dane zostają na Twoim komputerze. Interfejs po polsku i angielsku (zgodnie z językiem Windows, do zmiany w Ustawieniach).

## Co robi

- **Aplikacje** – śledzenie każdego wysłanego CV: statusy, rozmowy, follow-upy. Aplikacje bez odpowiedzi same dostają status **Ghosted** (po 30 dniach) i trafiają do archiwum (po 60). Nową aplikację dodasz z wklejonego ogłoszenia, z linku (Pracuj.pl, LinkedIn, ArtStation, Skillshot, Hitmarker, Work With Indies, SmartRecruiters…) albo ze zrzutu ekranu (rozpoznawanie tekstu bez internetu). Stawki w obcych walutach przeliczają się po kursie z dnia publikacji oferty, a rozmowę wpiszesz w strefie czasowej firmy.
- **Firmy i czarna lista** – Kairosfold ostrzeże Cię, zanim wyślesz CV do firmy, która nie płaci, nikomu nie odpisuje albo każe robić darmowe „testy”. Już tu aplikowałeś? Ogłoszenie wraca od miesięcy? Zobaczysz to. Czarną listą podzielisz się ze znajomymi (eksport/import).
- **Biblioteka i Kreator CV** – doświadczenie, umiejętności i narzędzia jako klocki z wersjami. Import gotowego CV (PDF/DOCX), bazowe CV i kopie pod konkretną ofertę, 6 szablonów, test ATS, list motywacyjny, eksport do PDF. Projektujesz w InDesign? Nazwij ramki we własnym layoucie, a Kairosfold je wypełni (.idml), albo wyeksportuj CSV do scalania danych w InDesign lub Affinity.
- **Zlecenia** – zapytania z VGen, DM-ów, maili i poleceń na jednej tablicy: wycena, zaliczka, w realizacji, oddane, opłacone. Płatności i raty, rundy poprawek w cenie, terminy na ekranie Dziś i które Twoje posty przynoszą pracę.
- **Ogłoszenia** – timery dla Reddita, Discorda, grup na Facebooku i forów: kiedy możesz się znowu wystawić, warianty tekstu i obrazy, sesja publikowania krok po kroku ze schowkiem.
- **Dziś i Kalendarz** – rozmowy, follow-upy i szkice w jednym widoku; miesiąc, tydzień i lista; eksport do Google Calendar / Outlooka (.ics); powiadomienia w Windows z godzinami ciszy.
- **Raporty** – wykres statusów, lejek (wysłane → odpowiedź → rozmowa → oferta), wysłane w czasie, które portale i które CV dają odpowiedzi, przychód ze zleceń według źródeł; eksport CSV i PDF.
- **Rozszerzenie przeglądarki** (Chrome, Edge, Opera, Brave, Firefox) – na dowolnej ofercie kliknij ikonę Kairosfold: stanowisko, firma, stawka i ostrzeżenia (czarna lista, „już tu aplikowałeś”, „oferta wraca”), potem **Do kolejki** albo **Otwórz w Kairosfold** z wypełnionymi polami – także na LinkedIn po zalogowaniu.
- **Ctrl+K** – szukanie po wszystkim i polecenia. **Import** starych aplikacji z Excela/CSV. **Codzienne kopie zapasowe** i przywracanie jednym kliknięciem.

## Instalacja

1. Kliknij **[Pobierz Kairosfold 1.5.0](https://github.com/Crimyan/kairosfold/releases/download/v1.5.0/Kairosfold_1.5.0_x64-setup.exe)** (albo otwórz [Wydania](https://github.com/Crimyan/kairosfold/releases) i wybierz plik `Kairosfold_…_x64-setup.exe`).
2. Uruchom pobrany plik. Instaluje się tylko dla Twojego użytkownika – bez uprawnień administratora.
3. Windows SmartScreen może pokazać *„System Windows ochronił ten komputer”* (instalator nie ma płatnego certyfikatu wydawcy). Kliknij **Więcej informacji → Uruchom mimo to**.
4. Kairosfold uruchomi się po instalacji. Znajdziesz go w menu Start; zamknięcie okna chowa go do zasobnika (przypomnienia i timery działają dalej) – całkiem zamkniesz go z menu ikony w zasobniku.

Wymagania: Windows 10 lub 11, 64-bit.

## Rozszerzenie przeglądarki

Rozszerzenie jest dołączone do Kairosfold. W Kairosfold otwórz *Ustawienia → Rozszerzenie przeglądarki* i kliknij **Pokaż folder**, a potem:

- **Chrome / Edge / Opera / Brave:** otwórz `chrome://extensions` (`edge://extensions`), włącz **Tryb dewelopera**, kliknij **Załaduj rozpakowane** i wskaż ten folder.
- **Firefox:** otwórz `about:debugging` → *Ten Firefox* → **Załaduj tymczasowy dodatek** → plik `manifest.json` z folderu (do czasu publikacji podpisanej wersji działa do zamknięcia Firefoksa).

Potem kliknij w Kairosfold **Połącz przeglądarkę** i wpisz 6-cyfrowy kod w okienku rozszerzenia. Rozszerzenie łączy się tylko z Kairosfold na Twoim komputerze (127.0.0.1).

## Aktualizacje

Kairosfold sprawdza nową wersję chwilę po starcie i co 6 godzin. Gdy jest dostępna, w pasku bocznym pojawia się przycisk **„↑ Zainstaluj …”** – kliknij, a Kairosfold zaktualizuje się i uruchomi ponownie. Dane zostają. Możesz też sprawdzić ręcznie w *Ustawienia → Aktualizacje*. Kairosfold pobiera tylko plik z numerem wersji z tego repozytorium, nic o Tobie nie jest wysyłane.

Jeśli wybierzesz walutę do przeliczania stawek (*Ustawienia → Waluty*), Kairosfold pobiera kursy walut: z NBP dla złotówek, w innych przypadkach z serwisu Frankfurter (dane EBC). Wysyła tylko kody walut i daty. Możesz to wyłączyć.

## Twoje dane

Wszystko jest w folderze `%APPDATA%\app.kairos.desktop`. Codzienne kopie zapasowe trafiają tam do folderu `backups` – albo do dowolnego folderu wybranego w *Ustawienia → Kopie zapasowe* (np. OneDrive). Żeby przenieść Kairosfold na inny komputer, przywróć tam plik kopii.

Odinstalowanie: *Ustawienia Windows → Aplikacje → Kairosfold → Odinstaluj*. Folder z danymi zostaje, dopóki go nie usuniesz.
