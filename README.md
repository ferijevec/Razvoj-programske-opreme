# Razvoj programske opreme

Vaja iz Gita in GitHuba. Repozitorij vsebuje majhen program v C++, na katerem vadim veje, pull requeste, CI, oznake in razveljavljanje.

## Zagon

    g++ main.cpp -o main
    main

## Datoteke

- `main.cpp`: program
- `.github/workflows/ci.yml`: CI, ki program prevede in zažene
- `.gitignore`: izključuje `.env`, `*.exe` in `*.o`

## Pravila

`main` je zaščiten. Spremembe gredo prek veje in pull requesta, ki mora prestati preverjanje `build`.

Avtor: David Jelen

Commiti so podpisani ;)