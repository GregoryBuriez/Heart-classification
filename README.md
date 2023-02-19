# Heart-classification

Explication du projet : 


Les personnes atteintes de maladies cardiovasculaires ou à haut risque cardiovasculaire (en raison de la présence d'un ou plusieurs facteurs de risque tels que l'hypertension, le diabète, l'hyperlipidémie ou une maladie déjà établie) ont besoin d'une détection et d'une prise en charge précoces dans lesquelles un modèle d'apprentissage automatique peut être d'une grande aide.

Informations sur les attributs : 

- Âge : âge du patient [années]
- Sexe : sexe du patient [M : Masculin, F : Féminin]
- ChestPainType : type de douleur thoracique [TA : Angine typique, ATA : Angine atypique, NAP : Douleur non angineuse, ASY : Asymptomatique]
- BP au repos : pression artérielle au repos [mm Hg]
- Cholestérol : cholestérol sérique [mm/dl]
- FastingBS : glycémie à jeun [1 : si FastingBS > 120 mg/dl, 0 : sinon]
- ECG au repos : résultats de l'électrocardiogramme au repos [Normal : normal, ST : présentant une anomalie de l'onde ST-T (inversions de l'onde T et/ou élévation ou dépression du segment ST > 0,05 mV), HVG : montrant une hypertrophie ventriculaire gauche probable ou certaine selon les critères d'Estes]
- MaxHR : fréquence cardiaque maximale atteinte [Valeur numérique entre 60 et 202]
- ExerciseAngina : angine induite par l'effort [O : Oui, N : Non]
- Oldpeak : oldpeak = ST [Valeur numérique mesurée en dépression]
- ST_Slope : la pente du segment ST d'exercice maximal [Haut : ascendant, Plat : plat, Bas : descendant]
- HeartDisease : classe de sortie [1 : maladie cardiaque, 0 : normal]


Source
Ce jeu de données a été créé en combinant différents jeux de données déjà disponibles indépendamment mais non combinés auparavant. Dans cet ensemble de données, 5 ensembles de données cardiaques sont combinés sur 11 caractéristiques communes, ce qui en fait le plus grand ensemble de données sur les maladies cardiaques disponible à ce jour à des fins de recherche. Les cinq ensembles de données utilisés pour sa conservation sont :

Cleveland: 303 observations
Hungarian: 294 observations
Switzerland: 123 observations
Long Beach VA: 200 observations
Stalog (Heart) : 270 observations

Total: 1190 observations
Duplicated: 272 observations

Fichier final: 918 observations
