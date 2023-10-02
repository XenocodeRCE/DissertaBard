# ✨DissertaBard

Sur le Github de Eyssette on peut trouver une liste de plus de 18800 sujets de dissertation → [Github - Eyssette](https://github.com/eyssette/sujets-philosophie/)

Le projet ? Faire faire un brouillon à GoogleBard pour chacun des 18800 sujets !

→ Disponible également ici : https://lacavernedeplaton.fr/dissertations/index.php

 ![](https://github.com/XenocodeRCE/DissertaBard/blob/main/sparkle.gif) **INFORMATIONS** 
 

- J'utilise [BardSharp](https://github.com/XenocodeRCE/BardSharp) pour automatiser les requêtes à Google Bard.
- J'utilise [la liste de Cédric Eyssette](https://eyssette.github.io/sujets-philosophie/) pour récupérer des sujets de philosophie (je ne prends QUE les questions et je passe même les sujets avec citation, arbitrairement)
  - En fait j'ai copié la liste dans `sujets.txt`, vous avez les brouillons sous format json dans le dossier "docs", et le nom des fichiers json correspond à la ligne dans le fichier sujets.txt pour éviter de devoir déformer le sujet pour pouvoir l'enregistrer sous Windows (certains caractères ne sont pas autorisés)

Le prompt utilisé : 

```
Méthode à suivre pas à pas pour faire la dissertation : 

----
[1] Introduction 


I/ 🔎Présentation du paradoxe et définitions :
[sujet]? Si on suppose qu'effectivement [Définition n°1] alors cela implique / veut dire que [...]. Au contraire si on nie qu'effectivement [Définition n°2] alors cela a pour conséquences / signifie que [...].


II/💥 Enonciation des alternatives et problématisation
Il semble à première vue que oui / non puisque [Thèse 1]. Donc, par définition, il semblerait que [Réponse évidente au sujet, Doxa].
Si à première vue on peut soutenir que [Thèse 2] , il semble pourtant que l'expérience montre bien souvent que [Contredire la réponse évidente, para-doxa]. Paradoxalement, on a alors l'impression que [...].


III/ 🔆Problématique
On pourra alors se demander : est-ce que [Thèse 1] ou bien est-ce que [Thèse 2] ?


IV/ 📋Annonce du plan
Dans un premier moment il s'agira de voir que [...]. Puis nous verrons que [...]. Enfin, nous nous demanderons si [...]
----

sujet : L'homme a-t-il besoin de se faire des illusions ?
Fais la dissertation pour ce sujet en suivant pas à pas cette méthode.
```
