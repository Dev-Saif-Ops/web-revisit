# Odin Recipes

Welcome to **Odin Recipes**! This project is a simple recipe website built using only HTML. It serves as a practice to solidify the HTML knowledge you have acquired. The website consists of a main index page that links to a few recipes.

## Table of Contents

- [Introduction](#introduction)
- [Setting Up Your Project’s GitHub Repository](#setting-up-your-projects-github-repository)
- [Assignment](#assignment)
  - [Iteration 1: Initial Structure](#iteration-1-initial-structure)
  - [Iteration 2: Recipe Page](#iteration-2-recipe-page)
  - [Iteration 3: Recipe Page Content](#iteration-3-recipe-page-content)
  - [Iteration 4: Add More Recipes](#iteration-4-add-more-recipes)
- [Viewing Your Project on the Web](#viewing-your-project-on-the-web)
- [Tips on When to Commit](#tips-on-when-to-commit)

## Introduction

It’s time to practice all of the HTML knowledge you have acquired. In this project, you are going to build a basic recipe website.

The website will consist of a main index page which will have links to a few recipes. The website won’t look very pretty by the time you’ve finished, unless you’re into brutalist web design, that is. But it’s important to keep in mind that this project is just to build your HTML chops; we will revisit this project in the future to style it up with CSS.

## Setting Up Your Project’s GitHub Repository

As mentioned in the Introduction to Git lesson, you’ll want to organize all your projects like a portfolio and link them to GitHub so it can be seen by others.

1. Create a new repository on GitHub.com and call it `odin-recipes` and choose the public option.
2. Clone that repository onto your local machine. The command should look like `git clone git@github.com:username/odin-recipes.git` (use SSH).
3. Navigate into the `odin-recipes` project directory on your local machine.
4. Set up your `README.md` file and write a brief introduction describing what the current project is and what skills you will have demonstrated once you have completed it.

## Assignment

### Iteration 1: Initial Structure

1. Within the `odin-recipes` directory, create an `index.html` file.
2. Fill it out with the usual boilerplate HTML and add an `<h1>` heading “Odin Recipes” to the body.

### Iteration 2: Recipe Page

1. Create a new directory within the `odin-recipes` directory and name it `recipes`.
2. Create a new HTML file within the `recipes` directory and name it after the recipe it will contain. For example, `lasagna.html`. You can use the name of your favorite dish or find a recipe to use at Allrecipes.
3. For now, just include an `<h1>` heading with the recipe’s name as its content.
4. Back in the `index.html` file, add a link to the recipe page you just created. Example: Under the `<h1>Odin Recipes</h1>` heading, write out the link like so: `<a href="recipes/recipename.html">Recipe Title</a>`. The text of the link should again be the recipe name.

### Iteration 3: Recipe Page Content

Your new recipe page should have the following content:

1. An image of the finished dish under the `<h1>` heading that you added earlier. You can find images of the dish on Google or Allrecipes.
2. Under the image, it should have an appropriately sized “Description” heading followed by a paragraph or two describing the recipe.
3. Under the description, add an “Ingredients” heading followed by an unordered list of the ingredients needed for the recipe.
4. Finally, under the ingredients list, add a “Steps” heading followed by an ordered list of the steps needed for making the dish.

### Iteration 4: Add More Recipes

1. Add two more recipes with identical page structures to the recipe page you’ve already created.
2. Don’t forget to link to the new recipes on the index page. Also, consider putting all the links in an unordered list so they aren’t all on one line. Example:
   ```html
   <ul>
     <li><a href="recipes/recipe1.html">Recipe Title 1</a></li>
     <li><a href="recipes/recipe2.html">Recipe Title 2</a></li>
     <li><a href="recipes/recipe3.html">Recipe Title 3</a></li>
   </ul>

## Viewing Your Project on the Web

If you want to show your work to others, you will need to publish your site so that others can access it from the web.

1. Make sure that the main HTML file of your project is called index.html.
2. Go to your GitHub repo on the web and click the Settings button.
3. Click on Pages on the left side bar.
4. Change the Branch from none to main branch and click Save.
5. It may take a few minutes (up to an hour) for your project to be accessible over the web from your-github-username.github.io/your-github-repo-name.

## Tips on When to Commit

Don’t forget everything we went over in the Commit Messages lesson!

When writing code, it’s considered best practice to commit early and often. Commit every time you have a meaningful change in the code. This will create a timeline of your progress and show that your finished code didn’t appear out of nowhere.

After you have entered git push origin main, switch over to your browser and open your repository on GitHub. You should now see all the files you just pushed.

Thank you for visiting Odin Recipes! Happy coding!


