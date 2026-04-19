# README


recipe-io

Food instructables and more for the busy-busy life

## Have you ever! 

Have you ever buried your face in your hands in the middle of the supermarket wondering why are you there, what life desicions took you to this extrange place, to buy food, food that you like, food that you don't like, and food you just don't give a f#ck. The primitive man used to hunt the food, to chase the food, to take only what is needed, and bring it back as trophy of glory. Modern men just go to the supermarket as the edge point of a global supply chain. The primitive man, used to to knows the ways to hunt, the modern man got lost in the supermarket which is mostly saturated with useless crap and sugary fashion... Back in modern times... Grandmothers could store 30 days recipes in their brains, in the daemonic 
sense of totla connection with food... while the latest generations cannot remember a 10 items food list and the energy electrolytic wall shelft is growing as a reminder that Idiocracy is closer than what we expect. But not everything is lost yet, we can get back on track with the "recipe-io" or "recipio" to help you... 



## recipe-io (should be read as "recipe input output")

The ultimate food recipe interface to make your life easier. You load your recipes and it shows the instructions but also if you select more than one recipe you generate a global list of all the ingredients you need.

### recipe-io

Recipe-io is a cutting edge code that runs locally on your phone or PC. Just donwload and open a browser

- recipe.html
- recipe.json

## recipe.json

Is a file of recipes in json format. you can modify it and bring your own recipes (BYOR) l. 


## Contribute 

Create a MR with more recipes and we do a bigger list. 

## Explore

Put the code to any LLM, or do it your self, and start your spin-offs but don't forget to share or comment.

## LLM tips

- Plain JS
- No Dependencies
- Basic Accessibility
- Basic CCS
- If yoy are new, go for the theory of what a good UI should look like.

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
