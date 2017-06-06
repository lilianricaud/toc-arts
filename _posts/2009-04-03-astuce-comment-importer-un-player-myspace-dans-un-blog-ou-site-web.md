---
ID: 731
post_title: 'Astuce: Comment importer un player Myspace dans un blog ou site web'
author: Lilian
post_date: 2009-04-03 08:11:58
post_excerpt: ""
layout: post
permalink: >
  http://toc-arts.org/blog/2009/04/03/astuce-comment-importer-un-player-myspace-dans-un-blog-ou-site-web/
published: true
---
Astuce pratique pour ceux qui ont leur musique sur MySpace et voudrait pouvoir l'exporter ailleurs sur leur site ou leur blog. Voici un petit tutoriel pour importer un player Myspace dans un blog ou n'importe quelle autre page qui accepte du html. Astuce fournie par notre [super référenceur et webdesigner Aymeric][1] , merci à lui. 
> *   *Allez sur la page Myspace de l’artiste et trouvez le player.*
> *   *Cliquez sur “ouvrir le player” en haut à droite et affichez la popup.*
> *   *Et là, **il y a une feinte**, il faut **utiliser firefox** et son magnifique outil en clic droit : Code source de la sélection.*
> *   *Cliquez sur une chanson du player Myspace affiché dans la popup.*
> *   *Posez votre souris **en haut de la popup la ou il n’y a ni logo ni info en flash.***
> *   *Faites clic droit > Code source de la sélection.*
> *   *Copiez tout le code affiché (**pas seulement celui sélectionné à l’ouverture de la fenêtre code source*) .
> *   *Passez à l’éditeur de votre blog (**ou votre éditeur html préféré*), passez en mode code (ou html) et insérez le code du player que vous avez copié.
> *   *Enregistrez la page.*
> 
> *Et là, devant vos yeux ébahis, tout fonctionne.* Et petit bonus, **si vous ne voulez pas que la musique démarre automatiquement** (*ce qui est particulièrement énervant, même avec Keren Ann*), changez la variable suivante dans le code : ap=1 en ap=0. PS : **sous wordpress**, évitez de repasser en mode d’édition “Visuel”, ça va va vous détruire le code. Voir l'article original [Comment importer un player Myspace dans un blog][2] publié initialement par Aymeric Jacquet sous [licence créative commons by-nc-sa][3] 
## Un exemple pratique: le player des Bijoux de Famille N'étant pas fan de Keren Ann, j'ai remplacé l'exemple d'Aymeric par les Bijoux de Famille. Le code du player ressemble à ça: 

<pre id="line1">&lt;<span class="start-tag">embed</span><span class="attribute-name"> type</span>=<span class="attribute-value">"application/x-shockwave-flash" </span><span class="attribute-name"> src</span>=<span class="attribute-value">"http://musicservices.myspace.com/Modules/ MusicServices/Services/Embed.ashx/ptype=3,ap=0, plid=45553,artid=6401378,profid=167890924,sindex=2.2, shuffle=true,sseed=78984,amix=false,pmix=false" </span><span class="attribute-name"> style</span>=<span class="attribute-value">"" </span><span class="attribute-name">id</span>=<span class="attribute-value">"shell" </span><span class="attribute-name">name</span>=<span class="attribute-value">"shell" </span><span class="attribute-name">bgcolor</span>=<span class="attribute-value">"#101010" </span><span class="attribute-name">quality</span>=<span class="attribute-value">"high"</span><span class="attribute-name"> allowscriptaccess</span>=<span class="attribute-value">"always" </span><span class="attribute-name"> wmode</span>=<span class="attribute-value">"transparent" </span><span class="attribute-name">flashvars</span>=<span class="attribute-value">"e=http%3A//music.myspace.com/ index.cfm%3Ffuseaction%3Dmusic.popupplayer% 26sindex%3D2.2%26shuffle%3Dtrue%26amix%3Dfalse%26 pmix%3Dfalse%26plid%3D45553%26artid% 3D6401378%26profid%3D167890924%26friendid% 3D167890924%26sseed%3D78984%26ptype%3D3%26stime %3D4.884920634920635%26ap%3D1" </span><span class="attribute-name">height</span>=<span class="attribute-value">"485" </span><span class="attribute-name">width</span>=<span class="attribute-value">"300"</span>&gt;</pre> pas très sexy, mais une fois collé dans une page ça donne ça: Le lecteur met un peu de temps à s'ouvrir sur ma machine, mais fonctionne bien (en espérant que MySpace ne trouve pas moyen de bloquer ce genre de diffusion hors de leur chasse gardée... ). 

## <span style="text-decoration: underline;">Mise à jour</span>: Une autre astuce pour récupérer le code et exporter le player MySpace Allez faire un tour sur le 

**générateur de code MySharingSpace pour [exporter un lecteur MySpace en 2 coups de clics][4]**. On pouvait pas faire plus simple. Merci à [Raildecom][5] ! 
## Une parenthèse pour finir J'avais déjà discuté de 

[comment j'avais piraté mon frère et volé les bijoux de famille][6]. Cette astuce montre aussi un autre moyen de "pirater" la musique d'un artiste pour la rediffuser (même si dans ce cas la, l'artiste reste maître des chansons qui sont diffusées dans son player).  **Musiciens, ne barricadez pas votre musique**, ça n'empêchera jamais une personne motivée de récupérer votre musique, par contre cela empêchera vos fans de la découvrir et de vous faire de la promo. Facilitez plutôt l'accès pour favoriser la [diffusion prescriptive. ][7] Par exemple, [utilisez un widget multimedia comme Sprout][8] et qui permet une [diffusion virale par les fans][9] ...

 [1]: http://www.ajcrea.com/ "agence web réferencement webdesign formation entreprises"
 [2]: http://ajblog.fr/aide-memoire/521-comment-importer-un-player-myspace-dans-un-blog.html "comment importer un player myspace dans un blog"
 [3]: http://creativecommons.org/licenses/by-nc-sa/3.0/deed.fr "by-nc-sa"
 [4]: http://myspace.raildecom.fr/ "exporter un lecteur myspace"
 [5]: http://myspace.raildecom.fr/ "rail de com"
 [6]: http://toc-arts.org/blog/2008/06/04/pourquoi-jai-pirate-mon-frere-et-vole-les-bijoux-de-famille/ "telecharger mp3 myspace"
 [7]: http://toc-arts.org/blog/tag/diffusion-prescriptive/ "diffusion prescriptive musique"
 [8]: http://toc-arts.org/blog/2008/06/06/creer-un-widget-avec-sprout-le-widget-des-bijoux-de-famille/ "creer un widget sprout"
 [9]: http://toc-arts.org/blog/tag/marketing-viral/ "marketing viral"