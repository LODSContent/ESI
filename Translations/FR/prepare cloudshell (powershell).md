## Préparer le cloud shell pour une utilisation ultérieure
1. Connectez-vous au portail Azure (+++https://portal.azure.com/?l=fr.fr-fr+++) en utilisant les identifiants ci-dessous :

    |||
    |--|--|
    |Nom d’utilisateur|+++@lab.CloudPortalCredential(LabUser).Username+++|
    |Mot de passe|+++@lab.CloudPortalCredential(LabUser).Password+++|

1. Dans la barre d’outils située en haut du portail Azure, sélectionnez l’icône **Cloud Shell**.

1. Dans la boîte de dialogue « Welcome to Azure Cloud Shell », sélectionnez **PowerShell**.

1. Sur l’écran « you have no storage mounted », sélectionnez **Show advanced settings**.

1. Dans l’écran des paramètres avancés, remplissez les champs suivants, puis cliquez sur **Create Storage** 

    |||
    |--|--|
    |Groupe de ressources|Un groupe de ressources qui n’est **not** NetworkWatcherRG|
    |Compte de stockage (Créer nouveau)|+++cloudshell@lab.LabInstance.Id+++|
    |Partager des fichiers (créer nouveau)|+++shellstorage+++|
    
    >[!KNOWLEDGE] Si vous recevez une erreur « Tenant User Over Quota », changez votre **Cloud Shell Region** pour une autre région.

1. Une fois que le cloud shell s’initialise et affiche une invite de texte, quittez l’interpréteur de commandes.
