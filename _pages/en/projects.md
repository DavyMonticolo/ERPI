---
title: "Projects ERPI"
permalink: /projects/
layout: single
class: wide
#layout: collection
collection: projects
entries_layout: grid


excerpt: "Some of the research projects at ERPI"
header:
  overlay_image: /assets/images/publications/articles.jpg
  image_description: "Equipe de Recherche sur les Processus Innovatifs"

sidebar:
  nav: "projects"

gallery:
  - image_path: /assets/images/projects/teasers/1.jpg
    alt: "ERPI Innovation metrology"
    url: /projects/#innovation-metrology
  - image_path: /assets/images/projects/teasers/2.jpg
    alt: "ERPI Prospective"        
    url: /projects/#prospective--weak-signals      
  - image_path: /assets/images/projects/teasers/3.jpg
    alt: "ERPI Design"        
    url: /projects/#design-support-in-front-end      
  - image_path: /assets/images/projects/teasers/4.jpg
    alt: "ERPI Acceptability"        
    url: /projects/#acceptability     

last_modified_at: 2019-10-16
---

{% include gallery  layout="four" %}


## Innovation metrology

<div class="entries-{{ page.entries_layout }}">
{% include documents-collection.html
    collection=page.collection
    type=page.entries_layout    
    Research-field = "Metrology"
%}
</div>
<div style="width: 100%; clear: both; "></div>

## Prospective & Weak signals


<div class="entries-{{ page.entries_layout }}">
{% include documents-collection.html
    collection=page.collection
    type=page.entries_layout    
    Research-field = "Prospective"
%}
</div>
<div style="width: 100%; clear: both; "></div>

## Design support in front end


<div class="entries-{{ page.entries_layout }}">
{% include documents-collection.html
    collection=page.collection
    type=page.entries_layout    
    Research-field = "Design"
%}
</div>
<div style="width: 100%; clear: both; "></div>

## Acceptability


<div class="entries-{{ page.entries_layout }}">
{% include documents-collection.html
    collection=page.collection
    type=page.entries_layout
    Research-field = "Acceptability"
%}
</div>
