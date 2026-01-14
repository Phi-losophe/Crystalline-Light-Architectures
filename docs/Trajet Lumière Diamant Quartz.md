# **Analyse Comparative et Modélisation Avancée de la Propagation Lumineuse : Diamant Isotrope vs Quartz Biréfringent**

## **Résumé Exécutif**

Ce rapport de recherche constitue une étude exhaustive des mécanismes de propagation de la lumière au sein de deux matériaux cristallins paradigmatiques : le diamant (carbone allotropique cubique) et le quartz (dioxyde de silicium trigonal). L'objectif est de déconstruire, modéliser et interpréter le chemin optique des photons pour mettre en lumière les divergences fondamentales imposées par la structure atomique et les constantes diélectriques de chaque minéral. À travers une analyse rigoureuse des équations de Maxwell appliquées aux milieux diélectriques, des modèles géométriques de Marcel Tolkowsky, et de la tensorielle de la biréfringence, nous démontrons comment l'isotropie à haute densité du diamant le prédispose à agir comme un "piège à lumière" hyper-réfléchissant, tandis que l'anisotropie du quartz en fait un "diviseur de lumière" complexe. Ce document développe les équations géométriques et ondulatoires nécessaires pour modéliser ces phénomènes, interprète les motifs de brillance et de feu (dispersion), et en déduit les techniques de taille (facettage) et d'ingénierie optique requises pour optimiser chaque matériau.

## **1\. Fondements Physiques de l'Interaction Lumière-Matière**

Pour analyser le chemin parcouru par la lumière, il est impératif de définir les contraintes physiques imposées par le milieu de propagation. Le diamant et le quartz représentent deux archétypes optiques opposés : l'isotropie à haute densité optique contre l'anisotropie à densité modérée avec biréfringence.

### **1.1 Structure Cristalline et Symétrie Optique**

La différence fondamentale dans la trajectoire lumineuse trouve son origine dans la symétrie du réseau cristallin, qui dicte la nature du tenseur de permittivité diélectrique \\boldsymbol{\\varepsilon}.

