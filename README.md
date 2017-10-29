# Livre 1 – Chapitre 1 – Introduction
## Logiciel - Micrologiciel
**Logiciel** : C’est un ensemble de programme, de procédures et de documentation associée et les données qui concernent le fonctionnement d’un système informatique. (ISO 24765)
Le terme logiciel comprend le firmware, la documentation, les données et les instructions de contrôle d’exécution.

**Micrologiciel (firmware)** : Combinaison d’un dispositif matériel et d’instruction d’un ordinateur.
## Erreurs - Fautes - Défaillance
**Erreurs** : Pendant la conception. Une action humaine qui produit un résultat incorrect, comme un logiciel contenant un défaut. (ISO 24765)

**Fautes (défaut)** : Pendant les essais, les tests. Plus les systèmes se complexifie, plus il y a de défauts. Une faute qui, si elle n’est pas corrigée, pourra causer une défaillance ou produire des résultats incorrects. (ISO 24765) Doivent être corrigés avant de devenir une défaillance.

**Défaillance** : En production. La manifestation d’une erreur dans le logiciel. Cessation de l’aptitude d’un produit à accomplir une fonction  requise ou de son incapacité à s’en acquitter à l’intérieur des limites spécifiées précédemment. (ISO 25000)

## Qualité, AQ, CQ
### Assurance qualité (AQ)
* Un ensemble d’activités planifiées et systématiques de toutes les actions nécessaires pour fournir une assurance suffisante qu’un élément produit est conforme aux exigences technique établies.
* C’est aussi un ensemble d’activités destinées à évaluer le processus par lequel les produits sont développés ou fabriqués.
* Les activités planifiées et systématiques mises en œuvre, dans le système qualité, et démontrées au besoin pour fournir une assurance suffisante qu’une entité satisfera aux exigences de qualité.

### Contrôle de la qualité (CQ)
* Un ensemble d’activités visant à évaluer la qualité des produits développés ou fabriqués.
* Le processus de vérification de son propre travail ou de celui d’un collègue.

## Cycle de vie et cycle de développement
### Cycle de vie
Évolution d’un système, produit, service, projet ou autre entité d’origine humaine de la conception à la retraite. (ISO 12207)

### Cycle de développement
Processus de cycle de vie du logiciel qui comporte des activités d’analyse des besoins, de conception, de codage, d’intégration, de tests, d’installation et de soutien pour l’acceptation des produits logiciels. (ISO 90003)

## Maîtrises d’un analyste d’affaires
1. Identification des intervenants concernés qui doivent participer
2. Gestion de réunion
3. Gestion des changements

## Modèle d’affaires
Un modèle d’affaires énonce comment un organisme gagne de l’argent en précisant où (et comment) il se positionne dans son ou ses marchés. Le modèle d’affaires décrit les aspects principaux d’une activité, incluant buts, offres, stratégies, infrastructures, organisations, pratiques de diffusion ou distribution et processus et règles de fonctionnement.
### 5 modèles d’affaires
#### Le développement à contrat
L’entreprise réalise des profits en vendant des services de développement de logiciels sur mesure pour des clients. (craintes : résultats incorrects, dépassement de budgets)

#### Le développement à l’interne
L’entreprise développe des logiciels pour améliorer son efficacité organisationnelle.
Ex.: la direction des ressources informationnelles de la police (craintes : résultats incorrects, projet annulé)

#### Les logiciels commerciaux
L’entreprise réalise des profits en développant et en vendant des logiciels à d’autres organisations.
Ex.: SAP (craintes : poursuites, rappels)

#### Les logiciels de masse
L’entreprise fait des profits en développant et en vendant des logiciels aux consommateurs.
Ex.: Microsoft (craintes : mauvaise critique de la presse, beaucoup d’appels de soutien)

#### Les logiciels embarqués de masse (Firmware Embedded)
L’entreprise fait des profits en vendant des logiciels qui se trouvent dans du matériel et des systèmes embarqués.
Ex.: caméras numériques, graveurs DVD (craintes : poursuites, rappels)

