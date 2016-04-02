---
layout: post
title:  "Let's Begin!"
date:   2016-04-02 15:48:10 +0800
tags: BlaBla, LaTeX
---
I've attempted to make a `github page` for a long time, but there are always something wrong with `jekyll`. At last, I found that the problem is `Windows`. When I changed my OS into `Ubuntu`, all problems have gone.

It's worth mentioning that, `MathJax` display engine is used to render the mathematical formulas. For example \\(x\\), \\(y\\), \\(\alpha\\), \\(a^2 + b^2 = c^2\\), and the Fourier transform equations are shown as follows.
\\[
    \begin{align}
        F(\omega) &= \int_{-\infty}^{\infty}f(t)e^{-i\omega t}\mathrm{d}t\text{,}\\\
        f(t) &= \frac{1}{2\pi}\int_{-\infty}^{\infty}F(\omega)e^{i\omega t}\mathrm{d}\omega\text{.}
    \end{align}
\\]

Of cause, `jekyll` includes syntax hilighting, the following code is an example of C language.
{% highlight c %}
#include<stdio.h>

int main(void)
{
    int i, sum = 0;
    for (i = 1; i <= 100; i++)
        sum += i;
    printf("%d", sum);
}
{% endhighlight %}

The following code is an example of Matlab Language. 
{% highlight matlab %}
x = 0:0.1:3;
y = sin(x);
plot(x, y, 'r');
{% endhighlight %}

Anyway, let's begin!