* **Le Diamant (Système Cubique \- Isotrope) :** Le diamant cristallise dans le système cubique (groupe d'espace Fd\\overline{3}m). Sa structure atomique, composée de carbone hybridé sp^3 en arrangement tétraédrique, est hautement symétrique dans les trois dimensions spatiales. Cette symétrie implique que la polarisabilité électronique est identique quel que soit l'angle d'incidence du champ électrique. Par conséquent, le diamant est optiquement **isotrope**. La lumière s'y propage à une vitesse de phase constante v \= c/n indépendamment de sa direction ou de sa polarisation. Le front d'onde généré par une source ponctuelle interne est une sphère parfaite.  
* **Le Quartz (Système Trigonal \- Anisotrope) :** Le quartz \\alpha (SiO\_2) cristallise dans le système trigonal (groupe d'espace P3\_121 ou P3\_221). Cette symétrie réduite engendre une anisotropie optique. Le quartz possède un axe de symétrie rotationnelle d'ordre 3, qui correspond à l'axe optique (axe C ou axe Z). La lumière interagissant avec les électrons le long de cet axe subit une impédance différente de celle interagissant perpendiculairement à cet axe. Le quartz est donc un matériau **uniaxe positif**. L'indice de réfraction dépend de la direction et de la polarisation, transformant le front d'onde en une surface complexe à deux nappes : une sphère (onde ordinaire) et un ellipsoïde de révolution (onde extraordinaire).

### **1.2 Indices de Réfraction et Vitesse de Phase**

L'indice de réfraction n est le ratio scalaire (pour les isotropes) entre la vitesse de la lumière dans le vide c et la vitesse de phase dans le matériau v.  
La magnitude de cet indice détermine la courbure du chemin lumineux (réfraction) selon la loi de Snell-Descartes.

* **Diamant :** Le diamant possède l'un des indices de réfraction les plus élevés parmi les minéraux transparents naturels, soit n \\approx 2.417 à une longueur d'onde de 589 nm (ligne D du sodium). Cela implique que la lumière est ralentie à environ 41% de sa vitesse dans le vide (v\_{diamant} \\approx 124,000 km/s). Ce ralentissement extrême est le moteur principal de sa brillance, car il réduit drastiquement l'angle critique.  
* **Quartz :** Le quartz présente des indices beaucoup plus faibles, typiques des silicates. En raison de sa biréfringence, il ne peut être caractérisé par un seul scalaire mais par deux indices principaux :  
  * n\_o \\approx 1.544 (Indice ordinaire, polarisation \\perp axe C)  
  * n\_e \\approx 1.553 (Indice extraordinaire, polarisation \\parallel axe C). La biréfringence \\Delta n \= n\_e \- n\_o \\approx \+0.009 est faible mais suffisante pour provoquer des effets optiques tangibles (flou, dédoublement). La lumière voyage ici à environ 65% de c, soit nettement plus vite que dans le diamant.

### **1.3 L'Angle Critique (\\theta\_c) : La Frontière de la Lumière**

L'angle critique est le paramètre géométrique le plus déterminant pour la modélisation du "chemin de retour" de la lumière. Il définit l'angle d'incidence limite au-delà duquel la lumière ne peut plus s'échapper du milieu dense vers l'air et subit une Réflexion Totale Interne (RTI).  
La formule dérivée de la loi de Snell pour une interface gemme-air (n\_{air} \\approx 1\) est :  
Une comparaison quantitative révèle la divergence comportementale des deux matériaux :

| Paramètre | Diamant (n=2.42) | Quartz (n=1.54) | Implications pour le Chemin Lumineux |
| :---- | :---- | :---- | :---- |
| **Calcul** | \\arcsin(0.413) | \\arcsin(0.649) | Le sinus de l'angle critique est inversement proportionnel à l'indice. |
| **Angle Critique (\\theta\_c)** | **\~24.4°** | **\~40.5°** | Valeur angulaire au-delà de laquelle le rayon est piégé. |
| **Cône d'Échappement** | 48.8° (2 \\times \\theta\_c) | 81.0° (2 \\times \\theta\_c) | Ouverture angulaire permettant à la lumière de sortir. |
| **Conséquence** | Piégeage massif. | Fuite facile. | Le diamant capture la lumière sur une plage angulaire énorme (180^\\circ \- 48.8^\\circ \= 131.2^\\circ). Le quartz la laisse fuir si l'angle n'est pas rasant. |

Cette différence de près de 16 degrés impose des architectures de taille (facettage) radicalement différentes. Une forme optimisée pour le diamant sera optiquement inerte (fenêtrée) pour le quartz.

## **2\. Analyse et Modélisation du Diamant : Le Piège à Lumière Isotrope**

L'analyse du diamant se concentre sur la maximisation du retour lumineux par réflexion totale interne. Le modèle standard de référence est celui développé par l'ingénieur et mathématicien belge Marcel Tolkowsky en 1919\.

### **2.1 Le Modèle Mathématique de Tolkowsky**

Marcel Tolkowsky, dans sa thèse *Diamond Design*, a cherché à résoudre un problème d'optimisation sous contraintes : trouver les angles de la couronne (\\alpha) et du pavillon (\\beta) qui maximisent simultanément la **brillance** (retour de lumière blanche par réflexion interne) et le **feu** (dispersion chromatique).

#### **Hypothèses et Simplifications**

Tolkowsky a modélisé le diamant en 2D (coupe transversale), en supposant un rayon lumineux entrant perpendiculairement à la table (incidence normale, i=0). Il a ignoré l'épaisseur du rondiste (girdle), modélisant un "rondiste couteau" (knife-edge).

#### **Dérivation du Chemin Lumineux Idéal**

Suivons le chemin d'un photon dans ce modèle théorique :

1. **Entrée (Table) :** Le rayon entre verticalement. Comme l'incidence est normale à la surface (i=0^\\circ), il n'y a pas de réfraction. Le rayon pénètre en ligne droite.  
2. **Première Réflexion (Pavillon 1\) :** Le rayon frappe une facette du pavillon inclinée d'un angle \\beta par rapport à l'horizontale. L'angle d'incidence par rapport à la normale de la facette est : Pour que le rayon soit réfléchi totalement, il faut \\theta\_1 \> \\theta\_c (24.4°). Cette condition est facilement remplie par la plupart des géométries de gemmes. Le rayon est réfléchi selon la loi de la réflexion spéculaire, dévié de 2\\theta\_1.  
3. **Seconde Réflexion (Pavillon 2\) :** Le rayon traverse horizontalement la pierre et frappe la facette du pavillon opposé. Par géométrie symétrique, l'angle d'incidence sur cette seconde facette \\theta\_2 est relié à l'angle du pavillon. Tolkowsky a déterminé que pour renvoyer la lumière vers le haut (vers la couronne), l'angle \\beta devait être proche de 45°. Cependant, si \\beta \= 45^\\circ, le rayon réfléchi remonte verticalement (\\theta\_{sortie} \= 0^\\circ). Bien que cela maximise le retour, cela minimise la dispersion (le feu), car la dispersion nécessite une réfraction à la sortie.  
4. **Sortie (Couronne/Table) et Optimisation du Feu :** Pour générer du feu, le rayon doit sortir par les facettes de la couronne (biseaux) avec un angle d'incidence non nul pour subir la dispersion prismatique. Tolkowsky a calculé que l'angle de réfraction de sortie optimal pour équilibrer brillance et dispersion est de **45°** par rapport à la normale de sortie. En résolvant les équations trigonométriques du chemin optique pour cette condition de sortie, il a obtenu l'angle de pavillon optimal : Avec cet angle, le rayon frappe le second pavillon avec un angle d'incidence \\theta\_2 \\approx 49.25^\\circ, ce qui est bien supérieur à l'angle critique (24.4°), garantissant une seconde réflexion totale.  
5. **Calcul de l'Angle de Couronne (\\alpha) :** Pour capturer les rayons sortants et les rayons entrants obliques, Tolkowsky a déterminé que l'angle de la couronne devait être : Cette combinaison (P=40.75^\\circ, C=34.5^\\circ) permet au rayon entrant verticalement d'être réfléchi deux fois et de sortir par la couronne avec une forte dispersion spectrale, tout en permettant aux rayons entrants obliques d'être également capturés.

#### **Équations de Proportions**

Le modèle aboutit à un ensemble de ratios géométriques définissant le "Brillant Idéal" :

* Diamètre de la Table : 53% du diamètre total.  
* Profondeur du Pavillon : 43.1%.  
* Hauteur de la Couronne : 16.2%.  
* Profondeur Totale : 59.3%.

### **2.2 Analyse de la Dispersion Chromatique (Le Feu)**

Le diamant ne se contente pas de réfléchir la lumière ; il la disperse. L'indice de réfraction varie en fonction de la longueur d'onde \\lambda selon l'équation de Cauchy approximée pour le diamant dans le visible :  
Avec n\_{rouge} (687 nm) \\approx 2.407 et n\_{bleu} (430 nm) \\approx 2.451. La dispersion est la différence \\Delta n \= n\_{bleu} \- n\_{rouge} \= 0.044. Bien que cette valeur semble faible, le long chemin optique à l'intérieur du diamant et les angles de sortie élevés amplifient la séparation angulaire des couleurs. L'angle de sortie \\theta\_{out} varie selon la couleur :  
La dérivée \\frac{d\\theta\_{out}}{d\\lambda} est maximale lorsque \\theta\_{out} est grand. Le choix de Tolkowsky de viser des angles de réfraction de sortie élevés optimise précisément ce gradient, transformant le diamant en un prisme complexe.

### **2.3 Scintillation et Facettes Virtuelles**

Une analyse moderne en 3D dépasse le modèle statique de Tolkowsky pour inclure la **scintillation** (l'éclat dynamique lors du mouvement). Le chemin de la lumière dans un diamant taillé crée des "facettes virtuelles". Bien qu'un diamant brillant rond possède 57 facettes physiques, les réflexions internes multiples créent une mosaïque de plusieurs centaines de miroirs virtuels perçus par l'œil.

* **Contraste Dynamique :** La scintillation naît de l'alternance rapide entre l'observation de facettes virtuelles éclairées (renvoyant la source lumineuse) et de facettes virtuelles sombres (renvoyant l'image de la tête de l'observateur ou un fond sombre).  
* **Motif Hearts & Arrows (Cœurs et Flèches) :** Ce pattern est une manifestation de symétrie optique extrême.  
  * *Les Flèches (Vue de face)* sont formées par la réflexion des 8 facettes principales du pavillon. Les rayons frappent ces facettes et sont renvoyés directement vers l'observateur à travers la table.  
  * *Les Cœurs (Vue de dos)* sont formés par une double réflexion complexe impliquant les facettes du pavillon et la table. La formation de ce pattern exige que les facettes soient alignées avec une précision inférieure au degré, garantissant que les chemins lumineux de chaque facette symétrique soient congruents.

## **3\. Analyse et Modélisation du Quartz : Le Diviseur de Lumière Anisotrope**

Le quartz impose une complexité vectorielle absente dans le diamant. En tant que matériau biréfringent, il ne peut être modélisé par un simple tracé de rayon scalaire. Le chemin lumineux y subit une bifurcation fondamentale.

### **3.1 Tenseur de Permittivité et Indices Principaux**

Dans le quartz, la réponse électrique du matériau dépend de l'orientation du champ électrique \\vec{E} de l'onde lumineuse. La relation constitutive est tensorielle : \\vec{D} \= \\boldsymbol{\\varepsilon} \\vec{E}. Dans le repère des axes cristallographiques principaux (x, y, z) où z est l'axe optique (C-axis), le tenseur diélectrique est diagonal :  
Cette matrice diagonale reflète la symétrie uniaxe : les axes x et y sont équivalents (indice n\_o), tandis que l'axe z est unique (indice n\_e).

### **3.2 La Bifurcation : Rayons Ordinaires et Extraordinaires**

Lorsqu'un rayon lumineux non polarisé pénètre dans le quartz (sauf parallèlement à l'axe C), il se décompose en deux modes normaux de propagation orthogonaux :

1. **Le Rayon Ordinaire (o-ray) :**  
   * *Polarisation :* Perpendiculaire au plan principal (plan contenant le vecteur d'onde \\vec{k} et l'axe optique).  
   * *Indice :* Constant n\_o \= 1.544.  
   * *Vitesse de phase :* v\_o \= c/n\_o.  
   * *Trajectoire :* Suit la loi de Snell classique (n\_1 \\sin i \= n\_o \\sin r). Son vecteur de Poynting \\vec{S} est parallèle à son vecteur d'onde \\vec{k}.  
2. **Le Rayon Extraordinaire (e-ray) :**  
   * *Polarisation :* Dans le plan principal.  
   * *Indice Effectif :* Dépend de l'angle \\theta entre la normale d'onde et l'axe optique z. L'indice n(\\theta) est donné par l'équation de l'ellipsoïde des indices :  
   * *Trajectoire :* Ne suit **pas** la loi de Snell standard. Le rayon est réfracté même à incidence normale si la surface n'est pas un axe principal.

### **3.3 L'Angle de Walk-off (\\rho) : Divergence Spatiale**

Une caractéristique critique du chemin dans le quartz est l'angle de "walk-off" (dérive). Pour le rayon extraordinaire, la direction de propagation de l'énergie (vecteur de Poynting \\vec{S}) n'est pas alignée avec la direction de propagation de la phase (vecteur d'onde \\vec{k}). L'angle \\rho entre \\vec{S} et \\vec{k} est donné par :  
Pour le quartz, bien que la biréfringence \\Delta n soit faible (0.009), cet effet a deux conséquences majeures pour la modélisation de la taille :

1. **Le Dédoublement (Doubling) :** Un rayon entrant unique est physiquement séparé en deux rayons distincts qui frappent les facettes du pavillon à des endroits différents. Lors de l'observation à travers la table, les arêtes des facettes du pavillon apparaissent doublées. C'est un critère diagnostique immédiat distinguant le quartz du diamant (isotrope, pas de dédoublement).  
2. **Flou Artistique :** Contrairement à la netteté "rasoir" des réflexions dans le diamant, le quartz produit une image interne légèrement plus douce due à la superposition incohérente des deux images (ordinaire et extraordinaire).

### **3.4 Modélisation de la Forme pour le Quartz**

Si l'on applique les équations de Tolkowsky (Pavillon 40.75°) au quartz, le résultat est un échec optique complet.

* **Calcul de l'Angle Critique :**  
* **Analyse du Chemin Tolkowsky dans le Quartz :** Un rayon vertical entrant frappe le pavillon à un angle d'incidence de 90^\\circ \- 40.75^\\circ \= 49.25^\\circ. 49.25^\\circ \> 40.49^\\circ, donc la première réflexion a lieu. Cependant, considérons les rayons légèrement inclinés (tête de l'observateur bougeant). Le cône d'acceptance est très étroit. Dès que l'angle d'incidence interne tombe sous 40.5°, la lumière traverse le pavillon et est perdue. Dans le diamant, la marge est énorme (49^\\circ vs 24^\\circ). Dans le quartz, la marge est critique (49^\\circ vs 40.5^\\circ). Plus grave, pour les rayons centraux, le phénomène de "Windowing" (fenêtrage) apparaît : le centre de la pierre apparaît transparent et vide, laissant voir le doigt ou le support à travers la gemme.

