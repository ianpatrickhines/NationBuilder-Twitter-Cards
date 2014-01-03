#NationBuilder Twitter Cards (Version 1.0)
Created by Ian Patrick Hines

*January 3, 2014*

Original: [ianpatrickhines.com](http://ianpatrickhines.com)

License: The MIT License (MIT) (See [LICENSE.markdown](https://github.com/ianpatrickhines/NationBuilder-Twitter-Cards/blob/master/LICENSE.markdown))

**NationBuilder Twitter Cards** is a liquid partial template for NationBuilder website themes that enables them to dynamically support [Twitter Cards](https://dev.twitter.com/docs/cards). 

![Example Twitter Card](http://via.ianhin.es/mMWA+)

To add this functionality to your custom theme:

1. Download the `_twitter_card.html` file in this repository and add it to your NationBuilder theme.

2. Add `{% include "twitter_cards" %}` in the `<head>` section of your `_layout.html` template.

3. Save & Publish the changes to your theme.

4. Visit [Twitter's Card Documentation](https://dev.twitter.com/docs/cards/validation/validator) and apply for approval to display Twitter cards for your site. 

5. Tweet links from your site and see awesome, beautifully formatted Twitter cards.

*Note: Twitter cards will only display for pages for which you have explicitly set an "Excerpt" in your page's SEO settings. [To learn more about how to configure your page's SEO settings in NationBuilder, read this FAQ](http://nationbuilder.com/how_do_i_change_the_excerpt_shown_on_facebook_for_my_pages).