## Facteurs situationnels
Un ensemble d’attributs ou de facteurs propres à un modèle d’affaires:
* La criticité du logiciel
  - Le potentiel de blesser l’utilisateur ou les intérêts de l’acheteur varie selon le type de produit. Certains logiciel peuvent tuer en cas de panne.
* L’incertitude des besoins et exigences des utilisateurs
  - Les exigences pour un logiciel qui met en œuvre un processus connu de l’organisme sont mieux connues que les exigences relatives à un produit de consommation qui est si nouveau que les utilisateurs finaux ne savent même pas ce q’ils veulent.
* La gamme d’environnement informatiques
  - un logiciel écrit pour être utilisé dans une société spécifique doit être compatible uniquement avec son environnement informatique, alors que les logiciels vendus dans le marché de masse doivent fonctionner dans un large éventail d'environnement.
* Le coût de correction des erreurs
  - la distribution des correctifs de certains logiciels est beaucoup plus coûteuse que de colmater un seul site web.
* La communication
  - il existe un certain nombre de facteurs, outre la dimension du projet, qui peuvent augmenter la quantité de communications de personne à personne ou de rendre les communications plus difficiles.
* La réglementation
  - les organismes de réglementation et les clauses contractuelles peuvent exiger l'utilisation de pratiques logicielles qui autrement ne seraient pas être adoptées.
* Culture de l’organisation
  - l'organisation a une culture qui définit comment les gens fonctionnent.
* La taille du projet
  - les projets qui s'échelonnent sur plusieurs années avec des centaines de développeurs sont courants dans certaines organisations, alors que dans d'autres organismes, les projets plus courts développés par une seule équipe sont plus typiques.

Ces facteurs situationnels permettent de déduire un ensemble d’hypothèses applicable à ce modèle d’affaire :
1. Le respect du budget et des délais prescrits est très important
2. Un logiciel fiable et correct est très important
3. Les exigences doivent être connues et détaillées dès le début du projet
4. Les projets sont typiquement de grande envergure et les canaux de communication sont nombreux.
5. Il est nécessaire de démontrer que ce qui a été initialement promis a bel et bien été livré.
6. Il faut régulièrement développer des plans et produire des rapports d’étapes

# Livre 1 – Chapitre 2 – Culture

## 5 dimensions d’un projet logiciel et les compromis
Il faut comprendre et possiblement négocier les dimensions avec le client avant le début du projet et peut-être renégocier lors d’un changement important au projet. Graph de Kiviat avec une échelle graduée de 10 valeurs où 0 est une contrainte et 10 est la liberté totale.
1. Fonctionnalités
   * Capacité implémenté par le logiciel
2. Qualité
3. Coût
   * Prix du projet
4. Échéance
   * Facteur de garantie des tâches à accomplir
4. Personnel
   * Quantité de personnel, personnel efficace

## COQ – prévention - détection – défaillance – préjudice
### Coût de prévention
Pour prévenir l’occurrence d’erreurs dans les diverses étapes durant le processus de développement ou de maintenance.
### Coût de détection (ou d’évaluation)
Le coût de vérification ou d’évaluation d’un produit ou d’une service pendant les différentes étapes du processus de développement
### Coût de défaillance
**Interne** : le coût résultant des anomalies avant que le produit ou le service ne soit livré au client.

**Externe** : Le coût encouru par la compagnie quand c’est le client qui découvre le problème.

**Préjudice commercial** : Conséquences de la dégradation de l’image d’une entreprise, de la perte de clients et des poursuites en justice.

## Comment la culture d’entreprise est prédictive de la qualité des produits
La culture d’un organisme est un facteur de réussite déterminant dans ses efforts d’amélioration des processus. La culture comprend un ensemble de valeurs et de principes partagés qui guident les comportements, les activités, les priorités et les décisions d’un groupe de personnes travaillant dans le même domaine. Quand des collègues s’alignent sur des croyances communes, il est plus facile d’amener des changements qui permettront d’accroître l’efficacité du groupe ainsi que ses chances de survie.