#### **La Forme Corrective : "Deep Cut" (Taille Profonde)**

Pour modéliser une taille efficace dans le quartz, il faut augmenter artificiellement l'angle d'incidence interne pour s'éloigner de la zone critique.

* **Équation de Correction :** On augmente l'angle du pavillon \\beta à **43° \- 45°**. Si \\beta \= 43^\\circ, l'angle d'incidence interne (pour un rayon vertical) devient 90 \- 43 \= 47^\\circ. Cela semble *réduire* l'angle d'incidence par rapport à 40.75°, ce qui est contre-intuitif? *Correction Géométrique :* En réalité, l'augmentation de l'angle de pavillon sert surtout à rediriger la lumière vers des angles de sortie plus sûrs et à gérer les rayons entrants *obliques*. Surtout, une taille plus profonde augmente le volume de matière, allongeant le chemin optique, ce qui compense la faible dispersion (0.013 pour le quartz vs 0.044 pour le diamant) en augmentant la séparation physique des couleurs.

## **4\. Analyse Comparée : Synthèse des Chemins et Techniques**

Cette section met en perspective les deux modèles pour en déduire des techniques pratiques d'identification et de valorisation.

### **4.1 Comparaison des Paramètres Optiques**

| Propriété Physique | Diamant (C) | Quartz (SiO\_2) | Impact sur le Modèle de Chemin |
| :---- | :---- | :---- | :---- |
| **Indice de Réfraction (n\_D)** | **2.417** (Isotrope) | **1.544 \- 1.553** (Biréfringent) | Le diamant courbe la lumière 2x plus. |
| **Angle Critique (\\theta\_c)** | **24.4°** | **40.5°** | Le diamant piège la lumière ; le quartz la laisse fuir. |
| **Dispersion (\\Delta n)** | **0.044** (Haute) | **0.013** (Faible) | Le diamant génère des arcs-en-ciel vifs ; le quartz reste blanc/neutre. |
| **Biréfringence** | Nulle (0) | 0.009 (Faible) | Netteté absolue vs Dédoublement subtil. |
| **Transmission UV/IR** | Transparent (Type IIa) | Transparent (sauf impuretés) | Utilisation possible en optique instrumentale pour les deux. |

