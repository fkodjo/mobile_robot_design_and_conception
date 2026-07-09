# Cahier des charges
## 1. Contexte
Après mon master en Informatique et Systèmes à l'EPL-UL, en septembre 2025, j'ai commencé le master 2 Ingénierie des Systèmes Complexes, parcours robotique et Systèmes Autonomes à l'UTBM. D'une part, de la théorie à la pratique, j'ai acquis beaucoup de connaissances sur la robotique mobile et la vision par ordinateur; qui sont entre autres, l'asservissement visuel, calibrage caméra, flot optique, homographie, triangulation, ordonnancement, PID, KALMAN, suivi de trajectoire, cinématique, odométrie, localisation, SLAM, traitement d'image, détection d'objets, apprentissage profond, et, d'autre part sur la conception de carte électronique (PCB avec KiCad, du dimensionnement à la réalisation), la compatibilité électromagnétique, le système embarqué avec la programmation de carte STM32 (communication CAN, LIN, UART, I2C, FreeRTOS, optimisation de mémoire, d'énergie et le dimensionnement de batterie).

Si j'ai appris une chose tout au long de mon parcours (plus en systèmes et réseaux informatiques), c'est que le monde virtuel, aussi évolué qu'il soit, démontre un énorme décalage de celui physique (ce qui marche dans le monde virtuel ne marche pas toujours dans le monde physique). J'ai encore fait cette remarque durant mon parcours en Robotique ; portabilité des programmes de la simulation vers le matériel, ROS de RviZ Gazebo GYM au Turtlebot3.
De ces constats, j'ai eu l'idée d'acheter un turtlebot3 burger (je n'avais pas encore de connaissance sur la BCP et le système embarqué). A la fin de ce printemps 2026, après avoir acquis toutes ces connaissances, je me suis posé la question : "Pourquoi acheter un robot si je pourrais plutôt mettre en pratique toutes ces compétences acquises durant toute cette année en assemblant de A à Z un moi-même ?"

C'est donc dans cet esprit que j'ai décidé d'assembler un robot mobile de type CAR moi-même ; d'où ce projet.

## 2. Objectifs
## 2.1. Objectif général
L'objectif général de ce projet est de construire un robot mobile pour des essais expérimentaux en robotique mobile et/ou industrielle.

## 2.2. Objectifs spécifiques
Afin d'atteindre l'objectif général, nous allons passer par plusieurs étapes dont découlent les objectifs spécifiques qui sont les suivants : 
 - Recherches documentaires
 - dimensionnement, schéma et conception de la carte PCB
 - mesures de conformité de la carte
 - programmation du microcontrôleur STM32 (les communications)
 - installation de l'ordinateur embarqué
 - dessin et impression 3D du châssis du robot
 - assemblage final
 - tests (déplacement, SLAM, LIDAR, Caméra)

## 3. Spécifications techniques
## 3.1. Spécification matérielle
 - Composante électronique
 - Batterie Li-Po 11,8V
 - carte STM32 Nucléo-144 (STM32H753ZI)
 - Raspberry Pi 4 modèle B 8 Go
 - Lidar (RPLIDAR C1)
 - Caméra Logitech Brio 100 Full HD Webcam
 - Imprimante 3D
 - Plaque d'essai électronique
 - Multimètre
 - Oscilloscope

## 3.2. Spécification logicielle et environnement
 - STM32CubeIDE
 - FreeRTOS
 - Ubuntu
 - KiCad
 - FreeCAD
 - 

## 4 Résultats attendus
A la fin de ce projet, nous disposerons d'un robot modèle capable de :
 - se déplacer suivant les modèles mathématiques en robotique
 - intégrer une caméra, un LiDAR, un bras robotisé à 4 ou 6 axes dans un environnement ROS
 - 
## 5. Compétences
A la fin de ce projet, nous acquerrons des compétences en :
 - Dimensionnement de circuit électronique
 - conception de schéma de carte électronique avec KiCad
 - conception de carte électronique (soudure des composants)
 - Programmation de carte STM32 et la communication avec le protocole CAN, UART, I2C
 - Installation et programmation d'un Raspberry
 - Configuration de l'environnement ROS
 - Modélisation et impression 3D (FreeCAD)