[![Yoobee School of Design](../images/yoobee-logo-300w.png)](http://yoobee.ac.nz)

# Javascript Best Practices

When producing Javascript for a web project at Yoobee School of Design, you should:

* Use external scripts unless justified
* Minimise the number of external scripts a page uses
* Acknowledge all third party scripts using comments
* Code should be written to the DRY principle i.e. no repetition. Create functions that take parameters, and return values to foster code reuse
* Comment your code https://github.com/shri/JSDoc-Style-Guide
* Ensure site is usable when Javascript is turned off
* Use consistent naming: functionNamesLikeThis, variableNamesLikeThis, ClassNamesLikeThis, EnumNamesLikeThis, methodNamesLikeThis, CONSTANT_VALUES_LIKE_THIS, and file-names-like-this-1.0.min.js 
* Name functions and variables logically
* Prefer single quotes over double quotes
* Always declare variables with var (or in ES6 - var, let, const)
* Always use semicolons
* Don’t declare a named function within a block https://google.github.io/styleguide/javascriptguide.xml?showone=Function_Declarations_Within_Blocks#Function_Declarations_Within_Blocks
* Minimize the use of global variables
* Separate event handling from functionality
* Minify all Javascript for production
* Use a Javascript linting tool
* Organize your code into the Modular Pattern, Object Literal/Singleton, or Objects with Constructors where possible




