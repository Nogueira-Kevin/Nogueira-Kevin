### Kevin Nogueira — développeur d'applications et d'automatisations · Suisse

Je construis des applications qui tournent **en production** et je les maintiens :
je trouve les bugs, je les corrige sans casser ce qui marche, et je le prouve par des tests.
Je développe **avec l'IA** — elle écrit vite ; moi, je conçois, je vérifie et je réponds du résultat.

---

#### Trois preuves, en trente secondes

**⚙️ Automatiser — de 3 jours à quelques secondes**
Préparer un événement (groupe WhatsApp, liste e-mail, rappels J-7, J-1, jour J) prenait des jours à la main.
Sur [Neuraframe](https://neuraframe.ch), ma plateforme SaaS (37 organisations inscrites), c'est automatique dès l'enregistrement de l'événement.
→ [Voir le code et les tests](https://github.com/Nogueira-Kevin/neuraframe-event-automation)

**🔒 Sécuriser — des clés secrètes qui partaient vers le navigateur**
En auditant les réponses de mon API, j'ai trouvé la clé Stripe *live* et des mots de passe SMTP renvoyés en clair au navigateur de l'administrateur.
Corrigé en production le jour même : les secrets ne quittent plus le serveur, l'interface n'en voit qu'une forme masquée.

**🧪 Fiabiliser — un bug d'envoi trouvé en revue de code**
Un rappel prévu à J-7 pouvait partir tout de suite. J'ai isolé la logique de planification, corrigé, puis écrit
16 tests (dont le passage à l'heure d'été) qui tournent à chaque envoi sur GitHub.
→ [Le correctif et ses tests](https://github.com/Nogueira-Kevin/neuraframe-event-automation/tree/main/tests)

---

#### Comment je travaille avec l'IA

1. **Je décide** de l'architecture et de ce qui doit être vrai à la fin.
2. **L'IA écrit** le code ; je le relis comme celui d'un collègue.
3. **Je vérifie** : tests qui échouent si on casse la protection, contrôle de la production avant et après.
4. **Je réponds** de ce qui tourne en ligne : sauvegarde avant chaque modification, retour arrière prêt.

#### Ce que j'apporte en plus du code

- **Électronicien CFC** (2021-2024) : diagnostic méthodique, calibration et tests de matériel avant livraison.
- **Analyste comportemental certifié** : je fais passer et j'interprète des tests de profil, je forme des analystes —
  et j'ai développé mon propre outil de tests avec rapports PDF automatiques.
- **Langues** : français et portugais (C2), anglais (B1-B2).

#### Outils

PHP 8 · MySQL · JavaScript / TypeScript · React · C# / Unity · API REST · WhatsApp (Evolution API) · Stripe · Ollama, LoRA

📫 [LinkedIn](https://www.linkedin.com/in/kevin-nogueira) · kevin.nogueira@neuraframe.ch
