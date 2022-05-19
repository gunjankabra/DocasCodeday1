---
title: Documentation
Name: Gunjan Kabra
layout: template.html
---

# DocasCodeday1
Doc as code training day 1 repo

# Feature one

This is the **feature** one. Click here for more details about [feature](https://techwriterstribe.com/course/docs-as-code-jekyll/).

{% for item in site.data.Sample %} 
- {{item.Name}}, {{item.Year}} 
{% endfor %}

## Subfeature one

This is the _sub feature_ one. Below is the bullet list:
- A
  * AA
  * AB
  * AC
- B
- C

# Feature two

This is the feature two. Below is the list
1. One
 * A
 * B
3. Two
4. Three
5. Four

# Feature three

This is the feature three.

> This is an important note.

# Feature four

Dislay your name from local variable {{page.Name}}

This is global variable {{site.author}}

````
This is a piece of code.
````
To delete the file click ![](/DocasCodeday1/docs/assets/images/delete.png "Delete Icon")
