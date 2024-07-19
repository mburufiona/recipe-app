# Wk3-Code-Challenge
## Recipe-app
## Description
This recipe app is a web application that allows users to search for different types of recipes, which they can also access video references.
## Introduction
This project is developed to help the user scheme through different recipes and one can search there preferred recipe.
### Features
- It has a db.json, which has only 10 objects 
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

A db.json file was created with only 10 objects as shown below:

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
     {
      "id": "3",
      "foodname": "pizza",
      "ingredients": ["300g strong white bread flour, plus extra for dusting", "1 tsp instant yeast", "1 tbsp olive oil", "1 tbsp olive oil, plus a drizzle", "2 garlic cloves, crushed", "200ml passata", "8 mozzarella pearls, halved", "small bunch fresh basil"],
      "Directions": "Tip the flour into a bowl, then stir in the yeast and 1 tsp salt. Make a well in the centre and pour in 200ml warm water (make sure it’s not too hot) along with the oil. Stir together with a wooden spoon until you have a soft, fairly wet dough. Tip the dough out onto a lightly floured surface and knead for 5 mins until smooth. Cover with a tea towel and set aside for an hour or so or until the dough has puffed up and doubled in size. You can also leave the rough, unkneaded dough in the bowl, cover with a tea towel and leave in the fridge overnight and the dough will continue to prove on its own. Meanwhile, make the tomato sauce. Put the oil in a small pan and fry the garlic briefly (don’t let it brown), then add the passata and simmer everything until the sauce thickens a little. Leave to cool. Once the dough has risen, knead it quickly in the bowl to knock it back, then tip out onto a lightly floured surface and cut into two balls. Roll out each ball into a large teardrop that is very thin and about 25cm across (teardrop shapes fit baking sheets more easily than rounds). Heat oven to 240C/220C fan/ gas 9 with a large baking sheet inside. Lift one of the bases onto another floured baking sheet. Smooth the sauce over the base with the back of a spoon, scatter over half the mozzarella, drizzle with olive oil and season. Put the pizza, still on its baking sheet, on top of the hot sheet in the oven and bake for 8-10 mins until crisp.",
      "video-reference": "https://youtu.be/12JNRq7e648",
      "food_img": "https://cdn.loveandlemons.com/wp-content/uploads/2023/02/vegetarian-pizza-500x500.jpg"
    },
    {
      "id": "4",
      "foodname": "Chocolate Chip Cookies",
      "ingredients": ["3 tablespoons butter, very soft or partially melted", "3 tablespoons packed brown sugar", "1 1/2 tablespoons white sugar", "1 egg yolk", "1/4 teaspoon vanilla", "1/3 cup + 2 tablespoons all-purpose flour", "1 teaspoon cornstarch", "1/4 teaspoon baking soda", "1/4 teaspoon kosher salt", "1/4 cup chocolate chips"],
      "Directions": "Preheat the oven to 350 degrees. Mix butter, sugars, vanilla, and egg yolk until combined. Roll the dough into two balls and place on a baking sheet – there should be plenty for two large cookies plus a little bit of dough for a snack. (You’re welcome.) You can add more chocolate chips to the top of the cookies if you want. Bake for 10-12 minutes, depending on your oven temp and desired level of gooey cookie center. Rest the cookies for a few minutes so they settle down and solidify a bit –  I set a timer for 10-15 minutes and just let them rest right on the pan. At that point they should be able to transfer to a plate, or maybe even held in your hand, for warm, delicious eating on the couch. Yum, yum, yum.",
      "video-reference": "https://youtu.be/82CXvUiHs7A",
      "food_img": "https://handletheheat.com/wp-content/uploads/2023/06/peanut-butter-chocolate-chip-cookies-SQUARE-500x375.jpg"
    },
    {
      "id": "5",
      "foodname": "Tomato Soup",
      "ingredients": ["two 28-ounce cans tomatoes (whole or crushed will work – I usually use whole tomatoes.)", "1 stick (8 tablespoons) salted butter", "1 yellow onion, peel removed and cut into 4 chunks", "4 cloves smashed garlic (optional)", "1 1/2 teaspoons salt"],
      "Directions": "Make the Tomato Soup: Put the tomatoes, butter, and onion in a large saucepan or Dutch oven. Bring it up to a low bubble, then turn the heat to medium low. Cover partially with a lid; let it simmer for 45 minutes. Stir every 15 minutes or so to prevent scorching on the bottom. Remove Onion Chunks: Remove the onion pieces using tongs. I leave the garlic in there, but that’s up to you! Blend the Tomato Soup: Using an immersion blender, blend up the soup until it’s a smooth as you want it. Taste and adjust; you can thin it out with milk, water, broth, cream, whatever you want; I just leave it as-is! Serve: Serve tomato soup with garlic bread, grilled cheese, croutons, crackers, pesto, whatever you like! ",
      "video-reference": "https://youtu.be/szjZ3vqwyXE",
      "food_img": "https://cafedelites.com/wp-content/uploads/2016/03/Roasted-Tomato-Basil-Soup-12-1-500x500.jpg"
    },
    {
      "id": "6",
      "foodname": "Chicken noodle soup",
      "ingredients": ["Extra-virgin olive oil", "onion", "celery", "carrots", "garlic", "chicken stock", "bay leaves", "shredded chicken breast", "egg noodles", "Parsley", "Salt", "Black pepper"],
      "Directions": "Slice and dice. A great chefs knife and a good cutting board are your friend. Start your soup engines! Like with all the best soup recipes, in a large (6 quart) soup pot or Dutch oven, heat the butter or olive oil. Cook the onion, celery and carrots until the onions are translucent for a few minutes and then add garlic. Broth-ify. Pour in the stock and bay leaves, and get that gorgeous simmering for about 10 minutes. Soup-ify. Add the chicken, egg noodles, parsley, salt and pepper. Simmer until the noodles are cooked. Want to give your chicken soup even more flavor? You could add a squeeze of lemon juice, fresh dill, or more fresh parsley sprinkled on each bowl of soup.",
      "video-reference": "https://youtu.be/O2XXgo_u7b0",
      "food_img": "https://www.beyondthebayoublog.com/wp-content/uploads/2024/04/chicken-noodle-soup-recipe-500x375.png"
    },
    {
      "id": "7",
      "foodname": "Mahamri",
      "ingredients": ["3 cups plain flour all purpose flour", "1 tsp cardamom powder", "1 tsp dry active instant yeast", "half a cup of sugar", "a quarter cup of hot milk", "1 cup coconut milk thick", "2 tbsp ghee clarified butter or butter", "extra flour for dusting", "oil for deep frying"],
      "Directions": "Sieve flour into a big bowl and mix in the cardamom powder and sugar. Add the instant yeast and mix well. Add 1 tbsp ghee and rub it into the flour. Mix the hot milk and coconut milk. Using the milk mixture, form a soft dough. Using the remaining butter or ghee, knead the dough for 5 minutes till it becomes smooth. Lightly grease a bowl. Place the dough in it. Cover with cling film and let the dough rise for about 1½ - 2 hours. Fermenting time will depend on how cold or warm your place is. Sieve some flour onto baking sheets or trays sparingly. Knead the dough gently. Divide the dough into 8 parts. Roll each part into a ball. Roll out one ball into a 6  inch diameter circle, using some flour. Cut it into 4 parts using a sharp knife or a pizza cutter. Place the triangles onto the floured baking sheet or tray. Repeat with the remaining dough. Heat oil in a frying pan, wok or karai oer medium heat. Add a small piece of the dough into the hot oil. If it sizzles and comes up immediately then the oil is ready. When it is hot, place the triangles (3 to 4 at a time) in it gently and fry till they are golden brown. Remember not to fry them over high heat as they will brown quickly and the inside will remain raw. Remove the fried mahamri into a colander and repeat with the remaining triangles. Serve hot with any curry of your choice or some spicy tea or coffee.",
      "video-reference": "https://youtu.be/Gss2gQFQNvo",
      "food_img": "https://i0.wp.com/mayuris-jikoni.com/wp-content/uploads/2013/03/mahamri-2.jpg?resize=550%2C733&ssl=1"
    },
    {
      "id": "8",
      "foodname": "pilau",
      "ingredients": ["1/2 kg Basmati rice, washed ", "1/2 kg potatoes, peeled, washed and coarsely chopped", "1/2 kg beef, chicken or fish filet, cubed", "1 small cup sunflower oil (or any other liquid oil)", "4 cups of hot water or broth", "1 onion, chopped", "5 cloves of Garlic, crushed", "1 fresh Ginger, crushed", "2 fresh Tomatoes , sliced", "2-3 teaspoon Pilau spices", "Salt and pepper to taste"],
      "Directions": "Boil beef or chicken with ginger for 10 minutes. Add potatoes and let them boil for 5 minutes then set aside (separate the cooked ingredients from the broth so you can use it later) Heat oil and fry onions till light brown, add garlic and Pilau spices and on a low heat, fry for 1 minute. Add tomatoes meat/chicken with potatoes and cook till tender. Add rice and ensure to mix everything very well before adding your broth or hot water then stir the mixture very well. Add salt and pepper to taste then cover the pot and cook on medium heat. When the Food is nearly dry, lower down the heat to very low, cover your Pilau with aluminium paper (please avoid newspapers or polythene papers) and place the lid on top. Leave to cook for 10 minutes . *Here you are, your Pilau is ready! Serve your Pilau hot with Kachumbari and Pilipili ya Maembe.",
      "video-reference": "https://youtu.be/WznN_NYMQqU",
      "food_img": "https://cdn.foodaciously.com/static/recipe/9yyfV7NERqMagoV6Z0rU/kenyan-pilau-rice-2-3673b6aa500f620d8075c23c6bda3e4d-960-q60.jpg"
    },
    {
      "id": "9",
      "foodname": "Chapati",
      "ingredients": ["3 Cups all purpose flour sieved(Not measuring cups)", "2 Tablespoon Margarine(Optional)", "1 Tablespoon Sugar(Optional)", "1/2 Teaspoon salt", "1 1/2 Cups warm water", "Oil for cooking"],
      "Directions": "In a bowl, mix flour, sugar and salt. Add Margarine, mix with hands to form crumbs. I use a little bit of sugar in mine because I love the savoury taste. Omit it, if you don't like sugar. Make a well and pour water bit by bit as you knead. Knead for atleast 5 mins, if the dough is sticky, add flour bit by bit as you knead. Continue kneading on your work surface for another 3 mins. (FOR SOFT CHAPATIS, YOU SHOULD KNEAD THOROUGHLY) Finally dough should be firm but soft and not sticky. Cover with a damp cloth/ cling film/plastic polythene bag for 30 minutes. After 30mins, knead again and cut into balls. Roll out the balls in a circular shape with a rolling pin, one at a time and brush with oil. Fold them into balls. Cover them to keep them soft. Roll the balls out again forming the circle.(Layers should be visible on the rolled out dough). In a medium heat, place your skillet, let it warm up. Then put your chapati ontop. Fry both sides until brown. Once cooked remove and place it in a container and cover. Serve with your favorite stew or even tea. Enjoy.",
      "video-reference": "https://youtu.be/RHzRwUuf4Zk",
      "food_img": "https://www.indianhealthyrecipes.com/wp-content/uploads/2022/11/chapati-recipe-soft-500x500.jpg"
    },
    {
      "id": "10",
      "foodname": "Smocha",
      "ingredient-1": ["Smokies (As a smocha veteran, I recommend Farmer/s Choice brand)", "Soft Chapatis: Don/t use the flaky chapatis with layers as they/ll disintegrate whilst wrapping", "Kachumbari (salsa; tomato-onion salad )", "Your favorite sauces: choma sauce or BBQ(recommended), hot sauce, chili sauce, garlic sauce, ketchup, or tomato sauce"],
      "Directions": "Make chapatis from scratch if you are depressed or if you are so good at making them or if you just want quality control. Buy some from kibandasky if you’re lazy, broke, busy or a combination of those. Whatever your choice just ensure you keep your chapatis warm for easy rolling. A cloth kitchen towel does the trick. Prepare your smokies. For the love of god, if your smokies are frozen defrost them before cooking. I prepare mine by adding them to boiling water and letting them set till firm, plump, and springy. Then I proceed to grill them in a pan by brushing melted butter over them. Vegetable oil works as well. Cook while occasionally rolling them around for even cooking( I roll mine continuously on medium heat). Once they’re slightly browned I take them off the heat and dry the excess oil. Make Kachumbari salad: Don’t use overly ripe tomatoes, we want the crunch! I prefer using white onions to red onions because white are mild. Who wants that onion breathe? Dice both up thinly and add to a bowl. Add-ons; slices of chilies if you love the heat. Add lemon juice from half of a lemon, salt the mixture up, and add black pepper mix thoroughly and finish it off with a dash of olive oil for extra flavor-All these add-ons are optional. Use whatever you got. Slit your smokies longitudinally about half deep, don’t slice them completely into halves you hungry monster, just enough to form a hinge-like structure. Fill them up with the kachumbari….at this point, you’ll have made a smokie pasua. Lay your chapati down on a flat surface, and add your smokie pasua in the center. Here you can go extra crazy with the kachumbari addition, go as much as to cover your smokie. Add your sauces, tomato sauce, and chili sauce if you wanna be basic. If you wanna be fancy substitute tomato sauce for ketchup and chili sauce for hot sauce. Choma sauce (Barbecue Sauce) is the best sauce for this, but any sauce is acceptable. The only limitation is your imagination. Now folding time, you’ll hate yourself here if your chapatis are small. It’s good to go with larger chapatis for better real estate and ease of wrapping. Wrap like a burrito and it results to clean wraps with no leaks and messes from dripping sauces. It is so simple, just fold opposite sides inwards, and once set roll the remaining sides. You roll one end while the other remains stationary. Done! You did it.",
      "video-reference": "https://youtu.be/br_WVfcJPwo",
      "food_img": "https://toasterding.com/wp-content/uploads/2024/05/image-66-500x500.jpeg"
    }

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
- Upon loading the page, The recipes will be displayed and a form  that the user will use to submit the name of the recipe the user would like filtered.
2. Input a recipe
Once the user inputs the name of the recipe among the ones displayed, the recipe of the submitted name will be displayed which will feature its name, ingredients, instructions on how meal will be prepared and video reference below it. 
### page reload
the app is yet to have a back button once the recipe will be filtered, but as for the moment, a reload of the page will return to its original display.
### File Structure

```bash
/recipe-app
│
├── index.html          # Main HTML file
├── style.css           # CSS file for styling
└── script.js           # JavaScript file containing the logic
|__ db.json             # reads data from a server for web app
```



### Contributing
Contributions are welcome! If you have suggestions for improvements or features, please feel free to create a pull request or open an issue.

### AUTHOR
[Fiona Nduta](https://github.com/mburufiona)
This project is open-source and available under the MIT License.

### deployed backend link
[LINK](https://recipe-app-six-brown.vercel.app/)