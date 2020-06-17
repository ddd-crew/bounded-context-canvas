# Caractéristiques du modèle

Un modèle peut être défini par un nombre de caractéristiques différentes. Passez en revue la liste ci-dessous et choisissez l'élément qui s'applique au contexte sur lequel vous travaillez ou trouvez-en une nouvelle !


| Caractéristique | Heuristique |
|---|---|
| Specification/Draft Model | Produit un document qui décrit un job ou une requête qui doit être exécutée. Ex: Un planificateur de campagne de pub |
| Execution Model | Exécute un job. Ex: Un moteur de campagne de pub |
| Audit/Metrics Model | S’occupe d'analyser les résultats de l’exécution d’un job. Ex: Statistiques d'une campagne de pub |
| Approver | Reçoit des requêtes et détermine s’il doit les faire passer à l’étape suivante du processus. Ex: Une vérification d’opération frauduleuse |
| Enforcer | S’assure que d’autres contextes se chargent bien de certaines opérations. Ex: Un contexte “enforcer” RGPD s’assure que tous les contextes suppriment les données d’un utilisateur |
| Octopus Enforcer | Garantit que tous les contextes du système respectent tous une règle standard. Ex: RGPD (comme ci-dessus) |
| Interchanger | Opère la traduction de plusieurs Langages Ubiquitaires |
| Gateway | Se trouve en bordure de système et gère les communications entrantes et sortantes. Ex: IoT Message Gateway |
| Gateway Interchange | La combinaison d’une Gateway et d’un Interchanger |
| Dogfood Context | Simule l'utilisation du contexte coeur de métier . Ex: Marque blanche |
| Bubble Context | Fournit un nouveau modèle plus propre en remplaçant un contexte legacy  |
| Autonomous Bubble | Un “Bubble Context” avec son propre espace de stockage (synchronisation nécessaire avec le legacy) |
| Brain Context (anti-pattern) | Contient un grand nombre de règles métier dont beaucoup d’autres contextes dépendent. Ex: Un moteur de règle avec toutes les règles du domaine |
| Funnel Context | Reçoit des documents de plusieurs contextes en amont et les passe à un autre contexte en aval, dans un format standardisé (après avoir appliqué ses propres règles) |
| Engagement Context | Fournit les fonctionnalités clés pour l’attractivité et gérer la rétention. Ex: Contexte de conseil financier gratuit |