# Eval #

## Evaluate Expressions in Strings.

### Return
An array (object) with the result of each expression.

### Credits
ExprEval() by Uberi

## Parameters

### $x:
The input string to be evaluated. You can enter multiple expressions separated by commas (inside the string).

### _CustomVars
An optional Associative Array object containing variables names as keys and values to replace them. For example, setting it to {A_Index: A_Index} inside a loop will replace occurrences of A_Index with the correct value for the iteration.

### _Init
Used internally for the recursive calls. If TRUE it resets the static object _Objects, which holds objects references to be restored.

