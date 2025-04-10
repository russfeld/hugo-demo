+++
title = "Hugo Demo Website"
archetype = "home"
+++

This is a homepage!

I can use **MARKDOWN** to edit the page

```javascript {title="src/javascript.js" hl_lines="2"}
const string = "It does syntax highlighting!";
cosnt updated = "I can even highlight invididual lines":
```

It can also do _math_ (LaTeX)

{{< math align="left" >}}
$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$
{{< /math >}}

{{% notice warning "Callout Box" %}}

I can make a pretty obvious callout box!

{{% /notice %}}