# README

... existing content ...

## How to Add New Recipes via Pull Request

1. **Fork the Repository**: Click on the `Fork` button at the top right corner of the repository page to create a personal copy of the repository.

2. **Clone Your Fork**: Use the following command to clone your forked repository to your local machine:
   
   ```bash
   git clone https://github.com/your-username/recipe-io.git
   cd recipe-io
   ```

3. **Create a New Branch**: Before making changes, create a new branch:
   
   ```bash
   git checkout -b add-recipe-name
   ```

4. **Edit the `recipes.json` File**: Open the `recipes.json` file in your preferred text editor and add your new recipe following the JSON format below:

   ```json
   {
     "title": "Recipe Name",
     "time": "30–40 min",
     "servings": "2",
     "ingredients": [
       "ingredient 1 with quantity",
       "ingredient 2 with quantity",
       "ingredient 3 with quantity"
     ],
     "instructions": [
       "Step 1 description",
       "Step 2 description",
       "Step 3 description"
     ]
   }
   ```

5. **Commit Your Changes**: After editing, save your changes and commit them:
   
   ```bash
   git add recipes.json
   git commit -m "Add new recipe: Recipe Name"
   ```

6. **Push Your Changes**: Push the changes back to your fork:
   
   ```bash
   git push origin add-recipe-name
   ```

7. **Create a Pull Request**: Go to the original repository on GitHub and click on the `Pull Requests` tab. Click on `New Pull Request` and select your branch. Fill out the necessary details and submit the pull request.

Thank you for contributing!