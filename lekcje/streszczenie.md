# Streszczenie treści kursu NodeJS dla programistów TypeScript

## Moduł 1: Podstawy środowiska Node.js i BUN w Windows

### Lekcja 1: Instalacja i pierwsza konfiguracja

#### M01L01C01: Instalacja Node.js w systemie Windows
**Streszczenie**: Rozdział wprowadza programistów TypeScript w świat Node.js, wyjaśniając czym jest runtime Node.js i dlaczego warto go używać do programowania backendowego. Szczegółowo opisuje proces pobierania i instalacji wersji LTS Node.js w systemie Windows, ze szczególnym uwzględnieniem konfiguracji PATH i weryfikacji instalacji przez PowerShell. Zawiera praktyczne przykłady testowania instalacji, rozwiązywanie typowych problemów oraz podstawowe polecenia do zapamiętania. Po ukończeniu tego rozdziału uczestnik ma w pełni funkcjonalne środowisko Node.js gotowe do dalszej nauki.

#### M01L01C02: Instalacja środowiska BUN
**Streszczenie**: Rozdział wprowadza BUN jako nowoczesną alternatywę dla Node.js, charakteryzującą się znacznie lepszą wydajnością i wbudowaną obsługą TypeScript. Opisuje proces instalacji BUN w Windows przez PowerShell, weryfikację instalacji oraz praktyczne porównanie wydajności między Node.js a BUN. Szczególny nacisk położony jest na natywną obsługę TypeScript w BUN - możliwość uruchamiania plików `.ts` bez kompilacji. Rozdział zawiera również wytyczne, kiedy używać Node.js, a kiedy BUN, oraz podstawowe polecenia package managera BUN. Po ukończeniu uczestnik ma oba runtime'y gotowe do użycia i rozumie różnice między nimi.

### Lekcja 2: Pierwszy projekt i różnice między Node.js a BUN

#### M01L02C01: Tworzenie projektu Node.js
**Streszczenie**: Rozdział wprowadza programistów TypeScript w praktyczne tworzenie projektów Node.js, wyjaśniając kluczowe różnice między projektami frontend (Angular) a backend. Szczegółowo opisuje proces inicjalizacji projektu przez `npm init`, analizę struktury package.json dla projektów serwerowych oraz instalację podstawowych dependencies (TypeScript, @types/node, ts-node, nodemon). Zawiera praktyczne przykłady tworzenia pierwszego skryptu TypeScript wykorzystującego Node.js API oraz konfigurację skryptów npm do uruchamiania aplikacji. Rozdział kończy się porównaniem z Angular CLI i praktycznymi wskazówkami dotyczącymi organizacji kodu. Po ukończeniu uczestnik ma pierwszy funkcjonalny projekt Node.js z TypeScript gotowy do dalszego rozwoju.

#### M01L02C02: Tworzenie projektu BUN
**Streszczenie**: Rozdział przedstawia proces tworzenia projektu z wykorzystaniem BUN jako alternatywy dla Node.js, szczególnie atrakcyjnej dla programistów TypeScript. Opisuje znacznie uproszczony proces inicjalizacji przez `bun init`, który domyślnie tworzy projekt TypeScript bez potrzeby dodatkowych konfiguracji. Szczegółowo analizuje różnice w package.json między BUN a Node.js, pokazując natywną obsługę TypeScript i ES modules. Rozdział obejmuje błyskawiczny package manager BUN, porównanie wydajności startupu aplikacji oraz praktyczne przykłady uruchamiania skryptów TypeScript bez kompilacji. Zawiera również wskazówki, kiedy wybierać BUN zamiast Node.js, oraz praktyczne porównanie workflow'u developmentu. Po ukończeniu uczestnik rozumie zalety BUN i potrafi stworzyć w pełni funkcjonalny projekt TypeScript z znacznie szybszym cyklem developmentu.

