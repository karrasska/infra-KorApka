# infra-KorApka
Repozytorium łączące frontend i backend.

## Docker

### `docker compose up --build`
Budowanie i uruchamianie wszystkich usług. 

### `docker compose down`
Zamykanie kontenerów. 

### `docker compose run --rm backend python manage.py migrate`
Wykonanie migracji Django w kontenerze backend. (to chyba nie jest niezbędne, ale mi się przydało)
