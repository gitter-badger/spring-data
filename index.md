---
layout: base_layout
---

{% capture billboard_description %}
Spring Data makes it easier to build Spring-powered applications that use new data access
technologies such as non-relational databases, map-reduce frameworks, and cloud based data services
as well as provide improved support for relational database technologies.
Spring Data is an umbrella open source project which contains many subprojects that are specific
to a given database. The projects are developed by working together with many of the companies
and developers that are behind these exciting technologies.
{% endcapture %}

{% capture main_content %}
[Spring Data JPA](/spring-data-jpa) | [Spring Data MongoDB](/spring-data-mongodb) | ...
{% endcapture %}

{% include project_aggregator_include.md billboard_description=billboard_description main_content=main_content %}
