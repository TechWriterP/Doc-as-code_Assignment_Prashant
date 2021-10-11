| [Home Page](./index.md) | [IBM Page](./web_pages/IBM_page.md) | [Page 2](./web_pages/Page2.html) |

## List of Passengers in Titanic

* **Name** - **Age**

{% for item in site.data.titanic %}
* {{item.Name}} - {{item.Age}}
{% endfor %}