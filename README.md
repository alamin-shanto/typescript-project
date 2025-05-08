** What are some differences between interfaces and types in TypeScript?
Interface is mainly used to describe the shape of an object. Interface can be extended using extends. 
if the same interface written twice, TypeScript merges them. Interface used when working with the objects, classes or structure definitions. 

Type also describe the shape of an object, but its more flexible. Type can be combined using & (intersection). 
Type doesn't support merging. Writing again it gives an error. Type used when working when need unions, intersections & so on.

** How does TypeScript help in improving code quality and project maintainability?
Typescript catches errors before run the code. Editors like VS code can suggest methods and properties. 
when change a variable, function or interface typescript shows where it affects the code. In big apps with many files and developers typescript ensures everyone follows the same rules.
