#  4. ORGANISATION DU CONTROLE QUALITE ET DU SUIVI DES PERFORMANCES

## CONTEXTE REGLEMENTAIRE

L'arrêté du 3 mars 2003 relatif à l'obligation de maintenance et de
contrôle de qualité des dispositifs médicaux (DM) précise que les DM
'nécessaires à la réalisation des actes de médecine nucléaire' sont
soumis d'une part à l'obligation de maintenance et d'autre part à un
double régime de contrôle : celui prévu par l'article L. 5212-1 du code
de la santé publique et les articles R. 5212-25 à R. 5212-35 concernant
le contrôle interne, réalisé par l'exploitant ou sous sa responsabilité
par un prestataire externe de son choix, et le contrôle externe, réalisé
par un organisme de contrôle indépendant agréé par l'AFSSAPS. Pour la
médecine nucléaire, la décision du 25 novembre 2008 fixe les modalités
du contrôle de qualité des caméras à scintillations et décrit les
procédures liées au contrôle interne (section 6), aux scanographes
associés (section 7) et du contrôle externe qui relève d'un audit annuel
(section 10).

L'organisation du contrôle de qualité des gamma caméras, y compris les
systèmes hybrides, est liée à l'offre clinique supportée par le système
et aux exigences en termes de qualité d'images et de quantification
telles que définies par les critères des bonnes pratiques des examens
scintigraphiques. Le cadre défini par l'AFSSAPS doit être placé en
perspective d'exigences complémentaires liées au matériel et aux
procédures cliniques en place dans le service.

Pour mettre en oeuvre le contrôle de qualité, il est possible d'utiliser
les procédures et les accessoires mis à disposition par le fournisseur,
en liaison avec les prestations de maintenance au cours desquelles les
calibrages du dispositif sont mis à jour.

La traçabilité des résultats peut faire l'objet d'une intégration dans
le système d'information de l'établissement. Les contraintes
d'immobilisation, les ressources humaines et matérielles qui découlent
de l'organisation spécifique d'un site peuvent alors être évaluées.

Dans ce chapitre, nous décrirons :

\- les documents de référence : vérification initiale, cahier de bord,
(inventaire et registre article R5212-28 du code de la santé publique)
nécessaires à la traçabilité et au contrôle externe ;

\- le programme interne du contrôle de qualité périodique du système et
des logiciels disponibles sur le système.

## DOCUMENTS DE REFERENCE

### Fiche inventaire

Au niveau du système d'acquisition, cette fiche constitue l'inventaire
du dispositif et mentionne la marque et le modèle de la caméra à
scintillations et du scanographe associé, son numéro de série et la date
de mise en service. A la mise en service clinique ou à la mise un œuvre
de nouveaux protocoles cliniques, une mise à jour mentionne :

$>$ La version logicielle,

$>$ Les radionucléides et les collimateurs employés en mode planaire,

$>$ Les caractéristiques d'acquisition en mode corps-entier
(collimateurs, radionucléides, type de déplacement et vitesse de
balayage en déplacement continu)

$>$ Les caractéristiques d'acquisition en mode tomographique
(collimateurs, radionucléides, type d'orbite, dispositif de contourage,
orientation des détecteurs)

