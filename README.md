# VSD_Jets_Enquete
Enquête sur les données relatives aux jets privés dans le cadre du cours La Vie Sociale des Données 
## Introduction

### Histoire du traçage des jets privés 

Pour notre enquête, nous avons choisi de s’intéresser au traçage des données des jets privés. Notre étude commence aux origines du suivi des aéronefs. C’est la technologie du radar, développée par Heinrich Hertz en 1888, qui permet de détecter et d’assister les avions en vol. Le radar est d’abord utilisé dans un contexte militaire. Pendant la Seconde Guerre Mondiale, il permet aux anglais de détecter la trajectoire des avions allemands. Plus la technologie du radar s’est améliorée, plus le suivi des avions s’est développé. Nous détaillerons l’évolution des technologies qui permettent le traçage des aéronefs plus tard dans notre étude. Le flight tracking s’est développé au fil du temps grâce à la mobilisation de nombreux acteurs. 

### Les acteurs mobilisés 

**Acteurs gouvernementaux** 

La DSNA, la Direction des Services de la Navigation Aérienne, est un acteur majeur dans la construction de cette collecte de données sur les vols publics et privés. Cette institution a longtemps été empêchée de rendre ses données publiques, puisqu'un enjeu de défense nationale rentre en compte. La DSNA est prestataire de la DGAC, la Direction Générale de l’Aviation Civile. Il existe un *État des lieux des outils de visualisation des trajectoires et du bruit des avions*, publié en février 2021 par l’ACNUSA, l’autorité de contrôle des nuisances aéroportuaires. Cette publication rend compte de la réticence de la DGAC à publier les données obtenues par la DSNA, jusqu’à 2015. C’est à cette date qu’un partenariat se crée entre la DSNA et certains aéroports français pour publier en ligne les trajectoires et émissions sonores des aéronefs volant au-dessus du territoire. Depuis, des outils de visualisation sont disponibles pour tracer les vols commerciaux et privés et s’ajoutent ainsi au travail entrepris par les sites d'initiatives personnelles comme FlightRadar24 et RadarBox. 

**Les aéroports**

Lorsque les vols commerciaux se démocratisent, les compagnies aériennes et les aéroports deviennent des acteurs majeurs du suivi des aéronefs. L’*État des lieux des outils de visualisation des trajectoires et du bruit des avions* indique que de nombreux aéroports ont mis en place des systèmes de traçage des aéronefs partant de leur tarmac depuis la levée de la réticence de la DGAC. Par exemple, le groupe ADP, Aéroports de Paris, a mis à disposition du public la plateforme Vitrail, qui permet de visualiser les trajets des vols au départ des aéroports parisiens ainsi que l'historique de leurs émissions sonores. 

**Les sites de flight tracking en ligne** 

Au début des années 2000, ce sont des sites privés qui commencent à recenser les trajets de vols des avions dans le monde entier. AirNav Systems est créé par deux ingénieurs américains en 2001. Leur site de tracking RadarBox permet de suivre la trajectoire de vols internationaux en direct. FlightRadar24 est créé en 2006 par deux suédois passionnés d’aviation. Ils développent le réseau de récepteur ADS-B, dont nous parlerons plus en détail dans la suite de notre étude. Ces deux plateformes sont en libre accès et incluent des services supplémentaires payants. 

**Les extracteurs de données sur les réseaux sociaux**

Depuis quelques années, d’autres acteurs interviennent dans cet enjeu de traçage des vols en visant l’utilisation d’avions privatisés pour le déplacement de personnalités politiques ou du monde du divertissement. Ce traçage prend la forme de comptes sur les réseaux sociaux, surtout sur Instagram et sur Twitter. Les individus derrière ces comptes utilisent des plateformes publiques de flight tracking comme celles que nous avons citées précédemment (FlightRadar24 et RadarBox) pour en extraire les données qui les intéressent le plus. Cette extraction permet de cibler des personnalités et de montrer au grand public les trajets qu’elles effectuent dans leurs jets privés. Nous préciserons dans notre enquête comment s’effectue ce traçage et à quelles fins sont utilisées ces données. 
    
### Le phénomène du Flight Tracking

Le phénomène qui caractérise le traçage des vols privés s’appelle le flight tracking. Ce terme peut comprendre toutes les formes de traçage d’aéronefs, mais il est surtout utilisé pour parler du suivi des jets privés de personnalités publiques qui s’opère aujourd’hui. Aurélien Défer précise dans *Le Monde* que le flight tracking était à l’origine une pratique réalisée par ‘des passionnés d’aviation et d’investigation en sources ouvertes’. Aujourd’hui, ce phénomène se démocratise, et permet à tout individu possédant un ordinateur et une connexion internet d’observer les trajectoires de vols commerciaux et de vols privés grâce aux plateformes publiques. 
    
