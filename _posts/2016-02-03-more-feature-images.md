---
layout: post
title: Feature images
feature-img: "img/parkbench.jpg"
---
This is an example of a post which includes a feature image specified in the front matter of the post. The feature image spans the full-width of the page, and is shown with the title on permalink pages.

{% highlight ruby %}
def foo
  puts 'foo'
end
{% endhighlight %}

Highlighting for code in Jekyll is done using Rouge.

{% highlight js %}
// count to ten
for (var i = 1; i <= 10; i++) {
    console.log(i);
}

// count to twenty
var j = 0;
while (j < 20) {
    j++;
    console.log(j);
}
{% endhighlight %}

Type Theme uses KaTeX to display maths. Equations such as $$S_n = a \times \frac{1-r^n}{1-r}$$ can be displayed inline.

Alternatively, they can be shown on a new line:

$$ f(x) = \int \frac{2x^2+4x+6}{x-2} $$

