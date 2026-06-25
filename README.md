# Jak odpalac projekt

## Co musicie mieć zainstalowane
Przed startem upewnijcie się, że macie na komputerach:
* **Docker Desktop** (musi być włączony i działać w tle)
* **Java 21**
* **Python 3.x**

---

## Jak odpalić projekt u siebie

### Krok 1: Baza Danych i pgAdmin (Od tego ZAWSZE zaczynamy)
Nie instalujecie żadnej bazy u siebie. Docker zrobi to za Was.
1. Otwórzcie terminal w **głównym folderze** repozytorium (tam, gdzie jest plik `docker-compose.yml`).
2. Wpiszcie komendę:
   ```bash
   docker compose up -d

To tyle na razie dziekuje za uwage, springa do testowania odpalacie normalnie, bedziemy spinac pythona z java to bedziemy sie potem martwic jak to odpalac

Aha no i pamiętajcie pullowac na biezaco zebysmy mialy aktualna wersje zeby merge konfliktow nie bylo potem XD
