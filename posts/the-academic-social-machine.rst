.. title: The academic (social) machine
.. slug: the-academic-social-machine
.. date: 2014-09-11 13:40:33 UTC+02:00
.. tags: social_machine, google, algorithmic_bias, ds106
.. link: 
.. description: 
.. type: text
.. author: Paul-Olivier Dehaye

There was recently a `picture circulating on Twitter <https://twitter.com/AndrewBRElliott/status/507912025599934464/photo/1>`_, like pictures do.

.. image:: ../why_google.jpg
   :scale: 100%
   :align: center

This is, to say the least, a skewed view of academia, although I am certainly not the best placed to say that. I tend to have a beard, use big words, have recently started blogging and did `wear robes at some point in my academic career <http://en.wikipedia.org/wiki/Academic_dress_of_the_University_of_Oxford>`_. This is however a good opportunity to show how algorithmic bias works. 

First off, where does the bias originate here? 
As I explained before in my post on `social teaching machines <../posts/social-teaching-machines.html>`_, autocompletion surfaces information collected previously. The information in this case is collected in various ways, most notably by looking at previous searches. I would posit that the way the information is collected leads itself to the bias. Some of those biases are more serious, as is amply demonstrated by any search of the form "Why do A people like", where A can be any of {asian, white, black}. Only one of those autocompletes works for me, the other two give nothing (presumably because the output is too vile and has been hand blocked). So these stereotypes, surfaced by humans, are inserted into the huge Google machine. Let's see where this leads. 

In the case of autocompletion, the impact is certainly weak, but it might correlate with other biases, underscoring a more ingrained problem. Let's go back to Google's view of academia: what does the output of a `Google Image Search of "academics faculty" <https://www.google.com/search?site=&tbm=isch&source=hp&biw=1366&bih=635&q=academics+faculty&oq=academics+faculty>`_ return? The link in the previous sentence is user agnostic (but its output will be personalized by Google once you click, unless you use privacy conscious tools). Here is the view I get:

.. image:: ../why_google_images.jpg
   :scale: 100%
   :align: center

Yours should be different: most probably, Terence Tao, the short-sleeved mathematician in the middle row is further down in yours. This is reasonable, and explained by Christian Sandvig in the Social Media Collective blog in a beautiful post called `Show-and-Tell: Algorithmic Culture <http://socialmediacollective.org/2014/03/25/show-and-tell-algorithmic-culture/>`_: since I am a mathematician, Google gives Tao a bump [1]_. And beyond that? Well, Google *really* thinks that academics wear robes, and perpetuates this bias also visually, not just in autocomplete. One consequence is that when humans need to illustrate something (a blog, an educational resource,...) it actually requires training and effort not to succumb to that bias. And of course this intermediate step of choosing a picture could itself be automated in various ways, leading to ...


.. [1] This effect, of showing me Tao higher than average, might be reasonable in this case, but it could also lead to some form of `filter bubble <http://en.wikipedia.org/wiki/Filter_bubble>`_ if there were (many) more mathematicians, and other unforeseen consequences as tested by the `recent Facebook experiment <http://www.forbes.com/sites/dailymuse/2014/08/04/the-facebook-experiment-what-it-means-for-you/>`_. 
