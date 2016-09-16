---
published: true
title: Ordinal Number (Set Theory)
layout: post
---
**In set theory,** an ordinal number (or ordinal) is a generalisation of the natural number that is used to describe a way to *arrange a collection of objects in order - one after another*. Put it in another way, ordinal numbers are the *labels* needed to arrange collections of objects in order. 

For finite collections of objects, ordinal numbers are just counting numbers. On the other hand, a more 
generalised concept called *well-ordering* is introduced for infinite collections. 

Every ordinal number is either zero, or a successor ordinal, or a limit ordinal. For example, 
*0, 1, 2, ..., \omega, \omega + 1*, *\omega* is a limit ordinal because, for any smaller ordinal, there is another ordinal larger than it, but still less than *\omega*. Also, *1, 2, ...* and *\omega + 1* are successor ordinals. 

## Von Neumann Definition of Ordinals

The standard definition, suggested by John von Neumann, is: *each ordinal is the well-ordered set of all smaller ordinals*, in symbols *x = [0, x)*. Formally, 

> A set *S* is an ordinal if and only if *S* is strictly well-ordered w.r.t. set membership and every element of *S* is also a subset of *S*.

## Well-order

A *well-order* (or *well-order relation*) on a set *S* is a total order on *S* with the property that every 
non-empty subset of *S* has a least element in this ordering. The set *S* together with the well-order relation is called a *well-ordered set*. 

Every non-empty well-ordered set has a least element. Every element *s* of a well-ordered set, except a 
possible greatest element, has a unique successor. *There may be elements besides the least element which have no predecessor*. In a well-ordered set *S*, every subset *T* which has an upper bound has a least upper bound, i.e. the least element of the subset of all upper bounds of *T* in *S*. 
Furthermore, every well-ordered set is uniquely *order isomorphic* to a unique ordinal number.

## References 

* <https://en.wikipedia.org/wiki/Well-order>
* <https://en.wikipedia.org/wiki/Ordinal_number> 