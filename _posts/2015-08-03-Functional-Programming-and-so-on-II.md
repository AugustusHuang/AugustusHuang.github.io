---
layout: post
title: Functional Programming and so on II
---

{{ page.title }}
================

A good language should be firstly beautiful, then efficient, more users don't
necessarily mean that it's more useful or successful, it only means that the
language is more suitable for those users. In my point of view, Lisp is no
doubt the GOAT. Its canonical form, which once give scientists lights of AI,
is the reason why I love it. Consider how you could extend Lisp, don't need to
extend the readtable, don't need to give a syntax with different prefix, all
you need is the parenthesis. Lisp compilers will complain about the undefined
variables, and variables could be anything... Fantastic!  
Every time I try to implement a brand new algorithm, I choose Lisp, only except
when I need to re-implement it. Chances are Lisp codes run as fast as C/C++
ones, but the coin has two sides and we have to face the reality, due to the
dynamic type system and the recursion calls, Lisp will be no faster than its
C compiled and optimized counterpart.  
Haskell is another language I feel good with. Not because of its syntax, but
of its Mathematical background. It uses a lot of concepts in Category theory
and cheerfully implements them. I can find Monads, Monoids and typeclasses.
Great. Since I'm new to Haskell land, I haven't digged into haskell's compiler
yet, so I can't tell the efficiency, but since it forces a user to write in
recursion, and maybe a lot of users don't know how to make tail recursions,
will they get what they want?  
So, what's the sense? What's the language in my mind? I have lots of questions
now. Is a function in 2-or-higher-category necessary? Will the typeclasses in
2-or-higher-category be used sometimes? If I use 5000 lines to implement a
higher category abstraction and some more lines to make them efficient, will
they be attractive? Computers don't know nothing about generalization until
we tell them how to, so the only way to define function is to give a defined
domain and codomain, if the domain/codomain pair is small, what's the sense of
making such a big effort to make them more abstract instead of making them
more easy to understand but less elegant?
