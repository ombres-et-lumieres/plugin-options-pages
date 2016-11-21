# plugin-options-pages
pages d' options sur un plugin

le fichier menu crée les pages d' administration nécessaires

Le fichier thumb-settings.php reprend les valeurs qui seront attibuées aux différentes imagettes rencontrées sur le site.
Le fichier galeries-settings.php reprend les différentes façon d' organiser les galeries.

Je n' ai jamais créé des pages d' options et je me heurte à deux problèmes: 
Le premier, voir thumb-settings.php, est l' accroissement du code à chaque ajout de section. Y a-t-il une méthode plus courte? 
Le deuxième est nettement plus génant: alors que la page s' affiche correctement pour les imagettes, celle des galeries s' y refuse et je n' arrive pas à trouver l' erreur.

En parlant d' erreurs, je suis persuadé en avoir laissé un certain nombre qui devront être corrigées. Si vous en trouvez, ayez la gnetillesse de le faire en expliquant pourquoi.


Je suis parti d' ici: https://developer.wordpress.org/plugins/settings/custom-settings-page/

Il y a une chose qui me tracasse: dans le codex, que ce soit add_setting_section ou add_setting_field, ces fonctions font appel en paramètre au nom de la page sur laquelle ils se trouvent. Et si je fais cela, mon champ disparaît. Il doit donc y avoir une règle non explicitée quelque part.

Si j' ai une explication claire de ce qui doit être fait, je pourrai terminer cette partie
