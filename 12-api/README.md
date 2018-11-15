# [PWL #12: The Little Manual of API Design](https://people.mpi-inf.mpg.de/~jblanche/api-design.pdf)

- PWL ❤️ Brasília [#12](https://www.meetup.com/papers-we-love-bsb/events/255992596/)
- Read [the paper](https://people.mpi-inf.mpg.de/~jblanche/api-design.pdf)
- View [the slides](pwl-bsb-12-slides.pdf)

# Reference:

Blanchette J. The little manual of API design. Trolltech, Nokia. 2008.

# Abstract 

An application programming interface, or API, is the set of symbols that are exported and available to the users of a library to write their applications. The design of the APIs is arguably the most critical part of designing the library, because it affects the design of the applications built on top of them. To quote Daniel Jackson:

> Software is built on abstractions. Pick the right ones, and programming will flow naturally from design; modules will have small and simple interfaces; and new functionality will more likely fit in without extensive reorganization. Pick the wrong ones, and programming will be a series of nasty surprises (Daniel Jackson).

This manual gathers together the key insights into API design that were discovered through many years of software development on the Qt application development framework at Trolltech (now part of Nokia). When designing and implementing a library, you should also keep other factors in mind, such as efficiency and ease of implementation, in addition to pure API considerations. And although the focus is on public APIs, there is no harm in applying the principles described here when writing application code or internal library code.
