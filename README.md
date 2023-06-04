# calculator-java
simple calculator written in Java; supports addition, subtraction, multiplication and division
LOC: 134.
Cyclomatic Complexity : 30

Staticka analiza za
Calculator.java:
loc:1 – Move this file to a named package.
loc:4 - Add a private constructor to hide the implicit public one.
loc:18 -Rename method "ToString" to prevent any misunderstanding/clash with method "toString" defined in superclass "java.lang.Object"
loc:24 -Rename this method name to match the regular expression
loc:70 -Immediately return this expression instead of assigning it to the temporary variable "textResult".
loc:74 -Rename this method name to match the regular expression

Staticka analiza za
Start.java:
loc:1 -Move this file to a named package.
loc:6 -Rename this local variable to match the regular expression.
loc:8 -Replace this use of System.out or System.err by a logger.
loc:19 -Replace this use of System.out or System.err by a logger
