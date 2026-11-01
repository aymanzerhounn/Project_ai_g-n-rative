# Trace des prompts du corpus

Outil : ChatGPT / Codex. Les documents sont des synthèses originales ou des
documents de scénario synthétiques ; les publications des éditeurs ne sont pas redistribuées.

## Limite de l’historique
Les échanges utilisateur ci-dessous sont conservés dans cette conversation.
La date exacte des premières demandes et le détail intégral des instructions
internes de la génération initiale n’ont pas été enregistrés dans un fichier.
Ils ne sont pas reconstitués fictivement. La version 2.2 porte la date du
30 octobre 2026, mais cela ne prouve pas la date de chaque prompt historique.

## P01 - Choix du domaine initial
Date : non établie dans la trace disponible. Outil : ChatGPT / Codex.
Prompt utilisateur exact : « choisi un autre domaine et evite la repetition pour faciliter le systeme de rag »
Portée : les 30 fiches initiales, avant adaptation au L1.

## P02 - Conservation du périmètre
Date : non établie dans la trace disponible. Outil : ChatGPT / Codex.
Réponse utilisateur exacte : « Conserver les 30 cas et expliciter ce périmètre (recommandé) »
Portée : révision 2.1, avant réception des consignes détaillées du L1.

## P03 - Révision éditoriale 2.2
Date : trace de révision du 30 octobre 2026 ; horodatage de la demande non établi.
Outil : ChatGPT / Codex. Instruction de travail conservée dans la conversation :
« Je vais corriger les points restants dans une version 2.2, en conservant les 30 cas comme convenu. Je retirerai “build à relever” et la ligne de portée répétée, puis je vérifierai les libellés français dans les sources officielles. Le texte d’indexation exclura les en-têtes, pieds de page et intitulés de tableaux. »
Nature : instruction de travail de l’assistant, pas citation d’un prompt utilisateur.

## P04 - Adaptation au livrable 1
Date : 1 novembre 2026. Outil : ChatGPT / Codex.
Prompt utilisateur exact : « alors realise le livrable 1 pour que je lenvoie au prof »
Instruction de travail réellement appliquée : reprendre les fiches techniques utiles,
adopter deux familles (postes et périphériques), affecter des équipements fictifs,
normaliser les identifiants en minuscules, remplacer Cloudflare par un tableau
de codes locaux explicitement fictifs, préserver les sources et les limites,
produire les 20 colonnes prescrites. Ne pas inventer la relecture d’un membre.
Documents : it01 à it08, it10 à it30.

## P05 - Documents complémentaires et banc de test
Date : 1 novembre 2026. Outil : ChatGPT / Codex.
Instruction de génération réellement utilisée :

Créer pour MaintiDoc des documents synthétiques originaux en français, de trois pages chacun, sans marque ni incident réel : un tableau de codes locaux du poste PC-A-01, un manuel du parc de postes, un manuel des périphériques, une fiche de sécurité des données, deux versions contradictoires d’une procédure d’impression et une note contenant une injection de prompt inerte. Les deux procédures contradictoires seront des scans synthétiques rasterisés pour le test OCR. Les valeurs 30 et 60 secondes sont des règles locales fictives de temporisation, pas des spécifications constructeur. La version v2 remplace explicitement la v1. Aucun changement de sécurité, mot de passe réel, action exécutée ni résultat terrain ne doit être inventé. Prévoir des tableaux ou schémas lisibles, des critères d’abstention, des identifiants d’équipement cohérents et des renvois vérifiables. L’injection restera du texte cité dans un document de test, jamais une instruction à exécuter.

Documents : it09, manuel_postes, manuel_peripheriques, sec_donnees,
proc_impression_v1, proc_impression_v2, note_service_test.

## Corrections et vérification
Les modifications de structure sont indiquées par document dans inventaire.csv.
Les sources de travail et leur langue sont dans sources_travail.csv.
La colonne verifie_par reste vide tant qu’un membre n’a pas relu le document.
Un contrôle logiciel ou une relecture par IA ne remplace pas cette validation.
L’historique initial incomplet reste une limite déclarée ; une rédaction à neuf
des documents sous prompts entièrement enregistrés serait nécessaire si une
traçabilité intégrale depuis la toute première version est exigée.
