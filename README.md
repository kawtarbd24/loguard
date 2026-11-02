# loguard
Application web qui collecte les journaux de connexion d’un site, détecte les comportements suspects (brute force, connexions inhabituelles) grâce à un modèle d’IA, et présente des alertes classées par gravité à un administrateur.

Utilisateurs : administrateurs et analystes sécurité.
IA : détection d’anomalies (Isolation Forest, Python), comparée à une détection par règles simples.
Technologies : Symfony, Python (FastAPI), SQL, Docker.
