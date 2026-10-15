# Relevés de la rubrique Apprendre de Meridal

Les relevés sur lesquels s'appuient les pages de la rubrique Apprendre de Meridal : prix des modèles d'IA et des abonnements d'équipe, notes aux classements, offres des éditeurs, chemins de réglages dans leurs consoles, calendrier réglementaire. **Version 2026-10-09.**

Chaque valeur porte sa source, son adresse et la date où elle a été lue. Ce qui n'a pas été trouvé reste vide : rien n'est estimé.

La source canonique, à jour, est le site : https://meridal.fr/apprendre/releves-en-telechargement/

## Ce que contient ce dépôt

| Relevé | Contenu | Relevé du |
|---|---|---|
| Marché des modèles et abonnements | `data/marche.json` | 8 octobre 2026 |
| Classements des modèles | `data/classements.json` | 8 octobre 2026 |
| Offres et prix des éditeurs | `data/offres.json` | 7 octobre 2026 |
| Réglages des consoles | `data/reglages.json` | 7 octobre 2026 |
| Calendrier réglementaire | `data/calendrier.json` | 8 octobre 2026 |
| Taux d'hallucination | `data/hallucinations.json` | 8 octobre 2026 |
| Tâches de tableur | `data/spreadsheetbench.json` | 8 octobre 2026 |
| Assistants de code | `data/assistants-code.json` | 9 octobre 2026 |
| Automatisation : arrêts, reprises, alertes | `data/automatisation-service.json` | 8 octobre 2026 |
| Bibliothèques pour agents | `data/bibliotheques-agents.json` | 8 octobre 2026 |
| Cache et traitement par lots | `data/cache-lots.json` | 8 octobre 2026 |
| Ce que chaque outil lit | `data/lecture-documents.json` | 7 octobre 2026 |
| Confidentialité des assistants | `data/confidentialite.json` | 7 octobre 2026 |
| Documents : limites des outils | `data/documents-outils.json` | 7 octobre 2026 |
| Extraction de documents : prix | `data/extraction.json` | 7 octobre 2026 |
| Hébergeurs d'une application | `data/hebergeurs.json` | 7 octobre 2026 |
| Modèles chinois et données | `data/modeles-chinois.json` | 8 octobre 2026 |
| Modèles d'embeddings | `data/embeddings.json` | 7 octobre 2026 |
| Observabilité des appels | `data/observabilite.json` | 8 octobre 2026 |
| Options pour les documents | `data/options-documents.json` | 7 octobre 2026 |
| Outils d'automatisation | `data/automatisation-outils.json` | 8 octobre 2026 |
| Services d'IA en Europe | `data/souverainete.json` | 8 octobre 2026 |

- `data/<nom>.json` : le relevé tel que les pages de la rubrique le lisent. Les clés restent celles d'origine : en anglais pour le marché et les classements, en français pour les autres.
- `data/<nom>.csv` : un CSV par tableau, en UTF-8, la virgule comme séparateur. Une cellule qui contient une liste ou un objet la porte en JSON.
- `datapackage.json` : la description du jeu (standard [Data Package](https://datapackage.org/)), avec le poids, l'empreinte et, pour chaque CSV, le nom et le type de chaque colonne.
- `CHANGELOG.md` : ce qui change d'un relevé à l'autre.

## Licence

- **Sous licence [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.fr)** : le choix des faits, leur mise en forme, les notes et les textes de Meridal. Reprenez-les en citant Meridal.
- **Restent à leurs sources** : un prix, une note de classement, un chemin de menu appartiennent à celui qui les publie. Chaque valeur donne sa source, pour qu'on la cite aussi.

Le texte de la licence est dans `LICENSE`.

## Citer

> Meridal, *Relevés de la rubrique Apprendre*, version 2026-10-09. https://doi.org/10.5281/zenodo.23334642. https://meridal.fr/apprendre/releves-en-telechargement/

Un fichier `CITATION.cff` est fourni : GitHub en tire un bouton « Cite this repository ».

## Interroger les relevés par un agent

Un serveur MCP en lecture seule, sans authentification, répond à l'adresse https://meridal.fr/mcp : prix d'un modèle, abonnements d'équipe, notes à un test, chemin d'un réglage, dates des relevés. Chaque réponse porte sa source et sa date.

```bash
claude mcp add --transport http meridal https://meridal.fr/mcp
```

## Qui publie

Meridal est un cabinet de conseil et de formation à l'IA pour les PME, édité par Oscar Grima. Meridal vend du conseil : c'est un intérêt, et vous pouvez le peser en lisant ces relevés. Chaque relevé donne ses sources, vérifiables sans passer par Meridal.

## Limites

- Un fichier est le relevé de sa date : un prix change, une offre disparaît. Rouvrez le fichier avant de vous appuyer sur une valeur.
- Les relevés bruts des recherches, avec la citation de chaque source, sont gardés par Meridal et ne sont pas publiés ici.
- Les relevés couvrent le marché lu à leur date, pas un marché complet à tout instant : chaque relevé dit ce qui lui manque (clés `gaps`, `lacunes`, `caveats`).
