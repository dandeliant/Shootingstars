# Neigh 🏢

Interaktywna wizualizacja 3D klatki schodowej — kto mieszka w którym mieszkaniu.

Budynek ma parter i 4 piętra, po 3 mieszkania na każdej kondygnacji (numery 11–25).
Model odwzorowuje prawdziwy blok: elewację z balkonami, elewację wejściową z klatką
schodową pośrodku (okna na półpiętrach), brązowy cokół z okienkami piwnicznymi,
podest z trzema schodkami, balustradę i zadaszenie wejścia na dwóch słupkach.

## Funkcje

- **Obracanie i zoom** — przeciągnij myszką / palcem, kółko myszy lub szczypnięcie
- **Notatki o mieszkańcach** — kliknij mieszkanie (na modelu albo na mini-planie),
  wpisz mieszkańców i notatki; zapis jest automatyczny (localStorage przeglądarki)
- **Świecące okna** — mieszkania z notatkami mają ciepło oświetlone wnętrza
  i zieloną kropkę przy tabliczce z numerem
- **Wnętrza za szybami** — każde okno ma losowy wystrój (lampy, rośliny, półki, koty)
- **Eksport / import** — notatki można zapisać do pliku JSON i przenieść
  na inny komputer lub urządzenie

## Uruchomienie

Wystarczy otworzyć [`index.html`](index.html) w przeglądarce — wszystko
(łącznie z biblioteką Three.js) jest w jednym pliku, działa bez internetu.

Opcjonalnie można wystartować lokalny serwer podglądu:

```
node server.js
```

i otworzyć <http://localhost:4173>.

## Technologie

Three.js (r128, wbudowane w plik), czysty HTML/CSS/JS — zero zależności do instalowania.