### **4.2 Analyse du Pattern "Bullseye" vs "Hearts & Arrows"**

La structure du chemin lumineux génère des signatures visuelles uniques exploitables pour l'identification.

* **Le Diamant et le Pattern H\&A :** Comme vu précédemment, l'isotropie permet une convergence parfaite des rayons. Le pattern "Hearts & Arrows" est la preuve d'une symétrie physique parfaite couplée à une isotropie optique. Si le diamant était biréfringent, le dédoublement des rayons brouillerait la netteté des flèches.  
* **Le Quartz et la Figure Conoscopique "Bullseye" :** Le quartz possède une propriété unique liée à sa structure cristalline hélicoïdale (groupe spatial énantiomorphe) : l'**activité optique** (pouvoir rotatoire). Le plan de polarisation de la lumière tourbillonne en traversant l'axe optique.  
  * *Technique d'Observation :* En plaçant un quartz entre deux filtres polarisants croisés (polariscope) et en observant dans l'axe optique (conoscopie), on ne voit pas une croix noire simple (isogyres) comme dans la plupart des cristaux uniaxes. On observe une croix dont le centre est "ouvert", ne touchant pas le milieu. Le centre présente une tache de couleur ou un cercle clair.  
  * *Interprétation du Chemin :* Au centre (axe optique), la biréfringence est nulle (n\_o \= n\_e), mais l'activité optique fait tourner la polarisation. Les rayons ne sont donc pas éteints par l'analyseur croisé. Ce motif en "œil de bœuf" (Bullseye) est une signature diagnostique absolue du quartz, impossible à reproduire par le diamant (isotrope, reste sombre en polarimétrie croisée sauf tensions internes anomales "tatami").