$>$ Les paramètres d'acquisition employés en imagerie de transmission
(tension, charge de tube, vitesse de rotation, collimation, déplacement
de la table, modulation d'intensité, indices dosimétriques).

La liste des sources scellées nécessaires au calibrage et leur
certificat d'étalonnage sont portés à l'inventaire du dispositif.

### Rapport de qualification

Il n'existe pas d'obligation réglementaire relative à l'existence d'un
document pour le rapport de qualification de la caméra à scintillations.

En liaison avec le représentant du fournisseur responsable de
l'installation, les calibrages nucléaires réalisés en usine et sur le
site lors de l'installation sont inventoriés. Pour chaque radionucléide,
sont spécifiées :

\- les fenêtres spectrométriques et position du pic d'absorption totale
de référence,

\- les tables de correction associées à ces paramètres (énergie,
linéarité et uniformité),

\- les caractéristiques des sources radioactives (activité,
positionnement de la source), ainsi que la limite de taux de comptage
préconisée par le constructeur pour le test de non-uniformité.

\- les accessoires nécessaires au contrôle de qualité et leurs
conditions de mise en œuvre. Les opérations de contrôle initial sont
définies contractuellement entre le fournisseur et l'exploitant dans le
document de cahier des charges du dispositif.

L'activimètre utilisé pour le mesurage des sources doit être calibré
avec une précision inférieure ou égale à $5 \%$ pour les radionucléides
employés.

L'évaluation des performances du système fait appel aux procédures
décrites dans le chapitre 3. L'inventaire des objets test est donné en
tableau 4-1.

# Sources radioactives

Il est préférable, pour des questions de préparation et de
reproductibilité des conditions de mesure, d'utiliser au quotidien une
source plane scellée de ${ }^{57}$ Co à la place $d{ }^{99 \mathrm{~m}}$
Tc. Certaines précautions, décrites en annexe 1 encadrent l'utilisation
d'une nouvelle source de ${ }^{57} \mathrm{Co}$ en raison de la présence
de contaminants.

Pour les tests de qualification et de référence, il convient d'employer
le ${ }^{99 \mathrm{~m}} \mathrm{Tc}$ et le ${ }^{131} \mathrm{I}$; le
${ }^{201} \mathrm{Tl}$ est utilisé pour tester l'uniformité si des
tables de calibrage spécifiques sont associées à ce radionucléide. Ces
radionucléides sont utilisés pour les examens cliniques et généralement
disponibles dans les services de Médecine Nucléaire. Objets test

!\[\](https://cdn.mathpix.com/cropped/2023_02_14_c5cac6413f5f6a21deb5g-04.jpg?height=1930&width=1642&top_left_y=297&top_left_x=207)

Tableau 4.1. Liste des objets test utilisés pour les tests de
qualification d'une caméra à scintillations et leur suivi.

Lors d'un appel d'offres concernant l'acquisition d'une gamma-caméra, il
est important que le matériel nécessaire à la réalisation des contrôles
qualité soit acheté et disponible en même temps que l'équipement.

# Logiciels d'analyse

Le traitement des données repose à la fois sur la bibliothèque
logicielle fournie par le constructeur pour la reconstruction des
projections en mode tomographique ( dont le nom et la version logicielle
seront enregistrés) et une bibliothèque de traitement d'images, dans la
mesure du possible, indépendante du fournisseur du système. Différents
logiciels en domaine public (ImageJ, MIPAV, \...) sont utiles dans ce
contexte.

Les fonctionnalités de base requises dans la bibliothèque de traitement
d'images comprennent :

\- L'export des images en format normalisé (Interfile, DICOM3).

\- La relecture d'images reconstruites et des paramètres nécessaires à
l'analyse quantitative des données (taille des voxels, durée d'examen,
valeur des pixels,\....) ;

\- L'analyse statistique d'images (moyenne, écart-type) par régions
d'intérêt paramétrables ;

\- La détermination du centre de masse d'une structure d'intérêt dans
l'image ;

\- La détermination de profils paramétrables (épaisseur d'intégration) ;

\- La détermination de distances entre points d'intérêt.

\*Lorsque ces images sont analysées par l'intermédiaire d'un système
d'archivage et de communication des images (PACS) ou par un nouveau
logiciel de traitement , il est nécessaire de s'assurer que le service
DICOM d'échanges des images produit des données dont la statistique de
comptage est fidèle aux données natives, le cas échéant des utilitaires
existent dans les bibliothèques domaine public (par exemple, le plug-in
rescale (ImageJ) pour les séquences tomographiques ).

Pour les dispositifs hybrides :

\- Les paramètres de traitement des images TDM en images d'atténuation ;

\- Lorsque les images d'atténuation ne sont pas accessibles, les données
nécessaires à la production de la carte des Facteurs de Correction
d'Atténuation et son traitement en images d'atténuation ;

\- Les paramètres du logiciel de fusion des images TEMP/TDM si
nécessaire, notamment la table de correspondance entre les référentiels
spatiaux des images TEMP et TDM.

!\[\](https://cdn.mathpix.com/cropped/2023_02_14_c5cac6413f5f6a21deb5g-06.jpg?height=1398&width=2804&top_left_y=200&top_left_x=60)

Tableau 4.2-A : Programme récapitulatif des principaux tests de
contrôles de qualité avec tolérances et durées d'immobilisation
associées (tests périodiques).

!\[\](https://cdn.mathpix.com/cropped/2023_02_14_c5cac6413f5f6a21deb5g-07.jpg?height=1376&width=2804&top_left_y=200&top_left_x=60)

Tableau 4.2-B : Programme récapitulatif des principaux tests de
contrôles de qualité avec tolérances et durées d'immobilisation
associées (tests annuels).

# SYSTEMES HYBRIDES

!\[\](https://cdn.mathpix.com/cropped/2023_02_14_c5cac6413f5f6a21deb5g-08.jpg?height=951&width=2772&top_left_y=505&top_left_x=76)

Tableau 4.2-C : Programme récapitulatif des principaux tests de
contrôles de qualité avec tolérances et durées d'immobilisation
associées pour les systèmes hybrides TEMP-TDM.

## PROGRAMME DE CONTROLE DE QUALITE INTERNE

### Calendrier des immobilisations de contrôle et de suivi

Les tableaux $4.2$ synthétisent l'ensemble des opérations de contrôle
qualité permettant le suivi des performances de l'appareil et son
adéquation avec les dispositions AFSSAPS.

Il faut souligner que la personne responsable du contrôle qualité doit
être en copie de tous les rapports d'intervention du constructeur afin
de pouvoir adapter la nature des contrôles à la nature de l'intervention
réalisée par le constructeur suite à une maintenance corrective ou lors
d'une mise à jour logicielle majeure.

### Conditions particulières de réalisation de certains tests de suivi

Certains tests de suivi n'ont pas été décrits dans la partie 3 du
document car ils n'entrent pas dans l'évaluation des performances. C'est
le cas du test de bruit de fond qui relève des règles de bonnes
pratiques, des contrôles du centre de rotation, de la qualité image TDM,
réalisés selon les procédures constructeur et des vérifications de la
spectrométrie et de l'uniformité (analyse visuelle ) effectuées au
quotidien.

### Bruit de fond :

Faire une acquisition en absence de source.

Noter le taux de comptage; il ne doit pas dépasser 2 fois sa valeur de
référence.

### Test visuel de non-uniformité et test de spectrométrie :

Le but de ce contrôle quotidien est d'écarter toute défaillance du
système avant la réalisation des images du patient. Il s'agit pour la
non-uniformité, d'un contrôle qualitatif à effectuer chaque matin.

Dans le cadre d'un programme de contrôle de qualité, l'utilisateur peut
choisir, compte tenu du mode de fonctionnement de la caméra et du
matériel dont il dispose, de réaliser ce test en mode intrinsèque ou en
mode extrinsèque indépendamment.

# - Matériel et acquisition des données:

Le positionnement du matériel correspond au positionnement décrit au §
3.2.2. L'utilisateur réalise une acquisition statique d'au moins 1
million d'évènements.

!\[\](https://cdn.mathpix.com/cropped/2023_02_14_c5cac6413f5f6a21deb5g-10.jpg?height=762&width=1610&top_left_y=227&top_left_x=223)

Tableau 4-3. Conditions d'acquisition du contrôle quotidien de la
réponse de la caméra.

Une acquisition spectrométrique peut également être réalisée en
conservant la même géométrie d'acquisition. La position du pic
d'absorption totale est alors notée pour chaque détecteur.

# - Analyse des images et tolérances :

Le contrôle de la spectrométrie ne devra pas révéler de décalage de plus
de $3 \mathrm{keV}$ entre le pic d'absorption totale mesuré et sa valeur
théorique ni de décalage de plus de $3 \mathrm{keV}$ entre les deux
détecteurs. Le contrôle visuel des images ne devra pas mettre en
évidence de défauts ou de structures particulières dans l'image.

### Centre de rotation :

Pour ce contrôle, il est recommandé d'utiliser la procédure fournie par
le constructeur pour l'acquisition des données, l'analyse et la
présentation des résultats. Le matériel et la préparation des sources
radioactives seront différents d'un dispositif à l'autre. En absence de
procédure constructeur, on pourra utiliser la méthode décrite dans le
paragraphe 3.4.3 du présent document et l'analyse présentée en annexe 2.

### Qualité image TDM :

Dans le cas des bonnes pratiques en TDM, on doit s'assurer que le test,
a minima hebdomadaire, de qualité de l'image TDM (mesure du CTeau,
bruit,\...), selon les modalités du constructeur, est réalisé pour
chaque calibrage du détecteur dans l'air.

# LEXIQUE DES ABREVIATIONS :

\- BCE (balayage corps-entier) : mode d'acquisition pour lequel les
détecteurs ou la table d'examen se déplacent pour enregistrer une image
de dimension supérieure à la dimension axiale du détecteur

\- FDP, fonction de dispersion ponctuelle (PSF : Point Spread Function)

\- FDL, fonction de réponse linéique (LSF, line spread function)

\- EM-ML, maximisation de l'espérance - maximum de vraisemblance (EM-ML,
expectation maximization - maximum likelihood)

\- LDH, largeur à un dixième du maximum (FWTM, full width at tenth
maximum)

\- $\quad$ LMH, largeur à mi-hauteur (FWHM, full width at half-maximum)

\- OSEM, maximisation de l'espérance par sous-ensembles ordonnés (OSEM,
ordered subset expectation maximization)

\- PFD principe fréquence-distance

\- ROI, région d'intérêt ( $R O I$, region of interest)

\- RPF, rétroprojection filtrée (FBP, filtered back projection)

\- TEMP, tomographie d'émission monophotonique (SPECT, Single photon
emission computed tomography)

\- TDM, tomodensitomètre (CT, computed tomography)

\- TPM, tube photomultiplicateur (PMT, photomultiplier tube)

\- CDV, champ de vue utile de l'image lié à la surface du détecteur dans
laquelle les événements sont affichés (UFOV: Useful Field of View,
d'après la définition NEMA)

# ANNEXE 1 : PRECAUTIONS DE MISE EN SERVICE DE LA SOURCE PLANE SCELLEE DE $^{57} \mathbf{C O}$

Le ${ }^{57}$ Co est régulièrement employé pour le calibrage et/ou le
contrôle de l'uniformité de la caméra. La source plane encore appelée
«galette de cobalt » est utile pour l'évaluation de la non-uniformité
extrinsèque.

Chaque source plane de ${ }^{57}$ Co est accompagnée d'un certificat
d'étalonnage indiquant :

\- les références de la source,

\- son activité à une date de référence,

\- sa période physique,

\- l'uniformité de la source,

\- la nature et le niveau de ses contaminants.

Pour le ${ }^{57} \mathrm{Co}$, les contaminants identifiés sont
notamment les ${ }^{56} \mathrm{Co}$ et ${ }^{58} \mathrm{Co}$; leurs
teneurs sont typiquement $<0,01 \%$. Les émissions photoniques
d'énergies élevées de ces radionucléides vont perturber la réponse de la
gamma-caméra. Ceux-ci génèrent des défauts dans l'image d'uniformité du
fait de la pénétration septale du collimateur basse énergie pour les
hautes énergies, ce qui leur donne, en pratique un rôle encore plus
important.

   Energie (keV)   Intensité (%)   Energie (keV)   Intensité (%)
  --------------- --------------- --------------- ---------------
        511            39,21          2015,2           3,02
       846,8           99,94          2034,8           7,74
      1037,8           14,03          2598,4           16,96
      1175,1           2,25           3009,6           1,04
      1238,3           66,41          3201,9           3,20
      1360,2           4,28           3253,4           7,87
      1771,3           15,45          3273,0           1,86

Tableau A1 : Principales émissions gamma
$\mathrm{du}^{56} \mathrm{Co}\left(\mathrm{T}^{1 / 2}=77,24 \mathrm{j}\right)$.

   Energie (keV)   Intensité (%)
  --------------- ---------------
        511            30,0
       810,8           99,45
       863,9           0,69
      1674,7           0,52

Tableau A2 : Principales émissions gamma du
${ }^{58} \mathrm{Co}\left(\mathrm{T}^{1 / 2}=70,83 \mathrm{j}\right)$.
Cet inconvénient peut être minimisé en laissant décroître la source
avant de l'utiliser (6 mois environ pour les sources de
$500 \mathrm{MBq}$ ) et/ou en l'éloignant du détecteur d'au moins
$20 \mathrm{~cm}$ (ce qui ne modifie pas l'efficacité du collimateur
parallèle vis à vis de l'émission à $122 \mathrm{keV}$ ).

L'interprétation des résultats d'uniformité obtenus avec une source
plane de ${ }^{57}$ Co doit également tenir compte de la non-uniformité
propre à cette dernière. A titre d'exemple, le laboratoire Areva calcule
pour chaque source, son uniformité au moyen d'un balayage par une sonde
de NaI collimatée sur environ 2500 points d'analyse équi-distribués sur
la surface utile. Les critères de non-uniformité calculés correspondent
à l'écart-type de cette distribution qui doit rester inférieur à 1%, et
au comptage maximal qui ne s'écarte pas de 3,5 % de la valeur moyenne de
l'ensemble des comptages.

Dans ces conditions, la source peut être employée pour le calibrage des
tables d'énergie et d'uniformité définies avec le fournisseur, ainsi que
pour les tests de suivi de non-uniformité et de spectrométrie pour une
fenêtre spectrale d'acquisition centrée sur le pic principal composé des
pics d'absorption totale des émissions $\ 2$ et $\bigvee 3$ (compte-tenu
de leurs résolutions en énergie, ces deux pics sont superposés sur les
caméras à scintillations actuelles).

# ANNEXE 2 : METHODE D'ANALYSE DU CENTRE DE ROTATION

# ÉVALUATION DES DÉCALAGES TRANSVERSES DU CENTRE DE ROTATION

(à utiliser en absence ou en évaluation de la solution logicielle
proposée par le constructeur)

Une méthode de calcul de l'ajustement du sinogramme expérimental
$\mathrm{X}_{\mathrm{e}}\left(\theta_{\mathrm{m}}\right)$ par la
fonction sinusoïdale $X_{\mathrm{a}}\left(\theta_{\mathrm{m}}\right)$
est développée ici pour le calcul des paramètres transverses
d'ajustement du centre de rotation nécessaires à l'analyse du centre de
rotation (section 3.4.3)

Calcul de l'élongation du centre de gravité : sinogramme des données
$X_{\mathrm{e}}\left(\theta_{\mathrm{m}}\right)$

Le calcul suivant s'opère suivant une ligne ou une colonne de matrice.
Soit C(i) le nombre d'évènements contenus dans le pixel de coordonnée i
et $\mathrm{N}$ le nombre de pixels d'une ligne (ou colonne), la
coordonnée $\mathrm{X}_{\mathrm{e}}$ (ou $\mathrm{Y}_{\mathrm{e}}$ ) est
donnée par:

$$X_{e}=\frac{\sum_{i=0}^{N-1} i C(i)}{\sum_{i=0}^{N-1} C(i)}$$

Ajustement des élongations des centres de gravité par une fonction
sinusoïdale $X_{a}\left(\theta_{\mathrm{m}}\right)$

Soit $X_{\mathrm{e}}\left(\theta_{\mathrm{m}}\right)$ l'élongation
transverse du centre de gravité relatif à la projection $\mathrm{m}$
(calcul précédent) et M le nombre de projections, l'équation de la
sinusoïde d'ajustement s'écrit :

$$X_{a}\left(\theta_{m}\right)=A \sin \left(2 \pi \frac{m}{M}+\varnothing\right)+R_{e}$$

$\mathrm{R}_{\mathrm{e}}$ représente la position du centre de rotation
expérimental.

Les étapes intermédiaires conduisant au calcul de $A, \varnothing$ et
$\mathrm{R}_{\mathrm{e}}$ sont les suivantes :

$$\text { Partie Réelle : PR }=\sum_{m=0}^{M-1} X_{e}\left(\theta_{m}\right) \cos \left(2 \pi \frac{m}{M}\right)$$

$$\begin{aligned}
& \text { Partie Imaginaire : PI }=\sum_{m=0}^{M-1} X_{e}\left(\theta_{m}\right) \sin \left(2 \pi \frac{m}{M}\right) \\
& A=\sqrt{P R^{2}+\mathrm{PI}^{2}} \quad \varnothing=\operatorname{arctg}\left(\frac{\mathrm{PI}}{\mathrm{PR}}\right) \\
& R_{e}=\sum_{m=0}^{M-1} \frac{X_{e}\left(\theta_{m}\right)}{M}
\end{aligned}$$