## Code de déontologie – IEEE / OIQ
Le souci pour la santé, la sûreté et le bien-être du public est primordial
C’est-à-dire que l’intérêt du public est central à ce code de déontologie.
Les 8 principes:
1. Le public
   - les ingénieurs logiciels doivent agir dans l’intérêt du public en tout temps
2. Le client et l’employeur
   - les ingénieurs logiciels doivent agir de manière à servir le mieux possible les intérpet de leur clients et de leur employeur, toujours en fonction de l’intérêt public
3. Le produit
   - les ingénieurs logiciels doivent s’assurer que leurs produits et les modifications connexes sont conformes aux normes professionnelles les plus élevées possible
4. Le jugement
   - les ingénieurs logiciels doivent maintenir leur intégrité et leur indépendance dans leur jugement professionnel.
5. La gestion
   - les gestionnaires et les responsables de génie logiciel doivent souscrire à une approche éthique de la gestion du développementet de la maintenance des logiciels et s’employer à en faire la promotion
6. La profession
   - les ingénieurs logiciels doivent s’assurer de l’intégrité et la réputation de la profession en tenant compte de l’intérêt public
7. Les collègues
   - les ingénieurs logiciels doivent être justes et appuyer leur collègues
8. Soi-même
   - les ingénieurs doivent être en situation d’apprentissage continu et promouvoir une approche éthique à la pratique de leur profession.

**Ce qu’on doit retenir sur les fraudeurs et comment y faire face dans nos organisations.**

Une autre punition possible est la limitation du droit d’exercice pendant une période donnée, l’obligation de suivre une formation, l’imposition d’amendes et l’obligation de rembourser des sommes.

# Livre 1 – Chapitre 3 – Exigences qualité

## Exigence fonctionnelles
Une déclaration qui indique ce qu’un produit ou un processus doit accomplir pour produire le comportement et/ou les résultats requis.

## Exigence non fonctionnelle
Une exigence logicielle qui ne décrit pas ce que le logiciel va faire, mais comment le logiciel va le faire. Synonyme : contraintes de conception.

## Exigence de qualité du logiciel
Une fois les parties prenantes identifiées, les activités menant à la spécification du logiciel sont:

**Éliciter** : rassembler les souhaits, attentes et besoins des parties prenantes

**Prioriser** : débattre de leur importance relative, par exemple selon deux priorités.

**Analyser** : vérifier la cohérence et l’exhaustivité.

**Décrire** : écrire les exigences sous une forme aisément compréhensible pour les utilisateurs et les développeurs.

**Spécifier** : transformer les exigences d’affaires en spécification logicielle

**Réviser**

## Évaluation
Détermination systématique de la mesure dans laquelle une entité répond aux critères spécifiés.

### Comment obtient-on les exigences?
Les besoins ou les exigences de ces systèmes sont documentés soit dans un document d’appel d’offres, dans un cahier des charges décrivant le système ou dans le document des spécifications du système.

## Garvin
5 perspectives de la qualité étudiées par Garvin.

**Perspective transcendantale de la qualité** : Quoique la qualité ne puisse pa être définie, vous le savez quand vous l’expérimentez.

**Perspective de l’utilisateur** : Le logicel de qualité fait ce qu’il doit faire du point de vue de son utilisateur.

**Perspective de la fabrication** : La qualité est définie comme étant la conformité aux spécifications.

**Perspective de la qualité du produit** : La perspective interne du produit comme par exemple la qualité de son architecture.

**Perspective de la qualité comme valeur** : Vise à éliminer toutes les activités qui n’ont pas de valeur ajoutée. Par exemple, la rédaction de certaines documentations.

Il a établi que les modèles de la qualité du logiciel peuvent mesurer la qualité telle que défini par les grands du logiciel.

