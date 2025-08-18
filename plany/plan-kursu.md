# Plan Kursu: NodeJS dla programistów TypeScript

## Moduł 1: Podstawy środowiska Node.js i BUN w Windows

### Lekcja 1: Instalacja i pierwsza konfiguracja
  - M01L01C01 Instalacja Node.js w systemie Windows
    - Pobieranie i instalacja LTS version
    - Weryfikacja instalacji przez PowerShell
    - Konfiguracja PATH i zmiennych środowiskowych
    - Pierwsze uruchomienie `node --version` i `npm --version`
  - M01L01C02 Instalacja środowiska BUN
    - Instalacja BUN w Windows przez PowerShell
    - Weryfikacja instalacji `bun --version`
    - Porównanie szybkości startup między node a bun
    - Konfiguracja BUN jako domyślnego runtime

### Lekcja 2: Pierwszy projekt i różnice między Node.js a BUN
  - M01L02C01 Tworzenie projektu Node.js
    - Inicjalizacja `npm init`
    - Struktura package.json
    - Instalacja pierwszych dependencji
    - Uruchomienie prostego skryptu przez `npm run`
  - M01L02C02 Tworzenie projektu BUN
    - Inicjalizacja `bun init`
    - Różnice w package.json dla BUN
    - Instalacja dependencji przez `bun install`
    - Uruchomienie skryptu przez `bun run`
  - M01L02C03 Porównanie wydajności i funkcjonalności
    - Test szybkości instalacji pakietów
    - Różnice w obsłudze TypeScript
    - Kiedy używać Node.js a kiedy BUN

### Lekcja 3: Package management i TypeScript setup
  - M01L03C01 Zarządzanie pakietami npm
    - Instalacja lokalnych i globalnych pakietów
    - Semantyczne wersjonowanie w package.json
    - package-lock.json vs bun.lockb
    - Best practices dla dependencies
  - M01L03C02 Konfiguracja TypeScript dla backend
    - Instalacja @types/node i typescript
    - Tworzenie tsconfig.json dla serwera
    - Różnice między frontend a backend TS config
    - Kompilacja i uruchamianie kodu TypeScript

## Moduł 2: TypeScript dla Backend - przejście z Angular

### Lekcja 1: Konfiguracja TypeScript w środowisku serwerowym
  - M02L01C01 tsconfig.json dla projektów serwerowych
    - Ustawienia target i module dla Node.js
    - Konfiguracja strict mode i najlepsze praktyki
    - Różnice między Angular CLI a backend TS setup
    - Konfiguracja path mapping i module resolution
  - M02L01C02 Typy Node.js i zewnętrznych bibliotek
    - Instalacja @types/node
    - Różnice między DOM types a Node.js types
    - Import i usage globalnych Node.js objektów
    - TypeScript z BUN - built-in types

### Lekcja 2: Struktura projektów i code organization
  - M02L02C01 Organizacja kodu w projektach Node.js
    - Różnice między Angular modules a Node.js modules
    - ES6 imports vs CommonJS requires
    - Struktura folderów dla backend projektów
    - Barrel exports i re-exports
  - M02L02C02 Typowanie i interfaces dla backend
    - Definiowanie typów dla API requests/responses
    - Interfaces vs types w kontekście serwera
    - Utility types w praktyce backend
    - Generic types dla reusable funkcji

### Lekcja 3: Environment variables i konfiguracja
  - M02L03C01 Zarządzanie konfiguracją aplikacji
    - Praca z process.env w TypeScript
    - Walidacja environment variables
    - Tworzenie .env files i dotenv
    - Typowanie konfiguracji aplikacji
  - M02L03C02 Debugowanie TypeScript w Node.js/BUN
    - Konfiguracja VS Code dla debugging
    - Source maps i ts-node
    - Debugging w BUN environment
    - Hot reload i watch mode

## Moduł 3: Podstawowe skrypty i CLI aplikacje

### Lekcja 1: Pierwsze skrypty Node.js
  - M03L01C01 Hello World i podstawowe operacje
    - Tworzenie prostego skryptu TypeScript
    - Console.log i podstawowy output
    - Čtenie argumentów z process.argv
    - Przykład prostego kalkulatora CLI
  - M03L01C02 Praca z plikami i filesystem
    - Import fs module w TypeScript
    - Asynchroniczne vs synchroniczne operacje na plikach
    - Čtenie i pisanie plików tekstowych
    - Error handling przy operacjach na plikach

### Lekcja 2: Programowanie asynchroniczne - podstawy
  - M03L02C01 Promise i async/await w praktyce
    - Różnice między callback a Promise
    - Async/await syntax i error handling
    - Tworzenie własnych Promise-based funkcji
    - Przykład skryptu pobierającego dane z API
  - M03L02C02 Równoczesne operacje i Promise.all
    - Promise.all vs Promise.allSettled
    - Równoczesne vs sekwencyjne operacje
    - Practical example: pobieranie z wielu APIs
    - Performance optimization w async operacjach

### Lekcja 3: Zewnętrzne biblioteki i HTTP requests
  - M03L03C01 Instalacja i użycie zewnętrznych pakietów
    - Wybór między różnymi HTTP biblioteki
    - Instalacja i typowanie bibliotek (np. axios)
    - Import i konfiguracja zewnętrznych dependencies
    - Best practices dla dependency management
  - M03L03C02 Praktyczny przykład: OpenAI API client
    - Instalacja openai package
    - Konfiguracja API key przez environment variables
    - Tworzenie prostego skryptu do chat completion
    - Error handling i retry logic

