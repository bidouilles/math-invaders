# **Maths Invaders Ultimate 🚀✖️**

**Maths Invaders Ultimate** est un jeu de tir spatial arcade au style rétro, conçu pour rendre l'apprentissage des tables de multiplication addictif et amusant pour les enfants. Entièrement construit dans un seul fichier HTML utilisant l'API Canvas HTML5, il combine des mécaniques de jeu « juteuses » avec des exercices éducatifs.

## **🎮 Fonctionnalités du jeu**

* **Gameplay Arcade :** Pilotez un vaisseau spatial et détruisez les astéroïdes contenant les bonnes réponses aux problèmes de multiplication.
* **Difficulté Adaptive :** Le jeu accélère et introduit davantage d'ennemis à mesure que le score augmente.
* **Système de Combo :** Enchaînez les bonnes réponses pour augmenter votre multiplicateur et marquer des points plus rapidement.
* **Power-ups :** Débloquez des capacités spéciales pendant le jeu :
  * 🛡️ **Bouclier :** Détruit les ennemis au contact sans perdre de vie.
  * 🔫 **Tir Double :** Tire deux balles à la fois pour un meilleur contrôle de la foule.
  * ❤️ **Vie Supplémentaire :** Restaure un cœur perdu.
* **Tables Sélectionnables :** Choisissez spécifiquement les tables de multiplication (de 2 à 10) à pratiquer via le menu principal.
* **Mode Révision :** Un « Mode Triche » qui met en évidence la bonne réponse en vert. Les scores obtenus dans ce mode ne sont pas enregistrés dans le tableau des meilleurs scores.
* **Révision Ciblée :** À l'écran de fin, un panneau « À RÉVISER » liste automatiquement jusqu'à 5 multiplications les plus souvent manquées pour guider la reprise des tables difficiles.
* **Visuels Juteux :** Inclut des tremblements d'écran, des explosions de particules, des effets de lueur néon et un basculement dynamique du vaisseau.
* **Design Responsive :** Fonctionne sur ordinateur (Souris) et mobile/tablette (Contrôles tactiles).

## **🕹️ Comment jouer**

### **Contrôles**

* **Ordinateur :** Déplacez votre souris pour diriger le vaisseau. Cliquez pour tirer.
* **Mobile/Tablette :** 
  * **Glissez** n'importe où sur l'écran pour déplacer le vaisseau.
  * **Tapez** rapidement pour tirer.
  * **Multi-touch :** Vous pouvez maintenir un doigt pour vous déplacer et taper avec un autre pour tirer en rafale.

### **Règles**

1. Une question de multiplication apparaît en haut (par exemple, 6 x 7).
2. Des astéroïdes tomberont avec différents nombres.
3. **Tirez sur l'astéroïde** qui contient la bonne réponse (42).
4. **Évitez de tirer sur les mauvaises réponses** (Perdez 1 Vie ❤️).
5. **Ne laissez pas la bonne réponse passer** en bas de l'écran (Perdez 1 Vie ❤️).
6. Survivez aussi longtemps que possible et battez le meilleur score !
7. Analysez la section **À RÉVISER** après une partie pour cibler les multiplications qui ont posé problème.

## **🛠️ Installation et utilisation**

Ce jeu est une **Application Mono-Fichier**. Il ne nécessite aucune installation, aucun serveur et aucun élément externe (les images ou sons sont générés de manière programmatique).

1. Téléchargez le fichier maths_invaders.html.
2. Ouvrez le fichier dans n'importe quel navigateur web moderne (Chrome, Firefox, Safari, Edge).
3. Amusez-vous !

## **💻 Détails techniques**

* **Langage :** HTML5, CSS3, JavaScript Vanilla (ES6+).
* **Rendu :** Contexte 2D du \<canvas\> HTML5.
* **Audio :** Web Audio API (Tous les effets sonores sont synthétisés en temps réel ; aucun fichier .mp3 ou .wav requis).
* **Stockage :** Utilise localStorage pour conserver le meilleur score sur l'appareil.

## **📱 Optimisation mobile**

Le jeu inclut des écouteurs d'événements spécifiques pour touchstart, touchmove et touchend afin de différencier entre :

* **Viser :** Glisser le doigt sans tirer.
* **Tirer :** Tapotements courts (<250ms).
