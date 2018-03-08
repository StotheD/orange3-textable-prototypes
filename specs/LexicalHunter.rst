#################################
Specification widget LexicalHunter
#################################

1 Introduction
**************

1.1 But du projet
=================
Créer un widget pour Orange Textable permettant de détecter des champs lexicaux en fonction de listes de mots préétablies.

1.2 Aperçu des étapes
=====================
* Premiere version de la specification: 15 mars 2018
* Remise de la specification: 23 mars 2017
* Version alpha du projet: 27 avril 2017
* Remise et presentation du projet:  25 mai 2017

1.3 Equipe et responsabilitées
==============================

* Simon Cappelle (`simon.cappelle@unil.ch`_):

.. _simon.cappelle@unil.ch: mailto:simon.cappelle@unil.ch

    - specification
    - code
    - documentation

* Maxime Bony (`maxime.bony@unil.ch`_):

.. _maxime.bony@unil.ch: mailto:maxime.bony@unil.ch

    - illustration
    - code
    - documentation

* Robin Pitteloud (`robin.pitteloud@unil.ch`_):

.. _robin.pitteloud@unil.ch: mailto:robin.pitteloud@unil.ch

    - code
    - documentation
    - debuggage

2. Technique
************

2.1 Dépendances
===============

* Orange 3.4

* Orange Textable 3.0b0

* gensim 0.13.4 (ou 1.0.1 si compatible avec Python 3.4?)

2.2 Fonctionnalités minimales
=============================

* Input : Un ou plusieurs segments

* permettre le choix d'un ou plusieurs "champs lexicaux" parmis ceux proposés par défaut.

* Output : les segments d'entrées formatés en XML afin d'assigner chaque mot trouvé au champs lexical correspondant.

2.3 Fonctionnalités principales
===============================

* Permettre d'importer, modifier et supprimer des listes de champs lexicaux.

2.4 Fonctionnalités optionnelles
================================

* Afficher un aperçu du texte mis en forme (couleur/champs)


2.5 Tests
=========

Interaction du texte de sortie avec le widjet segment de Textable.

3. Etapes
*********

3.1 Version alpha
=================
* L'interface graphique est complètement construite.
* Les fonctionnalités minimales sont prises en charge par le logiciel.

3.2 Remise et présentation
==========================
* Les fonctionnalités principales sont complétement prises en charge par le logiciel.
* La documentation du logiciel est complète.
* Le logiciel possède des routines de test de ses fonctionnalités (principales ou optionnelles).


4. Infrastructure
=================
Le projet est disponible sur GitHub à l'adresse `https://github.com/axanthos/TextablePrototypes.git
<https://github.com/axanthos/TextablePrototypes.git>`_
