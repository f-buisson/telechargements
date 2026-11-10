# Téléchargements f-buisson

Les installeurs Windows **certifiés** des logiciels f-buisson, et rien d'autre : ce dépôt ne contient ni code source, ni données, ni configuration.

- Site officiel, offres et conditions générales : <https://f-buisson.com>
- Chaque installeur est annoncé sur le site avec sa taille et son empreinte SHA-256. **Le site fait foi** : comparez l'empreinte du fichier reçu avant de l'ouvrir.

## Vérifier un installeur

Dans PowerShell, depuis le dossier du téléchargement :

```powershell
Get-FileHash .\PlanCaisse-Setup-9.4.0.exe -Algorithm SHA256
```

L'empreinte affichée doit être exactement celle du site et des notes de la version.

## Avertissement de Windows

Les installeurs ne sont pas encore signés. Windows SmartScreen peut afficher « Windows a protégé votre ordinateur ». Après avoir comparé l'empreinte, choisissez « Informations complémentaires », puis « Exécuter quand même ».

## Utilisation

L'utilisation des logiciels est soumise aux conditions générales publiées sur <https://f-buisson.com>. Tous droits réservés.

---

## f-buisson downloads (English)

Certified Windows installers for f-buisson software, and nothing else: no source code, no data, no configuration.

Each installer is listed on <https://f-buisson.com> with its size and SHA-256 fingerprint. The website is the reference: check the fingerprint of the file you received (`Get-FileHash <file> -Algorithm SHA256`) before running it. The installers are not code-signed yet, so Windows SmartScreen may warn you. Use is governed by the terms published on the website. All rights reserved.
