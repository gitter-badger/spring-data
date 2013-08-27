---
layout: base_layout
---

{% capture billboard_description %}
Spring Data makes it easier to build Spring-powered applications that use new data access technologies such as non-relational databases, map-reduce frameworks, and cloud based data services as well as provide improved support for relational database technologies. Spring Data is an umbrella open source project which contains many subprojects that are specific to a given database. The projects are developed by working together with many of the companies and developers that are behind these exciting technologies.
{% endcapture %}

{% capture main_content %}

<!-- Spring Data JPA -->
{% capture project_description %}
Makes it easy to implement JPA-based repositories
{% endcapture %}

{% include project_block.md site_url="/spring-data-jpa" repo_url="http://github.com/spring-projects/spring-data-jpa" project_title="Spring Data JPA" project_description=project_description %}

<!-- Spring Data MongoDB -->
{% capture project_description %}
Provides integration with the MongoDB document database
{% endcapture %}

{% include project_block.md site_url="http://www.springframework.io" repo_url="http://github.com/spring_hadoop" project_title="Apache Hadoop" project_description=project_description %}

<!-- end main_content -->
{% endcapture %}

{% include project_aggregator_include.md billboard_description=billboard_description main_content=main_content %}
