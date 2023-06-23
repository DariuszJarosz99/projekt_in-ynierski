# Projekt inżynierski Dariusz Jarosz
Temat pracy: Platforma rozwojowa  do zarządzania przemysłowymi sprężarkami powietrza

Opis pracy: Praca polega na stworzeniu platformy rozwojowej obsługującej sterowniki do sprężarek śrubowych.
Platforma będzie czysto pasywna. Będzie zapewniać w pełni zdalny dostęp do podglądu parametrów pracy sprężarki
oraz warunków w jakich pracuje. Pozwoli to na pełną swobodę w poglądzie pracy sprężarek oraz aktualnych błędów.
Tak jak mówiłem platforma będzie pasywna, co oznacza że pozwala tylko na podgląd bez możliwości ingerowania w pracę samej sprężarki.
Jest to spowodowane zapewnieniem jak największego bezpieczeństwa. Sprężarki powietrza bardzo często są jednymi z kluczowych elementów które
zapewniają ciągłość produkcji co sprawia że wymaganym jest uniemożliwienie cyber ataków na strukturę firm, ponieważ straty potrafią być kolosalne.

Mam pomysł umożliwiający tryb pół-aktywny który po lokalnym potwierdzeniu przyznania dostępu pozwoli na pewne ingerencję w parametry pracy sprężarki.

Pomijając aspekt podglądu pracy samej sprężarki, platforma będzie w stanie sklejać te dane w wykresy które będą służyć do takich rzeczy jak

- ocena opłacalności montażu falownika
- ocena jakości i wydajności pracy sprężarki

Klient który uzyska dostęp do platformy dostanie unikalne dane do logowania gdzie będzie widział wszystkie przypisane mu sprężarki(sterowniki w sprężarkach).
(zastanawiam się nad innymi formami logowania i weryfikacji użytkownika aby zapewnić jak największe bezpieczeństwo)

Forma ostateczna projektu to stworzenie prototypu który będzie w stanie obsługiwać bazę danych z użytkownikami, będzie w pełni cloud native aby zapewnić pełną skalowalność wraz ze wzrostem liczby klientów. Jeżeli uda mi się dogadać z jedną firmą to sterowniki które tworzą będą podłączone do platformy i będzie można na bieżąco zbierać informacje i oferować pełny podgląd. Jeżeli to się nie uda będę je po prostu jakoś symulował. Pisemna część będzie czysto dopełniająca. Chciałbym skupić się na stronie technicznej całej platformy skupiając się na następujących priorytetach: Działanie samej aplikacji > Stworzenie infrastruktury chmurowej > Frontend > Część opisowa


Wstępny Spis treści:

            WSTĘP
            Spis treści
            1. Opis architektury
            2. Bezpieczeństwo aplikacji
            3. Frontend
            4. Funkcjonalności oraz jej wdrożenia
            5. Integracja platformy ze sterownikiem
            6. Napotkane problemy
            7. Podsumowanie
            Bibliografia
            
            
Bibliografia:

            1. Brikman Y. Terraform: Up and Running: Writing Infrastructure as Code
            2. Laszewski T., Kamal A., Farr E. Cloud Native Architectures: Design high-availability and cost-effective applications for the cloud
            3. Podjarny G. Cloud Native Application Security
            4. Jakaś książka o sprężonym powietrzu oraz ogólnie o sprężarkach ale jeszcze nie jestem pewny
            5. Cloud Native DevOps with Kubernetes
            6. Continuous delivery with docker and Jenkins
            7. Docker in action
            8. Protokoły komunkacji


Pisemna część 
