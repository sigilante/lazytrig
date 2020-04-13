# lazytrig

A quick-and-dirty trig library in @rs for Urbit.

Copy these into your pier and use them as follows:

    +lazytest [.2.5 .3.4]

Nothing fancy, bad for even single-precision floats, but good enough for, say, graphics.  Don't launch a rocket based on this though.

    > +lazypown [.16 .0.5]
    .3.999892

Currently defines:

- sine
- cosine
- tangent
- factorial
- absolute
- exp
- log-e
- pow-n (for integers only)
- pow (using logs)

Tau has been given primacy of place over pi in the definitions, [and you should do so too](https://tauday.com/tau-manifesto).
