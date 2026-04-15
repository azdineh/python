# Cours Python - Sujets 2026


## Fonctionnement de Python
- Langage interprété vs compilé  
- Avantages et inconvénients  
- Types d’erreurs :
  - Erreur syntaxique  
  - Erreur sémantique  

---

## Les bases du langage Python
- Instructions de base :
  - `print()`
  - `input()`  
- Affectation des variables  
- Typage dynamique  

---

## Manipulation des types de données
- Conversion de types :
  - int()
  - float()
  - str()  
- Concaténation  
- f-string :
  - Formatage des nombres  
- Affichage avancé :
  - `sep`
  - `end`

---

## Les listes en Python
- Définition  
- Caractéristiques :
  - Ordonnée
  - Modifiable  
- Accès :
  - Index
  - Slicing  
- Fonctions principales 

---

## Les boucles
- Boucle `for`  
- Parcours d’une liste  
- Fonction `range()`  
- Fonction `enumerate()`
- Fonction: `enumerate()`


---

## Les chaînes de caractères
- Définition  
- Accès par index  
- Slicing  
- Fonctions importantes :
  - `split()`
  - `join()`  

---

## Les fonctions en Python
- Définition  
- Création d’une fonction  
- Paramètres et retour  
- Types de fonctions :
  - Sans paramètre
  - Avec paramètres
  - Avec valeur par défaut  
- Portée des variables :
  - Locale
  - Globale  
- Modularité (utils.py / main.py)

---

## Les collections en Python
- Liste  
- Tuple  
- Dictionnaire  
- Set  
- Comparaison entre les structures  

---

## Dictionnaires et JSON
- Structure clé → valeur  
- Avantages des dictionnaires  
- JSON :
  - Sérialisation (dump, dumps)
  - Désérialisation (load, loads)
  - Cas d’utilisation :
    - API
    - Stockage de données

---

## Programmation fonctionnelle
- map()
- filter()
- reduce() 

---

## Context Manager (Gestion de contexte)
- Définition  
- Utilisation du mot-clé `with`  
- Gestion automatique des ressources (fichiers, connexions)

---

## Visibilité des variables (Scope)
- Variable locale  
- Variable globale  

---

## Effet de bord (Side Effect)
- Définition  
- Problème lors de l’import  
- Utilisation de :
```python
if __name__ == "__main__":
```

---

## Listes et dictionnaires par compréhension

## List comprehension
```python
liste = [expression for element in iterable if condition]

---

## Encodage des fichiers (open)
L’encodage dépend du système d’exploitation :  
- Windows → souvent `cp1252`  
- Linux / Mac → souvent `utf-8`  
```python
with open("fichier.txt", "r", encoding="utf-8") as f:
    contenu = f.read()

---
## Programmation Orientée Objet (POO) 
