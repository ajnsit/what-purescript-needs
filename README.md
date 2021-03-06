# What Purescript Needs
Purescript community project ideas. a.k.a. What Purescript needs to take over the world

## Meta

### What should not change

Purescript's FP strengths should remain the number one goal. We need a grownup FP language that is pure, has strong static typing, and does not shy away from things like Traversable and Monad.

### Additional goals

1. Focus on the Javascript backend. That is where the biggest market is. Focus on projects which help interoperate with the existing JS ecosystem.
2. Focus on performance and improved code output.

## Projects

### Compiler and tooling ergonomics

1. Better, more user friendly error messages.
2. A standard code autoformatter.
3. Tool to suggest changes based on changelog across major versions.

### Code output improvements

1. Annotations that control the JS output

  Take inspiration from the options provided by Rescript - https://rescript-lang.org/docs/manual/latest/embed-raw-javascript

  One way to allow that without committing to a specific backend is by letting users create compiler plugins like GHC - https://downloads.haskell.org/~ghc/latest/docs/html/users_guide/extending_ghc.html#compiler-plugins.

2. Better typeclass representations. *elaborate*.
3. Better datatype representations. *elaborate*.

### A Killer App

Ideas -

1. Ruby-on-Rails-esque one size fits all solution for web dev. Preferably with server side integration.

### Ecosystem

1. Tool for typescript defs -> Purescript generation.
2. Community maintained type definitions / bindings for major JS libraries.
3. List of best in class library alternatives for each usecase.
4. A cookbook for common recipes
5. TryPurescript could do with some more features, e.g. being able to share snippets without github gists, better IDE support.

### Language improvements

1. GADTs
2. Graceful, canonical solutions for stuff like untagged unions, JS objects with optional fields, etc.
