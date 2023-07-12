# Compilateur langage ALGO vers Javascript

Compilateur écrit en langage C qui transforme un code source (langage algorithmique à syntaxe française) en un code objet (javascript).

## Fonctionnalités prises en charge

**Analyse lexicale/syntaxique :**
- opérateur binaire (+, -, >=, >, <, <=, ==, !=, *, /, ET, OU)
- appel de fonction
- définition de fonction (fonction mafonction (entier a) : entier { } )
- déclaration de variable / initialisation (entier a; entier b = 1;)
- affectation (b = 2)
- branchement (si / sinon si / sinon)
- boucle (tantque () { })
- retourner
- variable (type int seulement)
- entier

# Compiler et exécuter le projet

Compilation avec **Make**: ```make compile```

Compilation "à la main": ```gcc main.c */*.c -g -o main```

Execution: ```make compile run```