### **4.3 Techniques de Taille : Orientation de l'Axe C**

Dans le diamant, l'orientation du cristal brut (octaèdre, dodécaèdre) influence le rendement de poids et la dureté de polissage (anisotropie de dureté), mais *pas* le chemin optique fondamental.  
Dans le quartz, l'orientation est critique pour l'optique :

* **Technique de l'Axe C :** L'axe optique (C) doit être positionné perpendiculairement à la table pour les pierres taillées.  
  * *Raison 1 (Biréfringence) :* Cela minimise l'effet de dédoublement visible de face, gardant la pierre plus nette.  
  * *Raison 2 (Couleur/Dichroïsme) :* Dans les variétés colorées (Améthyste, Quartz Fumé), la couleur est souvent zonée ou dichroïque. L'axe C porte souvent la couleur la plus profonde ou la teinte différente. Le lapidaire doit aligner le chemin lumineux principal (table-culet) avec cet axe pour maximiser la saturation.

## **5\. Applications Avancées et Ingénierie Optique**

Au-delà de la gemmologie, la modélisation des chemins lumineux dans ces matériaux sous-tend des technologies critiques.

### **5.1 Génération de Seconde Harmonique (SHG) dans le Quartz**

L'anisotropie du quartz, qui est un défaut en gemmologie (flou), devient un atout en optique non-linéaire.

