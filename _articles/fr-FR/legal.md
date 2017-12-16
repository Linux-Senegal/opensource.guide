---
locale: fr-FR
title: Le côté légal de l'open source
description: Tout ce que vous avez déjà demandé sur le côté juridique de l'open source, et quelques choses que vous n'avez pas faites.
class: légal
toc:
  pourquoi-les-gens-se-soucient-tellement-du-côté-légal-de-lopen-source: "Pourquoi les gens se soucient tellement du côté légal de l'open source?"
  les-projets-publics-github-sont-ils-open-source: "Les projets publics github sont-ils open source?"
  donnez-moi-juste-la-tl-dr-sur-ce-dont-jai-besoin-pour-protéger-mon-projet: "Donnez moi juste la tl dr sur ce dont j'ai besoin pour protéger mon projet"
  quelle-licence-open-source-est-appropriée-pour-mon-projet: "Quelle licence open source est appropriée pour mon projet?"
  que-faire-si-je-veux-changer-la-licence-de-mon-projet: "Que faire si je veux changer la licence de mon projet?"
  mon-projet-nécessite-t-il-un-accord-de-contribution-supplémentaire: "Mon projet nécessite t'il un accord de contribution supplémentaire?"
  que-doit-savoir-léquipe-juridique-de-mon-entreprise: "Que doit savoir l'équipe juridique de mon entreprise?"
order: 10
image: /assets/images/cards/legal.png
related:
  - contribute
  - leadership
---

## Comprendre les implications juridiques de l'open source

Partager votre travail créatif avec le monde peut être une expérience passionnante et enrichissante. Cela peut aussi signifier un tas de choses juridiques dont vous ne saviez pas que vous aviez à vous soucier. Heureusement, vous n'avez pas à partir de zéro. Nous avons couvert vos besoins juridiques. (Avant de creuser, assurez-vous de lire notre [disclaimer](../notices/).)

## Pourquoi les gens se soucient tellement du côté légal de l'open source?

