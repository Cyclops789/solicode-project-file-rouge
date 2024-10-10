# Besoin

Application de déploiement qui automatise le déploiement d’applications logicielles dans plusieurs environnements (développement, mise en production, production) et fournit une interface conviviale pour les développeurs afin de surveiller les déploiements et assurer des versions sécurisées et fiables.


# Persona : **Alex – développeur DevOps**

#### **Renseignements de base :**
- **Nom** : Alex Johnson
- **Âge** : 32
- **Rôle** : développeur
- **Entreprise** : TechScale Solutions (société de développement de logiciels de taille moyenne)
- **Expérience** : 7 ans de déploiement logiciel.

#### **Objectifs :**
- Rationaliser et automatiser le processus de déploiement pour réduire les interventions manuelles et le temps de déploiement.
- Assurer des déploiements fluides et sécurisés sur plusieurs environnements (développement, mise en scène et production).
- Surveillez la progression du déploiement en temps réel et recevez des notifications instantanées sur les problèmes ou les pannes.
- Annulez facilement les déploiements qui ont échoué pour minimiser les temps d’arrêt et assurer un service continu.
- Intégrer le gestionnaire de référentiels comme GitHub / Gitlab.

#### **Frustrations :**
- Les processus de déploiement manuel sont sujets aux erreurs et prennent du temps.
- Manque de visibilité sur l’état du déploiement en temps réel dans différents environnements.
- Difficulté à suivre l’historique des déploiements et à identifier les problèmes après la diffusion.
- Problèmes fréquents de communication entre les équipes de développement et d’exploitation, entraînant des retards dans les cycles de publication.

##### **Besoins de l’application de déploiement :**
- Un tableau de bord clair et intuitif pour surveiller et gérer les déploiements.
- Automatisation des pipelines CI/CD intégrés à GitHub.
- Notifications en temps réel via Slack ou par courriel pour les déploiements réussis/non réussis.
- Enregistrement détaillé et données historiques sur les progrès du déploiement et les taux de réussite / échec.
- Connexion sécurisée par OAuth ou SSO pour protéger l’accès aux outils de gestion du déploiement.

#### **Scénario :**
Alex travaille dans une entreprise de logiciels en pleine croissance où plusieurs équipes travaillent sur divers projets. Le processus de déploiement actuel comporte beaucoup d’étapes manuelles, et Alex est responsable de s’assurer que les déploiements se déroulent sans heurts. Il passe des heures à suivre l’avancement des déploiements et à coordonner les équipes de développement et d’opérations. Il a besoin d’une application de déploiement qui automatise l’ensemble du processus, lui fournit une visibilité en temps réel, un