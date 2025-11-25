# Food Calorie Calculator

## Overview
This is a simple, interactive Python program that calculates the total calorie intake of a meal based on foods and quantities entered by the user. It is designed as a lightweight command-line tool for quick calorie estimation using a predefined list of common food items with calorie values. This can be useful for diet tracking, nutrition education, or basic meal planning.

## Features
- Interactive input of multiple food items and quantities
- Supports input in grams or units/pieces for flexibility
- Real-time calculation and display of calories per item and cumulative total
- Preloaded food calorie data for common foods, easily extendable
- Clear meal summary output

## Technology Stack
- Python 3.x
- Standard Python libraries (no external dependencies)

## How to Use
1. Run the https://github.com/hs0676711-cloud/Simple-Food-Calorie-Counter/blob/main/simple%20food%20calorie%20counter.ipynb script in a Python environment.
2. The program will display the list of available food items with their calorie information.
3. Enter the name of a food item from the list.
4. Specify whether the amount is by weight (grams) or by unit/piece.
5. Enter the quantity.
6. Repeat for each additional food item.
7. When finished, type `done` to see the calorie summary of the meal.

Example session snippet:
Enter food name (or 'done'): rice
Enter 'g' for grams or 'u' for unit/piece: g
Enter amount in grams: 150
Added 195.0 kcal. Current total: 195.0 kcal

Enter food name (or 'done'): egg
Enter 'g' for grams or 'u' for unit/piece: u
Enter number of units/pieces: 2
Added 156.0 kcal. Current total: 351.0 kcal

Enter food name (or 'done'): done

------ MEAL SUMMARY ------
rice - 150g : 195.0 kcal
egg - 2unit : 156.0 kcal

Total meal calories: 351.0 kcal
## Food Items Included
- Rice (cooked, per 100g)
- Roti (per medium chapati)
- Dal (cooked lentils)
- Chicken (boiled breast)
- Egg (per piece)
- Milk (per 100 ml)
- Banana (per medium piece)
- Apple (per 100g)
- Bread (per slice)
- Paneer (per 100g)

## Extending the Project
- Add more foods with accurate calorie counts (refer to trusted nutrition databases or charts)
- Modify the program to read food data from external JSON or CSV files
- Implement nutritional breakdown (protein, fat, carbohydrate) alongside calories
- Develop a graphical or web-based interface for easier use
- Add meal saving/loading functionality

## Contribution Guidelines
Feel free to fork and submit pull requests if you'd like to add features, fix bugs, or improve documentation.

## License
This project is open-source and free to use.

## Author
Himanshu Singh

---

For any questions or support, contact Himanshu Singh via GitHub or email.

