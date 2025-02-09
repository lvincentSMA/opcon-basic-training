---
sidebar_label: 'Unite 3 Exercice 8'
hide_title: 'false'
---

## Exercice 8: Gestionnaire de notifications

##### Objectif:

Dans **Notification Manager**, créez une notification en ajoutant un **groupe racine (Root Group)** nommé ```ALL MACHINES``` et en ajoutant à la fois les machines ```WINDOWS``` et ```UNIX```.

Ajoutez un **déclencheur machine (Machine Trigger)** pour ```Machine Marked Up```.

Envoyez un e-mail à ```smauser@congo.local``` avec le message: **"TESTING EMAIL NOTIFICATION"**.

Appuyez sur le bouton **Test** pour envoyer l'e-mail. Ouvrez Thunderbird pour vérifier la réussite de la notification.


<div>
<video width="320" height="240" controls>
  <source src="videobasic/U3E8.mp4" type="video/mp4"></source>
Your browser does not support the video tag.
</video>
</div>

<details>

<summary>Cliquez pour obtenir des instructions étape par étape</summary>

1. Sous la rubrique **Management**, double-cliquez sur **Notification Manager**.
2. Cliquez sur l'onglet **Machines**.
3. Cliquez avec le bouton droit de la souris dans la zone blanche sous l'onglet Machines et sélectionnez **Add Root Group**.
4. Tapez le nom du groupe de machines (par exemple, Toutes les machines) et cliquez sur **OK**.
5. Sur le côté droit de l'écran, développez les systèmes d'exploitation et cochez toutes les cases à côté de la ou des **machines**.
6. Cliquez sur le bouton **Save** (en bas à droite).
7. Cliquez avec le bouton droit sur le dossier **Groupe** créé à l'étape 4, déplacez la souris sur **Add Machine Trigger** et sélectionnez ```Machine Marked Up``` Trigger. 
9. Sous **Notification Definitions** à droite :
    * Cochez la case **Send Email (SMTP)** 
    * Cliquez sur l'onglet **Email**.
    * Dans le champ Email, saisissez ```smauser@congo.local```.
    * Entrez un **sujet**.
    * Dans le **message**, saisissez **Notification par e-mail de test**.
10. Cliquez sur le bouton **Test** pour tester les résultats de votre notification
11. Cliquez sur le bouton **Save**.
12. Ouvrez **Thunderbird** et vérifiez la boîte de réception.

</details>