---
layout: page
title: S’impliquer
permalink: /s-impliquer
---

L’association 404 ne serait rien sans le travail de tous les élèves qui y participent : pour pouvoir poursuivre nos activités, nous avons besoin de personnes motivées !

## 📥 Propose-nous tes idées

Tu as des suggestions pour l’association et ses activités ? Tu peux les proposer dans notre boite à idées, disponible ici :
> 🔗 <a href="https://github.com/404gg/suggestions" target="_blank">Boîte à idées</a> (sur GitHub)

## 📅 Participe aux assemblées générales
Si tu es intéressé-e par l’association, tu peux venir aux assemblées générales : nous y discutons du futur de l’association, des projets en cours et tu peux venir nous apporter tes idées.

L’<abbr title="assemblée générale">AG</abbr> de 404 a lieu au minimum une fois par an, en principe vers la fin de l’année scolaire. Nous organisons aussi des assemblées extraordinaires en cas de besoin.

Avant chaque assemblée générale, nous informons les élèves de la date de la réunion, notamment via des affiches collées dans les bâtiments du CFPT.

### Procès-verbaux des dernières assemblées générales
{: #liste-pv }
<div class="list-group posts-list">
  {% for document in site.proces-verbaux %}
  <a class="list-group-item" href="{{ document.url | relative_url }}">
    {{ document.title | escape }}
  </a>
  {% endfor %}
</div>

## 👥 Deviens membre de l’association
Lors des assemblées générales, tu peux te proposer pour assumer un poste au sein de l’association. Tous les postes sont élus lors des <abbr title="assemblées générales">AG</abbr> pour un an.

### Comité
Pour garantir le bon fonctionnement de l’association, nous avons besoin de :
- un-e **président-e** qui gère les activités de l’association
- un-e **vice-président-e** qui aide le président dans ses tâches, et le replace s’il ne peut pas être présent
- un-e **trésorier-ère** qui gère les finances de l’association
- un-e **secrétaire** qui s’occupe des tâches administratives de l’assocaition, comme la rédaction des [procès-verbaux]({{ '/proces-verbaux/' | relative_url }})

Ces personnes forment le **comité** de 404 qui dirige l’association et s’assure du bon déroulement de ses activités.

### Autres postes
En plus des membres du comité, nous avons besoin de personnes pour assumer les tâches suivantes :
- un-e **responsable de la communication** qui se charge de faire connaître 404 auprès des élèves du CFPT
- deux **vérificateurs•rices des comptes** qui contrôlent les finances de l’association et les valident

## 🌐 Contribue à notre site web
{: #site-web }

Notre site, [404.gg]({{ '/' | relative_url }}), est hébergé sur [GitHub Pages](https://pages.github.com) : cela signifie que tu peux envoyer sur GitHub des propositions de modifications en crééant une *merge request*.

Chaque page de notre site contient un lien *Modifier cette page* qui te mène vers la source de la page que tu es en train de consulter. Tu peux d’ici là modifier le fichier et nous envoyer une *merge request* (proposition de modification). Si tu as besoin d’aide pour l’utilisation de GitHub, voici un tutoriel (en anglais) qui t’indiquera comment modifier un fichier et envoyer :
> 🔗 <a href="https://help.github.com/articles/editing-files-in-another-user-s-repository/" target="_blank">Editing files in another user's repository</a> — *GitHub Help*

Nous utilisons le générateur de sites statiques [Jekyll](https://jekyllrb.com) pour gérer notre site : si tu as besoin d’installer le projet en local sur ton ordinateur pour travailler dessus, ce tutoriel de GitHub (en anglais) t’expliquera comment le faire :
> 🔗 <a href="https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/" target="_blank">Setting up your GitHub Pages site locally with Jekyll</a> — *GitHub Help*

