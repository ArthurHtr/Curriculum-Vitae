# Construire l'équipe, pas seulement choisir le modèle

Une vision d'Arthur Hottier, créateur d'OpenCode Team Studio.

[Read the English version →](VISION.en.md)

---

Je pars d'une conviction simple : l'avenir de l'intelligence artificielle ne repose pas uniquement sur la création de modèles toujours plus puissants. Il repose aussi sur notre capacité à organiser ces modèles, à leur attribuer des rôles précis et à leur donner les bons outils pour travailler ensemble.

Un système d'IA agentique peut être envisagé comme une équipe.

Cette équipe peut disposer d'un responsable chargé de comprendre un objectif global, de le décomposer et de distribuer le travail. Elle peut comporter des spécialistes du développement, de la recherche, de l'architecture, de la sécurité, des tests ou de la documentation. Chacun de ces agents peut utiliser un modèle différent, recevoir ses propres instructions, disposer de permissions spécifiques et accéder uniquement aux outils nécessaires à sa mission.

Comme dans une équipe humaine, la performance collective ne dépend donc pas uniquement de l'intelligence individuelle de ses membres. Elle dépend aussi de la qualité de leur organisation.

Un excellent spécialiste, isolé ou mal dirigé, peut produire un résultat médiocre. À l'inverse, plusieurs agents correctement spécialisés, équipés et coordonnés peuvent traiter des problèmes qu'un seul modèle aurait beaucoup de mal à résoudre de manière fiable.

## La prochaine frontière de l'IA agentique

Une partie du progrès continuera naturellement à venir des modèles eux-mêmes. Les grandes entreprises comme OpenAI, Anthropic, Google ou Mistral AI, ainsi que la communauté open source, poursuivront le développement de modèles plus compétents, plus rapides et plus efficaces.

Mais une seconde frontière devient tout aussi importante : celle de l'orchestration.

- Quel agent doit recevoir une tâche donnée ?
- Quel modèle doit-il utiliser ?
- À quels outils doit-il avoir accès ?
- Quelles actions peut-il exécuter librement ?
- Quelles actions nécessitent une validation humaine ?
- Quels spécialistes peut-il solliciter ?
- Quelles instructions, connaissances et méthodes doit-il appliquer ?

Ces questions ne concernent plus seulement la qualité d'un modèle. Elles concernent l'architecture complète du système qui l'entoure.

Pour un particulier, cette organisation peut permettre d'accomplir un travail qui aurait autrefois nécessité plusieurs personnes. Pour une entreprise, elle peut servir à introduire des agents dans une infrastructure existante tout en respectant ses processus, ses règles de sécurité, ses méthodes de travail et ses contraintes métier.

L'enjeu n'est donc plus simplement d'utiliser une intelligence artificielle. Il devient nécessaire de savoir construire, comprendre, contrôler et faire évoluer une véritable équipe d'agents.

## L'open source possède les composants, mais pas encore l'atelier

L'écosystème open source dispose déjà de nombreuses briques essentielles.

Il existe des modèles ouverts, des outils de développement agentique, des serveurs MCP capables de connecter les agents à des services externes, ainsi que des bibliothèques de skills et d'instructions réutilisables. Des outils comme OpenCode permettent déjà de créer des agents spécialisés, de définir leurs permissions, de leur attribuer des modèles et de leur fournir des outils supplémentaires.

OpenCode constitue aujourd'hui une base particulièrement intéressante : il est ouvert, extensible et compatible avec de nombreux fournisseurs de modèles. Il propose des agents principaux et des sous-agents, tout en permettant aux utilisateurs de construire leurs propres configurations.

Mais à mesure que cette configuration grandit, sa compréhension devient difficile.

Les agents peuvent être définis dans plusieurs fichiers. Les skills possèdent leurs propres dossiers. Les serveurs MCP sont déclarés séparément. Les modèles, outils, permissions et instructions sont répartis dans différentes sections de configuration. Chaque élément reste individuellement compréhensible, mais la vision d'ensemble disparaît rapidement.

On peut savoir qu'un agent existe sans comprendre immédiatement son rôle dans l'équipe. On peut lui attribuer des outils sans voir clairement l'étendue réelle de ses capacités. On peut créer plusieurs sous-agents sans disposer d'une représentation simple de leur hiérarchie et des délégations possibles.

Le problème n'est donc pas l'absence de puissance.

Le problème est l'absence de visibilité.

## OpenCode Team Studio

C'est précisément à cet endroit qu'intervient OpenCode Team Studio.