## McCall
Le modèle de qualité de McCall visait principalement la perspective de la qualité du produit (c-à-d le point de vue interne) et ne permettait pas facilement de faire le lien avec le point de vue de l’utilisateur qui ne se préoccupe pas des détails techniques.
Propose un mode d’évaluation subjectif de 0 à 10.

## Dromey
Dromey propose un cadre d’évaluation de la qualité implantée dans un logiciel en procédant à la mesure des propriétés observables concrètement dans le logiciel. Selon lui, chaque produit intermédiaire et composant logiciel peut faire l’objet d’évaluation.

## IEEE 1061
Fournit un cadre de la mesure de la qualité du logiciel qui permet d’établir et d’identifier les mesures de la qualité d’un logiciel à partir d’exigences de qualité et ainsi mettre en œuvre, analyser et valider les processus et les produits logiciels.

## ISO 9126
Norme qui tente de favoriser la mise en œuvre de la mesure de la qualité du logiciel d’une manière systématique. Permet l’évaluation du produit final.

## ISO 25000
Préconise les quatre étapes suivantes :
1. Fixer les exigences de qualité
2. Établir un modèle de qualité
3. Fixer les métriques de la qualité
4. Conduire les évaluations

### Interactions entre les caractéristiques de qualité
Ensemble d’attributs d’un produit logiciel au moyen desquels la qualité de ce produit est décrite, vérifiée et validée.

L’architecture de l’ISO 25000 préconise les quatre étapes suivantes :
1. Fixer les exigences de qualité
2. Établir un modèle de qualité
3. Fixer les métriques de la qualité
4. Conduire les évaluations

**Caractéristiques**
1. Modèle de qualité ---> Qualité
2. Caractéristiques ---> Rendement
3. Sous-caractéristiques ---> rendement et comportement vis-à-vis du temps
4. Mesures/attributs ---> nom:temps de réponse, but de la mesure: combien de temps prend l’exécution d’une tâche?, formule: t= a-b a= temps qui prend le système à répondre et b = temps…

## Modèle de qualité
Ensemble défini de caractéristiques et de relations entre elles qui fournit un cadre pour spécifier les exigences de qualité et pour évaluer la qualité.

## Traçabilité bidirectionnelle
* Une technique qui nous aide à suivre le développement des besoins ainsi que leurs changements
* L’association parmi 2 entités logiques ou plus tels que les exigences, l’architecture d’un système
* La traçabilité bidirectionnelle permet de suivre en aval et en amont que les exigences sont décomposées, raffiné pendant le cycle de vie.

# Livre 1 – Chapitre 4 – Normes
## Norme
Ensemble d’exigences obligatoire établies par consensus et maintenues par un organisme reconnu pour prescrire une approche disciplinée et uniforme ou pour spécifier un produit, des conventions et des pratiques obligatoires.

## ISO 9001
La norme internationale ISO 9001 constitue en ensemble de spécifications génériques, applicables à tous les secteurs d’activité quels que soient la taille de l’organisme et le domaine d’activité. Elle spécifie un ensemble de vigt exigences d’un système de management de la qualité, qui couvrent les politiques et les responsabilités de l’organisme, la gestion des ressources, la qualité du produit, la maintenance d’enregistrements sur la qualité, ainsi que les exigences d’amélioration continue telle que les revues et le contrôles qui doivent être appliqués le long du cycle de vie du produit ou service offert par l’organisme.

