I was most fascinated by <a href='https://twitter.com/nadiehbremer'>Nadieh</a>'s gooey example from her OpenVis Conf talk, and especially with the gooey color blending.  After reading her <a href='http://www.visualcinnamon.com/2015/05/gooey-effect.html'>blog post</a>, I decided to give the circles some colors - and it turned out to be as straightforward as I was hoping for.

The only two things I had to change:

- add a colorScale and replace the circles' fills with the colorScale outputs

- remove feComposite from the filters (I'm looking into why this is)


Thank you Nadieh for your brilliance 💕


--

forked from <a href='http://bl.ocks.org/nbremer/'>nbremer</a>'s block: <a href='http://bl.ocks.org/nbremer/69808ec7ec07542ed7df'>Gooey Effect - Circle</a>