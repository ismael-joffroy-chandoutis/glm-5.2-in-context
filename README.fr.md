[English](README.md) · **Français**

# GLM-5.2 in Context

Une analyse technique indépendante (juin 2026) comparant le modèle en poids ouverts **GLM-5.2** (Z.ai) à la frontière propriétaire (Claude Opus 4.8, GPT-5.5, Gemini 3.1 Pro, Claude Fable 5). Elle couvre les benchmarks standardisés, une évaluation multi-modèles en aveugle sur une tâche d'écriture créative, la capacité par type de tâche, la censure et la confidentialité, la viabilité de l'inférence locale sur Apple Silicon, et l'économie de l'inférence.

- Article : [`paper.md`](./paper.md) (en anglais)

## Résumé

GLM-5.2 est le modèle en poids ouverts le plus fort à ce jour et une véritable avancée de capacité, mais il reste proche de la frontière plutôt qu'à son niveau (Artificial Analysis Intelligence Index v4.1 : 51 contre 56 pour Opus 4.8). Il atteint une quasi-parité sur le codage borné tout en accusant un retard sur l'écriture littéraire, le travail agentique à long horizon, la mémorisation de long contexte et la multimodalité (il est uniquement textuel). L'auto-hébergement local du modèle de 744 milliards de paramètres est limité par le débit de préremplissage (prefill) plutôt que par la mémoire. Pour des charges de travail mixtes, un routage hybride l'emporte sur une substitution totale, et un achat matériel local devrait être reporté à la prochaine génération d'Apple Silicon.

## Note de méthode

Les chiffres de benchmark attribués aux éditeurs de modèles sont signalés comme auto-déclarés dans l'article. Les chiffres d'indice standardisés reflètent l'instantané de l'Artificial Analysis Intelligence Index v4.1 en vigueur en juin 2026 et peuvent évoluer avec des révisions ultérieures. L'évaluation d'écriture créative est rapportée sous forme abstraite ; le matériau de la tâche sous-jacente n'est pas divulgué.

## Licence

Texte et figures : CC BY-NC-ND 4.0. Voir [`LICENSE`](./LICENSE).

Par [Ismaël Joffroy Chandoutis](https://ismaeljoffroychandoutis.com).
