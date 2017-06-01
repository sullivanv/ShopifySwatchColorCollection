# ShopifySwatchColorCollection
A simple snippet for swatch color (like swatch.liquid on product.liquid) for collection.liquid.

# USAGE
create a snippet SwatchColorCollection
include in product-loop.liquid or equivalent
replace on the line {% if option == 'Color'... by the name of the attribute you want (color, couleur or other like size)...
Assign at your main image in your product-loop snippet the id 'img-{{ product-id }}'

# OPTION
colortab is an array of your color's name in shopify admin
codcolortab is an array of color display in the swatch

And Voila..
