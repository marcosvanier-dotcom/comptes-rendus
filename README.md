# Générateur de Comptes Rendus

Outil 100% local (HTML standalone) pour la gestion de comptes rendus d'une cellule de soudage industriel (EDF).

## Comme utiliser

1. Téléchargez le fichier [`ferramenta.html`](ferramenta.html).
2. Ouvrez-le directement dans votre navigateur (double-clic ou `Fichier > Ouvrir`).
3. Toutes les données sont sauvegardées localement dans le `localStorage` de votre navigateur — il n'y a pas de backend, pas de connexion, pas de serveur.

## Import par e-mail via IA (optionnel)

L'outil peut utiliser un fournisseur d'IA (Anthropic, OpenAI ou Gemini) pour aider à importer le contenu des e-mails. Pour l'activer :

1. Cliquez sur **⚙️ Configurer** dans l'outil.
2. Renseignez votre propre clé API du fournisseur choisi.
3. La clé est stockée uniquement dans le `localStorage` de votre navigateur — elle n'est jamais envoyée ailleurs qu'au fournisseur d'IA choisi, directement depuis votre navigateur.

> ⚠️ L'import de fichiers `.pst` est désactivé dans cette version (nécessiterait un backend pour traiter le format binaire).

## Confidentialité

- Aucune donnée n'est envoyée à un serveur tiers, sauf lors d'un appel explicite à l'API d'un fournisseur d'IA que vous avez configuré vous-même.
- Aucun compte, aucune authentification requise.
