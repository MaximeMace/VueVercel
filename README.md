# hello-world

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).



## QUESTIONS ##
## Q04 ##
sudo vercel -v

## Q05 ##
sudo vue create hello-world          

## Q06 ##
sudo vercel deploy

## Q07 ## 
sudo vercel list

## Q08 ##
sudo vercel list
sudo vercel logs <latest deployment>

## Q09 ##
sudo vercel inspect <latest deployment url>
La commande permet d'avoir des infos sur le dernier deploiment divisé en section General, Builes et Routes.


## Q10 ##
Les variables d'environnements permettent de communiquer de l'information entre des programmes ou des parties de programmes qui utilisent une convention pour communiquer ensemble.

## Q11 ##
sudo vercel env add

## Q12 ##
sudo vercel env list

## Q13 ##


## Q15 ## 
sudo vercel secret add SECRET EDDEEE

## Q16 ##
Les trois environnements sont Production, Preview et Development
Les environnements diffèrent par leur méthode de déploiment. 
Ce principe permet de construire des variables environnements appliquées soit lors de la production, les previews ou localement

## Q17 ##
Les pull requests permettent à un développeur de prévenir les membres de son équipe qu'il a terminé une fonctionnalité. Une fois que sa branche de fonctionnalité est prête, le développeur fait une pull request via son compte Collaboratif (Git, Bitbucket, Tortoise...). Ainsi, toutes les personnes concernées sont informées du fait qu'elles doivent réviser le code et le merger dans la branche master.

## Q19 ##
Vercel récupère le pull et l'intègre directement au déploiment sans demande particulière. C'est donc le Preview qui est trigger.

## Q20 ##
D'après les informations Git la Preview est trigger et lorsuque la merge est réalisée, c'est la Production qui est Trigger. 

## Q21 ##
Production ==> master
Permet de travailler sur des branches séparées exemple une branche par développeurs, merge sur une develop et pull request sur la master pour livraison (À évitez les vendredi à 16H)
Comme précisé au dessus, branche perso ou local, pull request sur develop, merge, puis pull request sur master, merge sur master, mise en production. 


## Q22 ##
Le serverless désigne un ensemble de services qui sont proposés par les fournisseurs de cloud et qui nous permettent de s’abstenir de la gestion des machines. Exemple typique : FAAS, Stockage, BDD, API...


