Pour garder une certaine constance dans le code source, voici les quelques règles à respecter :

Pour nommer les fonctions et composants :

Les noms doivent être en anglais
ils doivent respecter le camelCase (lesMotsSontAttachésEnsembleSansEspaceAvecLaPremièreLettreEnMajusculeSaufPourLePremierMot)
ils se composent d'un verbe d'action pertinent et d'un ou deux noms. => si 2 noms, le premier décrit l'objet et le second sa fonction
Les Branches Git :

La branche "master" est la branche principale de l'appli. Elle ne sert qu'a pousser les fonctionnalités complètes et sans bug connu. C'est la branche qui sera lancée en production. Aucun commit n'est à effectué directement dessus.

La branche "dev" est la branche principale à utiliser lors de la phase de développement de l'appli. Tout comme "master", on ne doit pas faire de commit directement dessus. Lorsque l'on merge une branche de travail dessus, on doit s'assurer que la tâche est terminée (pas de code incomplet ou non fonctionnel) et qu'elle n'entraîne pas de bug connu.

les branches de travail : Elles sont crées à partir de la branche "dev" lors d'une nouvelle tâche et ne doit contenir que les commits en rapport avec la tâche pour laquelle elle a été créé.

Lien de la maquette : https://www.figma.com/file/HVgyF75SKT5KsQYxbnoZcB/Veggie-Blog-Design---Responsive-(Community)?type=design&node-id=0%3A1&mode=design&t=SZbc6xv7MLHAVg8s-1
