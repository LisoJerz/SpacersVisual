                            Spacer's Visual
                        Instrukcja i informacje

Autor:    LisoJerz - Dominik Łagosz
Licencja: WTFPL-NW (szczegóły w pliku LICENSE.txt)

======================================================================
1. ZAWARTOŚĆ PACZKI
======================================================================

  SpacersVisual.ttf       - główny plik czcionki (zalecany do Worda,
                            PowerPointa i codziennego użytku)
  otf/SpacersVisual.otf   - wersja OpenType (alternatywa do programów
                            graficznych, nie instalować razem z .ttf)
  assets/                 - zasoby wektorowe i bitmapowe:
      font_atlas.png      - atlas znaków (PNG)
      font_metrics.json   - metryki i współrzędne UV do gier/aplikacji
      font_atlas.svg      - wektorowy atlas wszystkich znaków (SVG)
      svg/                - pojedyncze pliki SVG dla każdego znaku
  LICENSE.txt             - pełna treść licencji

======================================================================
2. INSTALACJA
======================================================================

WAŻNE: Najpierw wypakuj całe archiwum .zip do osobnego folderu!

Windows (pod Worda / PowerPointa):
  Metoda 1 (menu kontekstowe):
    1. Przytrzymaj klawisz Shift i kliknij prawym przyciskiem myszy
       na plik "SpacersVisual.ttf" (otworzy to pełne menu).
    2. Wybierz "Zainstaluj dla wszystkich użytkowników".

  Metoda 2 (gdy powyższej opcji nie widać w menu):
    1. Otwórz folder C:\Windows\Fonts w Eksploratorze plików.
    2. Skopiuj lub przeciągnij tam plik "SpacersVisual.ttf"
       (potwierdź monit administratora, jeśli się pojawi).

  Po instalacji zrestartuj Worda / PowerPointa, jeśli był otwarty.

  UWAGA: Nie instaluj jednocześnie pliku .otf z folderu otf/ - dwa
  pliki o tej samej nazwie czcionki potrafią się wzajemnie blokować
  w pakiecie Microsoft Office.

macOS:
  Otwórz "SpacersVisual.ttf" i kliknij "Zainstaluj czcionkę"
  w Albumie z czcionkami (Font Book).

Linux:
  Skopiuj "SpacersVisual.ttf" do katalogu ~/.local/share/fonts/
  i odśwież pamięć podręczną poleceniem: fc-cache -f

======================================================================
3. ZAKRES ZNAKÓW I WSKAZÓWKI
======================================================================

- Obsługiwane znaki:
    Litery: A-Z (małe litery a-z automatycznie wyświetlają się
            jako wielkie)
    Cyfry:  0-9
    Znaki:  _ - : . ! , ; ? ' " ( ) [ ] { } < > + = * % ~ ^ |
- Czcionka nie zawiera polskich znaków diakrytycznych
  (ą, ć, ę, ł, ń, ó, ś, ź, ż).
- Prezentacje i dokumenty: jeśli wysyłasz komuś plik .pptx lub .docx
  do otwarcia na innym komputerze, wyeksportuj go do PDF albo włącz
  w opcjach zapisu "Osadź czcionki w pliku" (czcionka ma włączone
  osadzanie bez ograniczeń).

======================================================================
4. LICENCJA
======================================================================

Projekt udostępniony na licencji WTFPL-NW (Do What The Fuck You Want
To Public License - No Warranty). Pełna treść znajduje się w pliku
LICENSE.txt.