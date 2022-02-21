---
remote_theme             : "mmistakes/minimal-mistakes"
minimal_mistakes_skin    : "default" # "air", "aqua", "contrast", "dark", "dirt", "neon", "mint", "plum", "sunrise"

title:  "Inverse Tangent U-Sub"
date:   2022-02-03
categories: calc1 calc2 integral usub inversetrig log naturallog
---
I see a lot of students struggling to see when an integral is related to inverse trig.  Let's take a look at the inverse tangent in this post.  If an integral can be written like this:
![image-center]({{ site.url }}{{ site.baseurl }}/assets/inversetrigusub/arctanindic.JPG){: .align-center}
then that's a good indication, <b>but not a guarantee</b>, that you should do a u-sub where <b>u=f(x)</b>.

For example, this:
![image-center]({{ site.url }}{{ site.baseurl }}/assets/inversetrigusub/origproblem.JPG){: .align-center}
can be rewritten as this:
![image-center]({{ site.url }}{{ site.baseurl }}/assets/inversetrigusub/rewrite.JPG){: .align-center}

So, like I said above, this is a good sign we should try doing a u-sub where u equals the thing that's being squared.
![image-center]({{ site.url }}{{ site.baseurl }}/assets/inversetrigusub/usub.JPG){: .align-center}

![image-center]({{ site.url }}{{ site.baseurl }}/assets/inversetrigusub/insert.jpg){: .align-center}

![image-center]({{ site.url }}{{ site.baseurl }}/assets/inversetrigusub/insert2.JPG){: .align-center}

Now this is in the [perfect form](https://math.libretexts.org/Bookshelves/Calculus/Book%3A_Calculus_(OpenStax)/05%3A_Integration/5.7%3A_Integrals_Resulting_in_Inverse_Trigonometric_Functions) to take the integral and plug in the original value of u:
![image-center]({{ site.url }}{{ site.baseurl }}/assets/inversetrigusub/answer.JPG){: .align-center}

Keep in mind, though, that this isn't always how to solve integrals that can be rewritten like shown above.  Let's take a look at a very similar integral:
![image-center]({{ site.url }}{{ site.baseurl }}/assets/inversetrigusub/lnorig.JPG){: .align-center}

We could rewrite the denominator the same way we could in the previous example, since it's the exact same denominator and all.  However, that isn't the correct strategy to use here.  If the numerator is a constant multiple of the derivative of the denominator, our u-sub should be setting u equal to the entire denominator:
![image-center]({{ site.url }}{{ site.baseurl }}/assets/inversetrigusub/lnusub.JPG){: .align-center}

![image-center]({{ site.url }}{{ site.baseurl }}/assets/inversetrigusub/lninsert.jpg){: .align-center}

![image-center]({{ site.url }}{{ site.baseurl }}/assets/inversetrigusub/lninsert2.JPG){: .align-center}

From here, we can take the integral and plug back in:
![image-center]({{ site.url }}{{ site.baseurl }}/assets/inversetrigusub/lnanswer.JPG){: .align-center}

So, while you're learning this, it's more important to remember all the potential strategies than to pick the correct strategy on your first try.  If you were to try the inverse tangent strategy on the second example here, it would not work, but it would only set you back like a minute or two as long as you try again with a different strategy.  Integrals can be tricky, but that's what I think makes them fun to solve :)


