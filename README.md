# Odin Recipes
This **Odin Recipes** website showcases the recipes of five of the various types of sandwiches relished across the world. 
Clicking on each food item in the homepage directs you to the recipe which shows you the image of the sandwich you'll be making with a short description. And of course the ingredients required and the steps to make the sandwich!!

Here is the [Live preview](https://velomorphis.github.io/odin-recipes/)

## Revelations
- Newline between `inline` elements create an empty space
- Images take 4px extra space at the bottom. Seems this is the case to accomodate descenders. To fix this there are several ways: Change display mode to `block`, Set the containing parent `line-height: 0` or `font-size: 0`
- `inline` elements don't support the horizontal center alignment with `margin: 0 auto;`. It only works on `block` elements with a **specified** width
- Margin collapsing applies only for vertical margins, not horizontal margins