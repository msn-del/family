# famille

Family management program in C using structures.
It reads the members of a family and sorts them by date of birth, from oldest to youngest.

## Features

- Enter the members of a family (last name, first name, date of birth)
- Sort members by date of birth
- Display the sorted list

## Compile and run

```bash
gcc main.c -o famille
./famille
```

## Example

Input:

```
Saisir le nombre des membres: 3

--- Membre numéro 1 ---
Nom: Alami
Prénom: Sara
Jour de naissance: 15
Mois de naissance: 6
Année de naissance: 2010
...
```

Output:

```
--- Liste des membres classés ---
Alami Omar né le 03/02/1975
Alami Fatima né le 20/09/1980
Alami Sara né le 15/06/2010
```