Content que tu aies demandé! Lorsque vous effectuez un travail de création (tel que l'écriture, les graphiques ou le code), ce travail est sous copyright exclusif par défaut. Autrement dit, la loi suppose qu'en tant qu'auteur de votre travail, vous avez votre mot à dire sur ce que les autres peuvent en faire.

En général, cela signifie que personne d'autre ne peut utiliser, copier, distribuer ou modifier votre travail sans risquer des démontages, des ruptures ou des litiges.

L'open source est une circonstance inhabituelle, cependant, parce que l'auteur s'attend à ce que d'autres utilisent, modifient et partagent le travail. Mais parce que le défaut légal est toujours le droit d'auteur exclusif, vous avez besoin d'une licence qui énonce explicitement ces autorisations.

Si vous n'appliquez pas de licence open source, tous ceux qui contribuent à votre projet deviennent également détenteurs exclusifs des droits d'auteur de leur travail. Cela signifie que personne ne peut utiliser, copier, distribuer ou modifier ses contributions - et que «personne» ne vous inclut.

Enfin, votre projet peut avoir des dépendances avec des exigences de licence dont vous n'étiez pas au courant. La communauté de votre projet ou les politiques de votre employeur peuvent également exiger que votre projet utilise des licences Open Source spécifiques. Nous couvrirons ces situations ci-dessous.

## Les projets publics GitHub sont-ils open source?

Lorsque vous [créer un nouveau projet](https://help.github.com/articles/creating-a-new-repository/) sur GitHub, vous avez la possibilité que le dépôt soit  **privé** ou **publique**.

![créer un dépôt](/assets/images/legal/repo-create-name.png)

**Rendre public votre projet GitHub n'est pas la même chose que d'autoriser votre projet.** Les projets publics sont couverts par [Conditions d'utilisation de GitHub](https://help.github.com/articles/github-terms-of-service/#f-copyright-and-content-ownership), ce qui permet aux autres de voir et de bifurquer votre projet, mais votre travail ne comporte aucune autorisation.

Si vous souhaitez que d'autres personnes utilisent, copient, modifient ou contribuent à votre projet, vous devez inclure une licence open source. Par exemple, quelqu'un ne peut légalement utiliser aucune partie de votre projet GitHub dans son code, même s'il est public, à moins que vous ne lui donniez explicitement le droit de le faire.

## Donnez-moi juste la TL, DR sur ce dont j'ai besoin pour protéger mon projet

You're in luck, because today, open source licenses are standardized and easy to use. You can copy-paste an existing license directly into your project.

[MIT](https://choosealicense.com/licenses/mit/), [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/), and [GPLv3](https://choosealicense.com/licenses/gpl-3.0/) sont les licences Open Source les plus populaires, mais il existe d'autres options. Vous pouvez trouver le texte intégral de ces licences, et des instructions sur la façon de les utiliser, sur [choosealicense.com](https://choosealicense.com/).

Lorsque vous créez un nouveau projet sur GitHub, vous serez [demandé d'ajouter une licence](https://help.github.com/articles/open-source-licensing/).

<aside markdown="1" class="pquote">
  <img src="https://avatars2.githubusercontent.com/u/282759?v=3&s=400" class="pquote-avatar" alt="avatar">
 Une licence standardisée sert de proxy pour ceux qui n'ont pas de formation juridique pour savoir précisément ce qu'ils peuvent et ne peuvent pas faire avec le logiciel. Sauf en cas d'absolue nécessité, évitez les termes personnalisés, modifiés ou non standard, qui constitueront un obstacle à l'utilisation en aval du code de l'agence.
  <p markdown="1" class="pquote-credit">
— @benbalter, ["Tout ce qu'un avocat du gouvernement doit savoir sur les logiciels open source & nbsp;"](http://ben.balter.com/2014/10/08/open-source-licensing-for-government-attorneys/)
  </p>
</aside>

## Quelle licence open source est appropriée pour mon projet

si vous commencez à partir d'une ardoise vierge, il est difficile de se tromper avec le [MIT License](https://choosealicense.com/licenses/mit/).Il est court, très facile à comprendre et permet à quiconque de faire quoi que ce soit tant qu'il conserve une copie de la licence, y compris votre avis de droit d'auteur. Vous pourrez lancer le projet sous une licence différente si vous en avez besoin.

Sinon, choisir la bonne licence open source pour votre projet dépend de vos objectifs.

Votre projet a très probablement (ou aura) **dépendances**.Par exemple, si vous ouvrez un projet Node.js, vous utiliserez probablement des bibliothèques du Node Package Manager (npm). Chacune de ces bibliothèques dépendra de sa propre licence open source. Si chacune de leurs licences est "permissive" (donne au public l'autorisation d'utiliser, de modifier et de partager, sans condition pour les licences en aval), vous pouvez utiliser la licence que vous voulez. Les licences permissives courantes incluent MIT, Apache 2.0, ISC et BSD.

D'un autre côté, si l'une de vos licences de dépendances est "forte copyleft" (donne également les mêmes permissions publiques, sous condition d'utiliser la même licence en aval), alors votre projet devra utiliser la même licence. GPLv2, GPLv3 et AGPLv3 sont les principales licences communes de copyleft.

Vous pouvez également considérer les **communautés** qui vont utiliser et contribuer à votre projet:

* **Voulez-vous que votre projet soit utilisé comme une dépendance par d'autres projets?** Probablement préférable d'utiliser la licence la plus populaire dans votre communauté pertinente. Par exemple, [MIT](https://choosealicense.com/licenses/mit/) est la licence la plus populaire pour[npm libraries](https://libraries.io/npm).
* **Voulez-vous que votre projet attire les grandes entreprises?** Une grande entreprise voudra probablement une licence de brevet express de tous les contributeurs. Dans ce cas, [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/) Avez-vous (et eux) couvert.
* **Souhaitez-vous que votre projet fasse appel à des contributeurs qui ne souhaitent pas que leurs contributions soient utilisées dans des logiciels à source fermée?** [GPLv3](https://choosealicense.com/licenses/gpl-3.0/) ou (s'ils ne souhaitent pas non plus contribuer à des services à source fermée)[AGPLv3](https://choosealicense.com/licenses/agpl-3.0/) ira bien.

Votre **entreprise** peut avoir des exigences de licence spécifiques pour ses projets open source. Par exemple, il peut nécessiter une licence permissive afin que l'entreprise puisse utiliser votre projet dans le produit de source fermée de l'entreprise. Votre entreprise peut également exiger une licence copyleft forte et un accord de contribution supplémentaire (voir ci-dessous) afin que seule votre entreprise, et personne d'autre, puisse utiliser votre projet dans un logiciel à source fermée. Votre entreprise peut également avoir certains besoins liés aux normes, à la responsabilité sociale ou à la transparence, qui pourraient nécessiter une stratégie de licence particulière. Parler à ton[company's legal department](#what-does-my-companys-legal-team-need-to-know).

Lorsque vous créez un nouveau projet sur GitHub, vous avez la possibilité de sélectionner une licence. Y compris l'une des licences mentionnées ci-dessus rendra votre projet open source GitHub. Si vous souhaitez voir d'autres options, consultez[choosealicense.com](https://choosealicense.com)pour trouver la bonne licence pour votre projet, même si [n'est pas un logiciel](https://choosealicense.com/non-software/).

## Que faire si je veux changer la licence de mon projet?

La plupart des projets n'ont jamais besoin de changer de licence. Mais parfois les circonstances changent.

Par exemple, au fur et à mesure que votre projet prend de l'ampleur, il ajoute des dépendances ou des utilisateurs, ou votre entreprise change de stratégie, chacune d'entre elles pouvant exiger ou vouloir une licence différente. En outre, si vous avez négligé d'autoriser votre projet dès le départ, l'ajout d'une licence équivaut à changer de licence. Il y a trois choses fondamentales à prendre en compte lors de l'ajout ou de la modification de la licence de votre projet:

**C'est compliqué.** Déterminer la compatibilité et la conformité des licences et qui détient les droits d'auteur peut devenir compliqué et déroutant très rapidement. Passer à une nouvelle licence, mais compatible, pour les nouvelles versions et les contributions est différent de la redistribution de toutes les contributions existantes. Impliquez votre équipe juridique le premier indice de tout désir de changer de licence. Même si vous avez ou pouvez obtenir l'autorisation des titulaires de droits d'auteur de votre projet pour un changement de licence, tenez compte de l'impact de ce changement sur les autres utilisateurs et contributeurs de votre projet. Pensez à un changement de licence comme un «événement de gouvernance» pour votre projet qui se déroulera plus facilement avec des communications et des consultations claires avec les parties prenantes de votre projet. Raison de plus pour choisir et utiliser une licence appropriée pour votre projet dès sa création!

**Licence existante de votre projet.** Si la licence existante de votre projet est compatible avec la licence que vous souhaitez modifier, vous pouvez simplement commencer à utiliser la nouvelle licence. En effet, si la licence A est compatible avec la licence B, vous respecterez les termes de A tout en respectant les termes de B (mais pas nécessairement l'inverse). Donc, si vous utilisez actuellement une licence permissive (par exemple, MIT), vous pouvez changer pour une licence avec plus de conditions, tant que vous conservez une copie de la licence MIT et tous les avis de droit d'auteur associés (c.-à-d. Conditions minimales de la licence MIT). Mais si votre licence actuelle n'est pas permissive (par exemple, copyleft, ou si vous n'avez pas de licence) et que vous n'êtes pas le seul détenteur des droits d'auteur, vous ne pouvez pas simplement changer la licence de votre projet au MIT. Essentiellement, avec une licence permissive, les détenteurs de droits d'auteur du projet ont donné leur permission à l'avance pour changer de licence.

**Les détenteurs de droits d'auteur existants de votre projet.** If you're the sole contributor to your project then either you or your company is the project's sole copyright holder. You can add or change to whatever license you or your company wants to. Otherwise there may be other copyright holders that you need agreement from in order to change licenses. Who are they? People who have commits in your project is a good place to start. But in some cases copyright will be held by those people's employers. In some cases people will have only made minimal contributions, but there's no hard and fast rule that contributions under some number of lines of code are not subject to copyright. What to do? It depends. For a relatively small and young project, it may be feasible to get all existing contributors to agree to a license change in an issue or pull request. For large and long-lived projects, you may have to seek out many contributors and even their heirs. Mozilla took years (2001-2006) to relicense Firefox, Thunderbird, and related software.

Alternativement, vous pouvez demander aux contributeurs d'accepter à l'avance (via un accord de contribution supplémentaire - voir ci-dessous) certaines modifications de licence sous certaines conditions, au-delà de celles autorisées par votre licence open source existante. Cela déplace un peu la complexité de la modification des licences. Vous aurez besoin de plus d'aide de la part de vos avocats et vous voudrez toujours communiquer clairement avec les parties prenantes de votre projet lors de l'exécution d'un changement de licence.

## Mon projet nécessite-t-il un accord de contribution supplémentaire?

Probablement pas. Pour la grande majorité des projets open source, une licence open source sert implicitement à la fois de licence entrante (des contributeurs) et sortante (aux autres contributeurs et utilisateurs). Si votre projet est sur GitHub, les conditions d'utilisation de GitHub font "entrant = sortant" le [explicit default](https://help.github.com/articles/github-terms-of-service/#6-contributions-under-repository-license).

Un accord de contribution supplémentaire - souvent appelé Accord de licence de contributeur (CLA) - peut créer un travail administratif pour les responsables de projet. La quantité de travail ajoutée par un accord dépend du projet et de la mise en œuvre. Un accord simple peut exiger que les contributeurs confirment, en un clic, qu'ils ont les droits nécessaires pour contribuer sous la licence open source du projet. Un accord plus compliqué pourrait nécessiter un examen juridique et une approbation des employeurs des cotisants.

En outre, en ajoutant «paperasse» jugée inutile, difficile à comprendre ou injuste (lorsque le destinataire obtient plus de droits que les contributeurs ou le public via la licence open source du projet), un accord de contribution supplémentaire peut être perçu comme inamical. à la communauté du projet.

<aside markdown="1" class="pquote">
  <img src="https://avatars1.githubusercontent.com/u/328614?v=3&s=460" class="pquote-avatar" alt="avatar">
    Nous avons éliminé le CLA pour Node.js. Cela réduit la barrière à l'entrée pour les contributeurs Node.js, élargissant ainsi la base des contributeurs.
  <p markdown="1" class="pquote-credit">
— @bcantrill, ["Broadening Node.js Contributions"](https://www.joyent.com/blog/broadening-node-js-contributions)
  </p>
</aside>

Certaines situations où vous pourriez envisager un accord de contribution supplémentaire pour votre projet incluent:

* Vos avocats veulent que tous les contributeurs acceptent expressément les termes de contribution (_sign_, en ligne ou hors ligne), peut-être parce qu'ils estiment que la licence open source n'est pas suffisante (même si c'est le cas!). Si c'est la seule préoccupation, un accord de contribution qui affirme la licence open source du projet devrait être suffisant. le [jQuery Individual Contributor License Agreement](https://contribute.jquery.org/CLA/) est un bon exemple d'un accord de contribution supplémentaire léger. Pour certains projets, un [Developer Certificate of Origin](https://github.com/probot/dco) peut être une alternative.
* Votre projet utilise une licence Open Source qui n'inclut pas une concession de brevet express (MIT par exemple), et vous avez besoin d'une demande de brevet de tous les contributeurs, dont certains peuvent travailler pour des entreprises ayant de grands portefeuilles de brevets qui pourraient vous être utiles. les autres contributeurs et utilisateurs du projet. le [Apache Individual Contributor License Agreement](https://www.apache.org/licenses/icla.pdf) est un accord de contributeur supplémentaire communément utilisé qui a une licence de brevet reflétant celle trouvée dans la licence Apache 2.0.
* Votre projet est sous licence copyleft, mais vous devez également distribuer une version propriétaire du projet. Vous aurez besoin de chaque contributeur pour vous attribuer des droits d'auteur ou vous accorder (mais pas le public) un accord permissif license. Le [MongoDB Contributor Agreement](https://www.mongodb.com/legal/contributor-agreement) est un exemple de ce type d'accord.
* Vous pensez que votre projet pourrait devoir changer de licence au cours de sa vie et que les contributeurs soient d'accord à l'avance sur de tels changements.

ISi vous avez besoin d'utiliser un accord de contribution supplémentaire avec votre projet, envisagez d'utiliser une intégration telle que [CLA assistant](https://github.com/cla-assistant/cla-assistant) pour minimiser la distraction des contributeurs.

## Que doit savoir l'équipe juridique de mon entreprise?

Si vous publiez un projet open source en tant qu'employé de l'entreprise, votre équipe juridique doit d'abord savoir que vous êtes en train d'ouvrir un projet.

Pour le meilleur ou pour le pire, envisagez de les informer même s'il s'agit d'un projet personnel. Vous avez probablement avec votre entreprise un «accord IP d'employé» qui lui donne un certain contrôle sur vos projets, surtout s'ils sont liés à l'activité de l'entreprise ou si vous utilisez les ressources de l'entreprise pour développer le projet. Votre entreprise devrait vous donner facilement la permission, et peut-être déjà à travers un accord de propriété intellectuelle favorable aux employés ou une politique d'entreprise. Sinon, vous pouvez négocier (par exemple, expliquer que votre projet répond aux objectifs d'apprentissage et de développement professionnel de l'entreprise pour vous), ou éviter de travailler sur votre projet jusqu'à ce que vous trouviez une meilleure entreprise.

**Si vous ouvrez un projet pour votre entreprise,** , alors faites-le savoir. Votre équipe juridique a probablement déjà des politiques pour ce que la licence open source (et peut-être un accord de contributeur supplémentaire) à utiliser en fonction des exigences de l'entreprise et l'expertise autour de s'assurer que votre projet est conforme aux licences de ses dépendances. Sinon, vous et ils ont de la chance! Votre équipe juridique devrait être impatiente de travailler avec vous pour comprendre ces choses. Quelques choses à penser:

* **Matériel de tiers:** Votre projet a-t-il des dépendances créées par d'autres ou inclut ou utilise le code d'autres personnes? Si ceux-ci sont open source, vous devrez vous conformer aux licences open source des matériaux. Cela commence par choisir une licence qui fonctionne avec les licences open source tierces (voir ci-dessus). Si votre projet modifie ou distribue des contenus open source tiers, votre équipe juridique voudra également savoir que vous remplissez d'autres conditions des licences Open Source tierces, telles que la conservation des avis de copyright. Si votre projet utilise le code d'autres personnes n'ayant pas de licence open source, vous devrez probablement demander aux mainteneurs tiers de [add an open source license](https://choosealicense.com/no-license/#for-users), et si vous ne pouvez pas en obtenir un, arrêtez d'utiliser leur code dans votre projet.

* **Secrets commerciaux:** Secrets commerciaux Examiner s'il y a quoi que ce soit dans le projet que l'entreprise ne souhaite pas mettre à la disposition du grand public. Si c'est le cas, vous pouvez ouvrir le reste de votre projet, après avoir extrait le contenu que vous voulez garder privé.

* **Brevets:** Votre entreprise demande-t-elle un brevet dont l'ouverture du projet constituerait [public disclosure](https://en.wikipedia.org/wiki/Public_disclosure)? Malheureusement, vous pourriez être invité à attendre (ou peut-être que l'entreprise reconsidérera la sagesse de l'application). Si vous attendez des contributions d'employés d'entreprises ayant de grands portefeuilles de brevets, votre équipe juridique voudra peut-être utiliser une licence avec un brevet exprès de contributeurs (comme Apache 2.0 ou GPLv3) ou un accord de contribution supplémentaire ( voir au dessus).

* **Marques:**Double vérifier que le nom de votre projet [n'entrent pas en conflit avec des marques de commerce existantes](../starting-a-project/#avoiding-name-conflicts).Si vous utilisez les marques de votre propre entreprise dans le projet, vérifiez qu'il ne provoque aucun conflit. [FOSSmarks](http://fossmarks.org/) est un guide pratique pour comprendre les marques dans le contexte de projets libres et open source.

* **secret:** Votre projet collecte-t-il des données sur les utilisateurs? "Phone home" aux serveurs de l'entreprise? Votre équipe juridique peut vous aider à respecter les politiques de l'entreprise et les réglementations externes.

Si vous publiez le premier projet open source de votre entreprise, ce qui précède est plus que suffisant pour passer à travers (mais ne vous inquiétez pas, la plupart des projets ne devraient pas susciter d'inquiétudes majeures).

À plus long terme, votre équipe juridique peut faire davantage pour aider l'entreprise à tirer le meilleur parti de son implication dans l'open source et à rester en sécurité:

* **Politiques de contribution des employés:** Envisagez d'élaborer une politique d'entreprise qui spécifie comment vos employés contribuent aux projets open source. Une politique claire réduira la confusion parmi vos employés et les aidera à contribuer à des projets open source dans le meilleur intérêt de l'entreprise, que ce soit dans le cadre de leur travail ou pendant leur temps libre. Un bon exemple est celui de Rackspace[Model IP and Open Source Contribution Policy](https://processmechanics.com/2015/07/22/a-model-ip-and-open-source-contribution-policy/).

<aside markdown="1" class="pquote">
  <img src="https://avatars3.githubusercontent.com/u/214698?v=3&s=400" class="pquote-avatar" alt="avatar">
 Laisser l'adresse IP associée à un correctif crée la base de connaissances et la réputation de l'employé. Cela montre que l'entreprise est investie dans le développement de cet employé et crée un sentiment d'autonomie et d'autonomie. Tous ces avantages mènent également à un meilleur moral et à une meilleure rétention des employés.
  <p markdown="1" class="pquote-credit">
— @vanl, ["A Model IP and Open Source Contribution Policy"](https://processmechanics.com/2015/07/22/a-model-ip-and-open-source-contribution-policy/)
  </p>
</aside>

* **What to release:** [(Presque tout)?](http://tom.preston-werner.com/2011/11/22/open-source-everything.html) Si votre équipe juridique comprend et est investie dans la stratégie open source de votre entreprise, elle sera plus à même d'aider plutôt que d'entraver vos efforts.
* **Conformité:** Même si votre entreprise ne diffuse aucun projet open source, elle utilise le logiciel open source des autres.. [Sensibilisation et processus](https://www.linux.com/blog/why-companies-use-open-source-need-compliance-program) peut prévenir les maux de tête, les retards de produit et les poursuites.

<aside markdown="1" class="pquote">
  Les organisations doivent disposer d'une stratégie de licence et de conformité qui corresponde à la fois aux catégories \ ["permissive" et "copyleft" \]. Cela commence par conserver un enregistrement des conditions de licence applicables aux logiciels Open Source que vous utilisez, y compris les sous-composants et les dépendances..
  <p markdown="1" class="pquote-credit">
— Heather Meeker, ["Logiciels Open Source: principes de base de la conformité et meilleures pratiques"](https://techcrunch.com/2012/12/14/open-source-software-compliance-basics-and-best-practices/)
  </p>
</aside>

* **Brevets:** Votre entreprise peut souhaiter rejoindre le [Open Invention Network](http://www.openinventionnetwork.com/), [alternative patent licensing](https://www.eff.org/document/hacking-patent-system-2016).
* **Gouvernance:** Surtout si et quand il est logique de déplacer un projet à un [entité juridique extérieure à l'entreprise](../leadership-and-governance/#do-i-need-a-legal-entity-to-support-my-project).
