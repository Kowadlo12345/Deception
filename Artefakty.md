# Deception
## Artefakty 
### Instrukcje
Instrukcje stworzone przez Technical Writera mają na celu przedstawienie sposobu funkcjonowania systemu. Pokazują, jak wdrożyć i obsłużyć system w infrastrukturze. Pomagają administratorom zarządzać produktem. Zawierają procedury postępowania w przypadku określonych wydarzeń. Ciągłe aktualizowanie instrukcji pozwala na dostarczanie informacji jak pracować z systemem w aktualnej wersji, co pomaga usprawnić działanie zespołu.
### Skrypty
Skrypty napisane przez programistów są połączone z komponentami takimi jak konta użytkowników, serwery, pliki, usługi, które mają imitować prawdziwe zasoby infrastruktury. Służą do wykrywania złośliwej aktywności. Ponadto, ich zadaniem jest umożliwienie generowania alertów w przypadku wystąpienia incydentu bezpieczeństwa. Dzięki połączeniu z systemem SIEM zapewniają natychmiastowe informowanie personelu o podejrzanej aktywności.
### Konsola zarządzająca
Konsola zarządzania jest narzędziem pozwalającym w prosty sposób konfigurować i kontrolować pracę praktycznie wszystkich mechanizmów i usług dostępnych w sieci Deception. Co ważniejsze możliwe jest to zarówno lokalnie, jak i zdalnie. Konsola zarządzająca ma na celu umożliwienie tworzenia narzędzi administracyjnych, oferujących możliwości zmiany ustawień systemowych w ściśle określonych przez nas dziedzinach.
### Generatory ruchu
Generator ruchu służy nam do wygenerowania określonego wolumenu pakietów o ustalonej strukturze analizy poprawności jego przesłania przez naszą infrastrukturę. Generatory ruchu mają za zadanie zwieść potencjalnego atakującego, że system Deception jest stale użytkowanym i żywym systemem oraz ma wzbudzić zainteresowanie adwersarza i chęć wejścia do środowiska.
### Reguły korelacyjne
Reguła korelacji pomaga rozwiązaniu SIEM w identyfikowaniu sekwencji zdarzeń wskazujących na anomalie w celu wykrycia incydentu bezpieczeństwa. Ma to na celu skupienie się na dokładnym doprecyzowaniu kryteriów i warunków logicznych każdej z reguł, tak aby w przypadku anomalii, incydentu, czy ataku został wysłany poprawny komunikat do konsoli zarządzającej. Zostały zaimplementowane scenariusze kaskadowe, tj. wiązanie kilku reguł korelacyjnych w jeden incydent.
