---
layout: default
title: Hidden Berkeley
---

# Discover Berkeley: Beyond the Campus

Berkeley is a vibrant city known for its university, diverse culture, and unique neighborhoods. Beyond the famous campus, visitors can discover hidden gardens, local restaurants, and scenic spots that make Berkeley special.

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
