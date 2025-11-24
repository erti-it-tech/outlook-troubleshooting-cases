# Cas 04 — Impossible d’ajouter une boîte partagée

## Symptômes
- “Impossible d’ouvrir le dossier”
- Accès refusé

## Analyse
Très souvent lié aux permissions.

## Diagnostic
1. Vérifier droits dans Microsoft 365 Admin :
   - Full Access
   - Send As (optionnel)

2. Synchronisation :
outlook.exe /updatefolders

## Solution appliquée
- Ajout des permissions
- Attente propagation 5–15 min
- Ajout manuel via :
Fichier → Paramètres du compte → Modifier → Plus de paramètres → Avancé

## Vérification finale
- Mailbox visible dans Outlook
