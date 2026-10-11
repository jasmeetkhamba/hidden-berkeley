---
layout: default
title: Hidden Berkeley
---

# Beyond the Classroom: Discover UC Berkeley

UC Berkeley offers more than just academics, with unique spaces, creative opportunities, and resources that support student life. From peaceful study spots to hands-on experiences and campus attractions, there is always something new to discover beyond the classroom.

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
