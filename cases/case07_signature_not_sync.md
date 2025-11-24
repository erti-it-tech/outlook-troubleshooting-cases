# Cas 07 — Signature Outlook non synchronisée

## Symptômes
- Signature visible sur un poste mais pas un autre

## Analyse
Problème de roaming signature

## Diagnostic
1. Vérifier chemins :
   - Local :
     ```
     %APPDATA%\Microsoft\Signatures
     ```
   - Cloud (M365)

## Solution appliquée
- Synchronisation manuelle
- Copie dossier Signatures
- Vérifier option “Signature cloud”

## Vérification finale
- Signature identique sur tous les postes
