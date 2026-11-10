# velo-app

Page mobile (HTML unique) pour armer/désarmer la surveillance du vélo et voir sa dernière position.

- Aucun secret dans le code : au premier lancement la page demande les topics ntfy et le jeton, et les garde dans le localStorage du navigateur (bouton « Oublier »).
- Les commandes sont signées en HMAC-SHA256 (le jeton n'est jamais transmis).
