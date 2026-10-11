---
layout: default
title: Hidden Berkeley
---

# Beyond the Classroom: Discover UC Berkeley

UC Berkeley is ranked as the #1 public university in the United States, but there is more to campus life than academics. From quiet places to study and relax to fun activities and helpful resources, students and visitors have plenty to discover around campus.

<!-- Edit the heading and introduction above. The supplied loop below displays each row of the CSV. -->
{% for resource in site.data.locations %}

### {{ resource.name | escape }}

**Category:** {{ resource.category | escape }}  
**Area:** {{ resource.area | escape }}  
**Access note:** {{ resource.access_note | escape }}  
<a href="{{ resource.source_url | escape }}">Official source</a>

{% endfor %}

---

The entries come from this project's CSV. Confirm current details using the official links.
