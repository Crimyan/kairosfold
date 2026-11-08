# Kairos

**Aplikacje o pracę, CV składane z biblioteki klocków i timery ogłoszeń – w jednym miejscu, na Twoim komputerze.**

**[⬇ Pobierz Kairos 1.2.0 dla Windows](https://github.com/Crimyan/kairos/releases/download/v1.2.0/Kairos_1.2.0_x64-setup.exe)** · [Wszystkie wydania](https://github.com/Crimyan/kairos/releases) · [English version](README.md)

> Działa bez internetu, bez konta i chmury. Twoje dane zostają na Twoim komputerze.

## Co robi

- **Aplikacje** – śledzenie każdego wysłanego CV: statusy, rozmowy, follow-upy. Aplikacje bez odpowiedzi same dostają status **Ghosted** (po 30 dniach) i trafiają do archiwum (po 60). Nową aplikację dodasz z wklejonego ogłoszenia, z linku (Pracuj.pl, LinkedIn, ArtStation, Skillshot, Hitmarker, Work With Indies, SmartRecruiters…) albo ze zrzutu ekranu (rozpoznawanie tekstu bez internetu).
- **Firmy i czarna lista** – Kairos ostrzeże Cię, zanim wyślesz CV do firmy, która nie płaci, nikomu nie odpisuje albo każe robić darmowe „testy”. Już tu aplikowałeś? Ogłoszenie wraca od miesięcy? Zobaczysz to. Czarną listą podzielisz się ze znajomymi (eksport/import).
- **Biblioteka i Kreator CV** – doświadczenie, umiejętności i narzędzia jako klocki z wersjami. Import gotowego CV (PDF/DOCX), bazowe CV i kopie pod konkretną ofertę, 6 szablonów, test ATS, list motywacyjny, eksport do PDF.
- **Ogłoszenia** – timery dla Reddita, Discorda, grup na Facebooku i forów: kiedy możesz się znowu wystawić, warianty tekstu i obrazy, sesja publikowania krok po kroku ze schowkiem.
- **Dziś i Kalendarz** – rozmowy, follow-upy i szkice w jednym widoku; miesiąc, tydzień i lista; eksport do Google Calendar / Outlooka (.ics); powiadomienia w Windows z godzinami ciszy.
- **Raporty** – wykres statusów, lejek (wysłane → odpowiedź → rozmowa → oferta), wysłane w czasie, które portale i które CV dają odpowiedzi; eksport CSV i PDF.
- **Rozszerzenie przeglądarki** (Chrome, Edge, Opera, Brave, Firefox) – na dowolnej ofercie kliknij ikonę Kairos: stanowisko, firma, stawka i ostrzeżenia (czarna lista, „już tu aplikowałeś”, „oferta wraca”), potem **Do kolejki** albo **Otwórz w Kairos** z wypełnionymi polami – także na LinkedIn po zalogowaniu.
- **Ctrl+K** – szukanie po wszystkim i polecenia. **Import** starych aplikacji z Excela/CSV. **Codzienne kopie zapasowe** i przywracanie jednym kliknięciem.

## Instalacja

1. Kliknij **[Pobierz Kairos 1.2.0](https://github.com/Crimyan/kairos/releases/download/v1.2.0/Kairos_1.2.0_x64-setup.exe)** (albo otwórz [Wydania](https://github.com/Crimyan/kairos/releases) i wybierz plik `Kairos_…_x64-setup.exe`).
2. Uruchom pobrany plik. Instaluje się tylko dla Twojego użytkownika – bez uprawnień administratora.
3. Windows SmartScreen może pokazać *„System Windows ochronił ten komputer”* (instalator nie ma płatnego certyfikatu wydawcy). Kliknij **Więcej informacji → Uruchom mimo to**.
4. Kairos uruchomi się po instalacji. Znajdziesz go w menu Start; zamknięcie okna chowa go do zasobnika (przypomnienia i timery działają dalej) – całkiem zamkniesz go z menu ikony w zasobniku.

Wymagania: Windows 10 lub 11, 64-bit.

## Rozszerzenie przeglądarki

Rozszerzenie jest dołączone do Kairos. W Kairos otwórz *Ustawienia → Rozszerzenie przeglądarki* i kliknij **Pokaż folder**, a potem:

- **Chrome / Edge / Opera / Brave:** otwórz `chrome://extensions` (`edge://extensions`), włącz **Tryb dewelopera**, kliknij **Załaduj rozpakowane** i wskaż ten folder.
- **Firefox:** otwórz `about:debugging` → *Ten Firefox* → **Załaduj tymczasowy dodatek** → plik `manifest.json` z folderu (do czasu publikacji podpisanej wersji działa do zamknięcia Firefoksa).

Potem kliknij w Kairos **Połącz przeglądarkę** i wpisz 6-cyfrowy kod w okienku rozszerzenia. Rozszerzenie łączy się tylko z Kairos na Twoim komputerze (127.0.0.1).

## Aktualizacje

Kairos sprawdza nową wersję chwilę po starcie i co 6 godzin. Gdy jest dostępna, w pasku bocznym pojawia się przycisk **„↑ Zainstaluj …”** – kliknij, a Kairos zaktualizuje się i uruchomi ponownie. Dane zostają. Możesz też sprawdzić ręcznie w *Ustawienia → Aktualizacje*. Kairos pobiera tylko plik z numerem wersji z tego repozytorium – nic o Tobie nie jest wysyłane.

## Twoje dane

Wszystko jest w folderze `%APPDATA%\app.kairos.desktop`. Codzienne kopie zapasowe trafiają tam do folderu `backups` – albo do dowolnego folderu wybranego w *Ustawienia → Kopie zapasowe* (np. OneDrive). Żeby przenieść Kairos na inny komputer, przywróć tam plik kopii.

Odinstalowanie: *Ustawienia Windows → Aplikacje → Kairos → Odinstaluj*. Folder z danymi zostaje, dopóki go nie usuniesz.
