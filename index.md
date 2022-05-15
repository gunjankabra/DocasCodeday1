---
Name: Gunjan Kabra
layout: template.html
---

# DocasCodeday1
Doc as code training day 1 repo
# Feature one

This is the **feature** one. Click here fro more details about [feature](https://techwriterstribe.com/course/docs-as-code-jekyll/).

{ % for item in site.data.Sample % } 
- {{item.Name}}, {{item.Year}} 
{ % endfor % }

## Subfeature one

This is the _sub feature_ one. Below is the bullet list:
- A
- B
- C

# Feature two

This is the feature two. Below is the list
1. One
2. Two
3. Three
4. Four

# Feature three

This is the feature three.

# Feature four

Dislay your name from local variable {{page.Name}}

This is global variable {{site.author}}