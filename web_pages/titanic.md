## List of Passengers in Titanic

* **Name** - **Age**

{% for item in site.data.titanic %}
* {{item.Name}} - {{item.Age}}
{% endfor %}