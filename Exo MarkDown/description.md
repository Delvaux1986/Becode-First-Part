![Logo MarkDown](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/130px-Markdown-mark.svg.png)

# Le MarkDown

**Markdown** est un langage de balisage léger créé en 2004 par *John Gruber* avec l'aide d'*Aaron Swartz*. Son but est d'offrir une syntaxe facile à lire et à écrire. Un document balisé par Markdown peut être lu en l'état sans donner l’impression d'avoir été balisé ou formaté par des instructions particulières.

Un document balisé par Markdown peut être converti en **HTML**, en **PDF** ou en d'autres formats. Bien que la syntaxe Markdown ait été influencée par plusieurs filtres de conversion de texte existants vers HTML — dont ***Setext***, ***atx***, ***Textile***, ***reStructuredText***, ***Grutatext*** et ***EtText*** —, la source d’inspiration principale est le format du courrier électronique en mode texte.

> Source: [Wikipedia](https://fr.wikipedia.org/wiki/Markdown)

# Objectif du language

> Markdown est censé être aussi facile à lire et à écrire que possible.

Le langage Markdown a été pensé pour pouvoir être publié tel quel (sans conversion, "en texte brut") et compris facilement.

Il propose un nombre de balises très succinct :

* [Titre sur plusieurs niveau](markdown/titres.md)
* [Gras et Italic](markdown/grasItalic.md)
* [Bloc de citation](markdown/citation.md)
* [Listes](markdown/listes.md)
* [Liens](markdown/liens.md)
* [Images](markdown/images.md)
* [Bloc de code](markdown/code.md)
* [Séparation (ligne horizontale)](markdown/separation.md)
* [Divers](markdown/divers.md)

Ces éléments on une correspondance directe avec des balises HTML.

# Exemples d'utilisation

Voici quelques domaines et exemples où Markdown est particulièrement utilisé.

### Les **README** 

Ils contiennent des informations sur les autres fichiers du même répertoire. Ils sont très utilisés pour donner des indications pour présenter un projet informatique ou donner des indications de fonctionnement.

Le plus souvent en texte simple, certains sont maintenant rédigés en Markdown. Cet essor est justifié par le fait que ces fichiers sont utilisés comme présentation des dépôts Git de plusieurs grand nom d’hébergeur de projets (*Github, Bitbucket, ...*).

Ils sont destinés soit à être affichés en texte brut mais également affichés en HTML.

### Commentaires, messages et textes cours

Beaucoup d’éditeur **WYSIWYG** de *commentaires / articles / textes* proposent également d'écrire directement en Markdown :

> *Wordpress, Trello, Stack Exchange, Reddit, Slack, ...*

### Les CMS

Plusieurs CMS *(Content managment system)* s’appuient sur le Markdown pour définir le contenu du site se passant donc de base de donnée et proposant un site statique, chaque page est généré à partir de fichiers Markdown. Ces CMS sont de très bonne options à considérer lorsque l'on créer un site qui n'est pas amené à être très dynamique *(site vitrine ou petit blog par exemple)*.

> ***Jekyll*** qui peut être hébergé directement sur *Github* avec *Github Pages*, ***Grav***,..

# Limitations et conséquences

### Langage fermé et limité

Voici entre autre les limitation de la version originale de Markdown par John Gruber :

* Absence de spécification formelle
* Syntaxe ambiguë
* Pas de suite de tests
* Une unique implémentation officielle (en Perl)
* Syntaxe ne faisant pas l'unanimité
* Pas assez de possibilités

### Réponses

Plus de *80 implémentations du langage*, chacune disposant de ces particularités syntaxique pour combler les lacunes de la version d'origine.

On peut noter par exemples les ajouts syntaxiques suivants :

* Références croisés
* Notes en base de page
* Tableaux
* Glossaires
* Formules mathématiques en LaTeX
* ...