## Moduł 4: Express.js i podstawowe serwery HTTP

### Lekcja 1: Setup Express.js z TypeScript
  - M04L01C01 Instalacja i konfiguracja Express
    - Instalacja express i @types/express
    - Tworzenie podstawowego serwera HTTP
    - Middleware concept i express.json()
    - Uruchomienie serwera i testowanie w przeglądarce
  - M04L01C02 Routing i podstawowe endpoints
    - GET, POST, PUT, DELETE routes
    - Route parameters i query strings
    - Request i Response objects w TypeScript
    - Praktyczny przykład: TODO API endpoints

### Lekcja 2: Middleware i request handling
  - M04L02C01 Built-in i custom middleware
    - Express middleware chain
    - Tworzenie custom middleware functions
    - Error handling middleware
    - Logging i request timing middleware
  - M04L02C02 Validation i type safety
    - Request body validation
    - Type guards dla incoming data
    - Error responses i status codes
    - Practical example: user registration endpoint

### Lekcja 3: Praktyczny projekt REST API
  - M04L03C01 Struktura REST API
    - RESTful conventions i best practices
    - Organizacja routes w separate files
    - Response formats i consistency
    - API documentation basics
  - M04L03C02 Complete CRUD operations example
    - In-memory data store dla przykładu
    - Implementacja wszystkich CRUD operations
    - Postman testing i przykłady requests
    - Error handling i edge cases

## Moduł 5: Zaawansowane wzorce architektoniczne

### Lekcja 1: Services Pattern i Dependency Injection
  - M05L01C01 Wprowadzenie do Services Pattern
    - Czym jest Service layer w backend architecture
    - Separation of concerns - routing vs business logic
    - Tworzenie pierwszego Service class
    - Porównanie z Angular Services
  - M05L01C02 Dependency Injection w Node.js
    - Manual dependency injection
    - Constructor injection pattern
    - Service composition i dependencies
    - Praktyczny przykład: OpenAIService

### Lekcja 2: Modularność i code organization
  - M05L02C01 Organizacja kodu w większych projektach
    - Folder structure dla scalable apps
    - Barrel exports i module organization
    - Types i interfaces w separate files
    - Utils i helper functions organization
  - M05L02C02 Interface-based design
    - Definiowanie interfaces dla services
    - Abstraction i loose coupling
    - Mockowanie dla testing purposes
    - Dependency inversion principle

### Lekcja 3: Praktyczny przykład: AI Chat Service
  - M05L03C01 Architektura multi-service aplikacji
    - OpenAIService, DatabaseService, FileService
    - Service composition i orchestration
    - Configuration management dla services
    - Error propagation między services
  - M05L03C02 Integration przykładu z Express
    - Router + Service layer integration
    - Request flow przez multiple services
    - Error handling na poziomie architecture
    - Complete working example z testami

## Moduł 6: Programowanie asynchroniczne i zewnętrzne integracje

### Lekcja 1: Zaawansowane async patterns
  - M06L01C01 Concurrent operations i performance
    - Promise.all dla równoczesnych operations
    - Promise.allSettled dla error resilience
    - Batching i rate limiting
    - Performance monitoring async operations
  - M06L01C02 Async generators i streaming
    - Async iterator pattern
    - Processing large data sets
    - Memory management w async operations
    - Practical example: streaming API responses

### Lekcja 2: External API integrations
  - M06L02C01 HTTP client patterns
    - Axios configuration i interceptors
    - Retry logic i exponential backoff
    - Request/response transformation
    - API rate limiting handling
  - M06L02C02 Error handling i resilience
    - Network error handling strategies
    - Circuit breaker pattern basics
    - Graceful degradation
    - Logging i monitoring external calls

### Lekcja 3: Praktyczny projekt: Multi-API aggregator
  - M06L03C01 Agregacja danych z wielu źródeł
    - Concurrent API calls z Promise.all
    - Data transformation i normalization
    - Caching strategies dla external APIs
    - Error handling quando niektóre APIs fail
  - M06L03C02 Complete implementation
    - Express server z multiple external integrations
    - Service layer dla każdego external API
    - Unified response format
    - Performance optimization i monitoring

## Moduł 7: File Processing i Advanced HTTP Features

### Lekcja 1: File upload i processing
  - M07L01C01 Multer i file upload handling
    - Instalacja i konfiguracja multer
    - Memory vs disk storage strategies
    - File validation i security considerations
    - Multiple file upload handling
  - M07L01C02 File processing i transformation
    - Reading different file formats
    - Image processing basics
    - Text extraction from documents
    - Asynchronous file processing workflows

### Lekcja 2: Streaming i advanced HTTP
  - M07L02C01 HTTP streaming responses
    - Stream concept w Node.js
    - Streaming large files
    - Server-sent events (SSE)
    - Practical example: real-time data streaming
  - M07L02C02 WebSocket basics
    - WebSocket vs HTTP comparison
    - Simple WebSocket server setup
    - Real-time communication patterns
    - Integration with Express applications

### Lekcja 3: Production-ready patterns
  - M07L03C01 Error handling i logging
    - Centralized error handling middleware
    - Structured logging best practices
    - Request correlation i tracing
    - Health check endpoints
  - M07L03C02 Security i performance basics
    - CORS configuration
    - Rate limiting implementation
    - Basic security headers
    - Performance monitoring i optimization tips