### L'enquête 

Notre enquête portera donc sur l’analyse de l’utilisation des données relatives aux vols de jets privés. Nous commencerons par aborder la partie technique de ces données : comment le traçage est effectué, quelle technologie est utilisée et comment les données sont rendues visibles pour les utilisateurs. Nous analyserons ensuite l’aspect juridique du phénomène du flight tracking, en se focalisant sur les potentielles atteintes à la vie privée que le traçage des aéronefs implique. Nous exposerons dans un troisième temps, les objectifs du flight tracking dénonciateur, en analysant l’enjeu écologique majeur qu’il dévoile. Nous terminerons par l’étude du lien étroit entre la pratique du flight tracking, la confiance du public dans les données et le développement du journalisme de données. 

## Partie 1 - Comment ces bases de données sont-elles construites ? 

### À L’origine des données 

**Le système ADS-B**

Les avions d’aujourd’hui sont un exemple parmi d’autres de la course à la donnée qui caractérise notre époque. En effet, on y retrouve une quantité de capteurs et d’outils destinés à créer et transmettre de la donnée. L’outil qui nous intéresse ici est l’ADS-B, Automatic Dependant Surveillance – Broadcast. À la différence de la plupart des autres outils, l’ADS-B est un système ouvert, les données sont diffusées (on parle de *squitters*). Ces données sont captées par d’autres outils sur le même avion, ou par les autres avions à proximité. Mais ces outils ne sont pas les seuls à pouvoir les récupérer, il est en effet possible de capter les données ADS-B des avions passant au-dessus de nos têtes à l’aide d’une simple antenne. Ces données sont parfois publiées sur des sites Internet libres d’accès, comme adsbexchange.com où l’on peut donc suivre tous les avions équipés de ce système ADS-B, qui est une obligation légale pour les avions récents. Certaines données de vol sont parfois également rendues disponibles directement par les aéroports et les lignes aériennes, ce qu’incorpore notamment le site FlightRadar24. 

**La mesure des émissions de CO2**
 
Si l’on entend fréquemment dire que l’avion est le mode de transport le plus polluant, il est peu souvent expliqué comment on arrive à ce résultat final précisément. C’est donc ce que nous allons voir ici, en reprenant les travaux de Brandon Graver Ph.D, Kevin Zhang et Dan Rutherford Ph.D, parus en 2018.
Pour créer leur propre modèle d’émissions de CO2, les auteurs ont employé le logiciel *Piano 5*, qui contient lui même une base de données composée d’une variété d’avions avec leurs caractéristiques techniques. Ils ont lié chaque avion provenant des données des opérations aériennes à son équivalent sur *Piano 5*. Il a fallu ensuite déterminer un grand nombre de critères à prendre en compte pour atteindre une modélisation la plus précise possible. On y retrouve entre autres la poussée des moteurs, la vitesse de croisière (approximée par les auteurs) ou encore le choix de prendre 25 minutes comme durée pour le déplacement au sol (taxi). Pour ce qui est de l’aviation de transport de passagers, il faut rajouter les valeurs qui en dépendent : le poids des passagers et leurs bagages par rapport au poids total ainsi que le taux de remplissage de l’avion. Elles permettent ainsi de déterminer la consommation de carburant imputable à un passager marginal. Ces données sont particulièrement importantes pour l’étude des émissions des jets privés puisque le nombre de passagers est fortement réduit par rapport à l’aviation commerciale, faisant ainsi peser sur moins de passagers le poids total de l’avion et donc sa consommation de carburant. Enfin, cette consommation de carburant permet d’aboutir aux émissions globales de l’avion grâce à la constante communément admise suivante : 3,16 tonnes de CO2 sont émises par la consommation d’1 tonne de carburant d’avion. C’est à partir de ces modèles, qui se sont développés et ont été largement acceptés, qu'il est possible de déterminer les émissions de CO2 d’un trajet en avion à partir des données émises par celui-ci ou trouvables conjointement avec les aéroports. 

### La représentation des données : un besoin de visualisation 

Nous avons ainsi vu les technologies permettant la collecte de données concernant les trajets aériens. Cependant, ces données sont brutes. Afin qu'elles puissent se constituer en tant que réflection de phénomènes sociaux, on trouve un besoin de représentation de celles-ci. Ces représentations sont fournies par les outils eux-mêmes et permettent non seulement une analyse des phénomènes évoqués, mais aussi, dans un traitement secondaire de ces représentations, une réflexion politique et sociale sur ces sujets traités par celles-ci. 

