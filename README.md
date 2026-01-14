# Projet-final-Algo

## 📌 About / À Propos

Final Project in Algorithm / Data Structure in C. This project consists in modeling a part of the Paris metro from a text file describing its stations and links.
The network is represented by a graph, allowing data analyzes with data structures and classic algorithms.
The main features are :
* Searching a station by its id or name
* Displaying the neighbors of a station
* Calculating the shortest path between two stations (Dijkstra Algorithm)
* Sorting the stations by their degree (number of neighbors)
* Comparing the sort algorithms (comparisons, moves / permutations)

-------------

Projet final en Algorithmie / Structure de données en C. Ce projet consiste à modéliser une partie du métro parisien à partir d’un fichier texte décrivant ses stations et liaisons.  Le réseau est représenté sous forme de graphe pondéré, permettant l’analyse et la manipulation des données à l’aide de structures de données et d’algorithmes classiques.
Les principales fonctionnalités sont :
* Recherche d’une station par identifiant ou par nom
* Affichage des voisins d’une station
* Calcul du plus court chemin entre deux stations (algorithme de Dijkstra)
* Tri des stations par degré à l’aide de plusieurs algorithmes
* Comparaison des algorithmes de tri (comparaisons, déplacements / permutations)

## Environment / Environnement

The program is cut in many files including source code and their headers :
* station.c / .h : evrything that deals with the stations
* edge.c / .h : same for the edges
* tri.c / .h : for all the sort algorithm
* hash.c / .h  : for the hash table
* dijkstra.c / .h : for the Dijkstra Algorithm
* menu.c / .h : for the display of the interactive menu
* main.c : the main file

----------

Le programme est divisé en plusieurs fichiers code source et leurs headers :
* station.c / .h : pour tout ce qui touche de près aux stations
* edge.c / .h : pareil pour les arêtes
* tri.c / .h : pour les algorithmes de tri
* hash.c / .h : pour la hash table
* dijkstra.c / .h : pour l'implémentation de l'algorithme de Dijkstra
* menu.c / .h : pour l'affichage du menu intéractif
* main.c : le fichier main

## 🧱 Data Structures / Structures de données

* Stations are stored in a dynamic array
* Adjacency list to represent the graph
* Hash map to search stations by their names

---------

* Stations stockées dans un tableau dynamique
* Listes d’adjacence pour représenter le graphe
* Table de hachage pour une recherche rapide des stations par nom  

## ⚙️ Compilation

Compile with the Makefile provided whithout additional options as stated

`make`
then generates :

`metro`

---------

La compilation se fait à l’aide du Makefile fourni, sans options supplémentaires comme le demandait l’énoncé.

`make`
qui génère l’exécutable :

`metro`

## ▶️ Execution / Exécution

The programe runs by passing the text file in arguments :


`./metro metro.txt`

A test file was also added to test the program at the end : 

`./metro test.txt`

---------

Le programme s’exécute en passant le fichier texte en argument :

`./metro metro.txt`

Un fichier test a aussi été ajouté pour tester le programme à la fin : 

`./metro test.txt`

## 🧭 Use / Utilisation

An interactive menu shows up and asks what to do : 
1. Display the informations of a station
2. List the neighbors of a station
3. Calculate the shortest path between two stations
4. Display the stations sorted by degree
5. Quit the program

Searches can be made by id or name

-----------

Un menu interactif s'affiche et demande ce qu'il doit faire :
1. Afficher les informations d’une station
2. Lister les voisins d’une station
3. Calculer le chemin minimal entre deux stations
4. Afficher les stations triées par degré
5. Quitter le programme
   
Les recherches peuvent être effectuées par identifiant ou par nom

## 📊 Sort Algorithms implemented / Algorithmes de tri implémentés

* Selection sort
* Insertion sort
* Recursive Quicksort
* Iterative Quicksort

Comparisons are made with counters directly in the program.

--------

* Tri par sélection
* Tri par insertion (avec comptage des déplacements)
* Quicksort récursif
* Quicksort itératif
  
Les algorithmes sont comparés expérimentalement à l’aide de compteurs.
