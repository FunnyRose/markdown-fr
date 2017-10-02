# Les titres

Comme nous commençons tout juste à écrire un document markdown, on doit en premier ajouter un titre et quelques sous-titres.

Markdown supporte deux styles de titres, **Setext** et **atx**.

**Les titres en style Setext** sont _"soulignés"_ en utilisant le signe égal (pour le plus grand des titres) et le signe tiret (pour le second niveau de titres). Par exemple :

```
Voici un H1
=============

Voici un H2
-------------
```

N'importe quel nombre de = ou de - marchera.

**Le style Atx** utilise 1 à 6 dièse(s) au début de la ligne, qui correspond au niveau de titre entre 1 et 6. Par exemple :

```
# Voici un H1

## Voici un H2

###### Voici un H6
```

En option, tu devrais "fermer" les titres atx. C'est purement esthétique - tu peux les utliser si tu trouves que c'est plus lisible. Fermer en utilisant les dièses ne nécessite pas le même nombre de dièses utilisés pour ouvrir le titre. (C'est bien le nombre du début des dièses qui détermine la grandeur du titre.) :

```
# Voici un H1 #

## Voici un H2 ##

### Voici un H3 ######
```


---

Voici pour finir un petit quizz sur les titres markdown.
Here's a quiz about markdown titles.

Sélectionne le bon titre :
- [x] `# coucou`
- [ ] `#coucou`

> Les titres ont besoin d'un espace entre les caractères hash et le text.

Sélectionne la bonne solution :
- [ ]  
```
test
########
```
- [x]   
```
test
=======
```

> Seulement '=' et '-' sont acceptés pour le surlignement d'un titre.

---


