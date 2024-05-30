# Recipe Application



## Description

The Recipe Application is a console-based program that allows users to manage recipes by adding ingredients, scaling ingredient quantities, and calculating total calories. Users can view a list of all recipes, choose a specific recipe to display, and clear recipe data. The program also notifies users when the total calories of a recipe exceed 300.

### Changes Based on Lecturer's Feedback

Based on the lecturer’s feedback, several modifications were made to enhance the functionality of the Recipe Application:
1. **Fixed Total Calories Notification**: The notification for exceeding 300 calories was moved from individual ingredients to the total calories of the entire recipe.
2. **Implemented Clear Method**: The `Clear` method in the `Recipe` class was implemented to properly reset the recipe data.
3. **Enhanced Ingredient and Step Entry**: Modified the ingredient and step entry in the `AddNewRecipe` method to allow multiple entries until the user indicates they are done.

## Instructions to Compile and Run

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/RecipeApplication.git
   cd RecipeApplication
