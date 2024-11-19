---
layout: default
title: Analysis
number: 2
---

# Analysis

## ANALYSIS 1: Women’s Role on the Homefront - Louise Price

## ANALYSIS 2: Homefront Economics - Katya Palma

## ANALYSIS 3: Homefront and Race relations / Civil Rights -  Noah Senzer

## ANALYSIS 4: Homefront and Culture - Samantha Kinggard




# Embedding a Single Image

{% assign media = site.media_metadata | where_exp: "item", "item.name == 'PrussianInfantryHohenfriedberg'" %}
{% include media.html pages=media %}

# Embedding a Single Video
{% assign media = site.media_metadata | where_exp: "item", "item.name == 'RiseOfPrussia'" %}
{% include media.html pages=media %}

({% assign media = site.media_metadata | where_exp: "item", "item.name == 'Womenandplane'" %}
{% include media.html pages=media %}!=250x250)

# Linking to a PDF File

[Download PDF file]({{ site.baseurl }}/media_files/pdfs/newspaper1942.pdf)

Voilà! Вуаля! שלום עולם! Ça va?
Ut scelerisque ultrices orci, nec egestas sem. Cras feugiat nulla eget efficitur tempus. Morbi at pulvinar odio. Duis tempus neque in efficitur iaculis. Nullam ornare erat ut elit convallis consectetur. Integer a pulvinar dolor. Interdum et malesuada fames ac ante ipsum primis in faucibus. Morbi semper mattis odio ac volutpat.[^3] Suspendisse placerat rhoncus ligula, in pretium turpis aliquam nec. Curabitur gravida pretium mauris, in vulputate mauris tristique in. Suspendisse id facilisis sem, et dapibus tortor. Sed nisl metus, commodo ornare tortor non, aliquam suscipit arcu.[^2]

Curabitur sed feugiat elit. Donec feugiat nisi volutpat magna venenatis volutpat. Fusce efficitur sapien dignissim, pretium dolor sit amet, placerat lectus. Quisque enim est, viverra ut sem id, eleifend imperdiet ipsum. Pellentesque imperdiet pretium dui, eu sodales quam iaculis id. Fusce tristique convallis hendrerit. Suspendisse id mauris est. Etiam accumsan nisl vel neque porttitor, nec finibus est vehicula. Aliquam quam sem, rutrum elementum tincidunt non, ultricies a urna. Sed commodo, magna sed dictum malesuada, nulla ligula efficitur nisl, sed condimentum mauris nisl non purus. Sed pulvinar maximus fringilla. Sed scelerisque imperdiet volutpat. Praesent ligula nisl, venenatis finibus pharetra at, luctus id neque. Proin a efficitur ex. Donec vitae enim quis arcu ullamcorper molestie.

[^1]: First example footnote. View other pages to see sample methods of working with Markdown.
[^2]: I copied this text from this [website](https://www.lipsum.com/feed/html) 
[^3]: Testing

