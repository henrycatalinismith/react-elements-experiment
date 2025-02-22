# react elements experiment

This project is an exploration of some ideas around React, TypeScript and HTML.
For a while I've wondered if React & TypeScript can be used to facilitate
generating valid, accessible HTML documents. So I made this to try it out.

The idea is that it should be impossible to render an invalid document if you
use these components. Basic HTML accessibility issues such as skipping
heading ranks should be impossible too. And pages that contain a mixture of
content in different languages should have the minimal set of `lang` attributes
necessary for screen readers to make sense of it all. That kind of thing.

It's been fun to explore the idea but I'm not convinced the result is worth it.
It needs a lot of meta-programming and a lot of functional programming
indirection. And it gets a little busy with all the context providers, to the
extent that I'd be concerned about client-side performance if this code was
used for anything other than server-side rendering.

So that's probably that for this project, but the repo gets to stay online
anyway just in case I want to borrow code or ideas from it.
