fpjsideas
=========

ideas for a library set to create a full fp runtime


GOAL: To enable users to write functional applications in javascript in node/browser/titanium with 1 require.

CORE Functions necessary:
- compose
- partialLeft
- partialRight
- constantly (K)
- identity (I)
- autoCurry

QUESTIONS:
- do we wrap all of ecmascript as it is or branch away (see https://github.com/loop-recur/lambdajs)
  - things like push are weird and unncessary (where's cons?!)
- how far do we go for core functionality vs helpful functions? We've found getter/setter functions, logging, and a combinator or two to be core, but they're probably not...

IDEAS:
- keep it modular for levels of fp. For instance fmap or mconcat should not be in the base library.
- have an "expose to namespace" feature