* **Phase Matching (Accord de Phase) :** Pour convertir une fréquence laser (ex: infrarouge 1064 nm) en sa seconde harmonique (vert 532 nm), il faut que les vitesses de phase des deux ondes soient égales (n\_\\omega \= n\_{2\\omega}).  
* Dans un milieu isotrope comme le diamant, c'est impossible à cause de la dispersion normale (n\_{bleu} \> n\_{rouge}).  
* Dans le quartz, on peut exploiter la biréfringence. En choisissant un angle de propagation \\theta\_m précis, on peut faire en sorte que l'indice extraordinaire de l'onde verte soit égal à l'indice ordinaire de l'onde rouge. Cette technique permet d'utiliser le quartz pour manipuler les fréquences lumineuses, une prouesse impossible avec la géométrie isotrope du diamant.

### **5.2 L'Analyse ASET : Cartographie de la Performance**

L'outil ASET (Angular Spectrum Evaluation Tool) permet de visualiser l'efficacité du modèle de taille en colorant les rayons selon leur angle d'entrée.

* **Code Couleur :**  
  * **Rouge (75°-90°) :** Lumière directe intense. C'est ce qu'on veut maximiser pour la brillance.  
  * **Vert (45°-75°) :** Lumière réfléchie (environnement). Important pour le contraste.  
  * **Bleu :** Lumière bloquée par la tête de l'observateur (0°-15° environ). Crée le contraste (les "flèches" sombres).  
