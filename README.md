# Transformer

Demystification of NLP Transformer and self-attention with some intuitions sprinkled on top.

# Motivation

I wanted to add some missing details to standard transformer annotations often found in courses and texts. But not wanting to reinvent the wheel with yet another explanation, the accompanying notebooks are mostly an expansion of [Chapter 11 of the Dive Into Deep Learning](https://d2l.ai/chapter_attention-mechanisms-and-transformers/index.html) open source book -- a valuable resource for learners. (We are all learners.)

I fully acknowledge the stirling work of the contributors/authors of that book and my only wish was to build upon their hard work by layering in a few extra details for the more discerning student. This is by way of adding in some lower-level details (with toy examples) and a smattering of intuition to connect the technical apparatus back to the task in hand, namely processing of language.

I guess I could have contributed to the book somehow, but, as you will see, my explanation is perhaps a bit too dense for the book's style and would not cohere with its fine standards and running narratives.

Mostly, I hope to demystify things.

The Transformer is on the one hand a remarkably simple invention -- one almost wonders why it wasn't thought of earlier. Well, actually it was, only it appears that no one attempted to use the idea at scale in this particular configuration (i.e. without recursion). On the other hand, down in the arithmetic weeds one might lose sight of why it's designed the way it is. (Note: many inventions in tech have been invented before, perhaps in different guises. For example, the core principle of Deep Learning frameworks is automatic differentiation, but it appears that the DL community had not noticed how far the Optimization community had already taken this subject.)

Well, I say "it" (The Transformer), but there are now many variants. My annotations are of the DIDL version, which is a kind of canonical representation of the original architecture from the referenced paper [Attention is all You Need](https://d2l.ai/chapter_references/zreferences.html#id297).

Feel free to fork, enhance, annotate, pull-apart as you wish.
Most of the code here is the DIDL open license code, and the rest is just my noodlings.

One message I hoped to convey in this annotation is that Deep Learning, whilst backed with various mathematical ideas, often works without theoretical explanation and in ways not entirely understood, especially when new ideas first surface. Moreover, with modern tools like Pytorch, it is easier than ever to play with ideas. I built my first MLP in 1994, possibly during the AI Winter, although I'm not sure as I wasn't really paying attention to the frontiers of the field in the way one can today via the Web. But much of what I did, taking weeks to get working, can now be done in a few lines of code. So, you have no excuse :)