OpenCode Team Studio est un espace de travail visuel permettant de concevoir, configurer et administrer une équipe d'agents OpenCode.

Au lieu de manipuler séparément des fichiers de configuration et de reconstruire mentalement leurs relations, l'utilisateur peut représenter son système sous la forme d'un graphe.

Les agents deviennent les membres visibles d'une équipe. Les relations de délégation montrent qui peut solliciter qui. Les connexions permettent d'identifier les skills, les outils, les serveurs MCP et les modèles associés à chaque agent. Les permissions indiquent clairement ce qu'un agent peut faire, ce qu'il doit demander et ce qui lui est interdit.

L'objectif n'est pas de remplacer OpenCode ni de créer un nouveau format propriétaire. OpenCode Team Studio travaille au-dessus de la configuration OpenCode existante. Il transforme cette configuration en une représentation compréhensible, modifiable et contrôlable, puis applique les changements aux fichiers utilisés par OpenCode.

La configuration reste locale, ouverte et maîtrisée par l'utilisateur.

OpenCode Team Studio ne cherche donc pas à devenir une nouvelle plateforme d'intelligence artificielle fermée. Il cherche à devenir l'atelier dans lequel chacun peut assembler sa propre équipe d'agents.

## D'une collection d'agents à une organisation cohérente

Créer plusieurs agents ne suffit pas à construire un système agentique efficace.

Il faut pouvoir répondre rapidement à des questions simples :

- Quel est le rôle exact de chaque agent ?
- Quel agent dirige l'exécution ?
- Quels spécialistes peuvent être sollicités ?
- Quelles compétences sont disponibles ?
- Quels outils externes sont connectés ?
- Quel modèle est utilisé pour chaque mission ?
- Quelles sont les limites et permissions de chaque agent ?
- Certaines ressources sont-elles inutilisées ou attribuées au mauvais endroit ?

OpenCode Team Studio rend ces relations visibles.

L'utilisateur ne voit plus seulement une succession de paramètres techniques. Il voit une organisation : ses membres, leurs responsabilités, leurs compétences, leurs outils et leurs relations.

Cette représentation peut aussi faciliter le partage. Une équipe d'agents bien conçue pourrait être documentée, versionnée, reproduite et adaptée à un autre projet. Des configurations spécialisées pourraient émerger pour le développement web, l'analyse de données, la cybersécurité, la recherche scientifique ou la gestion d'infrastructures.

Les bibliothèques existantes de skills et de serveurs MCP deviennent alors des catalogues de compétences et d'outils dans lesquels l'utilisateur peut construire son propre système.

## Rendre l'IA agentique compréhensible

L'IA agentique reste aujourd'hui difficile à appréhender parce que son fonctionnement est principalement décrit à travers des fichiers, des conventions et des paramètres techniques.

Pourtant, les concepts sous-jacents sont naturels : des rôles, des responsabilités, des compétences, des outils, des permissions et des délégations.

En rendant ces concepts visibles, OpenCode Team Studio veut réduire la distance entre l'idée d'une équipe d'agents et sa mise en œuvre concrète.

Je suis convaincu que cette compréhension constitue une première étape essentielle vers une IA agentique open source plus performante, plus accessible et mieux adaptée aux besoins réels de chacun.

Les modèles constituent l'intelligence des agents.

Les skills et les outils constituent leurs compétences.

Les protocoles leur permettent d'interagir avec le monde extérieur.

Mais c'est leur organisation qui en fait une équipe.

OpenCode Team Studio est conçu pour construire cette organisation.

## À propos de l'auteur

Je m'appelle Arthur Hottier. Je suis ingénieur et développeur, avec un intérêt particulier pour l'intelligence artificielle agentique, les modèles de langage et les outils open source.

Je ne m'intéresse pas seulement à ce qu'un modèle peut accomplir individuellement. Je cherche surtout à comprendre comment plusieurs agents peuvent être organisés, spécialisés et équipés pour former des systèmes réellement utiles.

J'ai créé OpenCode Team Studio après avoir constaté qu'OpenCode possédait déjà une grande partie des composants nécessaires à la construction d'une équipe d'agents, mais qu'il restait difficile de comprendre et de piloter visuellement cette organisation.

Ce projet est ma contribution à une vision plus ouverte, plus accessible et plus maîtrisable de l'IA agentique.

[Mon profil GitHub](https://github.com/ArthurHtr)

---

## OpenCode Team Studio

Les retours, les contributions et les discussions autour du projet sont les bienvenus.
