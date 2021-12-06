# JavaScript
Script at bottom of page; load javascript last so that webpage display loads first
<!-- DATA TYPES:
    * PRIMITIVE: value
        - numbers, boolean, string,
    * NON-PRIMITIVE: reference
        - object, function, array
        <!--  -->

    <!-- STRINGS:
    * DEFINED BY: '', "", `` (industry standard is '') -->

    let greet 'Hello'
    let group = 'World'
    <!-- *JOINING STRINGS (INTERPOLATIPOIN, CONCATENATION) -->

    let greeting(concat) = greet + ' ' + group
        <!-- *EVERYTHING between the ${} is treated as javascript -->
    let greetingInterpolate = `${greet} ${group}: ${3 +3}`

    <!-- NUMBERS
    OPERATORS +,-,/,*,%
    MODIFY/REASSIGN VARIABLE w/ '='
    +=, -=, 
     -->

<!-- BOOLEANS
*TRUE/FALSE: ==
&& is both variables are true, || is at least one variable is true
TRUTHY, FALSY (used with if/else statements; (if ))
INVERT BOOL WITH !-->


    function test(val){
        if (val > 0){
            console.log(true)
        } else {
            console.log(false)
        } 
        }
    }

Think of javascript like algebra functions; f(n)
    - we write functions and assign values
        * arguments are the values going into the "monster box"
        * parameters is the rules of the functions
        * for functions you want something back from; use return

Assign 'events' like a CSS tag; events call functions (also added like a CSS class)
        onclick= "cow" (will run defined function upon click of element; console will print "moo" on click)
                function cow(){
                    console.log('moo')
                }

<!-- innerTet is just string contents and is treated as a string
innerHTML is treated as HTML you (can add tags) -->

<!-- DOT NOTATION (drilling through an object with known properties) -->
<!-- BRACKET NOTATION (accessing properties on an objects using a variable) -->