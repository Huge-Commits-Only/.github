# Współpraca

Dzięki, że chcesz pomóc! W **Huge Commits Only** każda zmiana to jeden porządny PR, scalany jako jeden squash commit.

## Jak zgłosić zmianę

1. Utwórz gałąź od `main` z prefiksem: `feat/`, `fix/`, `docs/`, `chore/` albo `deps/`; od niego zależy etykieta PR.
2. Jedna zmiana = jeden PR. Tytuł w stylu [Conventional Commits](https://www.conventionalcommits.org/), np. `feat: tryb drużynowy`.
3. Przed PR uruchom lokalnie testy i lint opisane w README repozytorium.
4. CI musi być zielone, a gałąź aktualna względem `main`. PR scalany jest jako jeden podpisany squash commit, a gałąź usuwana automatycznie.

## Bezpieczeństwo

- Nie commituj sekretów, plików `.env`, danych ani kopii zapasowych. Push protection i tak je zablokuje.
- Nowe akcje GitHub przypinaj do pełnego SHA z wersją w komentarzu, np. `actions/checkout@<sha> # v7.0.1`.
- Podatności zgłaszaj prywatnie, zgodnie z [SECURITY.md](SECURITY.md).

## Nowy projekt

Zacznij od [go-app-template](https://github.com/Huge-Commits-Only/go-app-template) → **Use this template**.
