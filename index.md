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
Spring based, object-document support and repositories for MongoDB.
{% endcapture %}

{% include project_block.md site_url="/spring-data-mongodb" repo_url="http://github.com/spring-projects/spring-data-mongodb" project_title="Spring Data MongoDB" project_description=project_description %}

<!-- Spring Data Redis -->
{% capture project_description %}
Provides easy configuration and access to Redis from Spring applications
{% endcapture %}

{% include project_block.md site_url="/spring-data-redis" repo_url="http://github.com/spring-projects/spring-data-redis" project_title="Spring Data Redis" project_description=project_description %}

<!--Spring Data GemFire -->
{% capture project_description %}
Provides easy configuration and access to GemFire from Spring applications
{% endcapture %}
{% include project_block.md site_url="/spring-data-gemfire" repo_url="http://github.com/spring-projects/spring-data-gemfire" project_title="Spring Data GemFire" project_description=project_description %}

<!--Spring Data JDBC Extensions -->
{% capture project_description %}
Provides extensions to the JDBC support provided in the Spring Framework
{% endcapture %}
{% include project_block.md site_url="/spring-data-jdbc-ext" repo_url="http://github.com/spring-projects/spring-data-jdbc-ext" project_title="Spring Data JDBC Extensions" project_description=project_description %}

<!-- end main_content -->
{% endcapture %}

{% include project_aggregator_include.md billboard_description=billboard_description main_content=main_content %}
