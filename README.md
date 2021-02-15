# Crawler Test

Build a website crawler that generates a sitemap for https://www.matchesfashion.com/womens. The sitemap should include the first level link (i.e. https://www.matchesfashion.com/womens), and the second and third level links:

First level link:
- `https//www.matchesfashion.com/womens`

Second level link examples:
- Just In: `https://www.matchesfashion.com/womens/just-in/just-in-this-month`
- Designers: `https://www.matchesfashion.com/womens/designers`

Third level link examples:
- Just in / Accessories: `https://www.matchesfashion.com/womens/just-in/just-in-this-month/accessories`
- Designers / 16Arlington: `https://www.matchesfashion.com/womens/designers/sixteen-arlington`
- Stories / Fashion: `https://www.matchesfashion.com/womens/stories/categories/fashion`

You will need to add a `user-agent` to your crawler.
