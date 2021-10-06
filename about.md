---
layout: page
title: About
permalink: /about/
published: true
---

<div class="page" markdown="1">

{% capture page_subtitle %}
<img
    class="me"
    alt="{{ author.name }}"
    src="{{ site.author.photo | relative_url }}"
    srcset="{{ site.author.photo2x | relative_url }} 2x"
/>
{% endcapture %}

{% include page/title.html title=page.title subtitle=page_subtitle %}

## O blogu

Tady budu hodnotit státní správu z pohledu koncového uživatele (aka běžného občana).

Příspěvky budu přidávat průběžně, jak se mi dostane nových zkušeností. Takže ze začátku můžete očekávat celkem časté posty, za svůj život už jsem si toho trochu se státem zažil, až svoje zkušenosti vyčerpám, tak to asi trochu ochladne.

Tento blog zároveň není hotový, jenom jsem chtěl rychle nějaké místo, kam psát. V mezičase budu dělat na pozadí promakanější verzi, která nebude jen stažený template.
To taky znamená, že pokud si tu všimnete nějakých nesrovnalostí, které zůstaly z templatu, tak prosím napište, buď [Twitter](https://twitter.com/bertik23), [mail](mailto:bertikxxiii@gmail.com) nebo [issue na githubu](https://github.com/Bertik23/statnispravablog/issues/new).



</div>
