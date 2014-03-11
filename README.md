sources
=======

Ce répertoire contient les sources XML-TEI de l'édition numérique des cours d'Antoine Desgodets

L'édition des cours d'Antoine Desgodets a été produite dans le cadre de l'ANR Desgodets, . Elle est consultable en ligne à l'adresse suivante : [www.desgodets.net](http://www.desgodets.net)

Ces sources sont mises à disposition sous [licence CC-BY-SA](LICENSE.md).


Structure du répertoire
------------

Ce répertoire "desgodetsTei" contient l'arborescence de fichiers concernant l'édition des Cours de Desgodets réalisée dans le cadre du projet d'ANR Desgodets (http://www.desgodets.fr
).
Le responsable scientifique de l'ANR est Robert Carvais (rcarvais@noos.fr).
La production des fichiers XML-TEI a été coordonnée par Emmanuel Château (emchateau@laposte.net).

A la racine de ce répertoire, on trouve un fichier XML-TEI intitulé "desgodets.tei.xml" qui concerne l'ensemble du corpus des Cours de Dedgodets.
Le sous-répertoire intitulé "schema" comporte les schémas RelaxNG de l'édition. Le sous-sous-répertoire documentation comporte la documentation du schéma dans différents formats.
Le sous-répertoire "documentation", comporte la documentation générale du projet.
Le sous-répertoire "xslt" comporte les feuilles de styles utilisées pour les transformations utiles à la production des textes.

Le sous-répertoire intitulé "divs" comporte les sous-fichiers XML-TEI concernant ce corpus :
- les glossaires des termes techniques et juridiques "desgodetsGlossariumTechnicae.tei.xml" et "desgodetsGlossariumJuris.tei.xml",
- les index des noms de lieux, de personnes et de matières, respectivement intitulés "desgodetsIndexLocorum.tei.xml", "desgodetsIndexNominum.tei.xml" et "desgodetsIndexRerum.tei.xml",
- le fichier de références bibliographiques intitulé "desgodetsBiblio.tei.xml"

Les sous-répertoires "c", "l", "o", et "t", contiennent les fichiers relatifs à chaque Cours identifiés par leur initiale ("c" pour les Commodités, "l" pour les Lois, "o" pour les Ordres, "t" pour les Toisés).
A la racine de chacun de ces sous-répertoire, se trouve un fichier XML-TEI, du type "desgodetsC.tei.xml", qui concerne le corpus du cours concerné.
Chacun de ces sous-répertoire comporte également un sous-sous-répertoire intitulé "divs" qui contient les sous-fichiers XML-TEI relatifs au corpus de chacun des cours :
- fichiers d'alignement des témoins du texte, p.ex. "desgodetsAlignTexts.tei.xml"
- fichiers d'alignement des figures des différents témoins, p.ex. "desgodetsAlignFigures.tei.xml"

Les fichiers relatifs à chaque témoin du cours conservés sont placés dans des sous-sous-répertoires dont le nom est composé de l'initiale du cours, suivi d'un numéro d'ordre.
Chacun de ces sous-sous-répertoires (p.ex. c1, c2) peut contenir un répertoire "divs" dans lequel on place :
- les fragments de fichiers XML-TEI relatifs à l'établissement du texte : p.ex. "desgodetsC1Figures.tei.xml",
- ainsi que les fichiers de notes pour le témoin édité : fichiers de notes historiques, p.ex. "desgodetsNotesHistorical.tei.xml", fichiers de notes critiques, p.ex. "desgodetsNotesCritical.tei.xml"
Les répertoires "facs" contiennent les facsimile des témoins concernés.

Les fichiers des parties éditoriales du site se trouvent dans les répertoires "varia", "edition", "meetings". On retrouve ici la même structure de fichier : un fichier corpus rassemble les différentes pages de chaque section. pour plus de commodité, les fichiers XML-TEI de chacune des pages ont en revanche été réunis dans un seul sous-répertoire "texts" qui contient un sous-répertoire "divs" unique pour toutes les parties séparées de fichier.
À la racine, un répertoire "files" est destiné à recevoir les pièces jointes téléchargeables des pages éditoriales du site, et un répertoire images les illustrations.

NE PAS TENIR COMPTE DES FICHIERS COMPORTANT TROIS CHIFFRES DANS LEUR INTITULE AVANT L'EXTENSION DE NOM DE FICHIER
p.ex. "desgodetsAlignTexts.002.tei.xml", ce sont des fichiers de version pour l'archivage.



Remarques et problèmes
------------

On utilise la gestion des [issues][issues] du service GitHub pour discuter des problèmes rencontrés avec l'encodage ou la transcription.

[issues]: https://github.com/desgodets/sources/issues