## ISO 90003
La norme ISO 90003 donne des lignes directrices pour l’application de l’ISO 9001 aux logiciels informatiques. Elle fournit aux organismes des indications sur l’application de l’ISO 9001 pour l’acquisition, la fourniture,  le développement, l’exploitation et la maintenance des logiciels.
Le but de la vérification du logiciel est de s’assurer que les éléments de sortie d’une activité de conception et de développement sont conformes aux exigences des éléments d’entrée. Il convient que les résultats de la vérification et de toutes actions ultérieures soient enregistrés et contrôlés une fois les actions accomplies. Lorsque la taille, la complexité ou la criticité d’un produit logiciel sont avérées, il convient d’utiliser des méthodes spécifiques, d’assurance-qualité pour la vérification, telle que des métriques de complexité, des revues par des pairs, le taux de couverture des conditions /décisions ou des méthodes formelles. Il convient que seuls des éléments de sortie de la conception et du développement vérifiés fassent l’objet d’une acceptation et d’une utilisation ultérieure. Tout écart constaté doit être traité et résolu, selon le cas.

## ISO 12207
La norme internationale ISO 12207 établit un cadre commun pour les processus de cycle de vie des logiciels. Elle s’applique à l’acquisition de systèmes et de produits logiciels et de services, à ‘approvisionnement, au développement, à l’exploitation, à la maintenance et au retrait des produits logiciels et au développement de la partie logicielle d’un système, qu’elle soit effectué en interne ou en externe à un organisme. Définit 2 ensembles de processus, Sotware Specific Processes et System Context Processes.

## IEEE 730
La portée de la norme IEEE 730 Software Standard for Software Quality Assurance est très différente des versions antérieures. La nouvelle version établit les exigences pour la planification et l’exécution d’Activité d’assurance qualité logicielle pour un projet logiciel. Elle fournit des directives pour les activités d’assurance qualité logicielle de produits ou de services. Décrit le cadre du processus d’assurance qualité logicielle mais ne précise pas comment le mettre en œuvre ou comment exécuter les activité et tâches incluses dans le processus.

## CMMI
L’objectif du modèle CMMI est d’encourager les organismes à mettre leur processus de projet de développement de logiciel sous contrôle, à les améliorer de façon continue et d’évaluer leur niveau de maturité sur l’échelle de cinq niveaux de maturité proposés par le modèle. Le CMMI a été développé en 2 représentations : une représentation étagée comme le premier modèle et une représentation continue comme le premier modèle CMM pour l’ingénierie des systèmes.

## ITIL
C’est une collection de cinq livres qui donnent des conseils et recommandations afin d’offrir un service de qualité aux utilisateurs des services de TI. La liste des livres est la suivante :
1. Stratégies
2. Conception
3. Transition
4. Opération
5. Amélioration continue

Les processus de soutien décrits dans ITIL sont orientés vers les opérations au jour le jour. Leurs objectifs premiers sont de résoudre les difficultés au moment où elles se produisent ou d’éviter qu’elles se produisent lors d’un changement dans l’environnement informatique ou dans les façons de faire de l’organisme.

Décrit les 5 processus suivants :
1. Gestion des incidents
2. Gestion des problèmes
3. Gestion de la configuration
4. Gestion des changements
5. Gestion des mises en production

## ISO 27002
L’ISO 27002 est un ensemble de 133 mesures dites bonne pratiques, destinées à être utilisées par tous ceux qui sont responsables de la mise en place ou du maintien d’un système de management de la sécurité de l’information (SMSI).  Cette norme n’a pas de caractère obligatoire pour les entreprises. Son respect peut toutefois être mentionné dans un contrat : un prestataire de services pourrait ainsi s’engager à respecter les pratiques normalisées dans ses relations avec un client.

## ISO 29110
La caractéristique essentielle des organismes visés par les normes ISO 29110 est la taille. Les logiciels critiques sont ceux qui advenant une défaillance, pourraient avoir un impact sur la sûreté de fonctionnement ou causer des pertes financières ou sociales considérables.

# Livre 1 – Chapitre 5 – Revues
## À quoi servent les revues?
Une revue est un processus ou une réunion au cours de laquelle un produit logiciel, un sensemble de produits logiciels ou un processus logiciel est présenté au personnel de projets, gestionnaires usagers, clients, représentants des utilisateurs, des auditeurs ou d’autres parties intéressées pour examen, avis et approbation.

## Les différences entre les différentes revues

