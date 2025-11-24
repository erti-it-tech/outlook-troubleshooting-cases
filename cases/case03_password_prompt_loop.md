# Cas 03 — Outlook demande le mot de passe en boucle

## Symptômes
- Demande de mot de passe répétée
- Authentification impossible

## Analyse
Causes possibles :
- Credential Manager corrompu
- Problème M365/Exchange Online
- Mauvais token d’authentification

## Diagnostic
1. Supprimer les anciennes entrées :
control.exe keymgr.dll

2. Vérifier la connectivité :
Test-NetConnection outlook.office365.com -Port 443

3. Vérifier MFA / mot de passe expiré.

## Solution appliquée
- Nettoyage Credential Manager
- Redémarrage Outlook
- Si besoin : réinitialisation mot de passe + re-authentification

## Vérification finale
- Connexion stable sans pop-up
