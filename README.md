
# Python real-time parser

[*DOM RIA API documentation*](https://api-docs-v2.readthedocs.io/ru/latest/dom_ria/index.html)

## Aim

Write in Python a real-time parser for the site [dom.ria.com](https://dom.ria.com) - the section "long-term rent apartments, Kiev ". It is assumed that the parser should be able to constantly download fresh ads. Implement a site with a single page - search results by parsed content with pagination. Possible sorting - by "freshness" ads and for the price. Any issue page should be accessible via a direct link.

It is necessary to implement the following search form with such inputs and corresponding to them filters for issuing:

* admin. a district of the city
* number of rooms
* price from / to
* full-text search in the full text of the ad and its title (it is on page ad itself, for example. - "Long-term rental apartments, 2 com., Kiev, rn. Obolonsky, metro station Obolon, Obolonsky Avenue, house 1A ")

The announcement card in the issue must contain:

* short title (as issued on [dom.ria.com](https://dom.ria.com));
* abbreviated text
* number of rooms
* price
* admin a district of the city

Click on the title leads to the page on the source site.

### Technical limitations

1. Python;
2. any or even no frameworks;
3. run on hosting site;
4. GitHub;

## Links on realization

__Author__: [Maksym Halchenko](https://github.com/maxs-im)

__Repository__: [GitHub](https://github.com/maxs-im/LUN)

__Hosting__: [Heroku](https://lun---dom-ria.herokuapp.com/)
