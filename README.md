# HouwaydaLaabidi-RamziBorgi/SystemMessagerie
# android-client-serveur
Décrit une simple application client-serveur Android

<h3>Comment courir ?</h3>

Le référentiel contient deux projets Android. L'un est l'application serveur et l'autre est le client.<br/>
Exécutez les deux applications sur vos appareils.<br/>
Pour une exécution locale, recherchez l'adresse IP de l'appareil qui exécute l'application serveur.<br/>
Modifiez <b>SERVER_IP</b> dans l'application cliente dans ClientActivity.<br/>

  <b>public static final String SERVER_IP = "192.168.1.155" ;</b>
 
<i>Assurez-vous que les deux appareils sont sur le même réseau et utilisent le même PORT.</i><br/>
Accédez à l'application client et appuyez sur "Connecter le serveur"<br/>
Il devrait afficher connecté et appuyez maintenant sur "Envoyer un message au serveur".<br/>

Ouvrez l'application serveur pour voir le message du client.

Si vous vous connectez à un serveur, assurez-vous que le PORT que vous avez spécifié dans le code est autorisé à accepter les connexions socket entrantes.
<br/>Spécifiez des messages personnalisés en saisissant le message dans le TextField sur les deux applications.

<br />
<h4>Serveur</h4>
<br />
<a href=""><img src="https://github.com/MrVipinVijayan/android-client-server/blob/main/Screenshots/server.png?raw=true" alt="drawing" style=" largeur:300px;"/></a>
<h4>Client</h4>
<br />
<a href=""><img src="https://github.com/MrVipinVijayan/android-client-server/blob/main/Screenshots/client.png?raw=true" alt="drawing" style=" largeur:300px;"/></a>
