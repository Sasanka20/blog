---
layout: page
title: git
tagline: názvosloví
description: programming section content page.
---

![git](images/programming_git.jpg)

Před tím, než se pustíme do technických záležitostí, bylo by dobré vymezit si
několik pojmů, které by se mohly plést.

### git

Představte si, že pracujete na nějakém projektu. Každý den ho vylepšujete a
děláte nějaké úpravy. Těch úprav ale děláte tolik, že už si ani nepamatujete, co
jste dělali včera, natožpak před měsícem, nebo před rokem. A&nbsp;protože o své práci
a změnách, které jste udělali, nemáte nikde žádný záznam, nemůžete se jednoduše
vrátit k původnímu řešení, které bylo lepší, než je to současné. A teď si
představte, že na tomto projektu nepracujete sami, ale spolu s vámi je na něm
dvacet dalších vývojářů, z nichž každý udělá nějakou změnu každý den.
Někdo k lepšímu, někdo k horšímu. Když se ale podíváte na nějaký kousek kódu,
nevíte, kdo ho napsal, protože o tom nemáte žádný záznam. A přesně k tomu slouží
[verzovací systémy](https://en.wikipedia.org/wiki/Comparison_of_version-control_software).
Pokud verzovací systém používáte, potom snadno dohledáte, kdo, kdy a co (po)dělal,
což vede k tomu, že se můžete lehce vrátit k předchozím verzím, aniž byste
dlouze zjišťovali, co a jak bylo.

A jedním z nejvíce rozřížených verzovacích systémů je [git](https://git-scm.com/).
Git se používá při vývoji mnoha známých projektů, jako je např.
[jádro Linuxu](https://cs.wikipedia.org/wiki/Linux_(j%C3%A1dro)), nebo
[Ruby on Rails](https://cs.wikipedia.org/wiki/Ruby_on_Rails). Ač je verzovacích
systémů spousta, osobně jsem nikdy neslyšel o někom, kdo by používal jiný.

### GitHub a GitLab

Jak bylo řečeno výše - pokud používáte git, máte záznam o historii změn vašeho
projektu. Pokud ale chcete posunout práci na projektu na další úroveň,
používáte jej spolu s některou webovou službou, jakými jsou např.
[GitHub](https://github.com/), nebo [GitLab](https://about.gitlab.com/).
Takové webové aplikace vám umožní nejen nahližet na historii změn kódu v pěkné,
lidsky čitelné podobě, ale zároveň slouží i jako záloha vašeho projektu. Kromě
toho poskytují i mnoho dalších užitečných funkcí, které oceníte především
při práci v týmu:

- notifikace o změnách,
- diskuze nad kódem,
- návrhy změn,
- zasílání vlastních řešení (pull-requesty),
- tvorba projektové dokumentace (wiki).

V GitHubu je poté možno navíc ještě projektové webové stránky, které se jmenují
[GitHub Pages](https://pages.github.com/).

<!--
### Vytvoření pracovní branche

Na začátku je nutné mít vytvořený projekt, nebo-li repozitář, který chceme
verzovat. Pokud repozitář vytvořený není, je snadné ho vytvořit v kterémkoliv
editoru. Návod, jak vytvořit nový repozitář na [GitHubu](https://github.com/)
je k nalezení [zde](https://help.github.com/en/articles/creating-a-new-repository).
-->
