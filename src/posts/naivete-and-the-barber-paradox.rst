.. title: Naiveté and the barber paradox
.. slug: naivete-and-the-barber-paradox
.. date: 2014-08-19 14:40:13 UTC+02:00
.. tags: mathjax, logic, society, mathematics
.. link: 
.. description: 
.. type: text
.. author: Paul-Olivier Dehaye

.. image:: ../razor.png
   :scale: 50%
   :align: right

Over the turn of the XIXth and XXth century, some of the best mathematicians had to take a hard look back at the foundations of their science. A turning point in Russell's story was the 1900 Paris International Congress of Mathematicians. This post honors the ongoing ICM in Seoul. 

In the last decade of the XIXth, Cantor had developed what is now called `Naive Set Theory <http://en.wikipedia.org/wiki/Naive_set_theory>`_. Under his theory, one was allowed to introduce expressions such as :math:`S = \{ x: P(x)\},` which defines the set :math:`S` of all elements :math:`x` having property :math:`P.`

Russell quickly indentified a problem with this. This issue has a nice real-life illustration, known as the `barber paradox <http://en.wikipedia.org/wiki/Barber_paradox>`_: 

            Imagine a town where every man keeps himself clean-shaven, either by shaving himself or going to the unique male barber in town. The paradoxical question is then "Who shaves the barber?" 
            
In layman's term, the paradox does not lie in asking the question, but in assuming one can pick a town with such a hair-trimming setup. 

In mathematical language, Russell's paradox is formulated as:

.. math ::
    R = \{ x | x \notin x \} \Longrightarrow (R \in R \Leftrightarrow R \notin R)

.. image:: ../frege.jpg
   :scale: 60%
   :align: left

In other words, one gets a contradiction from constructing a set :math:`R` of all the sets which do not contain themselves. Indeed, should :math:`R` contain itself or not? Both conclusions could be obtained but should be mutually exclusive, a contradiction. 

As an answer to this contradiction, Zermelo and others built a new set theory over the first decade of the XXth century that led to the qualifier of *naive* for Cantor's original definition. Indeed, while Cantor assumed just any property :math:`P` would do and play nice, Russell had showed that this led to contradictions. The solution around this problem was to precisely define what a set and a property are allowed to be in the naive (and nice) sense. However, because of their experience as logicians, they also made every effort to include similar constructions not willing to play so nice, which led to the substantially more complicated notion of `proper class <http://en.wikipedia.org/wiki/Proper_class>`_. Together with `Cantor's prior argument of the diagonal <http://en.wikipedia.org/wiki/Cantor's_diagonal_argument>`_, these additional tools lead to spectacular discoveries that rocked mathematics and computer science a few decades later. These include the `Halting problem <http://en.wikipedia.org/wiki/Halting_problem>`_ or `Godel's incompleteness theorem <http://en.wikipedia.org/wiki/Godel_incompleteness_theorem>`_.

Russell arrived at this question by writing his *Principles of Mathematics*. While this question might seem like little more than `trolling <http://en.wikipedia.org/wiki/Troll_(Internet)>`_ due to its reflexivity, its importance was understood right away, and led Frege to repudiate his own *Foundation of Arithmetic*. 



      It is always instructive and revealing when real world situations lead to a barber paradox. 

The rhetoric of the New York Times, for instance, raises an expectation that this is an institution (i.e. a set of employees) whose core mission it is to challenge all institutions, **including itself**.
    
Yet it consistently fails, very often through self-censorship (for instance `here <https://medium.com/@lydiapolgreen/how-the-new-york-times-handles-israeli-censorship-22bcfa5addb>`_) and never more so than when it is supposed to `shine the spotlight on itself  <http://www.forbes.com/sites/kashmirhill/2014/05/17/the-problem-at-the-new-york-times/>`_. The New York Times innovation report is particularly interesting, since it reveals a struggle of generations and organisational units to adapt to changing realities an institution they value. Yet we can only read it because it was leaked, presumably by a journalist to an online outlet!

Since we are already talking about barbers, I can't resist: the ultimate beauty of the barber paradox, is that in the face of `Occam's Razor <http://en.wikipedia.org/wiki/Occam's_razor>`_, through its conciseness, it prevents finding any "simpler" explanation than "We need new foundations for mathematics". 

(The comic strip is *Logicomix: An Epic Search for Truth*, which you can buy on `Amazon <http://www.amazon.com/Logicomix-An-Epic-Search-Truth/dp/1596914521/ref=sr_1_1?ie=UTF8&qid=1408461633&sr=8-1&keywords=logicomix>`_. Highly recommended!)