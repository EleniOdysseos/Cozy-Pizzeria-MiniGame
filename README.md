# Cozy Pizzeria Game

A cozy pixel-art pizza building game developed in Java using Swing.  
The project was originally based on an object-oriented programming assignment and later expanded into a playable mini game with a graphical interface.

## Features

- Build pizzas based on customer orders
- Multiple pizza categories:
  - Vegetarian Pizza
  - Meat Lovers Pizza
  - Special Pizza
  - Custom Pizza
- Ingredient stock system
- Money / balance system
- Combo bonus for correct pizzas
- Win condition when reaching 100 EUR
- Order progression system
- Pixel-art inspired UI with custom graphics

## OOP Concepts Used

This project applies several object-oriented programming concepts:

- **Inheritance**  
  Pizza subclasses such as `VegetarianPizza`, `MeatLoversPizza`, `SpecialPizza`, and `CustomPizza`

- **Polymorphism**  
  Different pizza types override pricing behavior through `calculatePrice()`

- **Composition**  
  Each pizza contains `Ingredient` objects

- **Enums**  
  Used for pizza size, dough type, and ingredient type

- **Encapsulation**  
  Classes manage their own data through fields and methods

## Technologies

- Java
- Java Swing
- Object-Oriented Programming
- Custom pixel-art assets

## Project Structure

- `model/` → core OOP classes and pizza logic
- `ui/` → Swing interface and game panels
- `images/` → ingredient and pizza graphics

## Gameplay

The player must recreate the requested pizza by selecting:

- size
- dough type
- ingredients

If the pizza matches the customer order:
- the player earns money
- progress is made toward completing the order

If the pizza is incorrect:
- the player loses money

The game also includes:
- ingredient restocking
- score tracking
- combo bonuses
- a winning goal of reaching 100 EUR

## Why I Built This

This project started as a university Java OOP assignment about a pizzeria ordering system.  
I later expanded it into a visual mini game to improve its interface, make it more interactive, and turn it into a stronger portfolio project.

## Future Improvements

- improved animations
- more pizza types
- sound effects
- difficulty levels
- timer mode
- better responsive UI scaling

## Author

Created by Eleni
