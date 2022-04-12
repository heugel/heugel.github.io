---
remote_theme             : "mmistakes/minimal-mistakes"
minimal_mistakes_skin    : "default" # "air", "aqua", "contrast", "dark", "dirt", "neon", "mint", "plum", "sunrise"

title:  "Logger Problem"
date:   2022-04-12
categories: calc2 series sequence limit
---
Recently, I was helping a UMich student prepare for a test on series and sequences.  He brought along a practice exam for us to go through that included this question that I liked:

A certain lumber company starts with 50,000 trees.  Every year, they cut down 10% of their trees, then plant k more.

a) Find how many trees the lumber company has after 1 year and after 2 years.

b) Find the explicit formula for the sequence of the number of trees after every year.

c) What should k be if their goal is to have 70,000 trees after a long time?


Feel free to try it yourself first before checking my solution :)

## Solution

Part (a) is the easiest part here, since the question basically gives us the instructions for it.  We just have to multiply the previous number of trees by 0.9 (since we're cutting down 10% of the trees, there are 90% left), then add k:

![image-center]({{ site.url }}{{ site.baseurl }}/assets/logger/parta.JPG){: .align-center}

To help us see the pattern for part (b), let's extend our previous answer:

![image-center]({{ site.url }}{{ site.baseurl }}/assets/logger/b1.JPG){: .align-center}

If we look at this in 2 parts, the constant and the coefficient of k, we can see here what's happening to the constant: it's a geometric sequence, constantly being multiplied by 0.9.  But what's happening to the coefficient of k?  To make that easier to see, I'll separate some terms:

![image-center]({{ site.url }}{{ site.baseurl }}/assets/logger/b2.JPG){: .align-center}

Ah, so the coefficient of k isn't a geometric sequence.  Instead, it's the sequence of partial sums for a geometric series. [There's a formula](https://www.mathsisfun.com/algebra/sequences-sums-geometric.html) for partial sums of a geometric series, so let's use that here as part of the explicit formula:

![image-center]({{ site.url }}{{ site.baseurl }}/assets/logger/b3.JPG){: .align-center}

Now on to part (c).  We just need to set the limit of our answer to part (b) equal to 70000 and then solve for k.  Remember that if you take a number whose absolute value is less than one, then raise it to the power of infinity, you'll get zero.

![image-center]({{ site.url }}{{ site.baseurl }}/assets/logger/c1.JPG){: .align-center}

And that's it!  Personally, I like the style of this problem.  Sometimes sequence and series questions can get repetitive--they just give you problem after problem and you just write down "Converge" or "Diverge."  But this one at least changes up the pace.


