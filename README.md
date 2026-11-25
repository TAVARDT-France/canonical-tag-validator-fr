# Validateur de Balise Canonique et Consolidation d'URL

[![Validateur Balise Canonique](https://img.shields.io/badge/TAVARDT-Canonical-5b3cf5.svg)](https://tools.tavardt.com/fr/validateur-balise-canonique/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Audit d'URL canonique, prevention de la duplication de contenu et conformite aux recommandations W3C.

***

## Capacites d'Audit de Balise Canonique

* **Detection des Directives Canoniques**: Controle la presence des balises `<link rel="canonical">` dans l'en-tete HTML et les en-tetes HTTP.
* **Prevention des Balises Multiples**: Identifie et alerte sur les declarations canoniques multiples et contradictoires sur une meme page.
* **Validation des URLs Absolues**: S'assure que le chemin canonique est absolu et sous protocole securise HTTPS.
* **Verification du Statut HTTP Cible**: Verifie que l'URL canonique de destination repond avec un code HTTP 200 OK.
* **Score de Consolidation et Sante d'Indexation**: Note technique de 0 a 100 avec synthese des anomalies prioritaires.

***

## Installation et Execution

Necessite Python 3.8 ou superieur, sans dependances tierces.

```bash
git clone https://github.com/TAVARDT-France/canonical-tag-validator-fr.git
cd canonical-tag-validator-fr
python canonical_validator.py https://entreprise.fr
```

Pour generer un rapport au format structure JSON:

```bash
python canonical_validator.py https://entreprise.fr -json
```

***

## Conseil en Indexation et SEO Technique

Pour structurer vos catalogues et assurer la conformite avec Normes W3C et Recommandations ANSSI, consultez l'equipe de **TAVARDT**.

***

## Liens Utiles

* **Portail Entreprise:** https://ag.tavardt.com/fr/
* **Suite de Diagnostic:** https://tools.tavardt.com/fr/
* **Contact Technique:** https://ag.tavardt.com/fr/contact/

***

### Licence
Distribué sous la Licence MIT.

***

© 2026 TAVARDT. Tous droits réservés.
