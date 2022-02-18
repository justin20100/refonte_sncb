# SNCB pages modifiées

- Achetez votre ticket en ligne (accueil)
- service client
- objets perdu ou trouvé
- infos voyageurs



## Modifications dans le HTML

- modification des niveaux des titres

- ajout d'un encadre sur la page infos voyageurs pour les objets perdus

- ajout de la classe .container a la section "Completez le formulaire" pour regler le probleme de marge

  ![container](./ImageReadme/container.png)

- ajout d'une classe .required pour les champs de formulaire obligé a remplir

![class .required](./ImageReadme/class .required.png)

- ajout d'un bloque objets perdus sur la page info voyageurs pour declarer un objet perdu

![html bloque info voyageurs](./ImageReadme/html bloque info voyageurs.png)



## Modifications dans le css

- ajout de margin left de 10px sur les liens de la liste contactez-nous pour garder un espace entre les liens au redimensionnement de la fenêtre.

  ![margin left footer list](./ImageReadme/margin left footer list.png)

- ajoute d'une couleur sur *:focus pour la navigation clavier et pouvoir voir ou on se trouve

  ![css navigation clavier](./ImageReadme/css navigation clavier.png)

- ajout d'un after sur les champs de saisies obligatoires

![css required](./ImageReadme/css required.png)

- ajouter un i a coté de certains mot pour avoir une definition de celui-ci

  ![info sup](./ImageReadme/info sup.png)

- ajout d'une marge entre les deux bloques sur la page info voyageurs

![css margin info voyageurs](./ImageReadme/css margin info voyageurs.png)



**petites corrections css**

- 0 comme valeur de bac-shadow
- Font-smoothing n'existe pas
- il manque des quote pour les @font-face
- usage de !important
- background-color et border-left-color identique
- Auto n'est défini par aucune spécification comme une valeur autorisée pour pointer-events, mais est pris en charge dans plusieurs navigateurs
- *zoom est un css hack(pour montrer du css en fonction des navigateur)
- Background-color et border-left-color identique ?
- Border inutile
- Guillemet utilise pour les valeur de texte align
- deux positions pour le meme elements
- deux bordures pour le meme elements
- Deux padding pour le mme elements
- Span avec attribut style





## Mauvaises pratiques

- Du code javascript et du code CSS on été retouvé dans le code HTML

- Des console.log sont toujours dans le code (ligne 8844) ceux sont inutile

  Des console.log (ligne 37434) pour les erreurs. utilité ? 

- Taches irrealisable sans le JS on a besoin d'écouter certaines actions sur des boutons pour arriver a la fin des taches

- Aucun changement visuel pour la navigation au clavier



varifier voice over



### A CHANGER

- changer bouton de la page résumé en "Envoyer" ok

![bouton suivant en envoyer](/Users/justinvincent/Documents/projets/SNCB/refonte_sncb/imageReadme/bouton suivant en envoyer.png)

- modifier calendrier (mois avant année)
- page d'accueil :
  - "mon voyage" : h2 en 22px | h3 en 26px
  - "actualités" : h3 en 22px
  - ".container-content" : h2 en 30px
  - footer : h3 en 22px