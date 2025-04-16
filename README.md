# api-cli-fetcher

Pobiera dane z podanego API i zapisuje do pliku JSON

## Instalacja

1. Sklonuj repozytorium:
   ```bash
   git clone https://github.com/twoje_konto/api-cli-fetcher.git
   cd api-cli-fetcher
   ```

2. Nadaj uprawnienia do uruchamiania (jeśli używasz systemu Linux/macOS):
   ```bash
   chmod +x cli_fetcher.sh
   ```

## Przykład użycia

```bash
./cli_fetcher.sh --fetch --url https://jsonplaceholder.typicode.com/posts
```

## Dodawanie nowych źródeł danych

1. Otwórz plik `sources.txt` i dodaj nową linię z URL-em:
   ```
   https://api.nowe-api.com/data
   ```

2. Wybierz źródło z listy 
   ```bash
   ./cli_fetcher.sh --source 2
   ```
