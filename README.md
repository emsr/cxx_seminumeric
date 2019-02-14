Implement \<integer\> and \<rational\>.
You know, for the children.

The first bit to implement is the multiprecision
[\<integer\>](http://www.open-std.org/jtc1/sc22/wg21/docs/papers/2014/n4038.html).

Then [\<rational\>](http://www.open-std.org/jtc1/sc22/wg21/docs/papers/2019/p1438r0.html) will have integer numer and denom
in a more-or-less non-surprising way.

The guts of integer will use gmp.
A home-grown implementation would have a *lot* to answer for.
Not that it wouldn't be fun ;-)
