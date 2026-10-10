# Magistra pour Windows

Magistra aide les enseignants à préparer leurs cours, exercices et évaluations avec une IA locale ou une API personnelle optionnelle.

**[Télécharger Magistra pour Windows](https://github.com/juanrobin09-stack/Magistra-Downloads/releases/latest/download/Magistra-Setup.exe)** · **[Découvrir Magistra](https://www.mag-istra.fr)**

Ce dépôt contient uniquement les téléchargements et leur documentation. Le code de l’application est conservé dans un dépôt privé.

## Installation

1. Téléchargez l’installateur pour Windows 10 ou 11, 64 bits.
2. Ouvrez le fichier et suivez l’installation. L’installateur n’est pas encore signé numériquement : Windows SmartScreen peut afficher un avertissement. Vérifiez la provenance du fichier et son empreinte avant de l’exécuter.
3. Ouvrez Magistra depuis le menu Démarrer ou le raccourci du Bureau.

Les [versions publiées](https://github.com/juanrobin09-stack/Magistra-Downloads/releases) comprennent l’installateur, une archive de l’application et le fichier `SHA256SUMS.txt` permettant de vérifier leur intégrité. `Magistra-Setup.exe` et l’installateur portant le numéro de version sont le même fichier.

## Brancher une vraie IA

Dans l’application Windows, choisissez **Activer l’IA**. Magistra prépare le moteur local et un modèle adapté à votre ordinateur. La taille du téléchargement est indiquée avant de commencer ; cette préparation nécessite une connexion Internet et plusieurs Go d’espace libre.

Une fois le moteur prêt, les générations locales s’exécutent sur votre ordinateur. Relisez et adaptez les contenus avant de les utiliser avec vos élèves ou étudiants.

## Utiliser une clé API personnelle

Depuis la version 2.0.8, ouvrez **Réglages → Intelligence artificielle → IA avec une clé API personnelle**. Choisissez **OpenAI, Mistral, Gemini ou Anthropic**, collez votre clé, puis cliquez sur **Enregistrer et utiliser l’API**. Aucun moteur ni modèle local n’est nécessaire pour cette option.

La clé est masquée et chiffrée sur cet ordinateur. Une seule configuration en ligne est conservée : changer de fournisseur remplace la précédente. Le bouton **Utiliser l’IA locale** conserve la clé ; **Supprimer la clé API** efface cette configuration.

Le mode API nécessite Internet et envoie au fournisseur choisi les consignes et les extraits de documents utilisés pour générer. Les frais et quotas dépendent de votre compte API. L’IA locale reste disponible sans clé.

## Mises à jour

La version **2.0.9** corrige le téléchargement intégré des mises à jour sous Windows. Si vous utilisez **2.0.7 ou 2.0.8**, téléchargez et ouvrez le dernier installateur une fois depuis [le site Magistra](https://www.mag-istra.fr/telecharger) pour récupérer ce correctif. Enregistrez votre travail et fermez Magistra avant de l’ouvrir ; les données enregistrées, les réglages et les modèles sont conservés.

Les versions corrigées contrôlent chaque redirection officielle et vérifient la taille et l’empreinte SHA-256 du fichier avant son ouverture. Si l’installation intégrée échoue, un bouton permet de télécharger depuis le site.

## Contact et notices

Magistra, créé par Juan Robin · Un projet [FutureAI](https://futurai.space).

Contact : [juanrobin89@gmail.com](mailto:juanrobin89@gmail.com). Pour signaler une faille de sécurité, contactez directement l’éditeur sans publier de détails dans un espace public.

Les notices de licence applicables au logiciel et à ses composants accompagnent les fichiers distribués. Les installateurs déjà publiés sont conservés à l’identique.
