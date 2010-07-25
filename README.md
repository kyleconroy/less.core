# less.core

A standard library for less.js Currently includes

* Eric Meyer's reset CSS
* CSS3 border-radius
* CSS3 box-shadow
* Footer Push (experimental)

## Example

    @import "reset";
    @import "library";
    
    #wrapper {
       .box-shadow(0px, 0px, 3px, #000);
       .border-radius(5px);
    }

## Future

I want to support all CSS3 rules that currently require CSS prefixes      
