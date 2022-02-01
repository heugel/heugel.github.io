---
remote_theme             : "mmistakes/minimal-mistakes"
minimal_mistakes_skin    : "default" # "air", "aqua", "contrast", "dark", "dirt", "neon", "mint", "plum", "sunrise"

title:  "Kite Area Optimization"
date:   2022-02-01
categories: calc1 calc2 optimization
---
Let's say we have 4 metal rods, 2 of length <i>a</i> and 2 of length <i>b</i>.  We want to arrange these metal rods into a kite.  How long should the diagonals of the kite be to produce the largest possible area?  What is that resulting area?

Fist, let's draw the situation:
![image-center]({{ site.url }}{{ site.baseurl }}/assets/kitelabel.png){: .align-center}

Figure <b>A</b> shows the entire kite, and figure <b>B</b> shows half of the kite, which, in my opinion, makes it easier to see how to find essential parts to this problem.  Note that the longer diagonal, <i>y</i> is split up into two parts: <i>y-top</i> and <i>y-bottom</i>.

The area of a triangle is half the product of the base and height, so the area of the triangle in figure <b>B</b> is 1/2 <span>&#183;</span> y <span>&#183;</span> x/2.  Since that triangle is half of the entire kite, multiplying this area by 2 gives us an equation for the area of the kite:
![image-center]({{ site.url }}{{ site.baseurl }}/assets/kitework8.jpg){: .align-center}

Using the Pythagorean theorem, we can find <i>y-top</i> and <i>y-bottom</i> in terms of <i>x</i>:
![image-center]({{ site.url }}{{ site.baseurl }}/assets/kitework7.jpg){: .align-center}

We can then plug these into our area equation from earlier:
![image-center]({{ site.url }}{{ site.baseurl }}/assets/kitework6.jpg){: .align-center}

Now we have an equation to find the kite's area only using x, which we can call A(x).  To find the maximum value of A(x), we need to take the derivative, which in this case requires both the [product](https://tutorial.math.lamar.edu/classes/calci/productquotientrule.aspx) and the [chain](https://tutorial.math.lamar.edu/classes/calci/chainrule.aspx) rules:
![image-center]({{ site.url }}{{ site.baseurl }}/assets/kitework5.jpg){: .align-center}

Our goal now is to set this new equation equal to 0 and then solve for <i>x</i>.  The first thing I did was factor a -1 out of the second part of the equation, and I also noticed that you can multiply both sides of the equation by 2 to cancel out the halves:
![image-center]({{ site.url }}{{ site.baseurl }}/assets/kitework4.jpg){: .align-center}

From there it takes a bit of adding, subtracting, multiplying, and dividing to solve, but at least a few things cancel out along the way:
![image-center]({{ site.url }}{{ site.baseurl }}/assets/kitework9.jpg){: .align-center}
![image-center]({{ site.url }}{{ site.baseurl }}/assets/kitework10.jpg){: .align-center}

There we go!  We solved for <i>x</i>.  We can use this equation to also solve for <i>y</i> and the maximum possible area:
![image-center]({{ site.url }}{{ site.baseurl }}/assets/kitework3.jpg){: .align-center}
![image-center]({{ site.url }}{{ site.baseurl }}/assets/kitework1.jpg){: .align-center}

I also like to check my answers on [Desmos](https://www.desmos.com/), and these equations check out for multiple values of <i>a</i> and <i>b</i>:
![image-center]({{ site.url }}{{ site.baseurl }}/assets/desmos1.png){: .align-center}
![image-center]({{ site.url }}{{ site.baseurl }}/assets/desmos2.png){: .align-center}

I hope this wasn't too difficult to follow, this being my first post and all.  This problem seemed like a good place to start since I had a hard time finding any other decent solutions online.  I may revisit this post if I end up improving at this.