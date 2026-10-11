# Journal des relevés

Ce qui change d'un relevé à l'autre dans `marche.json` et `classements.json`, le plus récent en tête. Chaque changement de prix ou de note a été vérifié à sa source avant d'être publié.

## Relevé du 8 octobre 2026

Le relevé du mois, fait par deux recherches en parallèle sur le même cahier des charges,
puis comparé : chaque écart entre les deux a été tranché à la source. 40 modèles d'API et
9 abonnements d'équipe (`marche.json`) ; 22 tests, 28 modèles et 382 notes
(`classements.json`). Les 377 notes du relevé précédent sont inchangées à leur source.

- **Nouveaux modèles** : Claude Haiku 5.5 (Anthropic, sorti le 7 octobre 2026), 0,10 $ et
  0,50 $ par million de tokens jusqu'à 100 000 tokens par demande, le dixième de Haiku 4.5 ;
  Muse Glimmer 30B (Meta, open weight sous licence Apache 2.0, sorti en août 2026, absent
  du relevé précédent).
- **Claude Haiku 4.5** : passé en ancien modèle (« Legacy ») chez Anthropic.
- **Prix** : la lecture du cache de Claude Sonnet 5.5 passe de 0,20 $ à 0,10 $ (page des
  prix d'Anthropic, relue le 8 octobre) ; prix du cache ajoutés pour Amazon Nova 2 Lite,
  Seed 2.1 Turbo et Qwen3.8-Max, lus chez l'éditeur, et pour Command A+, chez OpenRouter.
- **Mistral Large 4** : compté fermé pour l'instant. La page du modèle le dit open weight,
  mais le journal de Mistral annonce les poids pour plus tard et aucun dépôt public n'existe.
- **Command A+** : sorti le 20 mai 2026, open weight sous licence Apache 2.0, fenêtre de
  128 000 tokens et sortie de 64 000, d'après la documentation de Cohere (OpenRouter
  additionne les deux : 192 000).
- **Licences** : ajoutées pour Gemma 4 31B et Ministral 3 14B (Apache 2.0).
- **Hébergement en Europe** : revu pour les Claude sur Amazon Bedrock (inférence répartie
  entre régions européennes, Paris comprise ; pas de traitement dans une seule région de
  l'Union), pour MAI-Thinking-1 et Qwen3.8 ; inchangé ailleurs.
- **Abonnements** : Claude Team inclut depuis le 7 octobre 2026 des crédits d'API chaque
  mois (20 $ par siège Standard, 100 $ par siège Premium, 500 $ au plus) ; prix de Google
  Workspace en euros (6,80 €, 13,60 €, 21,10 € HT) ; Mistral Vibe Team à 29,99 € TTC
  par personne et par mois sur sa page française.
- **Nouvelles notes** : 5, pour Claude Haiku 5.5. Artificial Analysis : indice 43,4 ;
  HLE 44,39 % ; Terminal-Bench 4.0 32,83 % ; Omniscience 10,67. Anthropic, mesure de
  l'éditeur : OSWorld 2.1, note partielle, 72,4 %.
- **Non vérifiés, donc absents** : Tencent Hy4 et Reflection Beam, vus seulement dans des
  résultats de recherche.

## Vérification du 6 octobre 2026

Les doutes du premier relevé, revus à la source le même jour.

- **Confirmé** : Gemini 3.1 Pro, indice d'Artificial Analysis 29,72 (v4.3.2), seule
  configuration listée ; l'écart vient des tâches d'agent (Terminal-Bench 4.0 : 4 %).
- **Hébergement en Europe** : précisé pour 18 modèles sur Vertex AI et Azure Foundry.
  GPT-6 Astra n'a pas de zone européenne sur Azure ; Gemini 3.1 Pro n'a que le point
  d'accès mondial sur Vertex AI ; les Claude ont la multirégion UE sur Vertex AI.
- **Abonnements** : Claude Team et Enterprise, données stockées aux États-Unis.
- **Source** : GPT-6 Astra à HLE, la note de 57,2 % avec outils est publiée par OpenAI
  (elle était dite citée par Anthropic) ; GPT-6 Astra à OSWorld 2.0, source passée de la
  page de Gemini 4 Argon à la page de lancement d'OpenAI.
- **Nouvelles notes** : 2, mesures de l'éditeur ; gpt-6-1-sol à osworld_2_partial : 71,4 ;
  gpt-6-luna à osworld_2_partial : 52,68.
- **Prix en euros** : seul Google les publie (Gemini 3.8 Flash : 0,66 € et 3,30 €).

## Relevé du 6 octobre 2026

Premier relevé, fait par deux recherches en parallèle sur un cahier des charges écrit.
38 modèles d'API et 9 abonnements d'équipe (`marche.json`) ; 22 tests, 27 modèles et
375 notes, dont 5 mesurées par l'éditeur (`classements.json`). Les doutes ouverts, à
lever au relevé suivant ou avant : l'indice d'Artificial Analysis de Gemini 3.1 Pro, les
prix en euros, l'hébergement en Europe modèle par modèle sur Vertex AI et Azure, les
chiffres publiés par OpenAI (`31`, §3).
