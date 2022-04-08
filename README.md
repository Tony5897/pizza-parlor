# Expected Output 
>
#                ###Achieve Baseline Functionality First!###
>

# Pizza-Parlor Testing 
 
>Describe: Pizza()
>
>Test: "It should create a Pizza object from the constructor with sizes and toppings properties values for foundational purposes."
>
>Code: Pizza()
>
>Expected Output: {Pizza}
# #######################
>Describe: Pizza()
>
>Test: "It should return the pizza object with the properties titled 'sizes', and 'toppings' for the pizza object."
>
>Code: pizzaJS = new Pizza(); 
>
>Expected Output: {Pizza(); with properties(sizes, toppings)}
# ########################
>Describe: Pizza()
>
>Test: "The new object 'pizza' should return an empty string from its parameters"
>
>Code: Pizza('');
>
>Expected Output: {''}
# ##########################
>Describe: Pizza.prototype.addSizes(sizes)
>
>Test: "It should add a method sizes to the prototype property
>
>Code: pizzaJS.pickSize();
>
>Expected Output: {sizes:[]} 
# #######################
>Describe: Pizza.prototype.addToppings(menuChoices)
>
>Test: "It should add an array " 
>
>Code: pizzaJS.addToppings(['ExtraCheese'];)
>
>Expected Output: {toppings:[]} 
# #########################
>Describe: Pizza.prototype.totalCost();
>
>Test: "It should use a formula to gather a sum value to return the total cost of the pizza object to the user." 
>
>Code: pizzaJS = new Pizza();
>
>Expected Output: {total cost}
# #########################










































<!-- ------------------------------------------------------------------- -->
<!-- <!-- 
# Rules/Baseline:
* Allow user to choose TOPPINGS and SIZE for pizza order
 * Creat a pizza OBJECT CONSTRUCTOR with PROPERTIES for TOPPINGS and SIZE.
 * Create a PROTOTYPE METHOD for the COST of a pizza depending on SELECTION chosen.
 * Use own formula for this.
 * FORMAT README!
 * SIMPLEST BEHAVIOR TO MOST COMPLEX
# #####################
<!-- #ALL IN ONE FUNCTION???? -->
<!-- special mold to create 'new' objects(instance) -->
<!-- this is your constructor(shell) -->
<!-- Describe: Pizza()
Test: "It should create a Pizza object from the constructor with empty properties for foundational purposes." 
Code: Pizza()
Expected Output: {Pizza} -->
<!-- # #################### -->

<!-- VIS:menu/user walk-in maybe?  -->
<!-- OBJECT -->
<!-- Describe: Pizza()
Test: "It should return the pizza object with the properties titled 'sizes', and 'toppings' for the pizza object."
Code: pizzaJS = new Pizza();
Expected Output: {Pizza(); with properties(sizes, toppings)} -->


<!-- 
function Pizza(){
  this.sizes = ?;
  this.toppings = ?;
} -->


<!-- User deciding size of pizza..determine sizes..??? -->
<!-- What determines sizes...small/med/lrg??...NOTE: FORMULA FOR COST FOR PIZZA/TOPPINGS  -->
<!-- NOTE: SIZE properties(User size choice) above in first test -->
<!--##VIS: USER PICK SIZE## -->
<!-- "PROTOTYPE" PROPERTY -->
<!-- Describe: Pizza.prototype.pickSizes(sizes)
Test: "It should add a method  
Code: pizzaJS.pickSize();
Expected Output: {sizes:[]} -->

<!-- ADD ARRAY??????  -->
<!-- NOTE: GETTING BACK USERS CHOICE OF PIZZA 'SIZE' AND TOPPING... -->
<!-- ##VIS: USER ADD TOPPINGS -->
<!-- "PROTOTYPE" PROPERTY -->
<!-- Describe: Pizza.prototype.addToppings(menuChoices)
Test: "It should add an array to the object pizza"
Code: pizzaJS.addToppings(["ExtraCheese"];)
Expected Output: {toppings:[]} -->

<!-- USE A FORMULA...REMEMBER 'NUMBERS/PARSING' -->
<!-- ##VIS: USER GETS TOTAL COST -->
<!-- "PROTOTYPE" PROPERTY -->
<!-- Describe: Pizza.prototype.totalCost();
Test: "It should use formula and return the total cost of the pizza object for the user."
Code:pizzaJS = new Pizza();
Expected Output: {total cost} -->
<!-- BASELINE ^^^^^^^^^^^^^^ ??? -->

<!-- Describe: Pizza
Test: 
Code:
Expected Output:

Describe: Pizza
Test: 
Code:
Expected Output: -->

<!-- NOTES:------------------------------------------------------------------ -->

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
<!-- 

/* mdn webs docs reference
    #Object.keys()#
    const object1 = {
      a:'something',
      b: 42,
      c: false
    };
    console.log(Object.keys(object1));
    //expected output: Array ["a","b","c"]
    "new" keyword 
*/ -->


<!--
-How many toppings/choices?

-How many sizes? Small..Med...Large 

-How much is each pizza? Per Size/Topping..?? ##COST FORMULA##
(Pizza.prototype.price <----------- ????)
(Price vs. Size)...numerical value(parse)..

###################^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
################...Toppings SAME PRICE FOR EASE!!!


##Literal Notation####

-










 -->
