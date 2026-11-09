# Kevin Nogueira

Développeur d'applications web et d'automatisations, en Suisse romande.

Formateur et mentor, je perdais des jours à préparer chaque événement à la main, sur plusieurs
logiciels, même avec de l'aide : oublis, erreurs, coordination difficile. J'ai donc construit
**Neuraframe** pour automatiser ce travail, puis je l'ai ouverte à d'autres formateurs.
Je la développe et je l'exploite aujourd'hui.

Je code depuis l'enfance et j'ai approfondi pendant mon CFC d'électronicien. Je me suis ensuite
formé au coaching et à l'analyse comportementale, et je forme moi-même des analystes : je
construis des outils pour des métiers que je pratique.

## Neuraframe

Plateforme SaaS multi-tenant pour formateurs et organisateurs d'événements (PHP 8, MySQL, React).
Elle automatise le parcours d'un participant : inscription, paiement, accès à la formation,
e-mails, groupe WhatsApp et rappels.

**Préparer un événement : de trois jours à quelques secondes.**
À l'enregistrement d'un événement, le système crée le groupe WhatsApp et la liste e-mail, puis
programme chaque rappel selon le scénario défini dans un éditeur visuel, à l'heure locale de
l'événement. S'il est relancé par erreur, il n'envoie rien deux fois.
[Extrait du code et ses tests](https://github.com/Nogueira-Kevin/neuraframe-event-automation)

**Un incident le jour J.**
Le jour du webinaire automatisé d'une cliente, préparé avec toute une campagne marketing,
l'automatisation n'a pas fonctionné. J'ai d'abord lancé le webinaire par une solution de
contournement manuelle : il a commencé avec dix minutes de retard, sans être reporté.
J'ai ensuite trouvé deux causes : des fichiers de logs qui avaient saturé le stockage du
serveur, et une connexion Google déconnectée côté cliente. J'ai corrigé le processus et ajouté
des vérifications préalables, pour détecter ce type de problème plusieurs heures avant un
événement plutôt que dans l'urgence.

## Autres projets

- **Asaria** : un jeu de rôle en ligne massivement multijoueur, en bêta publique sur
  [playasaria.com](https://playasaria.com). Client Unity en C#, serveur qui fait autorité,
  deux régions.
- **Un outil d'analyse comportementale** : questionnaires de profil et rapport PDF automatique.
  Je l'utilise avec mes clients ; sa finalisation est en cours.
- **Des assistants IA** : des modèles Qwen ajustés (LoRA) et exécutés en local. L'assistant de
  support est en service ; ceux pour les cours et la prise de rendez-vous sont en développement.

## Ma façon de travailler

Je travaille principalement avec des agents IA pour le développement. Je conçois la solution et
l'architecture, je découpe le travail, je relis le code, je le teste et je valide chaque mise en
production. Mes bases en PHP, HTML/CSS et C++ me permettent de comprendre le code et d'y repérer
les erreurs, avec une autonomie variable selon les technologies.

## Formation

- CFC d'électronicien, EPSIC, 2021-2024
- Coach neuropraticien, Académie européenne des neurosciences, 2024
- Coach émotionnel humanisé CEH® (intelligence émotionnelle), 2024
- Analyste HMI, Practitioner PNL, International Behavior Master Analyst, Mentor comportemental, 2024-2026

Français et portugais (C2), anglais (B1-B2).

[LinkedIn](https://www.linkedin.com/in/kevin-nogueira) · kevin.nogueira@neuraframe.ch
