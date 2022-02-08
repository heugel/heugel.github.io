---
remote_theme             : "mmistakes/minimal-mistakes"
minimal_mistakes_skin    : "default" # "air", "aqua", "contrast", "dark", "dirt", "neon", "mint", "plum", "sunrise"

title:  "Inverse Trig Triangle Method"
date:   2022-02-08
categories: calc2 trig
---
Here's something that becomes important for certain integrals in calc 2.  Let's simplify this expression fully, removing all trig:
![image-center]({{ site.url }}{{ site.baseurl }}/assets/trianglemethod/origprob.JPG){: .align-center}

The first thing we're going to want to do is come up with a middleman variable (usually theta) to make this easier to visualize.  Let's set theta equal to the inverse tangent of x, and then substitute back in:
![image-center]({{ site.url }}{{ site.baseurl }}/assets/trianglemethod/thetaequation1.JPG){: .align-center}
![image-center]({{ site.url }}{{ site.baseurl }}/assets/trianglemethod/pluggedintheta.JPG){: .align-center}

Now, let's solve for x:
![image-center]({{ site.url }}{{ site.baseurl }}/assets/trianglemethod/tantheta.JPG){: .align-center}

Here's where the triangle comes into play.  We know that the tangent of theta is x, so we're going to invent a triangle where that's true.  I always start my triangles like this:
![image-center]({{ site.url }}{{ site.baseurl }}/assets/trianglemethod/triangle1.jpg){: .align-center}

Time to remember SOH-CAH-TOA.  The tangent is the opposite leg divided by the adjacent leg.  We need those divided to equal x.  The simplest way to do that is this:
![image-center]({{ site.url }}{{ site.baseurl }}/assets/trianglemethod/triangle2.jpg){: .align-center}

We can find the third side using the Pythagorean theorem:
![image-center]({{ site.url }}{{ site.baseurl }}/assets/trianglemethod/triangle3.jpg){: .align-center}

Now that we have all the sides, we can use SOH-CAH-TOA again to find the sine of theta:
![image-center]({{ site.url }}{{ site.baseurl }}/assets/trianglemethod/answer.JPG){: .align-center}

This is possible with [any combination](https://en.wikipedia.org/wiki/Inverse_trigonometric_functions#Relationships_between_trigonometric_functions_and_inverse_trigonometric_functions) of trig and inverse trig functions.  Stay tuned--I will likely add more examples to this post soon :) particularly ones using secant, cosecant, and cotangent.
