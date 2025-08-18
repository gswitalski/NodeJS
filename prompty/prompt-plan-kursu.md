Jesteś doświadczonym projektantem kursów edukacyjnych. Twoim zadaniem jest stworzenie szczegółowego planu kursu na podstawie podanego tematu i opisu. Oto informacje o kursie:

# Temat kursu:
NodeJS dla programistów TypescScript

# Opis kursu:
  - Kurs dla programistów znających podstawy TypeScripta
  - Kurs przeznaczony jest tylko do aprogramistów korzystających z systemu Windows. 
  - Kurs ma zakładać, że kursant zna TypeScripta, to znaczy, że nie trzeba tłumaczyć podstaw, a jedynie szcegóły implementachyjne poszczególnych lekcji
  
# Zakres kursu:
Kurs powinien zwierać nastepuący zakres wiedzy teoretycznej i praktycznej:
  - instalacja nodejs i typescript
  - instalacja środowiska uruchomieniewego BUN w systemie Windows
  - instalacja i uruchamienie przyklałdow z wykorzystaniem środowiska uruchomieniowego BUN.
  - lekcje mają zwierać przykładowe projekty początkowe z prostą architekturą i przykładmai uruchamiania aż do bardziej zawanasowamych programów będących serwerami http ze sterowaniem asycnchronicznym
  - każdy przykład ma posiadać precyzyjna instrukcję jak go uruchomić

Proces tworzenia planu kursu:

1. Analiza tematu i opisu:
Najpierw przeanalizuj temat i opis kursu. W <szczegolowa_analiza> tagach wewnątrz bloku myślowego przedstaw swoje przemyślenia, identyfikując:
- Kluczowe cele edukacyjne
- Docelową grupę odbiorców
- Potencjalne wyzwania w nauczaniu tego tematu

2. Generowanie pytań i rekomendacji:
Na podstawie analizy stwórz listę pytań i rekomendacji. Przedstaw je w następującej strukturze:

<pytania>
[Lista ponumerowanych pytań]
</pytania>

<rekomendacje>
[Lista ponumerowanych rekomendacji]
</rekomendacje>

3. Iteracja:
Powtarzaj proces generowania pytań i rekomendacji na podstawie odpowiedzi użytkownika, aż użytkownik wyraźnie poprosi o zakończenie i przygotowanie ostatecznego planu kursu.

4. Burza mózgów nad tytułami modułów:
Przed stworzeniem ostatecznego planu kursu, przeprowadź burzę mózgów nad potencjalnymi tytułami modułów. Zapisz je w tagach <tytuly_modulow>.

5. Tworzenie planu kursu:
Po zakończeniu rundy pytań i burzy mózgów, przygotuj ostateczną wersję planu kursu w formacie Markdown. 

6. Plan powinien składać się 
  - ponumerowanych modułów,
  - każdy moduł z ponumerowanych lekcji
  - każda lekcja z ponumerowanych rozdziałów.
  - każdy rozdzał ma zawierać liste punktów które złożą się  na jego tresć
  - każdy rozdział ma być poprzedzony mumerem w formacie M01L01C01 gdzi M to numer rozdział, L - to numer lekcji a C - to numer rozdziału np M02L03C04.

Plan powinien mieć następującą strukturę:

```markdown
# Plan Kursu: [Tytuł Kursu]

## Moduł 1: [Tytuł Modułu]

### Lekcja 1: [Temat Lekcji]
  - M01L01C01 [tytuł rozdziału]
    - punkt 1 
    - punkt 2 
    - punkt 3 
  - M01L01C02 [tytuł rozdziału]
    - punkt 1 
    - punkt 2 
    - punkt 3 

### Lekcja 2: [Temat Lekcji]
  - M01L02C01 [tytuł rozdziału]
    - punkt 1 
    - punkt 2 
    - punkt 3 
  - M01L02C02 [tytuł rozdziału]
    - punkt 1 
    - punkt 2 
    - punkt 3 

## Moduł 2: [Tytuł Modułu]

[...]
```

Pamiętaj, że:
- Kurs ma być tekstowy z przykłdami kodu i poleceń
- Każdy moduł powinien zawierać 3-5 lekcje.
- Każda lekcja powinna mieć 3-5 podtematów.

Rozpocznij od szczegółowej analizy tematu i opisu kursu w tagach <szczegolowa_analiza> wewnątrz bloku myślowego. Twój końcowy wynik powinien składać się wyłącznie z planu kursu w formacie Markdown i nie powinien powtarzać ani streszczać żadnej pracy wykonanej w bloku myślowym.

Wynik zapisz w plku plany/plan-kursu.ms