||Gestion|Technique|Inspection|Walk-through|Audit|
|---|---|---|---|---|---|
|**Objectifs**|Assurer la progression|Évaluer la conformité (spécifications) |  Trouver les anomalies|Trouver les anomalies et de les améliorer/examiner|Évaluer la conformité (normes)|
|**Leadership**|Gestionnaire|Ingénieur en chef|Facilitateur entraîné|Facilitateur ou auteur|Auditeur en chef|
|**Nombre participants**|Illimité|Illimité|3-6|2-7|1-5|
|**Quantité de matériel**|Moyenne à élevée|Moyenne à élevée|Relativement basse|Relativement basse|Moyenne à élevé|
|**Management présent?**|Oui|Optionnel|Non|Non|Oui|
|**Output**|Rapport de gestion|Rapport technique|Liste d’erreurs|Rapport|erreurs|

## Les mesures des revues – défauts, efforts, taille – injection, détection
Les mesures servent essentiellement à répondre aux questions suivantes :
* Combien de réunions ont été effectuées?
* Quels produits logiciels ont été révisés?
* Quelle est l’efficacité des réunions?
* Quelle est la densité d’erreurs dans les produits logiciels?
* Combien d’efforts sont consacrés aux revues?
* Quels sont les bénéfices des revues?


Les mesures qui nous permettent de répondre à ces questions sont les suivantes :
* Nombre de réunions tenues
* Identification du produit logiciel révisé
* Taille du produit logiciel
* Nombre d’erreurs enregistrées à chaque phase du processus de développement
* Efforts consacrés à la révision et à la correction.

