# PROGRAMMATION-ORIENTEE-OBJET

## Description du projet

Ce projet est une application console en C# simulant un parcours d'épreuves où un Participant doit traverser différentes salles (SalleTest, SalleDelegue, SalleException). 
L'architecture repose sur l'utilisation intensive des délégués, des événements, de la réflexion et de la gestion des exceptions pour déverrouiller des passages.

## Objectifs

- **Maîtrise de la POO** : Implémenter des interfaces (IRepondreEpreuveSalles) et l'héritage de classes abstraites.

- **Communication entre Objets** : Utiliser les événements pour faire interagir la "foule" (spectateurs) avec les actions techniques sur les portes.

- **Gestion Robuste des Exceptions** : Dans la SalleException, le participant doit trouver la bonne clé en gérant différents types d'erreurs (FormatException, ArgumentOutOfRangeException, etc.) pour réussir à ouvrir la porte.

  ## Problèmes

  - Complexité du MRD (Modèle Relationnel) : Difficulté à structurer les relations entre les classes pour refléter un modèle logique fluide .

  ---------------------------------------------
  CONÇU LE 05 DECEMBRE 2025 - 19 DECEMBRE 2025
