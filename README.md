# Apache Answer-fr

## Situation

La locale francophone officiele d’Apache Answer est quasiment inutilisable :
- le vocabulaire n’est pas défini, une même notion pouvoant être exprimée par plusieurs mots différents ;
- la locale n’a pas été testée dans son contexte d’utilisation, et comporte de nombreux contre-sens.

On se propose donc de définir une meilleure locale ici.

L’outil retenu par Apache est [Crowdin](https://crowdin.com/project/answer/fr), mais il semble mal utilisé et ne permet pas la vue d’ensemble d’un vrai dépôt. On devra donc rétro-porter chaque modification, une par une. :-( 

## Branches

- la branche [main](https://github.com/fabi1cazenave/ApacheAnswerL10nFr) contient la locale officielle Apache ;
- la branche [ergonautes](https://github.com/fabi1cazenave/ApacheAnswerL10nFr/tree/ergonautes) contient la révision proposée et testée sur [l’instance Ergo‑L](http://37.59.115.120:1664/).

## Vocabulaire Q&A

- Il y a trois sortes de **messages** (*posts*) : 
  - les **questions** (*questions*) qui ouvrent une discussion ;
  - les **réponses** (*answers*) qui y sont assocïées (une réponse par utilisateur·ice) ;
  - les **commentaires** (*comments*) qui peuvent être associés aux questions comme aux réponses.
- Les utilisateur·ices peuvent voter pour ou contre chaque message : 
  - **approbation** (*upvote*) pour signifier que le message est utile/pertinent ;
  - **désapprobation** (*downvote*) pour signifier que le message n’est pas utile/pertinent.
- Les utilisateur·ices peuvent proposer des **révisions** des messages à d’autres personnes, qui devront en faire la **validation**, c’est-à-dire **accepter** ou **refuser** les révisions proposées. 
- Les utilisateur·ices gagnent des **points de réputation** (*reputation*), ou **points** tout court, au fur et à mesure de leurs contributions.

## Vocabulaire technique

- on distingue le **nom d’affichage** de l’**identifiant** (*username*), ce dernier pouvant être utilisé pour « ping » une personne
- on utilise les termes francophones pour **téléchargement**, **téléversement**…
- on utilise les termes techniques anglophones pour **e-mail**, **slug**…
