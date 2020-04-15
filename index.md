# Home of Aternity on GitHub
serving from **test-gh-pages**

## Why are we here
*insert an ispiring message to GH Aternity community*

## Quick tour
*insert a shord description on repos and how to use and contribute*

## Navigation examples
[Navigate to EUE repositpories](eue_home.md)

[Navigate to APM repositpories](https://github.com/Aternity?q=APM)

{% for post in paginator.posts %}

	## [{ post.title }}]({{ site.baseurl }}{{ post.url }})
	*{{ post.date | date_to_string }}*

	{{ post.content | strip_html | truncatewords:50 }}

  {% endfor %}
