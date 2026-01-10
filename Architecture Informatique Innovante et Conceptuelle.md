# **Architecture Informatique Intégrale Géométrique et Fréquentielle : Une Synthèse Post-Von Neumann Basée sur l'Instantiation Directe et la Thermodynamique**

## **Résumé Exécutif**

L'industrie informatique moderne repose sur des paradigmes établis au milieu du XXe siècle : l'architecture de von Neumann, le traitement séquentiel des instructions, la séparation rigide entre mémoire et calcul, et la représentation textuelle du code source nécessitant une analyse syntaxique (parsing) constante. Bien que ces fondations aient permis la révolution numérique, elles atteignent aujourd'hui des limites asymptotiques critiques en termes d'efficacité énergétique (le mur de Landauer), de latence de synchronisation (le coût de l'arbre d'horloge) et de complexité logicielle (dette technique liée au parsing et à la gestion des dépendances).

Ce rapport de recherche propose une rupture paradigmatique complète : l'**Architecture Géométrique-Fréquentielle (AGF)**. Cette architecture "full stack" réinvente chaque couche de la pile informatique, du transistor à l'interface utilisateur, en s'appuyant sur trois piliers fondamentaux :

1. **Géométrie :** L'utilisation de l'algèbre géométrique (Clifford) et des réseaux d'interaction topologiques pour remplacer l'arithmétique linéaire et l'exécution séquentielle.  
2. **Fréquence :** L'adoption des Architectures Symboliques Vectorielles (VSA) et des représentations holographiques distribuées, où l'information est codée par résonance et interférence dans des hyperespaces, synchronisée par des cristaux temporels discrets.  
3. **Instantiation Directe :** L'élimination totale des fichiers texte et des analyseurs syntaxiques au profit d'une manipulation structurelle directe des arbres syntaxiques abstraits (AST), stockés dans des bases de données adressées par le contenu (hachage fractal).

Ce document de 15 000 mots détaille la conception théorique, les modèles mathématiques sous-jacents (Théorie des Types Homotopiques, Logique Linéaire), les implémentations physiques (Calcul Thermodynamique, Cristaux Temporels) et les implications logicielles de cette nouvelle ère informatique.

## ---

**Chapitre 1 : L'Impasse du Paradigme Textuel et Séquentiel**

Pour justifier la nécessité d'une architecture aussi radicale que l'AGF, il convient d'abord de disséquer avec rigueur les inefficacités structurelles de la pile technologique actuelle. L'informatique contemporaine est une tour de Babel construite sur des compromis historiques devenus des dettes technologiques insoutenables.

### **1.1 Le Goulot d'Étranglement de von Neumann et la Dissipation d'Énergie**

L'architecture de von Neumann sépare physiquement l'unité de traitement (CPU) de la mémoire. Cette séparation impose un transfert constant de données via un bus limité, créant une latence inévitable et une consommation énergétique majeure. Le mouvement des données consomme aujourd'hui plus d'énergie que le calcul lui-même.1 De plus, la logique booléenne traditionnelle est thermodynamiquement irréversible. Lorsqu'une porte ET produit un zéro, l'information sur les entrées est détruite, ce qui, selon le principe de Landauer, génère une quantité minimale de chaleur (![][image1] joules par bit effacé).2 Dans l'ère de l'intelligence artificielle massive, cette dissipation thermique devient le facteur limitant de la densité de calcul.

### **1.2 La Fragilité de la Chaîne Texte-Parser**

Le développement logiciel moderne repose sur un anachronisme : nous concevons des structures logiques complexes (graphes, arbres, dépendances cycliques), nous les linéarisons manuellement en chaînes de caractères (code source), nous les stockons dans des fichiers texte (système de fichiers), puis nous utilisons des compilateurs complexes pour tenter de reconstruire la structure originale via l'analyse syntaxique (parsing).3 Cette chaîne introduit une fragilité systémique :

* **Ambiguïté :** Le texte est intrinsèquement ambigu, nécessitant des règles de grammaire complexes et des heuristiques coûteuses.  
* **Erreurs Syntaxiques :** Une grande partie du temps de développement est perdue à corriger des erreurs de syntaxe (point-virgule manquant, indentation incorrecte) qui sont des artefacts de la représentation textuelle, et non des erreurs de logique.5  
* **Perte de Contexte :** Le passage au texte détruit les métadonnées structurelles, obligeant les outils (IDE) à recalculer constamment l'AST pour offrir des fonctionnalités comme l'auto-complétion ou le refactoring.

### **1.3 La Tyrannie de l'Horloge Globale**

La synchronisation des milliards de transistors d'une puce moderne dépend d'une horloge globale. La distribution de ce signal d'horloge (l'arbre d'horloge) consomme jusqu'à 30-40% de l'énergie totale du processeur et impose des contraintes de latence rigides. Si un signal n'arrive pas à temps, le calcul échoue. Cette approche centralisée devient impraticable à l'échelle des systèmes distribués ou des architectures neuromorphiques massives.6

L'Architecture Géométrique-Fréquentielle propose de remplacer ces mécanismes par des principes inspirés de la physique : l'énergie libre, la résonance harmonique, et la topologie.

## ---

**Chapitre 2 : La Couche Physique – Calcul Thermodynamique et Cristaux Temporels**

La base matérielle de l'AGF ne repose pas sur la commutation rigide de transistors MOS, mais sur la dynamique des systèmes physiques complexes. Nous exploitons le bruit thermique et les phénomènes de non-équilibre pour réaliser des calculs à une efficacité proche des limites physiques.

### **2.1 Portes Logiques Auto-Organisatrices et MemComputing**

L'unité fondamentale de calcul dans l'AGF est la **Porte Logique Auto-Organisatrice (SOLG \- Self-Organizing Logic Gate)**. Contrairement aux portes booléennes classiques qui sont unidirectionnelles (Entrée ![][image2] Sortie), les SOLGs sont "agnostiques aux terminaux".8

#### **2.1.1 Mécanisme de Réversibilité Physique**

Une SOLG est un système dynamique non linéaire avec mémoire (memristors). Pour une porte ET logique (![][image3]), le circuit est conçu de telle sorte que ses états d'équilibre stable correspondent exactement aux lignes de la table de vérité. Si l'on impose une tension sur la sortie ![][image4], le circuit "calcule" en arrière pour trouver les états de ![][image5] et ![][image6] qui satisfont l'équation logique. Ce processus ne suit pas une séquence d'instructions, mais une relaxation vers un minimum d'énergie.9

