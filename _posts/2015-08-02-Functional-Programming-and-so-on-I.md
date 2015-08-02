---
layout: post
title: Functional Programming and so on I
---

{{ page.title }}
================

Abstraction is great, in Mathematics, and in my opinion the greatest
abstraction is Category theory. It is useful in Homology Algebra, in Quantum
Algebra, in Algebraic Geometry, to be honest, in almost all fields of modern
Mathematics, and especially... in Category theory itself.  
Category can be built upon category or categories. It is recursive, if we assume
a upper limit of number of objects in the category, some mathematician will
assume the object sets and the function sets are all "sets", not proper classes.
Consider two categories, what if we regard the functors between as functions,
and the categories themselves objects? If the amount doesn't surpass the
definition in Set theory, we can name it another category. Indeed we can build
the category world upon them, name our very beginning categories 0-categories,
and 1-categories, 2-categories...  
But wait, what's the relationship between what we've described and Functional
Programming?  
All programming languages has objects (elements, or values, here I mean rvalue)
and functions (will have arguments, return value, with side effects or not).
And all of them (as far as I know...) have reserved keywords or function like
"if". "if" is a signal to show the form (or equation, or expression) should
be true or false when evaluated, and we can't compare whether \\(5 \gt "abc"\\),
since there's no natural ordering relationship between these two objects, now
let's image the categories underlying two objects, in natural way, 5 is of type
\\(\mathbf{Int}\\) and "abc" of type \\(\mathbf{Str}\\), now \\(\mathbf{Int}\\)
has a natural ordering system, \\(0 \lt 1 \lt 2 \lt 3 \lt \dots \\), and
\\(\mathbf{Str}\\) may or may not has a ordering, here we assume ordering
implies equality, so in \\(\mathbf{Int}\\), any two objects will have a
relationship, less or more or equal, and \\(\mathbf{Str}\\), under different
definitions, maybe more loose.  
In haskell a lot of mathematical concepts are implemented, typeclass is the
higher-level category we've mentioned above, regard a type as a category, all
the things are trivial! Of course, the highest abstraction level should refer
to the lowest level implementation, so if we have a n-category level function,
it must be a n-functor between 0-categories, and so it's possible to define
the relationship among functions of functions of functions of...  
So is it necessary to design a new language that handles such kind of
generalization gently and efficiently?
