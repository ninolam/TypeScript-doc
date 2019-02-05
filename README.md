# Expose-TypeScript

## Présentation

TypeScript est un langage de programmation open-source développé par Microsoft.

Il reprend le langage JavaScript en ajoutant un typage strict. Si vous vous y connaissez déjà en JS, il sera facile de migrer vers TypeScript, ce n'est pas comme si vous passez d'un langage à un autre.
TypeScript, c'est un peu comme du JavaScript moderne et conforme aux normes.

Il a été conçu pour le développement d'applications volumineuses et la transcompilation (prend en entrée le code source d'un langage de programmation et produit le code source équivalent dans un autre langage de programmation) en JavaScript.

## Sources

https://blog.cellenza.com/developpement-specifique/web-developpement-specifique/introduction-a-typescript/
https://www.grafikart.fr/tutoriels/typescript-781

https://blog.logrocket.com/7-bad-excuses-for-not-using-typescript-dbf5e603a9a8

## Sommaire

1. Qu'est que TypeScript ?
2. Installation et configuration 
3. Syntaxe du typage en TypeScript
5. Les modules et les classes
6. String, number, array, functions
7. Avantages et inconvénients
8. Conclusion




### 3. Quelques types de bases en TypeScript

TypeScript introduit la notion d’un typage un peu plus fort que pour le langage Javascript. Ce typage se manifeste par l’ajout de plusieurs types de bases ainsi qu’un typage statique.

Rappelons qu’un langage est dit de typage statique quand celui-ci vérifie les types des variables à la compilation, alors qu’un langage dit de typage dynamique,effectue cette vérification à l’exécution.

```TypeScript

let myVar: boolean;

let myVarinitialize: number = 2;

let bar = "hello world";
```
Dans l’exemple ci-dessous, les 2 premières déclarations de variables sont typées explicitement et la dernière l’est implicitement. 




