---
title: Page web statique
author: 'ZHONG WenZhuo'
date: '2019-10-19'
slug: comment-faire-une-page-web-statique
categories: []
tags:
  - web
---

## Construisez une page Web statique avec blogdown + hugo + netlify + github  
Tout le logiciel dont nous avons besoin est：  
R(https://www.r-project.org/)  
rstudio(https://www.rstudio.com/)  
git(https://git-scm.com/)  

#### 1.Installez blogdown et hugo

install.packages("blogdown")  
blogdown::install_hugo()  
#### 2.Configuration de l'environnement  
* Tools -> Global Options -> Sweave -> Weave Rnw files using:knitr  
* Tools -> Global Options -> Sweave -> Typeset LaTex into PDF using:XeLaTeX  
* Tools -> Global Options -> Git/SVN -> Git executable

#### 3.Utilisation de github

* Inscrivez-vous pour un compte github  
* Créer un nouveau "repository"  
* Le mettre en public
[![KnusWn.md.jpg](https://s2.ax1x.com/2019/10/19/KnusWn.md.jpg)](https://imgchr.com/i/KnusWn)

#### 4.Utilisation de git

* Créer un nouveau projet dans Rstudio
* File -> New Project -> Version Control -> Git 
* Entrez le lien vers le référentiel github,Comme ce format：https://github.com/ZHONGWENZHUO/WENZHUO
[![KnM08s.md.png](https://s2.ax1x.com/2019/10/19/KnM08s.md.png)](https://imgchr.com/i/KnM08s)

#### 5.Utilisation de blogdown

* Créer un nouveau projet dans Rstudio
* File -> New Project -> New Directory -> Website using blogdown
* Remarque！ ici nous devons créer un projet avec le même nom
* Vous pouvez choisir votre thème préféré et l'utiliser en https://themes.gohugo.io/
[![KnQFIg.md.png](https://s2.ax1x.com/2019/10/19/KnQFIg.md.png)](https://imgchr.com/i/KnQFIg)
* Cliquez sur Server_site et vérifiez que le site Web est généré dans la fenêtre inférieure droite.
[![KnQ6SA.md.png](https://s2.ax1x.com/2019/10/19/KnQ6SA.md.png)](https://imgchr.com/i/KnQ6SA)
*  Addins-> New Post,Vous pouvez créer une nouvelle page de contenu
[![KnlP61.md.png](https://s2.ax1x.com/2019/10/19/KnlP61.md.png)](https://imgchr.com/i/KnlP61)

#### 5.Utilisation de git
* Cliquez sur commit
[![Kn1Avn.md.png](https://s2.ax1x.com/2019/10/19/Kn1Avn.md.png)](https://imgchr.com/i/Kn1Avn)
* Sélectionnez les fichiers à télécharger,Cliquez sur commit,Cliquez à nouveau sur PUSH
* Votre fichier local est synchronisé avec votre github
[![Kn16qP.md.png](https://s2.ax1x.com/2019/10/19/Kn16qP.md.png)](https://imgchr.com/i/Kn16qP)

#### 6.Utilisation de netlify
* S'inscrire avec un compte github
* Créer un nouveau site web, lien vers github
[![KnlZkD.md.png](https://s2.ax1x.com/2019/10/19/KnlZkD.md.png)](https://imgchr.com/i/KnlZkD)
* Remplir de cette façon
[![KnlUpj.md.png](https://s2.ax1x.com/2019/10/19/KnlUpj.md.png)](https://imgchr.com/i/KnlUpj)
* Tu peux changer ton nom
[![Knl29J.md.png](https://s2.ax1x.com/2019/10/19/Knl29J.md.png)](https://imgchr.com/i/Knl29J)

#### 7.Dernier！！
* Allez ici et votre site web est configuré, entrez votre URL pour l'ouvrir.
* Vous pouvez modifier votre site Web localement et changer le style. Ensuite, synchronisez avec github via git.