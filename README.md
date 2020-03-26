# Index
- [Index](#index)
- [Breakfasts](#breakfasts)
- [Lunch](#lunch)
  - [Curried Egg Salad](#curried-egg-salad)
- [Dinner](#dinner)
  - [Spicy Miso Soup with Roasted Cabbage and 5 Spice Lamb Shoulder](#spicy-miso-soup-with-roasted-cabbage-and-5-spice-lamb-shoulder)
    - [Ingredients](#ingredients)
    - [Directions:](#directions)
- [Dessert](#dessert)
- [Drinks](#drinks)

**Featured Dinner:** <a id="featured"></a>

# Breakfasts

# Lunch

## Curried Egg Salad

# Dinner

## Spicy Miso Soup with Roasted Cabbage and 5 Spice Lamb Shoulder
### Ingredients
For The Soup:
* 1/2 C White Miso Paste
* 2 Cloves Garlic, Roughly Chopped
* A Thumb Sized Piece of Ginger, Roughly Chopped
* 1 TBSP Of Sichuan Peppercorns
* 4 Cup Chicken Stock
* Spicy Pepper Paste (optional)
* Head of Napa Cabbage
* Scallions, green and dark green tops removed
* Sesame Oil

For The Lamb:
* 1LB Lamb Shoulder (Bone-in) cut into a steak
* Salt, Pepper, Chinese 5 Spice

### Directions:
1. Generously season the lamb on all sides with salt, pepper, and 5 spice. Leave in fridge uncovered to dry out
2. Cut napa cabbage into wide strips and lay out on a baking sheet. Roast under the broiler on LOW, turning and tossing as the top layer becomes brown. Remove from broiler when browned all over and starting to become tender.
3. Roast scallions under broiler until they begin to char. Flipping to char each side. Remove and roughly chop when cool.
4. Heat enough oil to coat bottom of pot on medium heat. When oil is shimmering, toss in garlic, ginger, and sichuan peppercorns. Stirring / Tossing until fragrant or until the garlic turns golden (about 2 minutes - 3 minutes).
5. Add miso paste and chili paste if using and stir until fragrant, about 1 minute.
6. Add enough stock to deglaze bottom of pan, scraping up any brown bits.
7. Add cabbage and scallions along with the rest of the stock. Bring to a simmer.
8. Preheat oven to 275. When preheated, add lamb chop. Bake until internal temp is about 115 (10-15 minutes).
9. Add a neutral oil to a cast iron pan (or similar) and heat over high heat until barely smoking. Add baked lamb chop and sear on both sides until a crust forms, about 1-2 minutes on each side.
10. Let rest and then slice into thin strips.
11. Fill bowls with soup, lay strips of lamb on top, and then top with light amount of sesame oil to taste.

# Dessert

# Drinks

<script>
    var featuredLink = document.getElementById('featured');
    var allRecipes = document.getElementsByTagName("h2");
    var randomIndex = Math.floor(Math.random() * allRecipes.length);
    var heading = allRecipes[randomIndex];
    var link = '#' + heading.innerText.replace(/ /g, "-").toLowerCase()

    featuredLink.href = link;
    featuredLink.innerHTML = heading.innerText;
    featuredLink.title = link;
</script>