Rendement (yield) = (# défauts détectés) / (# défauts présents)

### Les artéfacts de la revue
1. Formulaire d’enregistrement de la revue
2. Formulaire d’enregistrement des défauts
3. Guide de préparation des contrats
4. Processus de revue (ETVX)
5. Proposition à réviser

# Livre 1 - Chapitre 6 – Audits

## Audits
Un examen indépendant d’un produit logiciel, d’un processus logiciel, ou d’un ensemble de processus logiciel, d’un ensemble de processus logiciels pour évaluer la conformité aux spécifications, aux normes, aux accords contractuels ou à d’autres critères.

## Audits internes et externes selon ISO 9001
### ISO 9001
La norme ISO 9001 ont appris que dans un marché concurrentiel, une preuve indépendante de conformité pouvait leur donner un avantage compétitif afin de conquérir de nouveaux clients et de nouveaux contrats. ISO 90003 est un guide d’interprétation de la norme ISO 9001.

### Audit internes
Les audits internes à intervalles planifiés pour déterminer si le système de management de la qualité est conforme aux dispositions planifiées, aux exigences de la présente norme internationale et aux exigences du système de management de la qualité établie par l’organisme.

### Audit externes
Lorsque l’audit est réalisé par le client.
Les grandes étapes de l’évaluation et de l’audit des logiciels

#### Les grandes étapes de l'évaluation et de l'audit des logiciels
Choix des évaluateurs
* Rencontres/Questionnaires et Plans de l’évaluation/audits
  - Analyse des réponses et revue de la documentation
    * Visites au site (entrevues et revues)
      - Constats (basés sur le modèle ou la norme utilisée)
        * Représentation graphique du Profil de secteur clé

## Actions préventives et correctives
### Actions correctives
Actions utilisées pour remédier à une situation, supprimer une erreur ou ajuster une condition. (ISO/IEC/IEEE 24765) Directive documentée pour l’exécution de travaux pour un projet afin que le rendement attendu du projet soit en conformité avec le plan de gestion du projet. (PMBOK)

### Actions préventives
Une direction documentée pour effectuer une activité qui peut réduire la probabilité de conséquences négatives associés aux risques du projet. (PMBOK)

## Que peut-on auditer? Mandat d’audit – rapport d’audit
Le rapport des problèmes doit être utilisé dans le cadre du processus en boucle fermée décrit ci-dessus : à partir de la détection du problème, de l’investigation, de l’analyse, de la résolution du problème et de sa cause jusqu’à la détection des tendances de ces problèmes.

### Les documents archivés peuvent inclure
1. Le mandat de l’audit approuvé par l’initiateur
2. Le plan d’audit
3. Les comptes rendus de lancement et de clôture
4. Les listes de vérifications utilisées par les auditeurs
5. Le rapport d’audit
6. La liste des propositions d’amélioration des processus
7. La liste des actions correctives et de leur suivi jusqu’à leur clôture

Dans le rapport d’audit, on peut retrouver les sections Intention, Portée, Auditeur(s), Personnel contacté, Définitions, Sommaire, Demande d’amélioration et Constats.

## SCAMPI pour CMMI
Le SEI a développé la méthode d’évaluation appelée SCAMPI pour supporter l’évaluation de la mise en œuvre des pratiques du CMMI. La méthode SCAMPI peut être utilisée pour l’amélioration des processus internes, pour la sélection des fournisseurs ou pour la surveillance des processus. L’évaluation peut servir à
1. Établir un portrait des forces et faiblesses des processus actuels
2. Déterminer le niveau de maturité des processus actuels
3. Mesurer les progrès par rapport à une évaluation précédente
4. Servir d’intrants à la rédaction d’un plan d’amélioration des processus
5. À préparer l’organisme à une évaluation par un client
6. Auditer les processus

# Livre 2 - Chapitre 3 – Les politiques, processus et procédures

## Qu’est-ce qu’on processus – 3 éléments?

## Qu’est-ce que l’approche par processus?
Toute activité ou ensemble d'activités qui utilise des ressources pour convertir des éléments d'entrée en éléments de sortie peut être considérée comme un processus. L'identification et le management méthodiques des processus utilisés dans un organisme, et plus particulièrement les interactions de ces processus, sont appelés l'approche processus.
### Pyramide Structure documentaire
1. politiques
2. processus
3. procédures
4. enregistrements qualité

## Lien à faire entre l’approche processus et les normes

## Notations de processus
### Notation ETVX (Entry Task Verification eXit)
|intrant|(boucle) tâche -> valider| extrant|
|---|---|---|

ou

|intrant|Activités/Tâches| extrant|
|---|---|---|
|critère de déclenchement|mesures|critère d'achèvement|

## Institutionnalisation
Une pratique est institutionnalisée quand elle fait partie de la culture.

## Politiques
Des énoncés clairs et mesurables de la direction et du comportement privilégiés en vue d'orienter les décisions prises au sein d'un organisme.

### Directive organisationnelle
Principe directeur généralement établi par la hiérarchie et adopté par une organisation pour influencer et déterminer les décisions.

### Politique qualité
Orientations et intentions gémérales d'un organisme relatives à la qualité telles qu'elles sont officiellement formulées par la direction.

## Processus
Ensemble d'activités corrélés ou interactives qui transforme des éléments d'entrée en éléments de sortie. Expression documentée d'un ensemble d'activités réalisées pour atteindre un objectif donné.

## Procédures
Manière spécifiée d'effectuer une activité ou un processus. Les procédures peuvent ou non faire l'objet de documents. Lorsqu'une procédure fait l'objet de documents, les termes procédure écrite ou procédure documentée sont fréquemment utilisés. Le document contenant une procédure peut être appelé un document de procédure.

## Standards de l’organisation
La norme ISO 9001 définit l'environnement de travail comme un ensemble des conditions dans lesquelles le travail est effectué. Les standards ou conventions de l'organisme définissent les attentes et les performances acceptables en fournissant des définitions précises qui guident le travail, la collecte et l'utilisation des données comme des standards de programmation.

## Efficacité, efficience
**Efficacité** : Niveau de réalisation des activités planifiées et d'obtention des résultats escomptés.

**Efficience** : Rapport entre le résultat obtenu et les ressources utilisées.
