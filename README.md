# ShopifySwatchColorCollection
A simple snippet for swatch color (like swatch.liquid on product.liquid) for collection.liquid.

Demo : https://dealerdesourire.com/collections/tshirts

# USAGE
X-Create snippet 'SwatchColorCollection.liquid'

X-Include in product-loop.liquid or product-grid or equivalent (depend on theme) the SwatchColorCollecion snippet.

X-Replace on the line {% if option == 'Color'... by the name of the attribute you want (color, couleur or other attribute like size)...

X-Assign at your main image in your product-loop snippet the id 'img-{{ product-id }}'

# OPTION
colortab is an array of your color's name in shopify admin

codcolortab is an array of color display in the swatch


And Voila..
