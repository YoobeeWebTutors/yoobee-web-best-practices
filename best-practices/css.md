[![Yoobee School of Design](../images/yoobee-logo-300w.png)](http://yoobee.ac.nz)

# CSS Best Practices

When producing CSS for a web project at Yoobee School of Design, you should:

* Plan and create your HTML first
* Use CSS to adhere to a responsive design plan
* Use only one style sheet per page (IE conditional styles excepted)
* Validate your CSS http://jigsaw.w3.org/css-validator/
* Use comments to add meaning
* Include a CSS reset at the start of the style sheet
* Organise the style sheet with a top down structure from generic to specific
* Use classes (or multiple classes), combine rules and take other measures to reduce repetition
* All CSS should be consistent with a methodology, such as SMACSS, BEM, or OOCSS
* Reduce specificity as much as your CSS methodology will allow
* Selectors must be named consistently and meaningfully, not start with numbers and have no spaces or special characters
* Use absolute positioning only when default positioning can’t fulfill a use case
* If using floats, remember to clear them
* Don’t use an image where there is a CSS alternative
* Use external files unless justified
* Use the cascade appropriately
* Use inheritance where possible
* Don’t over-qualify selectors
* Use shorthand for properties like padding and margin
* Don't leave commented out styles in production CSS
* Compress CSS for production

