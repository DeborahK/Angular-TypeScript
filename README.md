# Angular-TypeScript
Starter files and support materials for the Pluralsight course: "Angular with TypeScript"

NOTE:
- In the productResourceMock.ts file, on some systems the id variable is typed as "any" and the code works "as is".
- In other cases, the implicit typing marks the id variable as a string. When this happens, the compiler generates an error on the comparison saying the operator "==" cannot be applied to types "number" and "string". The solution is to use the "+" unary operator to convert the array element to an integer:

`var id = +parameters[length - 1];`
