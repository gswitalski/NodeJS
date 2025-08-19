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

#### M01L02C03: Porównanie wydajności i funkcjonalności
**Streszczenie**: Rozdział stanowi praktyczne podsumowanie różnic między Node.js a BUN poprzez konkretne testy wydajności i benchmarki. Szczegółowo porównuje szybkość instalacji pakietów (BUN 3-6x szybszy), różnice w obsłudze TypeScript (natywna transpilacja vs ts-node) oraz startup time aplikacji (BUN ~100-300ms vs Node.js ~2-4s). Przedstawia matrycę decyzyjną opartą na realnych kryteriach projektowych: stabilność vs wydajność developmentu, kompatybilność ekosystemu vs TypeScript-first experience. Rozdział zawiera praktyczne wytyczne kiedy używać Node.js (projekty produkcyjne, duże zespoły, stabilność) a kiedy BUN (prototypy, TypeScript projects, szybkie iteracje). Kończy się strategią hybrydową dla programistów TypeScript - nauka z BUN, produkcja z Node.js. Po ukończeniu uczestnik potrafi świadomie wybierać runtime na podstawie specyfiki projektu i zespołu.

### Lekcja 3: Package management i TypeScript setup

#### M01L03C01: Zarządzanie pakietami npm
**Streszczenie**: Rozdział wprowadza programistów TypeScript w zaawansowane zarządzanie pakietami npm w kontekście projektów backend, wyjaśniając kluczowe różnice między frontend (Angular) a backend package management. Szczegółowo opisuje instalację lokalnych vs globalnych pakietów, praktyczne zastosowanie semantycznego wersjonowania (SemVer) z operatorami ^ i ~, oraz znaczenie lock files (package-lock.json vs bun.lockb) dla reproducible builds. Rozdział zawiera best practices dla organizacji dependencies, security audits, strategii aktualizacji pakietów oraz współpracy zespołowej. Szczególny nacisk położony jest na świadome podejście do wyboru pakietów, zarządzanie dependencies vs devDependencies oraz wykorzystanie npx zamiast globalnych instalacji. Po ukończeniu uczestnik potrafi profesjonalnie zarządzać ekosystemem pakietów w projektach Node.js z pełnym zrozumieniem konsekwencji każdej decyzji.

