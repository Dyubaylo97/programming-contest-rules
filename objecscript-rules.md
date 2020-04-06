# ObjectScript Linter
## ObjectScript Errors check

RequiredArgumentOmitted
For example Method A defined with two arguments required arguments, but called with one.

TooManyArguments.
    For example, Method has two formal arguments, but passed three.

IncompatibleType.
    For example, method expects to receive %String as argument, but receive Sample.Person

VariableNotFound.
    Variable is used in expression, but was neither passed as argument nor set before. For methods with ProcedureBlock=0 this error is not produced.

MethodNotFound and PropertyNotFound
    For variable of some class there is no corresponding property or method defined.

MissingParentheses.
    Tries to find expressions such as if a = 1 || a = 2 (should be: "if a = 1 || (a = 2)")

QuitWithoutArguments.
    Method is defined with ReturnType value but has quit (or return) without arguments

NoQuitFound.
    Method is defined with ReturnType value but has no quit (or return) command

ClassNotFound

MethodLackReturnType.
    Method is used in expression but has no ReturnType in definition
    
## ObjectScript Style check
No dot syntax in stack
    prohibit stacking with dots


