---
title: "include_relative"
description: "Includes a file relative to the current file."
sub_category: Other
---
##### Input

{% raw %}
~~~liquid
<h1>My site</h1>
{% include_relative about.html %}
~~~
{% endraw %}

##### Output

~~~html
<h1>My Site</h1>
<h1>About</h1>
~~~
