# OCaml-typeinference
simple type-inference and type-checking for bare simply-typed lambda calculus 

Tested with OCaml version 4.06.1

#use "substitution.ml"

use function typer which takes as arguments two strings, one the base of the term, which can be empty for closed terms (i.e."" or "x:(A -> B)", y:A"), and the other the term i.e. "lambda y. lambda z. (lambda x. (x y) z)"

UI need to be written
