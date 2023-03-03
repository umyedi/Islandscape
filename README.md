# TP NSI JavaScript

## Introduction

Le projet suivant consiste à créer un jeu dans le genre d'un livre dont on est le héros en utilisant les langages HTML, CSS et JavaScript. Le code doit être commenté et documenté, et écrit entièrement par les membres du groupe. La date de rendu est le **24 avril**.

Pour organiser notre script, nous avons utilisé [Figma](https://www.figma.com/file/xo2k0CaikHkmda4xud4eGg/TP-NSI-JavaScript?node-id=0%3A1&t=tyaRxUwvmQXWnIya-0).

## Développement

### Histoires
Les histoires seront stockées dans un fichier json. Le format est le suivant :

```json
{
    "nom_du_texte_1": {
        "type": "question",
        "content": "contenu de nom_du_texte_1",
        "answer_1": ["nom_texte_1", "texte de la réponse"],
        "answer_2": ["nom_texte_2", "texte de la réponse"]
    },
    "nom_du_texte_2": {
        "type": "random",
        "content": "contenu de nom_du_texte_2",
        "answer_1": ["nom_texte_1", "texte de la réponse", 0.7],
        "answer_2": ["nom_texte_2", "texte de la réponse", 0.3]
    },

    "nom_du_texte_3": {
        "type": "direct",
        "content": "contenu de nom_du_texte_3",
        "redirect": "nom_texte"
    }
}
```

### Page Web
Les pages web seront dynamiques, ce qui rend le développement plus modulable et permet une plus grande flexibilité

### Avancement
L'inventaire et l'avancement actuel seront stockés dans les cookies
