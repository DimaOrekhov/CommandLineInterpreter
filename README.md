# CommandLineInterpreter

Brief description of app's architecture:

There are 3 main modules:
1. Substitutor, substitutes variable values instead of their names, e.g. `echo $var > echo value`
2. CommandParser, parses a string containing command to CLI into internal representation
3. Environment, works with an internal representation of a command to execute it

1 and 2 are implemented as DFAs