* **Modèle Diamant :** Une taille Tolkowsky idéale montre une saturation de **Rouge** avec une étoile bleue symétrique au centre. Le chemin est optimisé pour capter la lumière zénithale.  
* **Modèle Quartz :** Une taille standard appliquée au quartz montrera un large anneau **Vert** ou même transparent (fuite), car le faible indice de réfraction ne parvient pas à replier les rayons rouges (zénithaux) vers l'œil. Pour obtenir du rouge dans un quartz, il faut des angles de pavillon très profonds qui "remontent" la lumière par des réflexions multiples, complexifiant le chemin.

## **6\. Conclusion : Deux Paradigmes de la Lumière**

L'analyse détaillée des chemins optiques permet de conclure que le diamant et le quartz, bien que tous deux transparents et cristallins, opèrent selon des régimes physiques distincts qui dictent leur forme et leur usage.

1. **Le Diamant est un Miroir Géométrique.** Son indice de réfraction élevé (2.42) et son isotropie permettent de le modéliser comme un résonateur optique parfait. Le modèle de Tolkowsky exploite l'angle critique fermé (24.4^\\circ) pour plier la lumière à angle aigu, maximisant le trajet pour la dispersion sans perte d'énergie. C'est le triomphe de la **réflexion**.  
2. **Le Quartz est un Prisme Complexe.** Son indice modéré (1.54) et son anisotropie (biréfringence, activité optique) empêchent le piégeage simple de la lumière. Le chemin lumineux y est une bifurcation constante (rayons o et e) sujette aux fuites angulaires (40.5^\\circ). Pour briller, le quartz ne peut compter sur la force brute de l'indice ; il doit compenser par le volume (taille profonde) et l'alignement cristallographique (axe C). C'est le domaine de la **transmission contrôlée**.

La modélisation mathématique de ces chemins, des équations scalaires de Snell pour le diamant aux tenseurs diélectriques pour le quartz, ne fournit pas seulement une explication théorique de leur beauté ; elle est la base de l'industrie moderne de la taille de précision et de la photonique instrumentale.

#### **Ouvrages cités**

