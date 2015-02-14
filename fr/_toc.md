
# Table des matières

* [Sur l'auteur](#sur-l'auteur)
* [Contributions](#contributions)
* [À propos de Sass](#À-propos-de-sass)
      * [Ruby Sass Ou LibSass](#ruby-sass-ou-libsass)
      * [Sass Ou SCSS](#sass-ou-scss)
      * [Autres préprocesseurs](#autres-préprocesseurs)
* [Introduction](#introduction)
      * [Pourquoi un guide de style](#pourquoi-un-guide-de-style)
      * [Avertissement](#avertissement)
      * [Principes fondamentaux](#principes-fondamentaux)
* [Syntaxe & Formatage](#syntaxe-&-formatage)
    * [Chaînes de caractères](#chaînes-de-caractères)
    * [Nombres](#nombres)
        * [Zéros](#zéros)
        * [Unités](#unités)
        * [Calculs](#calculs)
        * [Nombres magiques](#nombres-magiques)
    * [Couleurs](#couleurs)
        * [Formats de couleurs](#formats-de-couleurs)
        * [Couleurs et variables](#couleurs-et-variables)
        * [Éclaircir et obscurcir les couleurs](#Éclaircir-et-obscurcir-les-couleurs)
    * [Listes](#listes)
    * [Maps](#maps)
        * [Déboguer une map Sass](#déboguer-une-map-sass)
    * [Ensemble de règles CSS](#ensemble-de-règles-css)
    * [Ordre des déclarations](#ordre-des-déclarations)
    * [Imbrication des sélecteurs](#imbrication-des-sélecteurs)
        * [Règle générale](#règle-générale)
        * [Exceptions](#exceptions)
* [Conventions de nommage](#conventions-de-nommage)
    * [Constantes](#constantes)
    * [Namespaces](#namespaces)
* [Commentaires](#commentaires)
    * [Écrire des commentaires](#Écrire-des-commentaires)
    * [Documentation](#documentation)
* [Architecture](#architecture)
    * [Composants](#composants)
    * [Le pattern 7-1](#le-pattern-7-1)
        * [Dossier base](#dossier-base)
        * [Dossier layout](#dossier-layout)
        * [Dossier composants](#dossier-composants)
        * [Dossier pages](#dossier-pages)
        * [Dossier thèmes](#dossier-thèmes)
        * [Dossier utilitaires](#dossier-utilitaires)
        * [Dossier vendors](#dossier-vendors)
        * [Fichier principal](#fichier-principal)
    * [Fichier de la honte](#fichier-de-la-honte)
* [Responsive Web Design et points de rupture](#responsive-web-design-et-points-de-rupture)
    * [Nommer les points de rupture](#nommer-les-points-de-rupture)
    * [Gestion des points de rupture](#gestion-des-points-de-rupture)
    * [Utilisation des media queries](#utilisation-des-media-queries)
* [Variables](#variables)
    * [Scoping](#scoping)
    * [Le flag !default](#le-flag-!default)
    * [Le flag !global](#le-flag-!global)
    * [Variables multiples ou map](#variables-multiples-ou-maps)
* [Extend](#extend)
* [Mixins](#mixins)
    * [Les bases](#les-bases)
    * [Listes d'arguments](#listes-d'arguments)
    * [Mixins et préfixes constructeurs](#mixins-et-préfixes-constructeurs)
* [Structures conditionnelles](#structures-conditionnelles)
* [Boucles](#boucles)
    * [Each](#each)
    * [For](#for)
    * [While](#while)
* [Avertissements et erreurs](#avertissements-et-erreurs)
    * [Avertissements](#avertissements)
    * [Erreurs](#erreurs)
* [Outils](#outils)
    * [Compass](#compass)
    * [Systèmes de grilles](#systèmes-de-grilles)
    * [SCSS-lint](#scss-lint)
* [Too Long; Didn't Read](#too-long;-didn't-read)