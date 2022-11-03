# Transformer

Demystification of NLP Transformer and self-attention with some intuitions sprinkled on top.

# Motivation

I wanted to add some missing details to standard transformer annotations, although not want to reinvent the wheel with yet another explanation.

To wit, the notebook is an expansion of the Chapter 11 of the Dive Into Deep Learning open source book.

I fully acknowledge the contributors/authors of that book and only wish to add to their hard work by layering in a few extra details for the more discerning student. This is by way of adding in some lower-level details (with toy examples) and a smattering of intuition to connect the technical apparatus back to the task in hand, namely processing of language.

Mostly, I hope to demystify things.

The Transformer is on the one hand a remarkably simple invention -- one almost wonders why it wasn't thought of earlier. Well, actually it was, only it appears that no one attempted to use the idea at scale in this particular configuration (i.e. without recursion). On the other hand, down in the arithmetic weeds one might lose sight of why its designed the way it is.

Well, I say "it" -- as in the DIDL version, which is a kind of canonical representation of the original architecture from the referenced paper [Attention is all You Need](https://d2l.ai/chapter_references/zreferences.html#id297).

Feel free to fork, enhance, annotate, pull-apart as you wish.

One message I hoped to convey is that Deep Learning, whilst backed with various mathematical ideas, often works without theoretical explanation. Moreover, with modern tools like Pytorch, it is easier than ever to play. I built my first MLP in 1994, possibly during the AI Winter, although I'm not sure as I wasn't really paying attention to the frontiers of the field in the way one can today via the Web. But much of what I did, taking weeks to get working, can be done in a few lines of code today. So, you have no excuse :)
