# Cas 01 — Outlook ne s’ouvre pas / reste bloqué au lancement

## Symptômes
- L’utilisateur double-clique sur Outlook.
- Rien ne se passe OU Outlook affiche “Chargement du profil…” indéfiniment.

## Analyse
Problème fréquent lié :
- au volet de navigation (Navigation Pane),
- à un profil corrompu,
- à une extension défaillante.

## Diagnostic
1. Test via exécution :
outlook.exe /safe
→ Si Outlook s'ouvre, un add-in est en cause.

2. Reset du volet de navigation :
outlook.exe /resetnavpane

3. Vérification du profil Outlook via :
- Panneau de configuration → Mail → Profiles

4. Événements Windows (Event Viewer) → `Application`

## Solution appliquée
- Reset du volet de navigation
- Désactivation des add-ins
- Si non fonctionnel : recréation complète du profil

## Vérification finale
- Outlook démarre normalement
- Aucun message d’erreur

