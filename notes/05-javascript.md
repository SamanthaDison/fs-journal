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

COMPLEX OBJECTS


let Utahutes = {
    conference: "Pac-12",
    divisionChampionships: 4,
    conferenceChampionships: 1,
    power5: true,
    tags ['pac12', 'mountain teams', 'red', 'defense'],
    starters: [
        {
            name: "Britain Covey",
            positions: ['WR', 'PR']
        },
        {
            name: "Cameron Rising",
            positions: ['QB', 'P']
        }
    ]
}

console.log(utahUtes.starters[0].name) will print Britain Covey
console.log(utahUtes.tags[3]) will print defense

FOR LOOPS

const cats = ['garfield',' 'pepperbottom', 'ham', 'carl']
for (let i=0; i < cats.length; i++){
    let cat = cats[i]
    console.log(cat)
}

FOR EACH

cats.forEach(function blah(){

})

cats.forEach(c => console.log(c.name ))

PUSH FUNCTION (ADDING TO ARRAY

let cuddly []
for (let i=0-; i < cats.length; i++){
    let cat = cats[i]
    if (cat.cuddles){
        cuddly.push(cat)
    }
}

<!-- CREATES NEW ARRAY CALLED CUDDLY AND LOOP WILL ITERATE AND LOG ONLY CATS ^^^^^^^^^ -->

FILTER FUNCTION (creates new array w/ all elements that pass the function) *used to 'scrub' an array to create a new one from that data w/o destroying/altering the original array.

let cuddly = cats.filter(cat => cat.cuddles)
let orangeCats = cats.filter(cat => cat.color =='orange' && cat.cuddle)  *WILL CREATE NEW ARRAY OF ALL CATS WHO ARE CUDDLES:TRUE AND COLOR:ORANGE

<!-- TO PRINT TO PAGE -->

let template =
for (let i = 0; i < cats.length; i++){
    const cat = cats[i];
    template += '<li>Carl: Orange</li>'
}
document.getElementById('cats').innerHTML = template

<!-- USE CURLY BRACKETS TO ACCESS SPECIFIC VALUES AND PRINT THOSE -->

let template =
for (let i = 0; i < cats.length; i++){
    const cat = cats[i];
    template += '<li>${cat.name}: ${cat.name}</li>'
}
document.getElementById('cats').innerHTML = template

<!-- WITH BUTTON IN HTML ONCLICK = "filterCuddly()" -->

function filterCuddly()
let cuddlyCats = cats.filter(cat => cat.cuddles)
let template =
for (let i = 0; i < cats.cuddlyCats; i++){
    const cat = cuddlyCats[i];
    template += '<li>${cat.name}: ${cat.name}</li>'
}
document.getElementById('cats').innerHTML = template

<!-- NOTICE HOW THE TEMPLATE IS NOW ITERATING OVER THE NEW ARRAY ^^^^ -->

