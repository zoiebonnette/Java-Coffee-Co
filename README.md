# Java-Coffee-Co
Coffee ordering system for CS160 Lab final project

Coffee.java is an interface that includes the methods addTopping, Cost, and printCoffee.

CoffeeDecorator.java implements Coffee.java and declares the constructor Coffee coffee and has four methods CoffeeDecorator, addTopping, printCoffee, and Cost.

BasicCoffee.java implemens Coffee.java and has three methods addTopping, printCoffee, and Cost. 

BlackCoffee.java extends CoffeeDecorator.java and has five methods BlackCoffee, printCoffee, addTopping, instructions, and Cost.

Milk.java, HotWater.java, Espresso.java, Sugar.java, and WhippedCream.java all extend CoffeeDecorator.java and all have four methods:

-Each include their own respective Milk(Coffee coffee), HotWater(Coffee coffee), etc. method that creates a coffee object with the respective topping. 
  
-The second method each has is a printCoffee method that prints "Black coffee with milk", "Black coffee with hot water", etc. that is called in Main.java.
    
-The third method is addTopping which takes in a coffee and adds the respective topping to the existing coffee
  
-The fourth method is the Cost method, that holds the cost for each topping and adds it to the existing cost of the coffee
