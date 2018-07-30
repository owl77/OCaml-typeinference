# OCaml-typeinference
simple type-inference and type-checking for bare simply-typed lambda calculus 

Tested with OCaml version 4.06.1

#use "substitution.ml"

use function typer which takes as arguments two strings, one the base of the term, which should be empty for closed terms (examples: "" or "x:(A -> B), y:A" ), and the other the term. Example:  "lambda y. lambda z. (lambda x. (x y) z)"

# typer "" "lambda y. lambda z. (lambda x. (x y) z)";;
- : string = "( 'b -> ( ( 'b -> 'a ) -> 'a ) )"

UI needs to be written and also include constructors and primitives.
