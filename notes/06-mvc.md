# MVC

Think of classes like Allegory of the Cave; the physical representation of metaphysical thing

    class Chair{
        legs =4;                            THIS IS LIKE A BLUEPRINT OF CODE
        matieral = 'wood';
    }

    let myChair = new Chair()              THIS IS LIKE AN INSTANCE OF 'CHAIR' THAT NOW BECOMES A VARIABLE
    myChair.legs = 3

    <!-- BEGIN WITH: -->
    src=app.js type = "module"
    Use class tag (instead of var/let/const){
        Items HERE *look like arrays*
            }


        class Food {
            <!-- method that runs on instantiation -->
            name
            pice
        
        constructor (name, price){
            <!-- this is a reference to the instance being created   -->
            <!-- (whatever is left of the '.' at calltime) -->
            this.name = name
            this.price = price
            <!-- this allows objects to be expressed -->
        }
        
        print () {
            console.log(this.name, ':' this.price)      > You can add functions or 'methods' to classes 
}
        }
 > In order to use a class, we must instantiate it (new it up)
        const burger = new Food()
        burger.name = 'cheeseburger'
        burger.price = 1.50
        console.log(burger) will now print class properties


> Classes are singular items