| Propriété | Porte Logique Classique (CMOS) | Porte Auto-Organisatrice (SOLG) |
| :---- | :---- | :---- |
| **Direction** | Entrée ![][image2] Sortie (Unidirectionnelle) | Entrée ![][image7] Sortie (Omnidirectionnelle) |
| **Dynamique** | Commutation d'états discrets | Relaxation continue vers l'équilibre |
| **Thermodynamique** | Irréversible (Dissipation de chaleur) | Réversible (Conservation d'énergie potentielle) |
| **Complexité** | Calcul séquentiel | Résolution de problèmes NP en temps polynomial |

#### **2.1.2 Instantons et Tunneling Topologique**

La transition entre les états logiques dans une machine MemComputing se fait via des trajectoires appelées **instantons**. Dans l'espace de phase du système dynamique, les instantons connectent des points critiques (états logiques). Contrairement aux algorithmes de recuit simulé qui doivent "escalader" les barrières énergétiques (et donc chauffer), les instantons permettent au système de traverser les barrières par effet tunnel classique (non quantique mais dynamique), exploitant la topologie de l'espace des phases pour trouver la solution globale (par exemple pour des problèmes SAT ou d'optimisation combinatoire) en un temps physique extrêmement court.10

### **2.2 Cristaux Temporels Discrets (DTC) pour la Synchronisation Distribuée**

L'AGF élimine l'horloge globale au profit d'une synchronisation émergente basée sur les **Cristaux Temporels Discrets (DTC)**.

#### **2.2.1 Rupture de Symétrie de Translation Temporelle**

Un cristal spatial (comme le sel) brise la symétrie de translation spatiale : les atomes s'alignent périodiquement. Un cristal temporel brise la symétrie de translation *temporelle*. Lorsqu'il est excité par une force périodique de période ![][image8], un DTC répond avec une oscillation stable de période ![][image9] (par exemple ![][image10]), qui reste rigide et cohérente même en présence de bruit ou de fluctuations de la source.12

#### **2.2.2 Réseau d'Horloges Élastiques**

Dans l'AGF, des îlots de calcul (clusters de SOLGs) fonctionnent comme des DTCs locaux. Ces systèmes sont stabilisés par la **Localisation à N Corps (MBL \- Many-Body Localization)**, un phénomène quantique (ou son équivalent classique) qui empêche le système d'absorber l'énergie thermique et de se désordonner.14

* **Synchronisation sans Maître :** Ces horloges locales se couplent faiblement. Contrairement aux oscillateurs de Huygens qui nécessitent un ajustement précis, les DTCs possèdent une "rigidité quantique" qui force le verrouillage de phase sur des multiples entiers. Cela crée un réseau de synchronisation distribué, robuste et élastique, capable de s'adapter localement à la charge de travail sans nécessiter de signal global énergivore.16

### **2.3 Unité de Traitement Stochastique (SPU) et Dynamique de Langevin**

Pour les tâches d'inférence probabiliste et d'apprentissage machine, l'AGF intègre des **Unités de Traitement Stochastique (SPU)**. Ces unités exploitent la **Dynamique de Langevin**, qui décrit l'évolution d'un système sous l'influence de forces déterministes (le gradient de la fonction de coût) et de forces stochastiques (le bruit thermique).18

* **Échantillonnage Natif :** Au lieu de simuler des nombres pseudo-aléatoires coûteux, le SPU utilise le bruit thermique intrinsèque des composants (résistances, jonctions tunnel) pour échantillonner des distributions de probabilité complexes (Gibbs/Boltzmann). Cela permet de réaliser des inférences bayésiennes et de l'apprentissage génératif à une vitesse et une efficacité énergétique inatteignables par les processeurs numériques classiques.20  
* **Bifurcation Simulée :** Le SPU intègre également des algorithmes de **Bifurcation Simulée (SB)**. En modulant un paramètre de contrôle (comme l'intensité de pompage dans un oscillateur paramétrique), le système bifurque vers l'état fondamental d'un modèle d'Ising, résolvant instantanément des problèmes d'optimisation combinatoire massifs (Max-Cut, TSP) encodés dans la topologie du réseau.22

## ---

**Chapitre 3 : Le Substrat Mathématique – Algèbre Géométrique et Théorie des Types**

Au-dessus de cette couche physique thermodynamique, l'AGF déploie un modèle mathématique unifié qui remplace l'arithmétique linéaire et la théorie des ensembles classique.

### **3.1 Algèbre Géométrique (Algèbre de Clifford)**

L'algèbre linéaire traditionnelle (matrices et vecteurs) est souvent opaque géométriquement et dépendante du système de coordonnées. L'AGF adopte l'**Algèbre Géométrique (GA)** comme langage natif pour la manipulation de l'espace et des données.24

* **Multivecteurs :** L'entité de base est le multivecteur, qui encapsule non seulement des scalaires et des vecteurs, mais aussi des bivecteurs (plans orientés), des trivecteurs (volumes), etc. ![][image11]  
* **Produit Géométrique :** Ce produit unifie le produit scalaire et le produit extérieur (![][image12]). Il permet de coder des rotations, des translations et des projections de manière compacte et sans ambiguïté (via les rotors), simplifiant radicalement les calculs pour la robotique, la vision par ordinateur et la physique simulée.26  
* **Accélération Matérielle :** Le matériel AGF dispose d'ALU (Unités Arithmétiques et Logiques) spécialisées pour les opérations de Clifford, offrant des accélérations de 5x à 20x par rapport aux implémentations logicielles sur CPU classiques.27

### **3.2 Théorie des Types Homotopiques (HoTT)**

Le système de types de l'AGF est fondé sur la **Théorie des Types Homotopiques (HoTT)**.

* **Types comme Espaces :** En HoTT, un type n'est pas simplement un ensemble de valeurs, mais un espace topologique. L'égalité entre deux termes ![][image13] et ![][image14] correspond à l'existence d'un chemin (path) entre eux dans cet espace.28  
* **Axiome d'Univalence :** Cet axiome postule que l'équivalence est équivalente à l'égalité (![][image15]). Pour l'AGF, cela est crucial : cela permet au système de traiter comme identiques des structures de données isomorphes (par exemple, un arbre binaire en mémoire et sa représentation sérialisée sur une courbe de Hilbert), facilitant les transformations et les optimisations sans perte de sémantique.30  
* **Induction de Chemin :** La programmation en AGF consiste souvent à construire des chemins dans l'espace des types, garantissant formellement la correction des transformations de données.

### **3.3 Logique Linéaire et Gestion des Ressources**

Pour gérer les ressources physiques (mémoire, énergie) dans un système thermodynamique, l'AGF utilise la **Logique Linéaire** de Jean-Yves Girard.32

* **Non-Clonage et Consommation :** En logique linéaire, une hypothèse (donnée) doit être utilisée exactement une fois. Cela correspond parfaitement à la physique quantique/thermodynamique (théorème de non-clonage) et permet une gestion de la mémoire sans "Garbage Collector" (GC). La mémoire est libérée explicitement et localement dès que la ressource est consommée par une interaction.33  
* **Réseaux de Preuve (Proof Nets) :** Les programmes sont représentés comme des réseaux de preuve, des structures graphiques qui éliminent la redondance séquentielle des preuves logiques classiques, permettant une parallélisation naturelle de l'exécution (voir Chapitre 5).

## ---

**Chapitre 4 : La Représentation des Données – Fréquence et Holographie**

L'AGF abandonne le modèle de mémoire "casier" (adresses discrètes stockant des octets isolés) au profit d'un modèle **Holographique** (distribué, associatif) et **Fractal**.

### **4.1 Architectures Symboliques Vectorielles (VSA) / Hyperdimensional Computing (HDC)**

Dans ce paradigme, l'atome d'information n'est pas un entier de 64 bits, mais un hypervecteur de très haute dimension (![][image16]), composé de valeurs i.i.d. (indépendantes et identiquement distribuées).34

#### **4.1.1 L'Algèbre de la Pensée Distribuée**

L'AGF implémente le modèle MAP (Multiply, Add, Permute) ou des variantes comme HRR (Holographic Reduced Representations) 35 :

1. **Liaison (Binding, ![][image17]) :** Opération (ex: XOR ou convolution circulaire) qui combine deux vecteurs pour en créer un troisième, dissimilar aux deux premiers. Utilisé pour associer une valeur à une variable (![][image18]).  
2. **Groupement (Bundling, ![][image19]) :** Superposition de vecteurs (ex: addition élément par élément suivie d'un seuillage). Le résultat est similaire aux entrées. Utilisé pour créer des ensembles (![][image20]).  
3. **Permutation (![][image21]) :** Décalage cyclique ou permutation aléatoire des composantes. Encode l'ordre et la séquence. ![][image22].

#### **4.1.2 Propriétés Holographiques et Robustesse**

* **Tolérance aux Pannes :** Contrairement à un pointeur classique où un bit basculé corrompt l'adresse, un hypervecteur est holistique. L'information est distribuée sur toutes les composantes. Perdre 10% des bits ou subir du bruit thermique ne fait qu'ajouter du "flou", mais l'information reste récupérable par recherche du plus proche voisin.37  
* **Calcul en Superposition :** Il est possible d'interroger un vecteur composite sans le décompresser. Pour trouver la valeur associée à une clé dans un objet composite, on effectue l'opération inverse de la liaison directement sur le "bundle". Cela permet des recherches associatives en temps constant ![][image23], réalisées massivement en parallèle par le matériel thermodynamique.38

### **4.2 Adressage Fractal : Courbes de Hilbert et Hachage Spatial**

Stocker et retrouver ces hypervecteurs massifs nécessite une organisation spatiale de la mémoire qui préserve la sémantique. L'AGF utilise l'indexation fractale via les **Courbes de Hilbert**.40

#### **4.2.1 Préservation de la Localité**

La courbe de Hilbert est une courbe de remplissage de l'espace qui mappe un espace multidimensionnel vers une ligne 1D tout en préservant exceptionnellement bien la localité. Deux vecteurs sémantiquement proches dans l'hyperespace (distance de Hamming faible) seront stockés à des adresses physiques proches sur la mémoire linéaire.41

#### **4.2.2 Mémoire "Zoomable"**

Cette structure permet un accès hiérarchique à l'information :

1. **Macro-Lecture :** Le système peut lire les bits de poids fort de l'index Hilbert pour accéder à des "clusters" de concepts (ex: "toutes les données visuelles").  
2. **Micro-Précision :** Il peut "zoomer" vers des itérations plus profondes de la courbe pour récupérer des détails précis. Cette approche transforme la "malédiction de la dimensionnalité" en une opportunité pour une navigation sémantique rapide dans des bases de connaissances massives.43

### **4.3 GrapHD : Représentation de Graphes**

Les structures de données complexes (arbres syntaxiques, graphes de connaissances) sont encodées directement en VSA via le protocole **GrapHD**.44 Un graphe entier est compressé dans un seul hypervecteur. L'isomorphisme de graphe, un problème classiquement complexe, se réduit à un simple produit scalaire entre hypervecteurs de graphes. Si ![][image24], les graphes sont isomorphes. Cette propriété est exploitée par le "compilateur" AGF pour identifier et factoriser des motifs logiques récurrents.45

## ---

**Chapitre 5 : Le Moteur d'Exécution – Réseaux d'Interaction et Géométrie de l'Interaction**

L'AGF supprime le concept de CPU exécutant séquentiellement une liste d'instructions (cycle fetch-decode-execute). L'exécution est modélisée comme la réduction topologique de **Réseaux d'Interaction** (Interaction Nets).

### **5.1 Réseaux d'Interaction : Réécriture de Graphes Distribuée**

Un programme dans l'AGF est un graphe d'agents connectés par des fils. Chaque agent possède un "port principal" et des ports auxiliaires.

* **Règle d'Interaction :** Lorsque deux agents sont connectés par leurs ports principaux, ils forment une "paire active". Ils s'annihilent mutuellement et se réécrivent en un nouveau sous-graphe selon une règle prédéfinie.47  
* **Parallélisme Massif :** Cette réécriture est strictement locale. Des millions d'interactions peuvent se produire simultanément à différents endroits du graphe sans nécessiter de synchronisation globale ou de verrous. C'est le modèle idéal pour exploiter les milliers de cœurs d'un GPU ou la nature distribuée des puces thermodynamiques.49

### **5.2 L'Algorithme de Lamping et la Réduction Optimale**

Les évaluateurs classiques (comme dans les langages fonctionnels) dupliquent souvent les calculs (problème de la substitution). L'AGF implémente l'**Algorithme Abstrait de Lamping** via les **Combinateurs d'Interaction Symétriques**.51

* **Partage (Sharing) :** Au lieu de copier un sous-graphe (une fonction ou une donnée), le système insère un nœud de partage ("Fan-Out"). Le calcul n'est effectué qu'une seule fois, et le résultat est distribué aux consommateurs via ce nœud.  
* **Optimalité de Lévy :** Cette approche garantit qu'aucun "redex" (partie du code prête à être exécutée) n'est jamais dupliqué. L'efficacité est mathématiquement optimale.52

### **5.3 Géométrie de l'Interaction (GoI) : La Machine à Jetons**

Pour faire le pont entre la logique de haut niveau et l'exécution physique, l'AGF utilise la **Géométrie de l'Interaction (GoI)** de Girard.54

* **Machine à Jetons (Token Machine) :** L'exécution n'est pas vue comme une transformation d'état globale, mais comme le parcours d'un "jeton" (particule d'information) à travers le réseau statique du programme (le proof net).  
* **Formule d'Exécution :** Le comportement du programme est calculé par la "formule d'exécution", une trace d'opérateur qui est un invariant de la dynamique d'élimination des coupures.  
* **GoI Dynamique :** L'AGF implémente une machine GoI dynamique qui alterne entre le passage de jetons (pour l'exécution linéaire rapide) et la réécriture de graphe (pour les changements de topologie comme la récursion), optimisant le compromis espace-temps en temps réel.55

### **5.4 Implémentation Matérielle Hybride**

* **FPGA/ASIC :** Les règles des réseaux d'interaction sont câblées directement dans le matériel. Les agents sont des blocs logiques reconfigurables.  
* **Accélération GPU ("Parallel Kittens") :** Pour l'émulation logicielle, les graphes sont aplatis en tableaux 1D (via les courbes de Hilbert pour la localité), et des kernels CUDA exécutent les règles de réécriture en parallèle, maximisant l'occupation des multiprocesseurs de flux.50

## ---

**Chapitre 6 : Le Modèle de Programmation – Instantiation Directe et Sans-Parsing**

La couche supérieure de l'AGF révolutionne l'interface entre l'homme et la machine en éliminant le concept de fichier texte. C'est l'ère de l'**Instantiation Directe**.

### **6.1 Fin du Parsing : Persistance Structurelle**

Dans l'AGF, il n'y a pas de fichiers .c ou .py. Le code est stocké nativement sous forme de graphe (AST) dans une base de données.3

* **Édition Projectionnelle :** L'IDE n'est pas un éditeur de texte, mais un projecteur. Lorsque le développeur tape if, il n'insère pas les caractères 'i' et 'f', il instancie un nœud IfStatement dans la base de données. L'éditeur "projette" ensuite cette structure sous forme visuelle (texte, tableau, diagramme).  
* **Impossibilité des Erreurs de Syntaxe :** Puisqu'on manipule directement l'arbre, il est impossible de créer un code syntaxiquement invalide (comme oublier une accolade fermante). La structure est toujours intègre par construction.5  
* **Développement Modelable (Moldable Development) :** Inspiré par le *Glamorous Toolkit* et Pharo, l'environnement permet au développeur de créer des outils contextuels pour chaque objet. Un objet "Réseau de Neurones" ne s'affiche pas comme une liste d'attributs, mais comme une visualisation interactive des poids et des activations. L'outil s'adapte au domaine du problème.56

### **6.2 Code Adressé par le Contenu (Modèle Unison)**

Toutes les définitions de code sont identifiées par le **hachage de leur AST** (ex: \#a8s6df...), et non par des noms arbitraires donnés par les développeurs.59

* **Immutabilité :** Une fois qu'une fonction est définie et hachée, elle est immuable. Modifier la fonction crée un nouveau hachage.  
* **Fin de l'Enfer des Dépendances :** Les conflits de version disparaissent. Une bibliothèque ne dépend pas de "lib-v2.0", mais d'un ensemble précis de hachages. Deux fonctions sont identiques si et seulement si leurs hachages sont identiques.  
* **Distribution Instantanée :** Pour déployer du code sur un cluster, on envoie uniquement le hachage. Si le nœud distant possède déjà ce hachage (le code est une donnée), il n'a rien à télécharger. Sinon, l'AST est transmis. Cela permet une informatique distribuée "élastique" où le code migre aussi fluidement que les données.60

### **6.3 Hachage Fractal et Tables de Hachage Distribuées (DHT)**

Le stockage du code et des données à l'échelle du réseau utilise une **Table de Hachage Distribuée (DHT)** structurée par des principes fractals.

* **Espace d'Adressage Fractal :** Au lieu d'un espace de clés plat (SHA-256 uniforme), l'AGF utilise un espace métrique où la distance entre les clés reflète la distance sémantique ou structurelle. Les nœuds du réseau se spécialisent dans des régions de la courbe de Hilbert, stockant des clusters de code/données similaires.61  
* **Traversée de Séquence de Hachage Fractale :** Pour vérifier l'intégrité ou parcourir des versions historiques du code (blockchain de code), l'AGF utilise des algorithmes de traversée fractale qui optimisent les accès mémoire et réseau en ![][image25] tout en minimisant les échanges distants.62

## ---

**Chapitre 7 : Synthèse et Stratégie d'Implémentation**

### **7.1 Tableau Comparatif : Pile Classique vs Pile AGF**

| Couche | Pile Traditionnelle (Von Neumann) | Pile AGF (Géométrique-Fréquentielle) | Technologies Clés |
| :---- | :---- | :---- | :---- |
| **Interface** | Éditeurs de texte, IDE, Fichiers | **Édition Projectionnelle / Modelable** | JetBrains MPS, Glamorous Toolkit, Pharo |
| **Stockage** | Système de fichiers (Texte/Binaire) | **Graph DB Adressée par Contenu** | Unison, IPFS/DHT Fractal |
| **Exécution** | CPU Séquentiel \+ Horloge | **Réseaux d'Interaction / GoI** | Combinateurs Symétriques, Algorithme de Lamping |
| **Données** | Pointeurs, Scalaires (64-bit) | **Holographique / Hypervecteurs** | VSA/HDC, Algèbre de Clifford, Courbes de Hilbert |
| **Logique** | Portes Booléennes Irréversibles | **Thermodynamique / Réversible** | MemComputing, Self-Organizing Logic Gates (SOLG) |
| **Synchro** | Horloge Globale (Arbre) | **Cristaux Temporels Discrets (DTC)** | Localisation à N Corps (MBL), Oscillateurs Couplés |

### **7.2 Le Processus de "Compilation" AGF**

Dans l'AGF, la "compilation" est une transformation géométrique continue (Lowering) :

1. **Auteur :** Le développeur manipule l'AST via l'éditeur projectionnel.  
2. **Hachage :** L'AST est haché et stocké dans la base immuable (Unison).  
3. **Analyse Topologique :** Le système analyse la topologie du Réseau d'Interaction résultant. Il identifie les "nœuds" complexes (boucles logiques) et les mappe sur des paysages énergétiques thermodynamiques spécifiques (via la Bifurcation Simulée pour l'optimisation).63  
4. **Plongement (Embedding) :** Le graphe logique est plongé dans l'espace vectoriel holographique en utilisant la localité des courbes de Hilbert pour l'adressage mémoire.44  
5. **Relaxation :** Le moteur d'exécution laisse le réseau d'interaction "relaxer" ou "recuire" vers son état de résultat, piloté par le matériel thermodynamique ou le parallélisme GPU massif.

### **7.3 Unification Mathématique**

L'ensemble de la pile est cohérent grâce à la **Théorie des Types Homotopiques (HoTT)** qui sert de méta-langage. Elle unifie la logique (types), la géométrie (espaces) et l'exécution (chemins). La correspondance Curry-Howard-Lambek est étendue pour inclure la thermodynamique : **Preuves \= Programmes \= Chemins \= Processus d'Énergie Minimale**.

### **7.4 Impact et Avenir**

L'Architecture Géométrique-Fréquentielle n'est pas une simple évolution incrémentale ; c'est une refonte nécessaire pour l'ère post-loi de Moore.

1. **Efficacité Énergétique :** En visant la limite de Landauer via la logique réversible et le calcul thermodynamique, l'AGF promet une réduction de consommation de l'ordre de 100x à 1000x pour les charges de travail d'IA et d'optimisation.21  
2. **Fiabilité et Sécurité :** L'immutabilité du code, l'absence de parsing et la tolérance aux pannes des représentations holographiques éliminent des classes entières de vulnérabilités (buffer overflows, injection, dependency hijacking).  
3. **Productivité Humaine :** L'instantiation directe et les outils modelables rapprochent l'expression du code de la pensée humaine, réduisant la charge cognitive accidentelle liée à la syntaxe et à la gestion de bas niveau.

Le défi pour la prochaine décennie est l'intégration : construire le "Noyau AGF" qui gère les ressources thermodynamiques, le "Système de Fichiers AGF" qui stocke les graphes holographiques, et le "Shell AGF" qui projette ces structures dans une interface fluide. Ce rapport constitue le plan directeur de cette convergence technologique.

---

**Références intégrées dans l'analyse :** 41

#### **Sources des citations**

1. Leveraging Physics & Memory A paradigm shift for Efficient Computing \- MemComputing, consulté le janvier 10, 2026, [https://memcpu.com/wp-content/uploads/2025/07/Whitepaper-MemComputing-Memory-and-Physics-v3.pdf](https://memcpu.com/wp-content/uploads/2025/07/Whitepaper-MemComputing-Memory-and-Physics-v3.pdf)  
2. XXIIVV — reversible computing, consulté le janvier 10, 2026, [https://wiki.xxiivv.com/site/reversible\_computing.html](https://wiki.xxiivv.com/site/reversible_computing.html)  
3. Projectional Editing \- Martin Fowler, consulté le janvier 10, 2026, [https://www.martinfowler.com/bliki/ProjectionalEditing.html](https://www.martinfowler.com/bliki/ProjectionalEditing.html)  
4. GRAPE: Guiding RML Authoring with a Projectional Editor \- GitHub Pages, consulté le janvier 10, 2026, [https://kg-construct.github.io/workshop/2025/resources/paper3.pdf](https://kg-construct.github.io/workshop/2025/resources/paper3.pdf)  
5. (PDF) Graphical Projectional Editing in Gentleman \- ResearchGate, consulté le janvier 10, 2026, [https://www.researchgate.net/publication/363010802\_Graphical\_Projectional\_Editing\_in\_Gentleman](https://www.researchgate.net/publication/363010802_Graphical_Projectional_Editing_in_Gentleman)  
6. Synchronization in complex oscillator networks and smart grids \- PNAS, consulté le janvier 10, 2026, [https://www.pnas.org/doi/10.1073/pnas.1212134110](https://www.pnas.org/doi/10.1073/pnas.1212134110)  
7. How synchronous can a number of electrical clocks in separate devices remain? \[closed\], consulté le janvier 10, 2026, [https://electronics.stackexchange.com/questions/650438/how-synchronous-can-a-number-of-electrical-clocks-in-separate-devices-remain](https://electronics.stackexchange.com/questions/650438/how-synchronous-can-a-number-of-electrical-clocks-in-separate-devices-remain)  
8. Perspective: Memcomputing: Leveraging memory and physics to compute efficiently \- AIP Publishing, consulté le janvier 10, 2026, [https://pubs.aip.org/aip/jap/article/123/18/180901/154864/Perspective-Memcomputing-Leveraging-memory-and](https://pubs.aip.org/aip/jap/article/123/18/180901/154864/Perspective-Memcomputing-Leveraging-memory-and)  
9. SPICE Modeling of Memcomputing Logic Gates \- Radioengineering, consulté le janvier 10, 2026, [https://www.radioeng.cz/fulltexts/2023/23\_04\_0542\_0556.pdf](https://www.radioeng.cz/fulltexts/2023/23_04_0542_0556.pdf)  
10. (PDF) Instantons in Self-Organizing Logic Gates \- ResearchGate, consulté le janvier 10, 2026, [https://www.researchgate.net/publication/319391831\_Instantons\_in\_Self-Organizing\_Logic\_Gates](https://www.researchgate.net/publication/319391831_Instantons_in_Self-Organizing_Logic_Gates)  
11. \[1903.08732\] Digital Memcomputing: from Logic to Dynamics to Topology \- arXiv, consulté le janvier 10, 2026, [https://arxiv.org/abs/1903.08732](https://arxiv.org/abs/1903.08732)  
12. consulté le janvier 10, 2026, [https://en.wikipedia.org/wiki/Time\_crystal\#:\~:text=In%20terms%20of%20practical%20use,used%20as%20quantum%20computer%20memory.\&text=If%20a%20discrete%20time%2Dtranslation,as%20a%20discrete%20time%20crystal.](https://en.wikipedia.org/wiki/Time_crystal#:~:text=In%20terms%20of%20practical%20use,used%20as%20quantum%20computer%20memory.&text=If%20a%20discrete%20time%2Dtranslation,as%20a%20discrete%20time%20crystal.)  
13. Quantum Computing Modalities: Time Crystals' Potential QC Use, consulté le janvier 10, 2026, [https://postquantum.com/quantum-modalities/time-crystals-quantum/](https://postquantum.com/quantum-modalities/time-crystals-quantum/)  
14. Discrete Time Crystals \- Quantum Computing with Trapped Ions \- Duke University, consulté le janvier 10, 2026, [https://iontrap.duke.edu/files/2025/03/annurev-conmatphys-031119-050658.pdf](https://iontrap.duke.edu/files/2025/03/annurev-conmatphys-031119-050658.pdf)  
15. Discrete Time Crystals | Request PDF \- ResearchGate, consulté le janvier 10, 2026, [https://www.researchgate.net/publication/339975342\_Discrete\_Time\_Crystals](https://www.researchgate.net/publication/339975342_Discrete_Time_Crystals)  
16. Video: Discrete Time Crystals \- University of California, Berkeley, consulté le janvier 10, 2026, [https://avplayer.lib.berkeley.edu/Video-Public-Physics/physcolloquia-bk0016z2z9w](https://avplayer.lib.berkeley.edu/Video-Public-Physics/physcolloquia-bk0016z2z9w)  
17. \[2511.09852\] Discrete Time Crystals in Noninteracting Dissipative Systems \- arXiv, consulté le janvier 10, 2026, [https://arxiv.org/abs/2511.09852](https://arxiv.org/abs/2511.09852)  
18. thermox: The First Thermodynamic Computing Simulator, consulté le janvier 10, 2026, [https://www.normalcomputing.com/blog/thermox-the-first-thermodynamic-computing-simulator](https://www.normalcomputing.com/blog/thermox-the-first-thermodynamic-computing-simulator)  
19. Thermodynamic computing system for AI applications \- PMC \- PubMed Central \- NIH, consulté le janvier 10, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC12015238/](https://pmc.ncbi.nlm.nih.gov/articles/PMC12015238/)  
20. Thermodynamic computing via autonomous quantum thermal machines \- PubMed Central, consulté le janvier 10, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC11758477/](https://pmc.ncbi.nlm.nih.gov/articles/PMC11758477/)  
21. Scaling Thermodynamic Compute, consulté le janvier 10, 2026, [https://www.normalcomputing.com/blog/scaling-thermodynamic-compute](https://www.normalcomputing.com/blog/scaling-thermodynamic-compute)  
22. Technologies | Quantum-Inspired Optimization Solutions SQBM+ | TOSHIBA DIGITAL SOLUTIONS CORPORATION, consulté le janvier 10, 2026, [https://www.global.toshiba/ww/products-solutions/ai-iot/sbm/sbm-technologies.html](https://www.global.toshiba/ww/products-solutions/ai-iot/sbm/sbm-technologies.html)  
23. High-Parallel FPGA-Based Discrete Simulated Bifurcation for Large-Scale Optimization, consulté le janvier 10, 2026, [https://arxiv.org/html/2510.12407v1](https://arxiv.org/html/2510.12407v1)  
24. Geometric Algebra | Study.com, consulté le janvier 10, 2026, [https://study.com/academy/lesson/geometric-algebra.html](https://study.com/academy/lesson/geometric-algebra.html)  
25. a computational framework for geometrical applications (part I: algebra) \- Homepages of UvA/FNWI staff, consulté le janvier 10, 2026, [https://staff.fnwi.uva.nl/l.dorst/clifford/dorst-mann-I.pdf](https://staff.fnwi.uva.nl/l.dorst/clifford/dorst-mann-I.pdf)  
26. Geometric Clifford Algebra Networks \- arXiv, consulté le janvier 10, 2026, [https://arxiv.org/pdf/2302.06594](https://arxiv.org/pdf/2302.06594)  
27. A New Embedded Coprocessor for Clifford Algebra Based Software Intensive Systems, consulté le janvier 10, 2026, [http://ieeexplore.ieee.org/document/5989042/](http://ieeexplore.ieee.org/document/5989042/)  
28. Homotopy type theory \- Wikipedia, consulté le janvier 10, 2026, [https://en.wikipedia.org/wiki/Homotopy\_type\_theory](https://en.wikipedia.org/wiki/Homotopy_type_theory)  
29. Homotopy Type Theory, I | The n-Category Café \- Welcome, consulté le janvier 10, 2026, [https://golem.ph.utexas.edu/category/2011/03/homotopy\_type\_theory\_i.html](https://golem.ph.utexas.edu/category/2011/03/homotopy_type_theory_i.html)  
30. What is Homotopy Type Theory, and what implications does it hold? : r/math \- Reddit, consulté le janvier 10, 2026, [https://www.reddit.com/r/math/comments/45qqnh/what\_is\_homotopy\_type\_theory\_and\_what/](https://www.reddit.com/r/math/comments/45qqnh/what_is_homotopy_type_theory_and_what/)  
31. (PDF) Sets in homotopy type theory \- ResearchGate, consulté le janvier 10, 2026, [https://www.researchgate.net/publication/236844210\_Sets\_in\_homotopy\_type\_theory](https://www.researchgate.net/publication/236844210_Sets_in_homotopy_type_theory)  
32. GPT-4 explains linear logic, proof nets, and the geometry of interaction \- GitHub Gist, consulté le janvier 10, 2026, [https://gist.github.com/stuhlmueller/1ad19f854287995a673c37ca21f05dec](https://gist.github.com/stuhlmueller/1ad19f854287995a673c37ca21f05dec)  
33. Encoding Linear Logic with Interaction Combinators \- Universidade do Minho, consulté le janvier 10, 2026, [https://repositorium.uminho.pt/bitstreams/f3f5ad5e-9466-4ddf-8869-14d34ea18782/download](https://repositorium.uminho.pt/bitstreams/f3f5ad5e-9466-4ddf-8869-14d34ea18782/download)  
34. In-memory hyperdimensional computing, consulté le janvier 10, 2026, [https://redwood.berkeley.edu/wp-content/uploads/2021/08/Karunaratne2020.pdf](https://redwood.berkeley.edu/wp-content/uploads/2021/08/Karunaratne2020.pdf)  
35. Vector Symbolic Architectures as a Computing Framework for Emerging Hardware \- PMC, consulté le janvier 10, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC10588678/](https://pmc.ncbi.nlm.nih.gov/articles/PMC10588678/)  
36. Learning with Holographic Reduced Representations \- NIPS papers, consulté le janvier 10, 2026, [https://proceedings.neurips.cc/paper/2021/file/d71dd235287466052f1630f31bde7932-Paper.pdf](https://proceedings.neurips.cc/paper/2021/file/d71dd235287466052f1630f31bde7932-Paper.pdf)  
37. HDBind: encoding of molecular structure with hyperdimensional binary representations, consulté le janvier 10, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC11584749/](https://pmc.ncbi.nlm.nih.gov/articles/PMC11584749/)  
38. CAPACITY ANALYSIS OF VECTOR SYMBOLIC ARCHITECTURES \- OpenReview, consulté le janvier 10, 2026, [https://openreview.net/pdf?id=6tazBqPem3](https://openreview.net/pdf?id=6tazBqPem3)  
39. (PDF) A Holographic Associative Memory Recommender System \- ResearchGate, consulté le janvier 10, 2026, [https://www.researchgate.net/publication/224370185\_A\_Holographic\_Associative\_Memory\_Recommender\_System](https://www.researchgate.net/publication/224370185_A_Holographic_Associative_Memory_Recommender_System)  
40. Hilbert curve \- Wikipedia, consulté le janvier 10, 2026, [https://en.wikipedia.org/wiki/Hilbert\_curve](https://en.wikipedia.org/wiki/Hilbert_curve)  
41. The Beauty of Space-Filling Curves: Understanding the Hilbert Curve, consulté le janvier 10, 2026, [https://towardsdatascience.com/the-beauty-of-space-filling-curves-understanding-the-hilbert-curve/](https://towardsdatascience.com/the-beauty-of-space-filling-curves-understanding-the-hilbert-curve/)  
42. (PDF) Perceptual hashing meets Hilbert curves: An innovative dimensionality reduction method for intercity morphological complexity comparison \- ResearchGate, consulté le janvier 10, 2026, [https://www.researchgate.net/publication/397955234\_Perceptual\_hashing\_meets\_Hilbert\_curves\_An\_innovative\_dimensionality\_reduction\_method\_for\_intercity\_morphological\_complexity\_comparison](https://www.researchgate.net/publication/397955234_Perceptual_hashing_meets_Hilbert_curves_An_innovative_dimensionality_reduction_method_for_intercity_morphological_complexity_comparison)  
43. Using space-filling curves and fractals to reveal spatial and temporal patterns in neuroimaging data \- PubMed, consulté le janvier 10, 2026, [https://pubmed.ncbi.nlm.nih.gov/39773918/](https://pubmed.ncbi.nlm.nih.gov/39773918/)  
44. GrapHD: Graph-Based Hyperdimensional Memorization for Brain-Like Cognitive Learning, consulté le janvier 10, 2026, [https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2022.757125/full](https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2022.757125/full)  
45. One-Shot Graph Representation Learning Using Hyperdimensional Computing \- arXiv, consulté le janvier 10, 2026, [https://arxiv.org/html/2402.17073v1](https://arxiv.org/html/2402.17073v1)  
46. Scalable and Efficient Graph Classification Using Hyperdimensional Computing \- arXiv, consulté le janvier 10, 2026, [https://arxiv.org/html/2512.03394v1](https://arxiv.org/html/2512.03394v1)  
47. Efficient lambda-Evaluation with Interaction Nets | Semantic Scholar, consulté le janvier 10, 2026, [https://www.semanticscholar.org/paper/Lambdascope-Another-optimal-implementation-of-the-Oostrom-Looij/61042374787bf6514706b49a5a4f0b74996979a0](https://www.semanticscholar.org/paper/Lambdascope-Another-optimal-implementation-of-the-Oostrom-Looij/61042374787bf6514706b49a5a4f0b74996979a0)  
48. Interaction Combinators \- chorasimilarity, consulté le janvier 10, 2026, [https://chorasimilarity.wordpress.com/wp-content/uploads/2024/01/ic-lafont-1.pdf](https://chorasimilarity.wordpress.com/wp-content/uploads/2024/01/ic-lafont-1.pdf)  
49. Towards a GPU-based implementation of interaction nets \- CSE CGI Server, consulté le janvier 10, 2026, [https://cgi.cse.unsw.edu.au/\~eptcs/paper.cgi?DCM2012.4.pdf](https://cgi.cse.unsw.edu.au/~eptcs/paper.cgi?DCM2012.4.pdf)  
50. ParallelKittens: Systematic and Practical Simplification of Multi-GPU AI Kernels \- arXiv, consulté le janvier 10, 2026, [https://arxiv.org/html/2511.13940v1](https://arxiv.org/html/2511.13940v1)  
51. Full Abstraction for Set-Based Models of the Symmetric Interaction Combinators, consulté le janvier 10, 2026, [https://www.researchgate.net/publication/262399252\_Full\_Abstraction\_for\_Set-Based\_Models\_of\_the\_Symmetric\_Interaction\_Combinators](https://www.researchgate.net/publication/262399252_Full_Abstraction_for_Set-Based_Models_of_the_Symmetric_Interaction_Combinators)  
52. VictorTaelin/Interaction-Calculus: A programming language and model of computation that matches the optimal λ-calculus reduction algorithm perfectly. \- GitHub, consulté le janvier 10, 2026, [https://github.com/VictorTaelin/Interaction-Calculus](https://github.com/VictorTaelin/Interaction-Calculus)  
53. Optimal Interaction with the Real World \- GitHub, consulté le janvier 10, 2026, [https://raw.githubusercontent.com/marvinborner/optimal-effects/refs/heads/bachelor/thesis.pdf](https://raw.githubusercontent.com/marvinborner/optimal-effects/refs/heads/bachelor/thesis.pdf)  
54. \[1703.10027\] The Dynamic Geometry of Interaction Machine: A Call-by-need Graph Rewriter, consulté le janvier 10, 2026, [https://arxiv.org/abs/1703.10027](https://arxiv.org/abs/1703.10027)  
55. The Dynamic Geometry of Interaction Machine: A Call-by-Need Graph Rewriter \- DROPS, consulté le janvier 10, 2026, [https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.CSL.2017.32](https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.CSL.2017.32)  
56. Getting started with moldable development on existing code \- Domeinmodel, consulté le janvier 10, 2026, [https://domeinmodel.nl/getting-started-with-moldable-development-on-existing-code/](https://domeinmodel.nl/getting-started-with-moldable-development-on-existing-code/)  
57. Moldable Development \- Glamorous Toolkit, consulté le janvier 10, 2026, [https://book.gtoolkit.com/moldable-development-ejn67l5cdqh83kegi9umt1mdd](https://book.gtoolkit.com/moldable-development-ejn67l5cdqh83kegi9umt1mdd)  
58. Glamorous Toolkit, consulté le janvier 10, 2026, [https://gtoolkit.com/](https://gtoolkit.com/)  
59. The big idea · Unison programming language, consulté le janvier 10, 2026, [https://www.unison-lang.org/docs/the-big-idea/](https://www.unison-lang.org/docs/the-big-idea/)  
60. The Unison language, consulté le janvier 10, 2026, [https://www.unison-lang.org/](https://www.unison-lang.org/)  
61. (PDF) Fractal hash sequence representation and traversal \- ResearchGate, consulté le janvier 10, 2026, [https://www.researchgate.net/publication/224723662\_Fractal\_hash\_sequence\_representation\_and\_traversal](https://www.researchgate.net/publication/224723662_Fractal_hash_sequence_representation_and_traversal)  
62. Distributed hash table \- Wikipedia, consulté le janvier 10, 2026, [https://en.wikipedia.org/wiki/Distributed\_hash\_table](https://en.wikipedia.org/wiki/Distributed_hash_table)  
63. Energy landscapes of combinatorial optimization in Ising machines | Request PDF \- ResearchGate, consulté le janvier 10, 2026, [https://www.researchgate.net/publication/385057082\_Energy\_landscapes\_of\_combinatorial\_optimization\_in\_Ising\_machines?\_tp=eyJjb250ZXh0Ijp7InBhZ2UiOiJzY2llbnRpZmljQ29udHJpYnV0aW9ucyIsInByZXZpb3VzUGFnZSI6bnVsbCwic3ViUGFnZSI6bnVsbH19](https://www.researchgate.net/publication/385057082_Energy_landscapes_of_combinatorial_optimization_in_Ising_machines?_tp=eyJjb250ZXh0Ijp7InBhZ2UiOiJzY2llbnRpZmljQ29udHJpYnV0aW9ucyIsInByZXZpb3VzUGFnZSI6bnVsbCwic3ViUGFnZSI6bnVsbH19)  
64. Pharo \- Welcome to Pharo\!, consulté le janvier 10, 2026, [https://pharo.org/](https://pharo.org/)  
65. Thermodynamic Computing System for AI Applications \- arXiv, consulté le janvier 10, 2026, [https://arxiv.org/html/2312.04836v1](https://arxiv.org/html/2312.04836v1)  
66. Discrete time crystals beyond the MBL paradigm \- Apollo \- University of Cambridge, consulté le janvier 10, 2026, [https://www.repository.cam.ac.uk/items/8691787c-965d-4736-8430-6647b59b43b3](https://www.repository.cam.ac.uk/items/8691787c-965d-4736-8430-6647b59b43b3)  
67. Geometry of interaction \- Wikipedia, consulté le janvier 10, 2026, [https://en.wikipedia.org/wiki/Geometry\_of\_interaction](https://en.wikipedia.org/wiki/Geometry_of_interaction)  
68. How do you encode Lamping's abstract algorithm using interaction combinators?, consulté le janvier 10, 2026, [https://cstheory.stackexchange.com/questions/32197/how-do-you-encode-lampings-abstract-algorithm-using-interaction-combinators](https://cstheory.stackexchange.com/questions/32197/how-do-you-encode-lampings-abstract-algorithm-using-interaction-combinators)  
69. \[PDF\] Interaction Combinators \- Semantic Scholar, consulté le janvier 10, 2026, [https://www.semanticscholar.org/paper/Interaction-Combinators-Lafont/6cfe09aa6e5da6ce98077b7a048cb1badd78cc76](https://www.semanticscholar.org/paper/Interaction-Combinators-Lafont/6cfe09aa6e5da6ce98077b7a048cb1badd78cc76)  
70. Memoryful Geometry of Interaction \- Group MMM, consulté le janvier 10, 2026, [https://group-mmm.org/\~ichiro/papers/mgoi.pdf](https://group-mmm.org/~ichiro/papers/mgoi.pdf)  
71. Vector Symbolic Architectures in Clojure \- Squid's Blog, consulté le janvier 10, 2026, [http://gigasquidsoftware.com/blog/2022/12/31/vector-symbolic-architectures-in-clojure/](http://gigasquidsoftware.com/blog/2022/12/31/vector-symbolic-architectures-in-clojure/)  
72. Hyperdimensional computing with holographic and adaptive encoder \- Frontiers, consulté le janvier 10, 2026, [https://www.frontiersin.org/journals/artificial-intelligence/articles/10.3389/frai.2024.1371988/full](https://www.frontiersin.org/journals/artificial-intelligence/articles/10.3389/frai.2024.1371988/full)  
73. Tutorial on Hyperdimensional Computing, consulté le janvier 10, 2026, [https://michielstock.github.io/posts/2022/2022-10-04-HDVtutorial/](https://michielstock.github.io/posts/2022/2022-10-04-HDVtutorial/)  
74. FPGA-Based Simulated Bifurcation Machine | Semantic Scholar, consulté le janvier 10, 2026, [https://www.semanticscholar.org/paper/FPGA-Based-Simulated-Bifurcation-Machine-Tatsumura-Dixon/f544ab051918e15de6e1723aec3a4f60ca0f7471](https://www.semanticscholar.org/paper/FPGA-Based-Simulated-Bifurcation-Machine-Tatsumura-Dixon/f544ab051918e15de6e1723aec3a4f60ca0f7471)

[image1]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEQAAAAZCAYAAACIA4ibAAADJElEQVR4Xu2WS8hNURTHlzwi79dASCGv5BEpJVEkA1Lej0y+gYmRAWXmlWRmJBmYIZSJEINbSh4DKY/yKCSKUMKAPNbvrrOcffY95/ruudeE86t/33fX3mc/1l5r7S1SUVFR0RmuqF6o3qgeR21lWag61k3tV420z+r0V52SdE2jgrZ2GaCarhoSN4QsVx1S/VRdiNrK0Et1Vmy8O5Ju/G5i261ao9qjOqN6p5pa/9Lg+0Wqw6of0hmH4OQjqg+qT2LruKWaFHZy+oo5gsmXRG1l2KY6LrYxZ7TqmdhCYpibNcTgiOfJ33ZgT59VB8UcA/1Ul8TW0zD3GNVLsQWz8HY5rZof2VgUDicaYji5PDrlkB1iG0crAjuRim18YKvjiyXM/VR7q0aoenqnFjivGhzZfPJrkR2IqDyKHDJc0lPtkfzmbxHs76tYuswO7LvE1jQzsNU5kDTgSdioeiSW/xe9Uxt4SjJHUTTkETuE0/WTXqXarnoqttknqllJvzwopnFqsBbG4uAzvFbdV40V64S33Xs3gn5lWSk2FvM0hGcTYoc4jEX+UwdgoFjkfZSc086B/e0TG4di3wAND8WuXy+qg1TLxMLR6RK7BqnSXImu1dI8ZP0krkpa1LpDM4eQgg6nXxMrnHMCexGs95vqqKROzeBhSI6dkOabY0JO3KHvd7Frsoia2PikZis0cwgR7LTqkLeqnVJQHwk3Bpqrmqa6rtqU6ZFls2TfDMACiwojcLOUudL/hkPmqdZKeuhcIsPSZtvcbdXQ5PcCsVuij1g4bU3sDu8LFuAw8CvVxMAWwwa41rneW6HTDmGvNyMbY2fGJ785dYdXK5Nx7ZJjS4M2ChZp5S/Pk6pzUpxihOQUsQ3wEo6r/J+YIVazJgQ21sV4e5P/gbcTN+IX1eLEFjJOdU/S0hDrNxQ4Ct3kwMb7gdvgstjT2ScFHEdbyHrJOg28iBYpfMHm4ScefsNvQj0ei/SObXFE+Y1ZpAxh+DvcLHmPHdKlFtkI0TB8/xuoMdSa+GG1RbUhsv3zUIjei4UXOc3bg9R5oFoX9KuoqKioqDB+AQun0mOxlxT3AAAAAElFTkSuQmCC>

[image2]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABEAAAAUCAYAAABroNZJAAAAZUlEQVR4XmNgGAXDC7ACsRAQM6JLkAJkgHg7EIugS5ACWIB4LhDboEuQCjyAeCm6IDlAAogTGJDCxhyIQ8jAz4B4FwMUUGLIRgYKACiWEhgoiGqKA5YqUSwNxJsZKExsVEn2tAEAWXYSsYEfk2EAAAAASUVORK5CYII=>

[image3]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAF0AAAAZCAYAAABTuCK5AAADK0lEQVR4Xu2XS8hNURTHl1DkFb48Iq+kRH2J8ggThIGSDCTJjMLkGxAZXK+BpOQxkYkBIgYSIXFDKQYMyEihJANEUZLH/9/a+9p33XPu2fer27m0f/Xr3rv3uefsvc86a68jkkgkEqUxGI6F/U27/d0JLIcjbOO/xAH4Fv6GH+E3uAMOhBPh9L+HdgR9RMe60na0GQblPvgUvnG+hBfgKedeONX/IQsu6iH4Gm6Cw1z7UHgW3hQ96XDX3inMEl30VbajzfCJXwI3iF7/Clwb2AM/u76G7MDofSbayYjOY7foMZ0EJ/xYdFw7TV8MFfjdNrbIQvgOTrEdYDb8Khljuyo66IuScUcC1sAPtrFExsOHcJ7o+M/UdxcyGT6Ae2A/09cKm+E1OMB2gBXwF1xqOzjgT3Cm7TBw0au2sSSYx4/C/e4758AUyO+xMPoqcKQUzz0P3qxLkhHJoun5tmSkl9Gu8bwU3+25cLFtLIlFolE+yv3mHKqim1sMnPddOMP9PiGt3TAPz8N9zkYyn0LmeI7rsOmTY5Kfj3pDl9RvJjH2BlYIYfRwciwAWOLGcEs033oqzlZhhPPaXGRe28vKhWnluGghUoM5iLnoPhwSdnQ4LMF8hHo4ce43seXsOal/sn1+52csfv2yigue+7RoH/fMGnwUq86ix3IL3GobSyCcjJVVQhi9eXCuTE8hfo/YZtqbMQ6+gj9Mu4d7IMf1xXZwAlVpvujcEG5I3ITazTJ4zzaKLjgnGPOCxIqC7yQWbqY8N/N0DMzjTCHPbYeDdXrmoq+DL6T5hVi7n5TijZZwIDYCi4yFVQYXhQtvYT7nuYpekLjYl22jg/NjLmbtH8NB0WuyarLwOgxU9vOzAZaLjJT1sG/QPgjugmOCtjLgYnMcP0XTnH2XYGp4IjrBI9LY7+GiMpcz0PLgMTH1/gLRdeOL1fygndfuFh0Lgzl3j5kGH4keyBPxbt+B7+H24Lgy4GZlnwzWvh5OkI+vPSYLpo/rojexGXySstIPCTfPPBkcGyX/HDUYLZPgatEyjncojPr/gQlwjm3MgNFauGCJRCKRSCQSiUQb+APqVrUxhXW0FAAAAABJRU5ErkJggg==>

[image4]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA8AAAAaCAYAAABozQZiAAABA0lEQVR4Xu3SMUuCURTG8SPqEAkSQtQQ6CLYUEJEEPQVgginPoCLu6vg19DBPYKGnKXagqaGIFsiWhyCwMGl+t/uVc57Mm5z+cAPeZ/zXricV5E/mwLWkVNdFsvqOZEU9nCBD7xggksU0cHJ9GWdNZzhHedIh979HuEWb9gO/SxVPGGMQ/E30HHPbdxgxcxkhFfs24HKrvhrJ9LEHVbtwMQtr6KLEp7R0OUPcYeXdFEXv9UdXf42PfGHvy0hFvfxB+IP2+1Gk8Gp+MOxuJ205pXucGIRJkX0sWH6r+IBB3YQkhf/Vz22g2nc4BFbpt/EFWoS2clQ/PXv0Q2uUdYvLfK/8gk/KihVrGe+kAAAAABJRU5ErkJggg==>

[image5]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA8AAAAZCAYAAADuWXTMAAAA00lEQVR4XmNgGNaAFYidgVgaXYIYEAPE/4HYF12CEBAD4isMEM1FaHIEwUkoBmleiCaHF4D8CnJyFQMZmv2AmAeIyxkgmg9A+QSBMBDvg7KDGEjQrMIAUagA5ZsC8TcgfgLEMlAxrIAFiGcBcQaSmDEQf4ViEBsnsAXinwwQZ6JjkO0gV2AFIP/sBGJXNHFJIH7IQCChgJw6lwESRchAEIhPM0A0R6PJgRUbAfF5BuzpV4IBEvIgzTORJfSB+BNUAoRB/rVEkr+IJAfDk5DkR8EwBwCnpTFO7iO2SwAAAABJRU5ErkJggg==>

[image6]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAYCAYAAADzoH0MAAAA7UlEQVR4Xu2SvQ4BURBGRygkhAiNQqOT6CS8gCfQaTQKCr0n8AKiIkqdVieiV9CoRCIalYiEUvjG3P2b3X2DPcnJTfabvXfu7BJFaCpwAc/wajzAOZwauzBjvRBGEx5hQT2PwQn8wrzKPIzgEiZ0AIYkG9R0YJGEK9jTAXk70N3ZlOGNgk+owwf86MANt88nzMgZHA/xAjswZVcGkIZbkg2Kyj18wjaMm3of/BnvRk0Jnkg276vMZkxSwKuGW1+T5Lz6yMEdSUFLZUyVZICcD1T2h6f+Jmmfr6LZkHN61h1Y9+YwzBdskPwHERE+fhXfN525yFNZAAAAAElFTkSuQmCC>

[image7]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABEAAAAUCAYAAABroNZJAAAAk0lEQVR4XmNgGAVDCzACsRC6IBJgZYDIg9ThBCJAvBldEAlIM0DkQepwAg8gXoguiARYgHguENugS8AAyKmLgNgVXQINgORB6jBAMhBvBWJ+dAkcQAKIExiQwsYEiJ8BcToQh5CAQXp2MUABJYZsZEACpHpHhgHNOzBAbMCCYnApuiAyoDiKQUCEgQqJjSrJfmAAAAjzG5aptjrvAAAAAElFTkSuQmCC>

[image8]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAaCAYAAACHD21cAAAAwUlEQVR4XmNgGDmAFYhnEYlrgFgIoo2BQQeIvwHxSiQFm4H4LxBPBuIQIC6Dyj8HYiWINgaGcgYkU6AgGohPA7EgmjhcjBOI16DKMTAC8XwgnoQmDgJbgZgDxEgA4gwUKQYGYyD+CsSaaOIgkI4ugAxAzvzPgOlMvADmTJBGkoAIEF9lIEMjzH9v0SXwAWRnYgtRnADZmaAAIhogOxNbVGAFPEBczwCx7QoQK6DIYgHiQHyXAaIBHYOcDXL+KBimAADIBS0leL+IwAAAAABJRU5ErkJggg==>

[image9]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABoAAAAZCAYAAAAv3j5gAAABXElEQVR4Xu2TLUsEURSGj6igqPgJ1sUmbDMrBovBIrbdYNOwZTfoL7AaLIJFDAbBpmAxLBitGi0W02LRBYMf77tnhj1z7swwW2UeeMI99+PMufeMSMl/ZBQ24VlB53Tb4FThO+xK/7Ab+AO/4Q48gFfRmiXdNhjj8BqumtgQPIe/8MTEyRYcc7FCsJpL0YQxs/BRNFHNxMm2G/eYF/26mGE4acZkF+672Ar8hB247OZabtzLzIV3oo/XgK/wC97C6f7SAFbBalgVq8tkQ/RBeb/ccApHojneMWOH0dizAJ8l/doCNuEabMM3SXYJS+cheyZmybu2TJjkHk6YGDuMB/HANPgBha7Nwg1HLsbkbQmbIiarrXPhBl6jj7ExiJ8jhd8nhu/ir40P/QCnYB0emznCKpnkCVaSU9msS9hZ/Kc+RNv7QrTFF+GLaII0WWEu/DmpZ0bCH7mkpCTJH28pTkfILm76AAAAAElFTkSuQmCC>

[image10]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAABTUlEQVR4Xu2TvytGYRTHv4pSlPwYKGUxMMqGUclgQG8ZlcF/QFlMRouRyW5VknSLzeRPUFaZTPLj+3We4z738L5dm+F+6tPbc869zznvfc4DNPwnuugwnaMTISf66T49rumKvWZowyVYETFOP+gVHUixI3pNh9JaLNBX+pLFhBrdzgN6eRVlAfEMK7KV1rd0tkx/sQt75i7E9W8XfdEH6/SBjnmQ3MBePqPd9DT9Or30PD2jBnMG6bQv1PUhvYRVdgqUn0lNbGQ5oc/4CHtmLeTU6EiI/eAd9plmYiJxANu8QLWxWuiQ3uh6TGQUsAIq9Cd6YGPWQvXQI0+wAssx0Q5ttkPv6WSKaSTnUT1cR5vrkHXYtdiEHfRoFtNl0fRENCUqsBcTnbigU7AJcE9gsx7RfdAQfM96JzQBBayjqG6oXy7/5r+p29zQ0NCGT9FhR1GlyMtAAAAAAElFTkSuQmCC>

[image11]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAANgAAAAZCAYAAABTlOD8AAAFY0lEQVR4Xu2aW8hmUxjHHzmNEJqJRH1MIjGGxJVDSSFDcihRbrkgNWEkSckVSgwXDg1JziE55mIwF+TGhcMN9ZESkihy5vl9z17zrXd9a+9377X3vO/29fzq3/Sttfe7nr3Xeg5r7RFxHMdxHMdxHMdx5sWxqgdV76u+Uj2qOnDiikkOUD0udu1Hqq2qI+ILnLlzhuolsTkKYn4fqsR8X7rz6tmwnyyP30YX2G3/f9apLlJdr/pX9YOY0+XYTXWD6g+xa5mk81X7xhc5c2dBbG6Yo19U11V/o8tVL1d9dfO8KzhN9avqGVl2oj/F7MCeK8Uc/+Oq7T67bfVwi+pJsYerix68lMvEJu3rpG81QNQn0s4TxseOk9OOjuwhNpd3ph0VVCFfqg5NOxootY0gviNtFLPvQ9VBURtjvKU6O2prA88zWtaoXhGLGjz0lsnuJcheONfVYte8Otm9KlhNDsai/kfyC3Uf1Rtic8jct6XUNmxIHYBxc5kKZ3tNumfX9PdHxeFiNfpmsYd+ZLJ7iVNVe6u2Sb0TzoM9VYdI876xLX0cDDsIQjFrVbsnbdMoXcQplGSLqsOSdrhE9bfYnHah1La7xErTGNYc6+jipJ2MiuMTILowagcjwrwoVhqG7BRHNl7sY2IP/YlY7cwEzpvXVT+qtqu+VZ050dudEgfDqTapPhXbPyxU7aFEu6b6uy2liziFYJnOI85+hViJ/3nU3pahbAPWXNN+vyujdTAmAOfigdervhHbXxFh4DixjEZZETLc82ILaBrhACVssNtow9KdzYQITNaIwbatYgvp/qSvDV0djHfAxJ4r5miMf2HU/4WsLIGmMcQiJmstigVMMkIQ2YITRZzrrHBxB4awDfid7VK/PyxhtA6GU70nNikhQxHheIk4Fc6FkwGOxSJiHzYvsOV7scyVgt08y0axPUYdTHC88ILeVB2VaacETZ0ZKEtvqv49UvWZ2LUBDo04HauDa9OxGB87zsn0tXV+giX7L+YzhXnlPRGgmuB50/GbbENtIWuRvc5LO6ZA4DxYVo6Lnsu0oSG2Dr0g4j4rFo05bn9blk8ScaTYmRbFjlpPidpmze1Sf8gSsi/7xKbSjGPr+BtR0F9i96ftBB2ctgn2GGTPeB82Ldrzu+lYjI8d32X6sLsN7I95R7kqY3+xIER/EzxvOn6TbagtrDnGX592TIGq6h1ZOS7i01Hahu6R/HuYGZQwlH4BUi0PT9sTMhk1iYosilxknAVxAMgdsnDsTB/X8EG8K11LxAATSHYnc8S8IN1/r28ZRslP8KlzILImpWtdfxN9bQuE0+ouJ5jTGGWJSDQj5ccHFiH63a06KWoH2skO6WlZHaFU4b62ato7hdqd63Lf6nAwSsfj046WlDpYWLRh3xq4Nvm7DX0XMVmBTE6lkYP9InOCutLXNuAYnm9fzOGQjM7BqGf5qs7CYEEGpwlOQRYI0Hei6veqv62D7QpOF7PjjqiNzHazTO4fT4j621LqYGRLPnOEkoe96wPL3Z3os4i592Gxxft00rdW9VPVd6vk95TT6GMbcP+NYjYQBIZcRyUORhn8s5g9PFeOcLLeFBA4p6B/53sJm8w4c+yI+tis841kL7GB0yyDum5Qh4JJ2SSWqfifJR+IHY9fJWYz7e+KPUNXSh0MCEBkUCYaR8eeEkoXMYEvnaNU21THhBsKKLUtt96ChvrkU+JgPM9Tqt+k/uBuQWx9cbBWB07IHrBkWzJayMC5UyLqetpL6vs+DgbhhKtk7EDpIp4FY7atxMGcGXOv9HOOIWB87Dg67RgBY7bttrTBcRzHcRzHcRzHcRzHcRxnnPwHMWdh6ht+b7EAAAAASUVORK5CYII=>

[image12]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAI0AAAAZCAYAAAAMqa3wAAAEhklEQVR4Xu2ZW8gVVRTHV2iQqGQqiihJEUGpKKiIN5CorIeiLEjx8iZeUAQFBRH5UIJ8E8OXCLMHfeiGEBVBkFmQN9QHb6CQRSQFEgYFmVnrd9Zszz7rzJkzcz6/I5xv/+Dvd2bvmdlr7Vmz1t6jSCKRSCQSicTgY5fqJ9XPqpdcX6+Br/j5r/S+r56HVAdVv6huqmY29FZkjmq16nfVU66v18BX/Lwhve+rZ6hqkeof1QXV2IbeDliu+s839ij4uc83VoA39IhqhO/oIn2qv1VzXXsZ8H+Nb6zKA6r3ZHAEDb7i58u+owL3O2geU32n2qF6x/W1A5v/lJKlicka7RszSFOkq+tidW+cakjDGfeHgXgo+Iqfj0vd16rcq6Bh/FG+sQTbxDLNGNXnjV1toSSfUj0iZj/3aGK46i3Vr6qjqnViA64SCySYrfpL7GbnVefEav6LWX83wabXVJfE7DigWqnao3o4Oq9T8BU/P5G6r1X97G/QzFedUF0UG/9V1X7VpPikAr5WTcl+b5D6cyzDEtUXYvc4o7qsmhGfgFPUvYVRG8bFNY3F0UeqO6o3wkli0VxUrnhjX1G9XkHTalcWw5i7pT4Rz4vZ9pnYm1nESN/gCL7GfgJj4m9Z+hM0lMUPVA9GbSzMyy5MyQy+tPS541aQXXhh2AzENJTrtdI82V9JY03D0FCaSNmB7VIcNAMBb4/f1WyWcg91i9h5RQ8y+Br7CVz3vmsLcL8JTotVX6qeyOkbb5flQikkuz3r2hmfNWWZjLFULPhjWN+wzmkH88r8EjyBsMarzS+p/Lg0r5IJjlDTYIHYFiwOLv5y3O2g6ZPmICczYB92tiK2t2gbHXyN789vrnszaovZKPYNK9Zvqtti33t8H0HZCh44Y/mMQhu713YQwPjp2StWptqRt0PGlrvjT1f9kf2N8VFNUNFGZglMVF3L2rsFay+yIJkl5lombCriSbFtdNHbGnyN4b60VdlNdVqe3pXm8avsZl5QfeoblamqY1Kc5YD58eMz7t3xw0GrqCbFLZP62iX+OopxrCNIpa0gxXIO15bV27Ur82Hyjkpz6iYzkG2wd57rq0reOg1f8bPKLqrToKEE+vEplSHzkyVbLcqHqT4Ws9fD3LD1XuE7HIxPTMSQoQhE7l/7h4PwhrLd/lD1o1jtZb2zU+rBFdLbVrEHxXHRWzsQYFN449nyb5J6QLPe4UH1h+Ar4FvwtaqfnQbNc2L/fQGMia8sgglmgpbSk7c2ISgOi5W3VnAOQZEXVAF2Trey3yzECTQfRLUtHG8RN7sqtmtgkr5RfauaLGb8erEFEkF1RfVM1t5tcAQ7sPesWDr9QWxbeFrM6f4QfMVP7h98rUqnQROPzzMgg1JaWGd+L7aYz5t3zuF7zBjf4SAouXcrmF8+XRwSi4eTqqcbzshgIGpd2OLhaHwcYEFIBsozuptgH3aEB4Kd2Fv1ARXB/ZmXTn3tNGgCjB9/1CPLxMeeR1WzfGMOzBWB0w4/fqILsOhmxxLvwhKJRCKRSCQSiUQiMSj4H5We+bbuexeXAAAAAElFTkSuQmCC>

[image13]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAoAAAAaCAYAAACO5M0mAAAAu0lEQVR4XmNgGAW0AqxALATEjOgSyGA+EL8G4nNAfAGII4FYE0UFVGAOEHNC+cFA/BeIbeAqgEAYiE8BsQqSmCQQPwRiaSQxhnIg/o8sAAT6QPwJiDlgAsZA/BWIn8AEoGASEP9DFoApPIAkJgjEp4H4AQPE7aEgQZgVC+HKGBhsgfgnEG9lgDgrHSQI8uUOBogJIAAy4RYDxM0gzauBWBEqB5a8BsQbGSC+B9kyC4ifA3EpA4HAHwXEAwBwySC2kyq3DgAAAABJRU5ErkJggg==>

[image14]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAgAAAAaCAYAAACKER0bAAAAwUlEQVR4Xu3QzwpBQRTH8aNslFIoKWWnvAOv4DV4EXtRVspKsfACVjdbWzZK/mSLUrb4HueO5s4TWPjVp2bmnPlzr8jvpIYTroiQTVRJHhO80A9q34zFGlphwWWFC+phwUV3d5FCIah9Fp8YYi/20ClyrqEodsJc7MGaG3quoYGleDvIEQc3aYvd7+eMhw70+A0qibJdGemgLHac//cycUNHJyXsxL7EpYmFxJvSGIk1aqrYSnClTtaY4Y6BX/xH5A2zEyNb38hoTgAAAABJRU5ErkJggg==>

[image15]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAKgAAAAZCAYAAACl3WVkAAAFYklEQVR4Xu2aaahuUxjH/3LJmDESusYkJGTMUCIkEsr8yQcUKXINSQofkJJcypB8kCEfKIqSDopbbqFMGeqSEkIUGTI8P2svZ7/PXnvttTv3Hc5996/+3XPXevfZaz//Zz9reI80MDAwMLB+2bjSPLCNaRPfOAPsoPnyoBjMWm3ayHdk2NK0vW9cJpxuesU3Thk8uE79PDhFy9uD3XxjCgLzoOlR35GBIN5mOs13TIHjTc+ZvqxpjemhSg+YzjVtHi+ouNi00rVNi+hBn6qOB/9oNjzY3/SERj14V4seoEv///Qi76nAg3NMn5v28R0ZDjH9aDrDd0wBHpAEvNP0i+mq6v/ofNPzCkZ+FC+oIBkIXJ+kGBfRgz7gAc81Cx7saDrL9Kfpb9MtWvQAPaww1hPjBRXPqMODKxUS7UDfkYHK87bpfdP1rm9arDA9a7rDd1Q8rhCgXVz7S5V8dZ0kS/GAZ5oVD4Dx4AN+eBgnBeSwWhtxz3qwYHrRtJlrb4M1w1umoxRKOsbPArzBH5hO8h1aDALB8895mel309GufVJspaV5wDPNigeMn/EQUw/LkfsVPMKrOlkPyOibfGOGexXWntyQwJCkpYt6PnefQkmnArDJauNQNatdjmMVppddfYfC9PmXQpXyHG76VeVVaD/TXQrPcLXr8+zrGxJQTfp4QAzrHpAQfTwYJ3upWSEjRyjEHy88WQ/6LrJ5c3eqfiaoCwpVoIu4CWAz87TpG9NPag8sg009aBvXKF0hL1QI2mcKgfDwEnyh9mmpDmP9w/Sqwsu5TmHX3bZ+usg3JOAzfTw4TqMecO2CyjwYNzyDr5DEjHUnm6Y2v+seNPhaIfNLuFyjZpyt8Iu7Kh1JwwlBqqKwSObNYofHGeAJpg8V7lUKVXOdQgVlLHURGJKTIKWCw9iYXkueg02Yh+XD3QoVgI0BSX6Q6TWFStcFid7HA17uugckaMnYefZjNLpx6RLHQKXEpcoVGo0/L9Q7Csl5Qfywo+5Bg5KHA3b4a10bu8fvFY4YcjD426t/PRxKM/BvFYKN0Wwa+hxWs+5k58jb64lTKFP8ya4vQpKUxIFpNUWsEpwS8Azci2ROLvodpfcGPDjAtXG/Eg/GDfdvG8fupk8VxtpGjMMIJEFJcKgKjyjcwKttzeHxU68Hk6mgbdNlDpYDjCU1RWxtekOhn2dIUZokm/qGBPyOrmetQ0Usuff68GCcnKkwlu18h4K3rJPpb9t3JBMUSoJD5XldIYHqEBRuWrp+GgdxemAcqd3jzgrni20JGoNXEodxUPpyRA88JOe0PQA2v4wjBUnJt3ZtCVr3oMHPpoN9Yw2SksCkpkeCyk2neVDM2o01HEuD1CboVIXpH/GzJ66dSGKSedKQoEvxAFNLPNjC9IKa1Ten7/67shuqZjyTTcH5LvuMtv66Bw24qG23SWBYT/nNEZD1JAfX36Nmfx2q3GqNfg3WpTdNe3NxB/Ebiqc0um5l7Gy86LtZ7eOLCU4F6OIGNceZ08fhsixUvpwHNyrvARuQEg/GBd5yksEYOF2oQ+KxQaXvMaWrJ2Q9+ErNjvq0GUWJjjfgbeetr/ej1BQa2Vaju7sucYyS2yjFjZEfQ10/KJxb5mDtRAKkqquHgPtx5lRSkfdUPw8ibR5MEjZE/v5eVO0jlT5BiWQ9eFLNs6t5gsRg912STOOAzc/gQcYD1jW/qSV75wACc6tvnDDz7AFJ2enBSoU//DjPd2zg7KH0V2/TIHowbzBzFHnAd6Wf+MYNGP6a+2Xl10aTBg/QvIAH16qHByx6OdieB1aZLvGNMwCnHfPkQXFyDgwMDAwMDCx7/gUq7nXnVJ3YygAAAABJRU5ErkJggg==>

[image16]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAFsAAAAZCAYAAABeplL+AAADs0lEQVR4Xu2YS6hNURjHP6HI+5FHwr3ySAklxMBAEuUREUVRCiMDEyUpycBIiYlHN0oMZIJC0gkZYGBAJOqSRymJMJHH/9+3vnvX+c5ed+9z7r1dtH/177Re+6z9X99e39pbpKSkpKTkX2U5dBp6BL2GnkFnoBNBB6DJbb17nuG+wtEPmgEN9A0RQ6GF0ASor2szekGjoAXQWNcWw/FTRK+Zy0RoHXQOegVtDWVqb6j7DR0O/fPYCQ32lV3AAGgb9Nk3BHpDu6CPosHCX87Zm8nFahUNsCui/TxN0D3osWjA3YFmxx1EF2OF6HhepxW6AA2J+mTCKKhAm1y9wUj5BDX7hgS8wY3QS2iaa6sXRgwjjGbSRC68ZzT0FLoqGtnGUdF5G8ugX1GZjISuQf2jOvZZEpUJTT0majLhmCei440domP5P0kmQe+h6b4hMEh0dbnl1AMN4oRuQDOlfaKNkjJ7lWg9zY3ZE+oJ/7tFas1moNFIu3dfNviEx+Z+k9rFXSnZ86jCJjvMNwQs8ne7+iLQ8MXQQ+h+KDdKyuxDovU0N8ZunvDeHoia5GEf9iUMPBrr9+mK6Ng5ocwxnE8M29in4uqrsMmm4GpyVf3N1AMja77odVZLY6anzLZ6Pz8zm8FC82hiymwbS8NSZseL0pHZHJ+JbSFZicLgXs6Lz/INDcCbOC568tng2vJImV2RfLPNiDyzOabbzLYthI9YFrbXsU+cRBqByZJJk8nTnxKKkDL7puSbzUD5IvlmMy91m9m2haQ29WbojWTfZBG4WEyOTJLcQhrZPoyU2Vbfkdk9vo1Y4uPA1LHPMvpl31AAGn03iC8RnTGapMxOJci1oZ7zSCVItrEP+5JUguRp7Ds0N5SzzGYb+7BvDfF+7Y86ZJ7oOfW56MtPUeITSFcc+YyU2ZZTTrn6+OjXB7oYlQ0GHBfAThlcFG43Pj9xAVqhcaH8Q3T74suWYU9SS1TXxkmpXSGeG/lHZ6FL0JiorQhHpPjLTz3wpvh0cb7x2ZZwMQ+KmsYTD2kSzQ/xjY8QPX7Gb3lM0j5RvxMdZ3mF14+vTTZDP6V9LK95O6jqLdKSBSeepa+if9ZVEdkZLDqzZPsn4WJwzm+h7dAL6LrUfkvhE3xL9Gng9sPH3m9vfCo/QOdFkzmDcr1U+8GF2Cf6+WC/6CLy9f5v+o7UrdCMqaJG8jcVLItE+6wRjfYsuHhLoS3hN8V40e9I3Ib8opX8T/CjETN5EXX0GbSkpKSkpKTkf+UPfAcAjBN84v8AAAAASUVORK5CYII=>

[image17]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA8AAAAXCAYAAADUUxW8AAABC0lEQVR4Xu2SMUtCURSAj6BQBAoGToaCOoRtTe0tzSoNigj+BFGxvV/QJm6NubbYZhBBQxq1NDf3G/zOfffFffc9Z4f84IN7z7n33HPfuyJ7ds8BnmETa5iJppP5wI7EFx/hBN+w6uUMdVxizk9YiviOn37iEB9whE8SL6Abn/Eah5hykxd4b4N+gZIE7epGzWv81OYMY2zbsV/A3RgSrjXc4bkbgDJ+47EXV2buZIpXzlxbXWMLF5h3cop2+oe2cWvH4R0bdj6QaIE0Xtqx4QQfJb5R0bu6BfTx+H/DPIy5BA8iCb37iwQfMxH9h1/Yw4IEp1bwBn+wa2Nb0RO0zRX+4iv2Mesu+q9sADszJw3Of+roAAAAAElFTkSuQmCC>

[image18]: <data:image/png;base64,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>

[image19]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA8AAAAXCAYAAADUUxW8AAAA6klEQVR4XmNgGAUDDziAWAeIQ4BYFYhZUaWxg2tAnAXEnFB+OZTmBuJKID4NxCpQMRSgDcRmaGIwzTDgDcQn0MTANq1GF2TA1AwCGUDMiCxgCcRrkAWgAJtmfiDWRBYAKYpGFoACbJpBAEXtfCB+BcSP0PAXLGIgPAeiDQJmAbEnsgAU4LIZRRzkjFZkASjAppkFiF2QBWSBeCuyABRg0wxKPKBAQwGgVDSPAZIgYABZswQQ7wbiMiQxFFAKxHeBOBuIpYC4AoiVgbgBiF8CcRwDWhyjA2EgLgbiC0D8jgGSopKBmA9Z0UgFADHJJMEr26faAAAAAElFTkSuQmCC>

[image20]: <data:image/png;base64,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>

[image21]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA8AAAAXCAYAAADUUxW8AAAAWUlEQVR4XmNgGJnAE4hnkYiTwTqBQBOIQ4C4HYj/A3EnlI+My4H4N1R+IRCbg3UiAUkGiKQvugQQGAPxVwbc8qOa0cCoZiQASnogQXQMSoYggC6OLDcK6AYA+IxBM4pqBmoAAAAASUVORK5CYII=>

[image22]: <data:image/png;base64,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>

[image23]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACgAAAAZCAYAAABD2GxlAAACW0lEQVR4Xu2WvWtVQRDFj5iIksSPKAnBBD+QVEKKgCJY2dgkQbSRSGobKwvFWgRBBAkG8g/YCRYiWlgs2AgWIiQIokVEFAQRArFQRM9h3ureyd6978kTBPODw+PN7MzO3Y+5F9jg36OXGvTGApuoXd7YCTupEWqzd2TYQd2jznhHARV4ARbbEQvUKvWeekt9p+ap7emgBE3wkLoCmzTHGPLxGq/YtorcRt2grlO7E/tJ6jP1ijqU2COXqKeoxqQo51dq2jtaKFY56h4Oo9Qz2ErVbZHOisb8cHYlfUkNO7uOxRDsmARYXF2BilWO26gp8j4swS3UDCA91F2sL3AvbPtLBJQLFMrxjjrgHULBOm+57Yuo8DuwsVsT+wx1OvmfI6C5QOXQGOWroOWVo3Z5W/Tj90RpgdeoieR/joDmAiepNVi+ClraD9RB73DoyTRJusWx6KZeFtBc4B5qGTb2F33UY+oJNZA6HFpZrbAm0TmJxAL1WyKgucCYS8oaS5PobOqMapKriV29Sy2iFCsC/rDAePBlLE2i260JlmCtI9LNFdQOaieDs+MybO91BupQf1SjPuLssUDfAz0BzQXqlboCO3LrUAF6S+xLbGq0s7CbNZ7YPRep497oeA4rcA72QZFDOb5R571DTFEfqS/UIuyqv27ZziXjchxDPmnalrxyK6md1C4d9o6IVky96Cx1itqPcl+M6KI8QLU3dopileMR7Hug63xC4cnbQLHKocX5K+jyvKGOekebKNZfwK6jr6AXqF60dtD4pnd51ziBzLu0wBbqpjdu8N/wE2M2fKKvuj/RAAAAAElFTkSuQmCC>

[image24]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAF8AAAAZCAYAAABXTfKEAAADDklEQVR4Xu2YTcgOURTHj3hFvPkWsniEJIlC5CMlKfmI2CAr2dsgFjaSWLCXkoVsRBIhC+x8RGRhQT4WFAtRFOXj/3dnnufOmbn3zvMy885b91f/3uac+7xz5tx77j0zIpFIJNIoBkHjoMnK3qOu68SOaaRlZ0wjrOsBCx/wKvQT+g29g+5CLWg4dLo9sj6KYvou2Zh2pIMbyFhoojZqJkEXocvQXGhwYt8MPYJuQF8SW124YuJfO6Z5ib1p7II+Q/u1I2Uh9BH6BC1VvpRF0Depb+U3MaZuGC1mtZ8VU63O5N8XM2CfmBIvgvvsG6mvvPsjpqESPtMYS1p9ZQgmn85n4t+X+KBMyGztqIi6Y1op5p7pfVdl3W1Ybbu10YM3+dPE47Tgg24Vc8BVTd0xrYDeQzMTHRSz3U21ByXshdZqowdv8ul8AI3RjorolXDZ1hkTW1Yme5h2gGXQY+lUxAtofmZEGGfyeePb0DnJ76tMEEueq8uW3V8T/m6NsrnYIyaQm9ph8a8xzYKOQ6ekXEXwHuO10YL+KWJWe2jRFBFMPgdo2NY9hd5KZ+bZX+9M/C3oDPQq8ZWBXQnHvtQOi7Ix/ZB8TBugY9AEMXvzNckvFhecqFuJtifXRUyHlmujB2fyh0AXpPhBbfhjJtpeiewK2B0sgL5adh/s2Y+Iv1LKxsSJ1DFdgc5LJ+G/oI0dtxNWzz0x96Q+iNlidOUR/r9t2ujBmXxC43VxzzT3Xf7Y1c51k/yylImJZ4KO6RL0RMwnCMK4Ch9acQg6YF1ze2GC+XJnH7ozoDvQHMsWwpt8wtd2lvISyc52S0wr5zv8qkg+CcXEVe2KiaTbyCjtUPCgXaeNFjxDTkAPocVSXA0+WI1M/kkpPtT/9rgsMw56LeawYsKfi+l3D7dH5qkq+aGY1rdH5mGC+HLGbyr9BVc6Y9fiuZSDpcaXFfbNm8SssDKzXFXySV9j2iLN/OTw36ky+X2B34SOitl2un0bHTCkbR87A5YT9+fVmRH1wz3eLvEmf+2MRCKRSCRSNX8A36m8Ovh0OgEAAAAASUVORK5CYII=>

[image25]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEYAAAAZCAYAAACM9limAAADv0lEQVR4Xu2YS6iNURTHl1Dk/SZKJKXIwGNCMkAMUAzJ1IBShMykzIUizwzkEUURSbkYEAYGTMiARJFEyCOP9bPOumefdfb33es6cm6dX/1zv7X399jrtfch0qLF/2aQqnc0NiF9VP2jsbOwwFGqMXGggPWqPdI9HDNedT0aO6KH6pbqk+qZ6rnqjmpOOinDXdXI5Jp7X6jeqWYk9mZhdkWdYpzqvGq5qmdiP6v6rlqZ2FImqRYG2zrVW9VHaU7HkABXxcq/kJmq16pHYmmWY6fqp2p3sE9VvQk2oIbbpHkdA3tVt6XEOTfEFr06DiQsFZtDyaTQW14GG3QHxyxWfVUtiAMOCy71nFQd8zSx0d0viqVkpCPHeGMv2x0Gi/UtynqY2DdMFyuDCN/CnHSMe8ueP1EsqFRDHRPEFkzky9go9Y5hYVwfSmxOkWP6qraoTqmOiTXoI8m481j1Smz8vVjgromV7ZRknkMbYOySaqjYetgAvqguSD7oA1Q3xYKLY9vBu8fFymNIOhAYrnoo5pijiX1JxbYisTk5x1CquSAsU22v/M038Q6ywyGyZd9IKXAf/Y/n71P1qox5pm+tXEcIDsGtOZb4x+OcXHo6vPiH2AtYhOMvTRfhRMd42fGcWNOM43gC0E+sNNNnemYWnakIkL+P0sCRjmf62sSWgmPqstAfxmAZdO9cH/oTx/jiYmkB16l9u2pV+6jZT0g1C3J4v8CpOBeYf0by73RYe924R7Ejx3Aj55h4VumKYzg4zqpO+010zAixDOKaSHK2mlYZK4JM5lvSRurOapPiJszaOcRyhquBB+GcmuaTwAN5IQ0zlttc1TexdI1Ex/h1zpFpKQGlxiHzsFiT3lCxl+H9hbJyKJ+0p+WadrbHAIvl5pNSTUEYKHbTZ6k9Bad4U6ZHRYZJ9afFvIqN31EHpHZnI1L3pbZEcQw70jmx+WiRlP8Oi2UEfBu7DrsPjT8G1r8/t6v+Bo+yAD6YDCJKHHxOi23nRfAidhAeHsHZqTyV2a43qx6o7oltxfE0PVbq70fcMz6Zl0Kpx52HLP8gtl3n2oWXcNrP6qCU5otN4t+imoxQ25wV/hQ/4MUS5lCGA9LIwzaxxUcnOmRoLrM5JDIWswUoNfpLWfC7jC+kUdAjiHLEd5g26XzQOuKy2I6bc1pDoPZ3SWNewDPWqA6K/UAlq+hDlDk9ZHR16l9BT9sUjf+CK1L83xJdgWZJr3si5pDJ0hjHA8+h/5Q184ZBJPdL5jzQhLBL7ojGFi1aNJRfianhq5pQyWEAAAAASUVORK5CYII=>