1\. Gemstone Optics: The Basics \- International Gem Society, https://www.gemsociety.org/article/optics-gemology/ 2\. Refraction \- The Physics Hypertextbook, https://physics.info/refraction/ 3\. Newlight Photonics Inc. – Your source for BBO, LBO, BiBO, KTP, KTA, Nd:YAG, Nd:YVO4 crystals, polarizers, waveplates, http://www.newlightphotonics.com/quartz-properties.html 4\. Refractive Index and Critical Angle \- United States Faceters Guild, https://usfacetersguild.org/refractive-index-and-critical-angle/ 5\. Refractive index \- Wikipedia, https://en.wikipedia.org/wiki/Refractive\_index 6\. 5.2.2: The Velocity of Light in Crystals and the Refractive Index \- Geosciences LibreTexts, https://geo.libretexts.org/Bookshelves/Geology/Mineralogy\_(Perkins\_et\_al.)/05%3A\_Optical\_Mineralogy/5.02%3A\_Light\_and\_the\_Properties\_of\_Light/5.2.02%3A\_The\_Velocity\_of\_Light\_in\_Crystals\_and\_the\_Refractive\_Index 7\. Marcel Tolkowsky (figure 1\) was born in Antwerp in 1899, on the eve of the twentieth century. He died in New York 92 years later, in February 1991 \- Denney Jewelers, http://www.denneyjewelers.com/html/New\_Folder/tolkowsky.html 8\. The Ultimate Guide to Tolkowsky Ideal Cut Diamonds \- PriceScope, https://www.pricescope.com/education/diamonds/tolkowsky-ideal-cut-diamond 9\. The "Diamond Design" by Tolkowsky. A Study of the Reflection and Refraction of Light in Diamond | OctoNus, https://www.octonus.com/projects/diamond-cut-study/the-diamond-design-by-tolkowsky-1919 10\. Summary of: Diamond Design \-- by Marcel Tolkowsky. Edited by ..., https://www.folds.net/diamond/ 11\. Expert Guide to Tolkowsky Ideal Cut Diamonds \- Whiteflash, https://www.whiteflash.com/diamond-education/expert-guide-to-tolkowsky-ideal-cut-diamonds/ 12\. Refractive Index and Dispersion Explained \- Harro Gem \- Custom Cut Moissanite, https://harrogem.com/2018/06/17/1177-2/ 13\. Modeling the Appearance of the Round Brilliant Cut Diamond: An Analysis of Fire, and More about Brilliance \- GIA, https://www.gia.edu/doc/modeling-the-appearance-of-the-round-brilliant-cut-diamond.pdf 14\. The Benefits of Hearts and Arrows Optical Symmetry \- Victor Canera, https://www.victorcanera.com/education/diamonds/advantages-of-hearts-and-arrows-diamonds 15\. How Hearts and Arrows Diamonds are Graded | Whiteflash, https://www.whiteflash.com/diamond-education/how-are-hearts-arrows-diamonds-graded/ 16\. HEARTS & ARROWS \- JannPaul, https://www.jannpaul.com/content/hearts-arrows 17\. Realistic Rendering of Birefringency in Uniaxial Crystals \- Research Unit of Computer Graphics | TU Wien, https://www.cg.tuwien.ac.at/research/publications/2008/weidlich\_2007\_rrbuc/weidlich\_2007\_rrbuc-paper.pdf 18\. 1 Crystal Optics \- Wiley-VCH, https://application.wiley-vch.de/books/sample/3527413855\_c01.pdf 19\. Optical Birefringence \- Evident Scientific, https://evidentscientific.com/en/microscope-resource/knowledge-hub/lightandcolor/birefringence 20\. Birefringence Variations with Crystal Orientation \- Evident Scientific, https://evidentscientific.com/en/microscope-resource/tutorials/polarizedlight/crystalwavefronts 21\. Dispersion and Walkoff Matter \- Gamdan Optics, https://www.gamdan.com/blog/introduction-to-walkoff 22\. Non-linear Optics III (Phase-matching & frequency conversion), https://nmr.physics.ox.ac.uk/oxonly/C2/NLO3\_2010.pdf 23\. NONLINEAR OPTICS (PHYC/ECE 568), https://msbahae.unm.edu/Courses/568%20Nonlinear%20Optics/hw22\_3\_sol.pdf 24\. OPTICAL MINERALOGY-2.docx \- Ninova, https://ninova.itu.edu.tr/tr/dersler/maden-fakultesi/2315/jeo-242/ekkaynaklar?g199883 25\. Learn How to Cut Gemstones \- International Gem Society IGS, https://www.gemsociety.org/faceting-made-easy/Faceting-Made-Easy-Trevor-Hannam.pdf 26\. questions on the nature of gem cutting and light rendering \- Page 2 \- GemologyOnline.com, https://www.gemologyonline.com/Forum/phpBB2/viewtopic.php?t=25909\&start=15 27\. understanding optimal pavilion angles \- Aussie Lapidary Forum, https://aussielapidaryforum.com/forum/index.php?topic=3165.0 28\. Polariscope \- The Gemology Project, http://gemologyproject.com/wiki/index.php?title=Polariscope 29\. Learning to use the conoscope \- Gem Related Discussion \- IGS Forums, https://forums.gemsociety.org/t/learning-to-use-the-conoscope/59 30\. Faceting Made Easy, Part 1: Gemstone Properties \- International Gem Society, https://www.gemsociety.org/article/faceting-made-easy-part-1-gemstone-properties/ 31\. Double-pass rotating z-cut quartz plate as a rapidly variable waveplate, https://opg.optica.org/oe/fulltext.cfm?uri=oe-33-13-28739 32\. US8422119B1 \- Compensation of beam walkoff in nonlinear crystal using cylindrical lens \- Google Patents, https://patents.google.com/patent/US8422119B1/en 33\. What is the ASET ® Map on an AGS Ideal ® Report? \- GIA, https://www.gia.edu/gia-faq-other-services-what-is-the-aset-map 34\. ASET Scope \- cut quality assessment scope for round diamonds \- PriceScope, https://www.pricescope.com/tools/aset-scope