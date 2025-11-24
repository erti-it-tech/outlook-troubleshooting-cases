# Cas 05 — OST corrompu

## Symptômes
- Outlook lent
- Messages d’erreur
- Blocages fréquents

## Analyse
OST inutilisable → recréation nécessaire.

## Diagnostic
1. Réparation rapide Office
2. Test :
sfc /scannow

## Solution appliquée
- Renommer l’OST :
C:\Users%username%\AppData\Local\Microsoft\Outlook*.ost
- Redémarrer Outlook → Outlook recrée un nouveau fichier

## Vérification finale
- Outlook fluide et stable
