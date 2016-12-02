.. title: Naiveté, the barber paradox, and frontiers in publishing
.. slug: naivete-and-the-barber-paradox
.. date: 2014-08-19 14:40:13 UTC+02:00
.. tags: mathjax, logic
.. link: 
.. description: 
.. type: text
.. author: Paul-Olivier Dehaye

.. image:: ../razor.png
   :scale: 50%
   :align: right

Over the turn of the XIXth and XXth century, some of the best mathematicians had to take a hard look back at the foundations of their science. A turning point in the mathematical story below was the 1900 Paris International Congress of Mathematicians. This post is in honor of the `ongoing ICM <http://www.icm2014.org/>`_ in Seoul. 

In the last decade of the XIXth, Cantor had developed what is now called `Naive Set Theory <http://en.wikipedia.org/wiki/Naive_set_theory>`_. Under his theory, one was allowed to introduce expressions such as :math:`S = \{ x: P(x)\},` which defines the set :math:`S` of all elements :math:`x` having property :math:`P.`

Russell quickly indentified a problem with this. This issue has a nice real-life illustration, known as the `barber paradox <http://en.wikipedia.org/wiki/Barber_paradox>`_: 

    Imagine a town where every man keeps himself clean-shaven, either by shaving himself or going to the unique male barber in town. The paradoxical question is then "Who shaves the barber?" 
            
In layman's terms, the paradox does not rely in asking who, but in assuming one can pick a town with such a hair-trimming setup. 

In mathematical language, Russell considers the set :math:`R` of all the sets which do not contain themselves, and asks whether it does contain itself or not. Both conclusions could be obtained but should be mutually exclusive, a contradiction.  This is formulated as:

.. math ::
    R = \{ x | x \notin x \} \Longrightarrow (R \in R \Leftrightarrow R \notin R).

.. image:: ../frege.jpg
   :scale: 60%
   :align: left

As an answer to this contradiction, Zermelo and others built a new set theory over the first decade of the XXth century that painted Cantor's original definition as too *naive*. Indeed, while Cantor assumed just any property :math:`P` would do and play nice, Russell had showed that this just would not do. The solution around this problem was to precisely restrict which properties are nice enough to allow in the construction of the naive sets. Still, the logicians involved knew of the importance of these others not-so-nice constructions, and very much wanted a theoretical basis for them. This led to the substantially more complicated notion of `proper class <http://en.wikipedia.org/wiki/Proper_class>`_. Together with `Cantor's prior argument of the diagonal <http://en.wikipedia.org/wiki/Cantor's_diagonal_argument>`_, these additional tools lead to spectacular discoveries that rocked mathematics and computer science a few decades later. These include the `Halting problem <http://en.wikipedia.org/wiki/Halting_problem>`_ or `Godel's incompleteness theorem <http://en.wikipedia.org/wiki/Godel_incompleteness_theorem>`_.

Russell arrived at this question by writing his *Principles of Mathematics*, an attempt at formalising fully Cantor's original theory. While the barber question could have looked like little more than some Victorian form of `trolling <http://en.wikipedia.org/wiki/Troll_(Internet)>`_ to his peers (maybe due to its reflexivity), he was understood right away: it led Frege for instance to repudiate his own *Foundation of Arithmetic* while in press. 

**This carries lessons outside of mathematics too.**

    Imagine an institution which raises an expectation that its core mission would apply equally to all institutions.  It is always instructive and revealing when real world situations turn this expectation around, into a barber paradox. 

I will give two quick examples.

The first would be that of a generalist newspaper. A journalist's mission should be to consistently report on the news, **including news about their own newspaper's failures**.
Yet at this mission journalists often fail, mostly through self-censorship. 
The `New York Times innovation report <http://www.forbes.com/sites/kashmirhill/2014/05/17/the-problem-at-the-new-york-times/>`_  is particularly interesting, since it reveals quite a bit of all the internal tensions between advertising and editorial staff to adapt their newspaper to a changing publishing landscape. Yet we can only read this report because it was leaked, presumably by a journalist to an online outlet! A missed opportunity for the *New York Times* indeed.

A second example would be that of academic publishing. One would expect researchers to be free to publish in academic journals on the business aspects of academic publishing. In a `recent case <http://www.timeshighereducation.co.uk/news/taylor-and-francis-apologises-after-censorship-debate/2014017.article>`_, four academics submitted an article to a *Taylor & Francis* journal called *Prometheus: Critical Studies in Innovation*. The topic was scientific publishing itself. While the article had been accepted by the journal editors, the publisher `stalled and censored 
<http://hybridpublishing.org/2014/06/censorship-and-the-absurdities-of-journal-publishing/>`_ the publication of some of the information, otherwise available from public sources. Eventually the article was published after some editing and the publisher had to explain its actions. Still, this required the editorial board to threaten to resign en masse, and the publisher was still brazen enough to keep a disclaimer undermining all the research. 

    While in both cases the institution reacted to protect itself from a perceived threat, ultimately this institution's communication (or lack of it) was possibly more revealing of its own internal logic.

Since we are already talking about barbers, I can't resist to riff a bit more. Russell's paradox leverages a very simple initial statement to the profound conclusion that new mathematical foundations are needed. To reach bold conclusions, simplicity always wins. This might be a corollary of `Occam's Razor <http://en.wikipedia.org/wiki/Occam's_razor>`_...

(The comic strip is *Logicomix: An Epic Search for Truth*, which you can buy on `Amazon <http://www.amazon.com/Logicomix-An-Epic-Search-Truth/dp/1596914521/ref=sr_1_1?ie=UTF8&qid=1408461633&sr=8-1&keywords=logicomix>`_. Highly recommended!)
