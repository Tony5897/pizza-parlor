# Expected Output 
#                ###Achieve Baseline Functionality First!###

# Rules/Baseline:
* Allow user to choose TOPPINGS and SIZE for pizza order
 * Creat a pizza OBJECT CONSTRUCTOR with PROPERTIES for TOPPINGS and SIZE.
 * Create a PROTOTYPE METHOD for the COST of a pizza depending on SELECTION chosen.
 * Use own formula for this.
 * FORMAT README!
#
# #####################
<!-- special mold to create 'new' objects(instance) -->
<!-- this is your constructor(shell) -->
Describe: Pizza()
Test: "It should construct a pizza object." 
Code:Pizza()
Expected Output: Pizza object constructor
# ####################

<!-- VIS:menu/user walk-in maybe?  -->
<!-- OBJECT -->
Describe: Pizza()
Test: "It should return an object with the properties for Size, and Toppings."
Code: pizzaJS = new Pizza();
Expected Output: Pizza {topping[""], size: "" }

<!-- User deciding size of pizza..determine sizes..??? -->
<!-- What determines sizes...small/med/lrg??...NOTE: FORMULA FOR COST FOR PIZZA/TOPPINGS  -->
<!-- NOTE: SIZE properties(User size choice) above in first test -->
<!--##VIS: USER PICK SIZE## -->
<!-- "PROTOTYPE" PROPERTY -->
Describe: Pizza.prototype.pickSizes(sizes)
Test: "It should return a size based on user size choice."
Code: pizzaJS.pickSize();
Expected Output: sizes

<!-- ADD ARRAY??????  -->
<!-- NOTE: GETTING BACK USERS CHOICE OF PIZZA 'SIZE' AND TOPPING... -->
<!-- ##VIS: USER ADD TOPPINGS -->
<!-- "PROTOTYPE" PROPERTY -->
Describe: Pizza.prototype.addToppings(menuChoices)
Test: It should add an array to the object pizza
Code: pizzaJS.addToppings(["ExtraCheese"];)
Expected Output: {toppings: array}

Describe: Pizza
Test: 
Code:
Expected Output:

Describe: Pizza
Test: 
Code:
Expected Output:

Describe: Pizza
Test: 
Code:
Expected Output:



#
<!-- NOTES: -->

<!-- README Layout Note:
-References/documentation section..maybe?
-Fix overall layout for readability
-Add all notes to README for visual representation 'thought process' throughout application build...Checkout README best practices first. -->

<!-- 
# obj-check #
-constructors and protype utilization
-App works as expected upon use
-Quality, plain english specs in README
-Baseline functionality by dealine -->

<!-- FORMULA: ???
#(pick)...size..toppings..total cost... -->