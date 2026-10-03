# Lokista Live

Twitch, YouTube i Kick Lokisty naraz, na jednym ekranie: PC, telefon, tablet.

**Otwórz:** https://lokista.github.io/lokista-live/

## Instalacja jak aplikacja

- **Android (Chrome):** menu ⋮ → *Dodaj do ekranu głównego* / *Zainstaluj aplikację*.
- **iPhone / iPad (Safari):** przycisk Udostępnij → *Do ekranu początkowego*.
- **PC (Chrome / Edge):** ikonka instalacji na końcu paska adresu → *Zainstaluj*.

## Obsługa

- Wszystkie trzy transmisje startują bez dźwięku (tak wymagają przeglądarki). **Włącz dźwięk** włącza go dla dużego okna.
- Dotknij małego okna, a przejdzie na duży ekran (dźwięk idzie razem z nim).
- **Wszystkie równo**: trzy równe okna; głośnik przy nazwie wybiera, które gra z dźwiękiem.
- Gdy kanał jest offline, YouTube pokazuje ostatnią transmisję, a Twitch i Kick planszę „offline”.

## Twitch: dwie zasady, których nie da się obejść

Odtwarzacz Twitcha osadzony na stronie startuje (i liczy widza) tylko, gdy:
1. ma **co najmniej 400×300 px**,
2. **nic go nie zasłania** — dlatego nazwy i przyciski są na pasku nad obrazem, a nie na nim.

Telefon w pionie ma za mało szerokości, więc tam Twitch pokazuje: „Obróć telefon poziomo albo otwórz w aplikacji Twitch”.
Telefon poziomo, tablet i PC: Twitch jako duże okno gra normalnie.

## Kanały

Ustawione w `index.html` (`CHANNELS`): Twitch `lokista_`, YouTube `@lokistaofficial`, Kick `lokista`.
Bez serwera i bez kluczy API: zwykła strona statyczna.
