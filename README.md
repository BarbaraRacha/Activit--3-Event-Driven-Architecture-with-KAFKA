<h1 align="center" > Event-Driven Architecture avec Kafka </h1>

<p>Ce projet illustre l'intégration de Kafka avec Spring Cloud Streams pour bâtir une architecture réactive et scalable.</p>

<h1>Configuration et test de Kafka :</h1>

<h2>1. Installation de Kafka.</h2>

<h2>2. Démarrage de Zookeeper et Kafka Broker.</h2>
<h3>Commandes: </h3>
  <textarea style="width: 100%; height: 100px;" placeholder="Écrivez vos commandes ici..."></textarea>
<img src="images/img1.png">

<h2>3. Tests avec kafka-console-producer et kafka-console-consumer.</h2>
<h3>Commandes: </h3>
  <textarea style="width: 100%; height: 100px;" placeholder="Écrivez vos commandes ici..."></textarea>
<div style="display: flex; justify-content: center; gap: 20px;">
  <img src="images/img2.png" alt="Commande Producer" width="500">
  <img src="images/img3.png" alt="Commande Consumer" width="500">
</div>


<h1>Développement des services Kafka :</h1>

<h2>1. Producer Kafka : Service REST permettant de produire des événements.</h2>
<img src="images/img4.png">

<h2>2. Consumer Kafka : Service consommant les messages produits.</h2>
<img src="images/img5.png">

<h2>3. Supplier Kafka : Génération automatique d'événements.</h2>
<img src="images/img6.png" alt="img4" width="500">

<h2>4. Stream Processing avec Kafka Streams : Service d'analyse de données en temps réel.</h2>
<img src="images/img6.png" alt="img4" width="500">

<h1>Application Web temps réel :</h1>
<p>Interface permettant d'afficher les résultats des analyses de flux de données en temps réel.</p>
<div style="display: flex; justify-content: center; gap: 20px;">
  <img src="images/img5.png" alt="Commande Producer" width="500">
  <img src="images/img6.png" alt="Commande Consumer" width="500">
</div>
