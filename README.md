# Web Security Lab Writeups

Mes writeups de labs pratiques en sécurité web offensive : démarche, payloads, explications et captures de validation.

Les exercices documentés sont réalisés dans des environnements de formation autorisés. Chaque writeup relie l'exploitation à la correction de la vulnérabilité.

## Labs réalisés

| Lab | Thème | Plateforme | Résultat | Writeup |
| --- | --- | --- | --- | --- |
| 01 | Injection SQL — récupération de données cachées | PortSwigger Web Security Academy | Résolu, confirmé par capture | [Lire le writeup](labs/01-sqli-hidden-data/README.md) |

## Organisation

```text
labs/
└── 01-sqli-hidden-data/
    ├── README.md
    └── screenshots/
        ├── 01-catalogue.jpeg
        ├── 02-filtre-categorie.jpeg
        └── 03-lab-resolu.jpeg
templates/
└── writeup-template.md
```

## Contenu des writeups

Chaque lab présente l'objectif, le point d'entrée, les étapes visibles dans les captures, le fonctionnement du payload, le résultat et les mesures de correction. Les explications reconstruites sont distinguées des observations directes.

Pour ajouter un lab, utiliser le [modèle de writeup](templates/writeup-template.md), placer ses captures dans son dossier et ajouter une ligne au tableau ci-dessus.

## Sources et captures

Les captures proviennent de mes exercices. Les interfaces et noms de labs appartiennent à leurs plateformes respectives. Les références officielles sont indiquées dans chaque writeup.
