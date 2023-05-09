# crafting_interpreters_robert_nystrom

## Lexing/Scanning
tokens

## Parsing 
abstract syntax tree represent structure language
report syntax errors

## Static analysis
above we figured out the syntactic structure of the language
here we see what each indentiefier refers to
match identifiers with their corresponding definitions, for this we need to know the scope rules of the language.
here we also do type checking if the languages is statycaly typed.

we store the results of the analysis in a data structure

    Syntax Tree Attributes: Often, the analysis data is stored as attributes on the nodes of the syntax tree itself. These attributes are extra fields on the nodes that are not initialized during parsing, but get filled in during static analysis.

    Symbol Table: Another common approach is to store the data in a separate data structure known as a symbol table. This is essentially a lookup table where the keys are identifiers (like variable names), and the values are information about those identifiers, like where they're defined and what their types are.