La première représentation présentée sur les deux outils principaux (FlightRadar24 et RadarBox) est une carte présentant les vols en cours dans le monde. En cliquant sur un avion en particulier, sur les deux sites, des données précises et la manière de les acquérir sont données. À noter, sur FlightRadar24, une première distinction entre avions (bleu pour ceux dont les données sont collectées par sattelite, jaune pour les autres) est faite, ce qui n'est pas le cas chez son concurrent. Cependant, cette représentation ne donne que peu de possibilité d'analyse et c'est pourquoi d'autres existent. L'image ci-dessous vous montre la représentation visuelle du vol des avions au dessus du continent européen grâce au site FlightRadar24 : 

![Représentation visuelle de vol des avions au dessus du continent européen grâce au site FlightRadar24](https://live.staticflickr.com/4007/4540719465_5910abd6d0_c.jpg) 

Source : FlightRadar24 

En effet, FlightRadar24 se concentre dans sa partie 'data representation' sur la quantité du trafic. Cela est fait sous forme de graphiques. Dans une seule représentation, les fluctuations de trafic aérien en fonction de l'heure, le jour de la semaine, le mois et les années sont représentées. Un autre graphique est proposé pour le trafic commercial seulement. Cela laisse aisément deviner le trafic privé grâce à une simple soustraction, mais il est intéressant de noter que ce graphique en particulier n'est pas proposé. De plus, les données plus spécifiques concernent des critères techniques plutôt que sociaux (caractéristiques, marques et modèles des avions plutôt que propriétaire, appartenance etc.) Chez RadarBox, l'accent est mis sur la différence entre usage des avions : avant même d'être confronté à des représentations, l'utilisateur doit choisir entre commercial flights, business jets, business jets operators ou major airlines par exemple. Les graphiques sont alors similaires à ceux évoqués, mais ils proposent en plus un outil de comparaison et des critères beaucoup plus spécifiques (et gratuits, contrairement à FlightRadar) qui permettent de trier la catégorie (par exemple jets privés) par région d'appartenance à l'appareil ou sa non-appartenance. 

La représentation, après une collecte de données qui est sensiblement la même chez les deux sites, relève d'un choix et a pour conséquence une présentation de différentes approches du réel, sous différents prismes. Ce n'est pas pour dire qu'il y a une tentative de manipulation : toutes les données sont vraies et il y a une sincère volonté d’exactitude. Seulement, la représentation relève d'un choix. Ces différences dans les choix peuvent s'expliquer par la demande des utilisateurs (qui payent pour accéder au service). Certains auront besoin de données techniques tandis que d'autres de données socio-économiques. Ainsi, les outils étant concurrents, il est normal qu'ils se soient tous deux spécialisés dans différents domaines en espérant attirer une part de marché correspondant aux services proposés. 

## Partie 2 - Des controverses autour des usages de ces bases de données 

### Un enjeu juridique : la protection de la vie privée

Comme expliqué précédemment, les données relatives aux vols de jets privés sont disponibles grâce aux systèmes ADS-B et publiées sur des sites internet en libre accès. Les avions ont l’obligation d’être équipés d’un système de traçage dont les informations doivent être rendues publiques pour garantir la sécurité du trafic aérien. La publicité de ces données et leur utilisation dans le cadre de traçage de jets privés soulèvent principalement des questions liées à la protection des données personnelles et au droit à la vie privée.

L’utilisation des données à caractère personnel est encadrée au niveau européen par le RGPD. Selon l’article 4 du RGPD, est considérée comme donnée personnelle *'toute information se rapportant à une personne physique identifiée ou identifiable'*. Le point de tension est que seules les personnes physiques sont concernées. Or, les jets privés tracés sont pour la plupart enregistrés au nom d’une entreprise, soit une personne morale. De plus, les données collectées par les systèmes de traçage n’indiquent en aucun cas la ou les personnes se trouvant dans l’avion. Si la donnée n’est pas directement ou indirectement rattachable à une personne physique désignée, elle ne peut donc pas être traitée au prisme du RGPD. Dans le cas contraire, l’acteur à l’origine du traitement ou de la publication de la donnée pourrait être amené à devoir fournir une base légale comme justification de son acte. Le cadre légal du traitement de données personnelles, établi par l’article 6, inclut notamment que celui-ci est possible lorsqu’il est *'nécessaire aux fins des intérêts légitimes poursuivis par le responsable du traitement ou par un tiers, à moins que ne prévalent les intérêts ou les libertés et droits fondamentaux de la personne concernée qui exigent une protection des données à caractère personnel'*. Il semble donc qu’il puisse y avoir une appréciation de l’importance du droit fondamental face à l’importance des intérêts légitimes poursuivis par le traiteur de la donnée. Une hiérarchisation et une prévalence d’un droit sur un autre serait donc possible au cas par cas. 

Un autre enjeu est celui du droit à la vie privée, comme garanti au niveau national par l’article 9 du Code civil, et au niveau européen par la Charte des droits fondamentaux de l’Union européenne. Cependant, ce droit n’est pas absolu, et peut être mis en balance en considérant le droit à la libre information et, au niveau français, la Charte de l’environnement, dont l’article 3 stipule que *'Toute personne doit, dans les conditions définies par la loi, prévenir les atteintes qu'elle est susceptible de porter à l'environnement ou, à défaut, en limiter les conséquences'*. Le contenu de cette Charte a par ailleurs une valeur constitutionnelle équivalente au droit à la vie privée, puisqu’ils font tous deux partie du bloc de constitutionnalité. Là encore, une mise en balance au cas par cas est donc nécessaire pour déterminer la prévalence de l’un sur l’autre.

Cependant, il semble nécessaire d'indiquer que ce traçage intervient dans un cadre international pour lequel il n’y a pas de restriction universelle. Cette pratique est critiquée par de nombreux pays comme la Russie, la Chine ou l’Arabie Saoudite, qui dénoncent de l’espionnage. Certaines personnalités issues de ces pays auraient d’ailleurs demandé la suppression des données concernant leurs vols, ce qu’a refusé le fondateur d’ADS-B Exchange Dan Streufert. Lors d’une interview accordée au *Nouvel Observateur*, celui-ci aurait justifié cette décision par le fait que *'Ce sont des informations publiques. Et je ne veux pas être l’arbitre qui décide qui a raison ou tort'*. 

### Une prise de conscience collective autour de l’impact environnemental des aéronefs

Bien que ces bases de données posent certaines questions quant au respect de la vie privée, elles sont également l’un des éléments déclencheurs d’une prise de conscience collective autour de l’impact environnemental et social de ces jets privés.
Les jets privés, longtemps considérés comme un symbole de richesse ou de succès, deviennent progressivement un réel problème écologique, à l’heure où les préoccupations environnementales ne cessent de prendre de l’ampleur. Comme le souligne Jo Dardenne, directrice de l’aviation chez Transport & Environment, *'Voyager avec des jets privés émet jusqu’à dix fois plus de dioxyde de carbone que de voler avec des vols de ligne et 150 fois plus que d’utiliser un train à grande vitesse.'*. Comme on l’observe sur le graphique ci-dessous, le jet privé est, de très loin, le mode de transport le plus polluant et émetteur de CO2 quand on rapporte le volume d’émission au passager. En effet, ces avions ne transportent en général que très peu de personnes, et ce sur des trajets courts, rendant ainsi leur usage aberrant sur le plan climatique. Par exemple, le trajet Paris-Genève en jet privé, rejette chaque année 6923 tonnes de CO2 pour une distance de moins de 500 kilomètres, ce qui correspond au bilan carbone annuel d’environ 636 français (en 2018). Le même parcours en train ne dure que 2h22 et émet 50 fois moins. C’est de loin le trajet le plus polluant en Europe.*

(* . Rappel : l’empreinte carbone annuelle moyenne d’un Français est de 11,5 tonnes de CO2. L’objectif fixé pour limiter le changement climatique est de 2 tonnes par personne et par an.)

![Comparaison des émissions de CO2 de différents moyens de transport](https://static.wixstatic.com/media/d2a522_3d2d241d34ab4c71bda0664b4c20e073~mv2.png/v1/fill/w_829,h_606,al_c,lg_1,q_90,enc_auto/Capture%20d%E2%80%99%C3%A9cran%202022-11-17%20%C3%A0%2010_34_30.png) 

Source : MonImpactTransport.fr, calculs franceinfo 

Or le nombre de vols privés n’a cessé d’augmenter depuis le début des années 2000. L’ONG Transport & Environment estime qu’entre 2005 et 2019, c’est une hausse de 30% des émissions de CO2 qu’on observe. De plus, comme le montre le graphique ci-dessous, le nombre de décollages et d’atterrissages d’avions d’affaires n’a jamais été aussi élevé qu’en 2022. Et contrairement à l’aviation de ligne, qui a fortement décru avec la crise du Covid-19, ces petits avions privés ont repris, dès août 2020, une activité normale, contre une reprise de seulement 30% pour les lignes commerciales.

![Nombre de décollages et atterrissages d’avions d’affaires en Europe](https://static.wixstatic.com/media/d2a522_0e65fc345c3f491f926032753d5c8e21~mv2.png/v1/fill/w_674,h_568,al_c,q_90,enc_auto/d2a522_0e65fc345c3f491f926032753d5c8e21~mv2.png)

Source : ADS-B Exchange, calculs franceinfo.fr 

Grâce aux nombreuses données disponibles sur les sites de tracking, les ONG sont parvenues à épingler les pays les plus impliqués dans ces vols de jets privés. En Europe, c’est la France et le Royaume Uni qui comptent à deux pour plus de 35% des émissions de CO2. Au-delà des informations sur les pays de départ ou d’arrivée des avions d'affaires, les bases de données ont également permis d’identifier les principaux usagers de ces jets. Sans surprise, de nombreuses entreprises apparaissent comme étant des utilisateurs assidus d’avions d'affaires. Comme on peut l’observer sur le graphique ci-dessous, c’est le groupe TotalEnergies qui est largement en tête du classement des avions d’entreprises françaises émettant le plus de CO2, avec une émission de plus de 2330 tonnes depuis le 1er janvier 2022. Suivent les groupes Pinault avec 1442 tonnes, Bolloré (1243 tonnes) et Bouygues (1227 tonnes). De plus, le tracking a également permis de mettre en évidence la durée très courte d’utilisation des appareils de vol, comme on le voit ci-dessous. La durée moyenne est de 1h11 pour le groupe Bolloré et de 1h20 pour JCDecaux. D’après les calculs de France Info, le 17 mars, un jet privé appartenant au groupe JCDecaux a réalisé 4 vols en 1 journée, émettant environ 10,4 tonnes de CO2. L’un de ces vols a duré 16 minutes, entre Toulon et Nice.

![Emissions de CO2 des avions appartenant à des groupes français](https://static.wixstatic.com/media/d2a522_cbff937165f94b3f9dc2f086bdabe762~mv2.png/v1/fill/w_812,h_608,al_c,lg_1,q_90,enc_auto/d2a522_cbff937165f94b3f9dc2f086bdabe762~mv2.png)

![Durée moyenne des vols par avion](https://static.wixstatic.com/media/d2a522_0b76d3942f3749c9ad4d6730ae29adab~mv2.png/v1/fill/w_807,h_547,al_c,lg_1,q_90,enc_auto/d2a522_0b76d3942f3749c9ad4d6730ae29adab~mv2.png)

Source : ADS-B Exchange, calculs franceinfo.fr 

Enfin, les bases de données ont également permis de pointer certaines personnalités publiques. En moyenne, les utilisateurs de tels avions possèdent une fortune d’environ 1,3 milliards d’euros. Ainsi, de nombreux comptes sur les réseaux sociaux sont apparus dans l’optique de dénoncer les vols en jet privé de certaines de ces personnalités. C’est Jack Sweeney, un Américain passionné d’aéronautique qui, en juin 2020, lance le compte @ElonJet sur Twitter, pour suivre les trajets d’Elon Musk, propriétaire de Tesla. Progressivement de nombreux autres comptes sont lancés, tels que @GatesJets (qui suit les trajets de Bill Gates), @BezosJets (pour Jeff Bezos) ou encore @ZuccJet (pour le patron de Facebool Mark Zuckerberg). Grâce aux données récoltées sur ces comptes, les émissions de ces personnalités américaines ont pu être mises en lumière (voir ci-dessous).

![Emissions de CO2 des avions appartenant à des personnalités américaines](https://static.wixstatic.com/media/d2a522_be184dea53794930a22234602f8ec9ac~mv2.png/v1/fill/w_681,h_696,al_c,q_90,enc_auto/d2a522_be184dea53794930a22234602f8ec9ac~mv2.png)

Source : ADS-B Exchange, calculs franceinfo.fr 

Le même concept arrive rapidement en France. Les comptes @LaviondeBernard et @IFlyBernard recensent tous deux les trajets du jet privé de Bernard Arnault, propriétaire de LVMH. Dans un des récapitulatifs posté sur Instagram, @laviondebernard dénonce : 25 vols, 42 tonnes de kérosène et 133 tonnes de CO2 émis, soit l’équivalent de 13 ans d’empreinte carbone d’un Français moyen.
 
Nous avons donc voulu aller à la rencontre de ce mouvement du flight tracking, et d’une des personnes se cachant derrière ces comptes Instagram et Twitter. Après avoir contacté plusieurs comptes, nous n’avons malheureusement pas reçu de réponse de leur part. Ce manque de réponse peut s’expliquer par la sensibilité du sujet que nous traitons. Jack Sweeney s’est notamment retrouvé menacé par Elon Musk qui souhaitait la suspension de son compte @ElonJet. Comme on l’a dit précédemment, de nombreuses questions juridiques se posent, sur la protection de la vie privée des personnalités trackées par ces comptes. Ce phénomène a une ampleur politique, ce qui peut mettre en danger les dénonciateurs. En fonction de l’importance de la personnalité, et de son pouvoir, il est compréhensible que les individus derrière les comptes de traçage ne souhaitent pas prendre de tels risques en révélant leur identité. 

À travers des interviews données au média *Brut* et au journal *Le Monde*, certaines de nos questions ont obtenu des réponses. Comme l’explique @laviondebernard, *'notre intention est de montrer qu’un large panel de personnes continue d’utiliser leurs jets privés en pleine urgence climatique'*.  *'Les principaux responsables du réchauffement climatique sont aussi ceux qui en souffrent et souffriront le moins'*. Pour lui, créer ce compte n'avait d'autre but qu’alerter sur l’urgence ; *'Comment expliquer à un travailleur que le kérosène des jets privés est moins taxé que son essence ? Ce type d’incohérence crée de l’apathie politique'*. L’initiateur du mouvement, Jack Sweeney n’avait à la base pas de motivation écologique, mais la création de ce concept a quand même permis certaines réactions de la part des célébrités traquées. En effet, il affirme au média Vulture, avoir vu un changement de comportement chez certaines personnalités publiques. C’est notamment le cas de Kim Kardashian et Kylie Jenner. Leur avion au départ de Camarillo faisait auparavant une pause à Van Nuys avant de continuer vers la destination finale, mais c’est récemment moins le cas, celui-ci se dirigeant directement vers la destination finale.
 
En mettant en lumière les émissions de ces vols privés, les bases de données ont ainsi entraîné et accéléré l’action militante. Par exemple, en décembre 2020, la section suisse du mouvement Extinction Rébellion a bloqué le terminal destiné aux aéronefs privés de l’aéroport de Genève pour dénoncer l’aberration climatique de ces modes de transport. Une action similaire a été menée dans l’aéroport d’Amsterdam le 5 novembre 2022. Une centaine de militants vêtus de combinaisons blanches, dont certains à vélo, ont empêché le décollage de jets privés. Dewi Zloch, responsable de Greenpeace Pays-Bas a expliqué les revendications : *'nous voulons moins de vols, plus de trains et une interdiction de vol pour les court-courriers et les jets privés non nécessaires'*.

L’action militante a également touché les personnes directement concernées. En effet, au premier tour des présidentielles en France, l’ex Premier Ministre Jean Castex a pris l’avion pour se rendre dans son bureau de vote dans les Pyrénées Orientales. Suite à cela, une pétition, lancée par un collectif de citoyens, a récolté en moins de 10 jours plus de 37 000 signatures, demandant à Jean Castex de faire une procuration pour le second tour.
Les manifestations et autres mouvements militants ont également appelé à la législation. La responsable de Transport & Environment appelait *'Les législateurs européens à taxer les jets privés qui fonctionnent aux énergies fossiles et interdire leur fonctionnement dès 2030'*. La Convention Citoyenne pour le Climat a, elle, demandé à ce que le kérosène soit davantage taxé, pour que l’avion ne constitue plus un 'avantage comparatif' pour les plus riches.

En réaction, la question des jets privés a finalement été saisie par les pouvoirs politiques. En septembre 2022, des parlementaires de La France Insoumise et Europe Écologie Les Verts ont déposé au moins 3 propositions de loi à ce sujet. Leur texte, surnommé 'La loi PSG' en référence au scandale qui avait éclaté quelque temps plus tôt, vise à *'élargir à toute l'aviation privée les restrictions s'appliquant aux services réguliers de transport aérien public de passagers'*. Autrement dit, il s’agirait d’interdire les vols privés si le trajet est aussi assuré en train et a une durée inférieure à 2h30. Le texte comporte deux articles qui prévoient *'l'interdiction de la circulation des jets privés dans l'espace aérien français en dehors des vols d'évacuation sanitaires, des vols qui concernent la sécurité nationale ou encore des jets privés militaires'*, ainsi qu'un *'plan d'action pour la reconversion des salariés du secteur'*. Et en cas d’abus, les usagers de jets seraient punis d’un an d’emprisonnement et d’une amende de 150 000 euros.

## Partie 3 - confiance et journalisme de données 

Le flight tracking pose également la question de la relation de confiance que les chiffres peuvent faciliter. En effet, L’*État des lieux des outils de visualisation des trajectoires et du bruit des avions* souligne qu’en rendant leurs données publiques, les sociétés aéroportuaires permettent de créer *‘une relation de confiance avec les collectivités et populations riveraines’*. Ici, il s’agit de permettre aux individus impactés par l’intensité des allers-retours et des bruits des aéronefs de constater de potentiels efforts et  améliorations de la part des sociétés aéroportuaires. Dans le cas du flight tracking des jets privés, une personnalité qui partagerait au public sa volonté de réduire ses trajets, serait tenue de réaliser ces efforts au vu de l’accessibilité des données pour vérifier son engagement. Les chiffres permettent de créer un lien de confiance entre les individus. Les paroles ne suffisent plus, car la facilité de l’accès aux données permet au public de ne plus être dupe et de choisir de se fier à des résultats concrets et donc chiffrés. Le fonctionnement de la technologie de l’ADS-B est transparent et ouvert au public. Ainsi, il représente une base solide, dans laquelle les citoyens peuvent avoir confiance, et sur laquelle s’appuyer pour rendre compte des abus de certains puissants. 

Le phénomène du flight tracking permet cette meilleure relation de confiance grâce au journalisme de données. Cette pratique consiste à renouveler le journalisme en utilisant les données d’une nouvelle manière. La journaliste Anne-Sophie Novel explique dans *La Revue des Médias* qu’il s’agit de *‘donner une nouvelle vie aux chiffres’*, en étayant l’analyse d’un sujet grâce aux données chiffrées et en les partageant avec le public sous une forme visuelle. Un des objectifs du journalisme de données consiste à rendre compte des activités des puissants de manière claire et transparente. Ces puissants peuvent être des entreprises, des gouvernements ou, comme dans le cas du flight tracking, des personnalités publiques. Ainsi, les individus qui participent au mouvement du flight tracking à visée dénonciatrice, rendent compte des trajets des puissants dans leurs jets privés et font connaître au grand public de potentiels abus. Ils révèlent leur impact environnemental et l’absurdité de leurs comportements face à l’urgence climatique. L’objectif terminal est de pousser les puissants à se responsabiliser sur leur impact climatique. Tout ceci est possible grâce à la libération de l’accès aux données, au développement du système ADS-B et à la création de sites qui regroupent ces méthodes comme FlightRadar24 et RadarBox. La multiplication des sites de flight tracking et des comptes Instagram et Twitter qui dénoncent les abus permet de pointer du doigt le manque systémique de responsabilité environnementale chez les puissants. Le soutien qu’apportent les données chiffrées des trajets des jets privés donne de la crédibilité à ceux qui enquêtent, à ceux qui dénoncent et tisse un lien de confiance entre tous les acteurs. 

## Conclusion 

Cette enquête nous a permis de mieux comprendre ce qu'il se cache derrière la vie sociale des données relatives aux jets privés. En retraçant l'origine du phénomène du flight tracking, nous avons pu comprendre comment le traçage des aéronefs est réalisé, du développement du radar, à celui de la technologie de l'ADS-B. Nous avons constaté que la démocratisation de l'utilisation de l'ADS-B a permis une amélioration de la visualisation des trajets des avions, grâce à la mise en place de sites spécialisés comme FlightRadar24 ou RadarBox. Ces sites avait un potentiel restreint lorsqu'ils ne concernaientt que les passionnés d'aviation. Leur utilisation a évolué, et permet aujourd'hui de porter un message militant. Nous nous sommes aussi intéressé à l'enjeu juridique de la protection de la vie privée, un enjeu majeur qui concerne tous les utilisateurs du web 2.0. Nous en avons conlcus que l'ADS-B permet de rendre public les données portant sur les trajectoires des vols mais que la représentation visuelle de celles-ci n'est pas forcément la plus neutre. Un réel enjeu politique se pose quand des personnalités se retrouvent visées par ces sites de tracking. Nous avons en effet conlus que la principale utilisation du flight tracking aujourd'hui a pour objectif de dénoncer les abus des utilisateurs de jets privés. À travers des comptes Instagram, des threads Twitter ou même des enquêtes journalistiques, les citoyens s'emparent de ces données pour faire entendre leur voix et dénoncer le manque de responsabilité systémique chez les puissants. Ces enquêtes relèvent d'un nouveau journalisme, celui des données, qui se base sur les chiffres pour mieux informer son public et créer une relation de confiance entre les citoyens. 


## Bibliographie et Sitographie 

### Introduction 

ACNUSA, *État des lieux des outils de visualisation des trajectoires et du bruit des avions*, Février 2021. Accessible sur : https://www.acnusa.fr/sites/default/files/2021-09/1608_2102-17-synthese-systeme-visualisation.pdf 

Flight Tracking, *History of flight tracking*. Accessible sur : https://flight-tracking.org/ 

Plane Finder, *A Brief History of Flight Tracking*, 20 Janvier 2017. Accessible sur : https://planefinder.net/about/news/a-brief-history-of-flight-tracking/ 

FlightRadar24, *Histoire de l'apparition*. Accessible sur : https://flightradars24.fr/flightradar24/  

RadarBox, *About*. Accessible sur : https://www.radarbox.com/about  

Entre Voisins, *Vitrai*. Accessible sur : https://vitrail.entrevoisins.org/vitrail/ 

Aurélien Defer, *Le « flight tracking », nouvel outil des militants écologistes pour dénoncer l’impact du transport aérien*. Le Monde, 23 mai 2022 (en ligne). Accessible sur : https://www.lemonde.fr/pixels/article/2022/05/23/le-flight-tracking-nouvel-outil-des-militants-ecologistes-pour-denoncer-l-impact-du-transport-aerien_6127257_4408996.html 

### Partie 1 

Brandon Graver, Ph.D., Kevin Zhang, Dan Rutherford, Ph.D, *CO2 emissions from commercial aviation*, 2018, ICCT, september 2019. Accessible sur : https://theicct.org/wp-content/uploads/2021/06/ICCT_CO2-commercl-aviation-2018_20190918.pdf

Wikipedia, *Automatic dependent surveillance-broadcast*. Accessible sur : https://fr.wikipedia.org/wiki/Automatic_dependent_surveillance-broadcast

Wikipedia, *Système de contrôle automatisé du trafic aérien*. Accessible sur : https://fr.wikipedia.org/wiki/Syst%C3%A8me_de_contr%C3%B4le_automatis%C3%A9_du_trafic_a%C3%A9rien
 
Aero Hesbaye, *L' avenir du transpondeur ! - L' ADS-B*. Accessible sur : http://www.aero-hesbaye.be/dossiers/informations/ADS-B.html
 
BioAddict Magazine, *Calculez l'impact environnemental de votre trajet en avion*, 29 janvier 2010. Accessible sur : https://www.bioaddict.fr/article/calculez-l-impact-environnemental-de-votre-trajet-en-avion-a598p1.html
 
Samuel Sauvage, *« Un vol privé en avion émet environ cinq fois plus de CO₂ par passager qu’un vol commercial »*. Le Monde, 11 juin 2022 (en ligne). Accessible sur : https://www.lemonde.fr/idees/article/2022/06/11/un-vol-prive-en-avion-emet-environ-cinq-fois-plus-de-co-par-passager-qu-un-vol-commercial_6129855_3232.html 

Manon Romain, *Les trajets en jet privé les plus fréquents en France et les alternatives (beaucoup moins polluantes) en train ou en voiture*. Le Monde, 6 septembre 2022 (en ligne). Accessible sur : https://www.lemonde.fr/les-decodeurs/article/2022/09/06/jets-prives-visualisez-les-trajets-les-plus-frequents-ou-les-plus-courts-en-france_6140407_4355770.html
 
ADSB Exchange. Accessible sur : https://globe.adsbexchange.com/

### Partie 2 

HAAS, G. et al. 31 janvier 2022. *Peut-on librement publier les données sur les vols de jets privés ?*. Accessible sur : https://info.haas-avocats.com/droit-digital/peut-on-publier-donnees-sur-vols-jets-prives

CHAPITRE II - Principes, CNIL. (s.d.). Accessible sur : https://www.cnil.fr/fr/reglement-europeen-protection-donnees/chapitre2

LE BONNIEC, T. 17 octobre 2022 *« Le grand détournement » : Les données de vol et les jets privé*, CNIL. Accessible sur : https://linc.cnil.fr/fr/le-grand-detournement-les-donnees-de-vol-et-les-jets-prive

*Déni, menaces, marchandage… Les milliardaires irrités par le suivi en ligne de leurs trajets aériens.* L’Obs., 8 août 2022 (en ligne). Accessible sur : https://www.nouvelobs.com/societe/20220808.OBS61813/deni-menaces-marchandage-les-milliardaires-irrites-par-le-suivi-en-ligne-de-leurs-trajets-aeriens.html

MOREAU, Sylvain et JANIN, Lionel. *« L’empreinte carbone des Français reste stable »*, Commissariat général au développement durable, janvier 2020.

Brice Le Borgne et Thomas Baïetto, *Bill Gates, Taylor Swift, Bernard Arnault… L'été où les voyages en jet privé des ultra-riches sont devenus un scandale climatique*. France Info, 30 août 2022 (en ligne). Accessible sur : https://www.francetvinfo.fr/monde/environnement/crise-climatique/infographies-bill-gates-kylie-jenner-taylor-swift-bernard-arnault-totalenergies-l-ete-ou-les-voyages-en-jet-prive-des-ultra-riches-sont-devenus-un-scandale-climatique_5324140.html?fbclid=IwAR2A4YXNkONxk51wF_UJ9sRFRS0sFvpUafnc7wsxT2-P3StwC72e3Rrqfq8  

### Partie 3 

Jean-Philippe Cointet, *Le journalisme de données*, cours 'La Vie Sociale des Données', Sciences Po Paris, 9 novembre 2022. 

Anne-Sophie Novel, *Le journalisme de données, ou comment faire parler les chiffres*, La Revue des Médias, 10 octobre 2019 (en ligne). Accessible sur : https://larevuedesmedias.ina.fr/le-journalisme-de-donnees-ou-comment-faire-parler-les-chiffres

## Auteurs

* DE CARRÈRE, Albéric
* DÉRAND, Eva
* GALLET, Marion 
* MARTIN, Clémence
* REIGNEAUD, Jules
