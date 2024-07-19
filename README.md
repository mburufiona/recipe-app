# Wk3-Code-Challenge
## Recipe-app
## Description
This recipe app is a web application that allows users to search for different types of recipes, which they can also access video references.
## Introduction
This project is developed to help the user scheme through different recipes and one can search there preferred recipe.
### Features
- 
### Installation
To run this project locally, follow these steps:

1. #### Clone the repository:

```bash
git clone 
cd Recipe-app
```

2. #### Set up JSON Server:

Ensure you have JSON Server installed. If not, install it using npm:

```bash
npm install -g json-server
```

3. #### Create a db.json file:

Use the provided JSON structure or the one from the example in the project instructions:

```{
  "meals": [
    {
      "id": "1",
      "foodname": "Beef Burger",
      "ingredients": ["750g Beef Mince","1 cup of fresh breadcrumbs", "1 onion, grated", "25g of chopped parsley leaves", "2 garlic cloves, crushed", "1 egg, whisked", "6 hamburger buns, halved", "150g cheddar cheese, thinly sliced", "2 tbsp olive oil", "80ml of mustard (optional)", "6 lettuce leaves", "3 large tomatoes, sliced", "1 tbsp worcestershire sauce", "tomato sauce, to serve"], 
      "Directions": "Place the beef, breadcrumbs, onions, parsley, egg, garlic and worcestershire sauce in a large bowl. Mix them together. Divide the mixture into 6 equal portions. Shape them into a patty.Place the patties on a tray, cover with plastic wrap and place i the fridge for at least 30 minutes to rest. Heat the patties on a large non-stick frying pan over medium heat using 1 tbsp of olive oil. Cook the patties for about 4 minutes on each side  ot until cooked through. Preheat the grill on high. line a baking tray with foil. Place the buns, cut side up, under the grill and toast for one minute. Leave the grill on. Place the patties on prepared tray. Top patties with cheddar and place under grill until cheddar is melted. Spread the bottom halves of toasted buns with mustard, top with lettuce, tomato and patties. Dollop with tomato sauce. Cover with the hamburger bun tops to serve.",
      "video-reference": "https://youtu.be/HePdhcxLOUU",
      "food img": "https://img.taste.com.au/sdEnTKyA/taste/2016/11/basic-beef-burger-image1-198145-1.jpg"
    },
    {
      "id": "2",
      "foodname": "Chicken curry",
      "ingredients": ["2 tbsp sunflower oil", "1 onion, thinly sliced", "2 garlic cloves, crushed", "large piece of ginger, grated", "6 chicken thighs, boneless and skinless", "3 tbsp medium spice paste (tikka works well)", "400g can of chopped tomatoes", "100g Greek yoghurt", "1 small bunch of chopped coriander leaves", "50g ground almonds", "naan breads or cooked basmati rice, to serve"],
      "Directions": "Heat the oil in a casserole dish or large frying pan over a medium heat. Add the onion and a generous pinch of salt and fry until onion has turned golden brown and sticker. Add the garlic and ginger, cooking for a further minute. Chop the chicken into chunky 3cm pieces, add to the pan and fry for 5 mins before stirring through the spice paste and tomatoes, along with 250ml water. Bring to the boil, lower to a simmer and cook on a gentle heat uncovered for 25-30 mins or until rich and slightly reduced. Stir though the yogurt, coriander and ground almonds, season and serve with warm naan or fluffy basmati rice.",
      "video-reference": "https://youtu.be/WRYOVVexMhU",
      "food img": "https://images.immediate.co.uk/production/volatile/sites/30/2020/08/easy-chicken-curry-aa22a0b.jpg?quality=90&webp=true&resize=300,272"
    },
  ]}
```
4. #### Run the JSON server:

Start the server by running the following command in the project directory:

```bash
json-server db.json 
```

5. #### Open the HTML file:

Open index.html in your web browser to view the application.

#### Usage
1. Views Recipes:
- Upon loading the page, a form will be displayed that the user will use to submit the value of the recipe.
2. Input a recipe
- Once the page loads, a form will be displayed, here you can input a recipe you want to view.
3. view an image, and reference video:
-you can view the image and the reference video, in-order to get visual instructions.
### File Structure

```bash
/recipe-app
│
├── index.html          # Main HTML file
├── style.css           # CSS file for styling
└── script.js           # JavaScript file containing the logic
```



### Contributing
Contributions are welcome! If you have suggestions for improvements or features, please feel free to create a pull request or open an issue.

### AUTHOR
[Fiona Nduta](https://github.com/mburufiona)
This project is open-source and available under the MIT License.

### deployed backend link
