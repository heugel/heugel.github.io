---
remote_theme             : "mmistakes/minimal-mistakes"
minimal_mistakes_skin    : "default" # "air", "aqua", "contrast", "dark", "dirt", "neon", "mint", "plum", "sunrise"

title:  "Take the Derivative Instead"
date:   2022-02-09
categories: calc2 integral IBP
---
[Integration by parts](https://www.mathsisfun.com/calculus/integration-by-parts.html) allows us to use a strategy I like to call "take the derivative instead" for certain integrals, such as these:

1)
![image-center]({{ site.url }}{{ site.baseurl }}/assets/derivinstead/int_ln.JPG){: .align-center}

2)
![image-center]({{ site.url }}{{ site.baseurl }}/assets/derivinstead/int_arctan.JPG){: .align-center}


Let's start with question #1.  Not many students have the integral of the natural log of x memorized.  The derivative, however, is required knowledge by the time integration by parts is taught.  So let's set up our integration by parts like this:
![image-center]({{ site.url }}{{ site.baseurl }}/assets/derivinstead/ln_parts1.JPG){: .align-center}

Now we need to take the derivative of our u to get our du and also take the antiderivative of our dv to get our v:
![image-center]({{ site.url }}{{ site.baseurl }}/assets/derivinstead/ln_parts2.JPG){: .align-center}

All that's left is to plug these values into the integration by parts formula:
![image-center]({{ site.url }}{{ site.baseurl }}/assets/derivinstead/ln_answer.JPG){: .align-center}

So, you see how in the process of finding the integral of the natural log of x, we never really had to attack the problem directly?  Instead, we found the derivative of the natural log of x to create an easier integral with integration by parts, hence "take the derivative instead."  Question #2 is a littler trickier--the first steps are the same, but a u-substitution is required after the integration by parts.  See if you can solve it yourself :)