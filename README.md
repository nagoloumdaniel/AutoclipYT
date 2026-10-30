# AutoclipYT

> **Projet en conception : aucun code n'est livré pour l'instant.** Ce dépôt ne contient que la présentation du projet. Le cahier des charges sera ajouté dans `docs/`.

## Objectif

Concevoir un studio éditorial « sans visage » assisté par IA pour des chaînes YouTube (science, inventions, technologies, innovations) : de l'idée au script sourcé, storyboard, voix off, visuels, montage, sous-titres et exports 16:9 / 9:16, piloté depuis **Telegram**.

Principe directeur : automatiser la production, mais **garder une validation humaine avant toute publication**.

## Périmètre prévu

- Idées et tendances, recherche et registre de sources.
- Script éditorial et vérification factuelle.
- Storyboard, visuels (SVG, graphiques, Manim, Blender), voix off par TTS.
- Montage et sous-titres (FFmpeg), vidéos longues et Shorts.
- Titres, description, chapitres, mention de divulgation IA.
- Bot Telegram : création, suivi, validation, calendrier.
- Plus tard : upload privé puis programmation, analytics.

## Architecture cible (prévue, non implémentée)

| Couche | Technologies envisagées |
|---|---|
| Orchestration | Python 3.12+, FastAPI si API, file de jobs, SQLite |
| Bot | aiogram ou python-telegram-bot |
| Voix | TTS interchangeable (Gemini TTS, repli Piper) |
| Visuels / montage | SVG, Manim, Blender (optionnel), FFmpeg |

Architecture « provider-agnostic » : modèles de langage, TTS et moteurs de rendu sont des fournisseurs interchangeables.

## Avertissements

- **Droits des contenus sources** : images, sons, musiques, polices et modèles 3D doivent avoir une provenance et des droits clairs ; aucune reprise de contenus de tiers sans autorisation.
- **Conditions d'utilisation** : respecter les CGU et règles de YouTube (contenu original, divulgation IA, monétisation) et de Telegram. Aucune publication en masse ni contournement des règles.
- Aucune promesse de revenus ni d'éligibilité à la monétisation.

## État d'avancement

Phase : **cadrage / spécification**. Aucune fonctionnalité n'est disponible.

## Licence

Aucune licence n'est définie : **tous droits réservés par défaut**. Une licence (MIT pour un projet ouvert, ou licence propriétaire) pourra être choisie plus tard.
