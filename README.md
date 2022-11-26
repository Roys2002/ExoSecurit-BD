> INTRODUCTION
<p>La sécurité informatique est de nos jours devenue un problème majeur dans la gestion des réseaux d’entreprise ainsi que pour les particuliers toujours plus nombreux à se connecter à Internet. La transmission d’informations sensibles et le désir d’assurer la confidentialité de celles-ci est devenue un point primordial dans la mise en place de réseaux informatiques.
</p>

___
## **1.	Attaques et type d’attaques**
___
En informatique, l’on parle d’attaque lorsqu’une personne exploite une faille ou une limite dans un système informatique. Les attaques sont classées en type :   
*	L’interception : c’est un type d’attaque qui consiste à intercepter les données circulant sur un réseau. Ce type d’attaque rassemble une attaque comme le sniffing passif : c’est le fait qu’un utilisateur malveillant espionne un réseau dans lequel il est situé.

 <br>
 <img src="man in the middle.png">
Image illustrant la technique du sniffing passif  
<br>

*	L’interruption : c’est un type d’attaque qui touche la disponibilité de sorte à rendre un système inaccessible. Ici, nous pouvons citer le déni de service qui est une attaque qui consiste à submerger un serveur de trafics inutiles afin de le rendre hors service.
 <br>
<img src="DDoS-attaque.png">
Image illustrant un black hat causant un déni de service  
  
<br>

*   La modification : C’est un type d’attaque qui consiste à modifier un message. Elle porte atteinte à l’intégrité. On peut citer, l’attaque de l’homme du milieu (Man in the middle), elle a pour but de s’insérer entre deux ordinateurs qui communiquent. Dans ce cas, le pirate se fait passer pour l’ordinateur qui devrait recevoir le message afin de l’intercepter. 

<br>  
<img src="Man-in-the-middle-attack.png">
Image illustrant la technique de l’homme du milieu  
<br>

*	Modification : c’est n type d’attaque qui porte atteinte à l’authenticité. C’est le fit d’insérer un message dans un réseau.

___
## **2. Rapport entre la cybercriminalité et les bases de données**
___

Certaines attaques touchent plus les bases de données que d’autres. Par exemple :
*	Le déni de service : il peut être obtenu en profitant de la vulnérabilité d'une plate-forme de bases de données pour faire tomber un serveur. D'autres techniques communes de déni de service incluent la corruption de données, l'engorgement du réseau, et la surcharge en ressources du serveur (mémoire, unité centrale, etc.). La surcharge des ressources est une technique très commune dans les environnements de bases de données.

*	Injection SQL : Dans une attaque par injection SQL, l'auteur insère généralement (ou « injecte ») des informations de bases de données non autorisées dans une chaîne de données SQL vulnérable. Généralement les chaînes de données visées incluent les procédures enregistrées et les paramètres d'entrée des applications Web. Ces informations injectées sont ensuite envoyées vers la base de données où elles sont exécutées. En utilisant l'injection SQL, les auteurs d'attaques peuvent obtenir l'accès illimité à l'ensemble d'une base de données.

*	Elévation de privilège : Les auteurs d'attaques peuvent profiter des vulnérabilités des logiciels plate-forme de bases de données pour transformer les privilèges d'accès d'un utilisateur ordinaire en ceux d'un administrateur. Les vulnérabilités peuvent se trouver dans les procédures enregistrées, les fonctions intégrées, les implémentations de protocoles, voire même dans les données SQL

___
## **3. Emplacement des fichiers de données**
___

* Dans MySQL, les fichiers de données se trouvent dans **"mon.ini"**.

* Dans SQL Server, les fichiers de données se trouvent dans le fichier MDF.

* Dans Oracle, pour retrouver les fichiers de données, il faut cliquez sur Paramètres du compte, puis cliquez sur Paramètres du compte. Sous l’onglet Fichiers de données, cliquez sur une entrée, puis cliquez sur Ouvrir l’emplacement du dossier.

___
## **4. Définition de la politique de sécurité de l'INTSEC**
___

Les ITSEC définissent la politique de sécurité comme l’ensemble des lois règles ou pratiques qui régissent la façon dont l’information sensible et les autres ressources sont gérées, protégées et distribuées à l’intérieur d’un système d’information.