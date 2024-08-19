Liste des questions
==================

#. Qu'est-ce que K-Shap et à qui s'adresse-t-il ?
    K-Shap est une application web conçue pour aider les organisations à gérer et surveiller les décaissements. Elle est idéale pour les entreprises cherchant à rationaliser leurs processus de décaissement en mettant en place une hiérarchie de validation structurée et en s'assurant que toutes les transactions financières sont correctement suivies et approuvées.

#. Comment inscrire mon entreprise sur K-Shap ?
    Pour inscrire votre entreprise sur K-Shap :

    #. Créez l'entreprise dans le système K-Shap.
    #. Définissez les statuts de validation (Accepté, Rejeté, En cours) et les montants maximums des décaissements.
    #. Configurez les rôles utilisateurs, y compris Validateur Financier, Chef de Département, Caissier, et Agent.
    #. Créez le premier utilisateur, qui sera un administrateur avec tous les rôles, chargé de créer les autres utilisateurs et de leur attribuer des rôles.

#. Quels sont les rôles obligatoires dans K-Shap et que font-ils ?
    K-Shap nécessite quatre rôles obligatoires :

    * **Validateur Financier :** Valide les décaissements dans une plage de montants attribuée.
    * **Chef de Département :** Gère et valide les décaissements de son département.
    * **Caissier :** Finalise et gère le décaissement des fonds.
    * **Agent :** Initie les décaissements au sein de son département.

#. Puis-je personnaliser les noms des statuts de validation et des rôles utilisateurs ?
    Oui, vous pouvez personnaliser les noms des statuts de validation et des rôles utilisateurs pour les adapter à la terminologie de votre organisation. Cependant, la fonctionnalité et la hiérarchie de ces statuts et rôles doivent rester conformes à la configuration par défaut (par exemple, Accepté, Rejeté, En cours pour les statuts).

#. Que se passe-t-il si un décaissement est rejeté ?
    Si un décaissement est rejeté à une étape de validation, le validateur doit fournir une raison pour le rejet. Le processus de décaissement ne pourra pas se poursuivre tant que les problèmes ayant causé le rejet ne sont pas résolus.

#. Qui peut initier un décaissement dans K-Shap ?
    Tout employé de l'entreprise assigné comme Agent, Chef de Département, ou Validateur Financier peut initier un décaissement. L'initiateur est la personne responsable du lancement du processus de décaissement.

#. Comment K-Shap garantit-il que les décaissements sont correctement validés ?
    K-Shap met en place une hiérarchie de validation structurée où les décaissements doivent être approuvés à plusieurs niveaux :

    #. Le Chef de Département valide les décaissements de son département.
    #. Le Validateur Financier approuve les décaissements dans sa plage de montants attribuée.
    #. Le Caissier finalise le décaissement après toutes les validations précédentes.

    Chaque validateur est notifié à son étape respective et doit approuver ou rejeter le décaissement en fournissant une raison en cas de rejet.

#. Un Validateur Financier peut-il approuver n'importe quel montant de décaissement ?
    Non, un Validateur Financier ne peut approuver que les décaissements dans la plage de montants spécifique qui lui a été attribuée par l'administrateur principal de l'entreprise. Cela garantit que les contrôles financiers sont respectés conformément aux politiques de l'organisation.

#. Comment fonctionne le système de notification dans K-Shap ?
    K-Shap notifie automatiquement les utilisateurs concernés à chaque étape du processus de décaissement :

    * Le Chef de Département est notifié lorsqu'un décaissement est initié.
    * Le Validateur Financier est notifié après l'approbation du Chef de Département.
    * Le Caissier est notifié une fois que le Validateur Financier approuve le décaissement.
    * L'Initiateur est notifié lorsque le décaissement est finalisé et prêt à être collecté.

    Ces notifications permettent de garantir que les décaissements sont traités rapidement et que toutes les parties concernées sont informées.

#. Quelles sont les restrictions pour le rôle de Chef de Département ?
   Le Chef de Département ne peut voir et valider que les décaissements liés à son propre département. Il ne peut pas accéder aux décaissements des autres départements, garantissant ainsi que les frontières départementales et les responsabilités sont respectées.

#. Que se passe-t-il après l'approbation d'un décaissement ?
    Une fois qu'un décaissement est entièrement approuvé (validé par le Chef de Département, le Validateur Financier et le Caissier), l'Initiateur reçoit une notification. L'Initiateur peut alors se rendre chez le Caissier pour collecter le montant décaissé.

#. Une entreprise peut-elle utiliser K-Shap pour des décaissements dans plusieurs départements ?
    Oui, K-Shap prend en charge la gestion des décaissements dans plusieurs départements au sein d'une entreprise. Chaque département peut avoir son propre Chef de Département qui gère et valide les décaissements spécifiques à ce département.
    
#. Comment puis-je gérer la hiérarchie de validation au sein de mon entreprise ?
    En tant qu'administrateur, vous pouvez définir la hiérarchie de validation en configurant les rôles utilisateurs requis et en les attribuant aux employés de votre entreprise. Vous attribuez également des plages de montants aux validateurs financiers, garantissant que les décaissements sont validés conformément aux politiques financières de votre entreprise.

#. Est-il possible de modifier les statuts de validation ou les rôles utilisateurs après la configuration de l'entreprise ?
    Oui, les administrateurs peuvent mettre à jour les statuts de validation et les rôles utilisateurs même après la configuration initiale. Cependant, il est important de veiller à ce que les modifications soient conformes au processus global de décaissement pour maintenir l'intégrité des validations.

Ces FAQs couvrent les questions courantes liées à l'utilisation de l'application K-Shap de Gestion des Décaissements. Si vous avez d'autres questions ou besoin d'assistance supplémentaire, veuillez contacter notre équipe de service client.