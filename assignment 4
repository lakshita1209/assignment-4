#include <iostream>
#include <string>
#include <vector>

using namespace std;

// Function declarations
void displayRecipe(const vector<string> &ingredients, const vector<string> &steps);

int main()
{
    int choice;

    // Recipes for different meals
    vector<string> aaluParathaIngredients = {
        "2 cups whole wheat flour",
        "4-5 boiled potatoes (mashed)",
        "2 finely chopped green chilies",
        "1 teaspoon grated ginger",
        "1/2 teaspoon red chili powder",
        "1/2 teaspoon turmeric powder",
        "1 teaspoon garam masala",
        "Salt to taste",
        "2 tablespoons chopped coriander leaves",
        "Oil or ghee for frying"};

    vector<string> aaluParathaSteps = {
        "1. In a mixing bowl, combine whole wheat flour with enough water to knead into a soft dough. Let it rest for 15-20 minutes.",
        "2. In another bowl, mix mashed potatoes, green chilies, grated ginger, red chili powder, turmeric powder, garam masala, salt, and chopped coriander leaves to make the stuffing.",
        "3. Divide the dough into small balls and roll each ball into a small disc.",
        "4. Place a portion of the stuffing in the center of the disc, bring the edges together, and seal the edges to form a ball again.",
        "5. Roll the stuffed ball into a flat paratha using a rolling pin.",
        "6. Heat a tawa or skillet and cook the paratha on both sides until golden brown, applying oil or ghee as needed.",
        "7. Serve hot with yogurt, pickle, or chutney."};

    vector<string> anotherMealIngredients = {
        "1 cup rice",
        "2 cups water",
        "1 teaspoon salt",
        "Optional: Vegetables, chicken, or other additions"};

    vector<string> anotherMealSteps = {
        "1. Rinse the rice under cold water until the water runs clear.",
        "2. In a pot, bring 2 cups of water to a boil.",
        "3. Add rice and salt to the boiling water.",
        "4. Reduce heat to low, cover, and simmer for about 15-20 minutes or until rice is tender and water is absorbed.",
        "5. Optional: Add cooked vegetables or chicken for additional flavor."};

    while (true)
    {
        cout << "\nRecipe App\n";
        cout << "1. Aalu Ka Paratha\n";
        cout << "2. Simple Rice Meal\n";
        cout << "3. Exit\n";
        cout << "Enter your choice: ";
        cin >> choice;

        switch (choice)
        {
        case 1:
            cout << "\nIngredients for Aalu Ka Paratha:\n";
            displayRecipe(aaluParathaIngredients, {});
            cout << "\nSteps to make Aalu Ka Paratha:\n";
            displayRecipe({}, aaluParathaSteps);
            break;
        case 2:
            cout << "\nIngredients for Simple Rice Meal:\n";
            displayRecipe(anotherMealIngredients, {});
            cout << "\nSteps to make Simple Rice Meal:\n";
            displayRecipe({}, anotherMealSteps);
            break;
        case 3:
            cout << "Exiting...\n";
            return 0;
        default:
            cout << "Invalid choice. Please try again.\n";
        }
    }

    return 0;
}

void displayRecipe(const vector<string> &ingredients, const vector<string> &steps)
{
    for (const auto &item : ingredients)
    {
        cout << item << endl;
    }
    for (const auto &step : steps)
    {
        cout << step << endl;
    }
}