# My Favorite Public GraphQL APIs

*This is just a fork of the graphql-kit repo for me to curate based on my personal interests. Check out the original for a more comprehensive list.*

If you are interested in GraphQL in general, check out [awesome-graphql](https://github.com/chentsulin/awesome-graphql).

## Official APIs

| API | Description | Graph*i*QL | Docs/Repo
| --- | ----------- | :--------: | :-: |
| Artsy | free online platform for collecting and discovering art | [Try it!](https://metaphysics-production.artsy.net/) | [Repo](https://github.com/artsy/metaphysics)
| Braintree | Payment platform | [Try it!](https://graphql.braintreepayments.com/explorer) | [Docs](https://graphql.braintreepayments.com/)
| Buildkite | Continuous integration and deployments | [Try it!](https://graphql.buildkite.com/) | [Docs](https://building.buildkite.com/tutorial-getting-started-with-graphql-queries-and-mutations-11211dfe5d64#.7uhjusw1q)
| Canopy | The missing GraphQL API for Amazon.com e-commerce | [Try it!](https://graphql.canopyapi.co/) | [Repo](https://github.com/canopy-api/canopy-api)<br> [Docs](https://docs.canopyapi.co/)         |
| Changetrip | The Chargetrip API gives you the ability to integrate smart, EV-specific routing into products built for electric car drivers. | [Try it!](https://playground.chargetrip.com/) | [Docs](https://developers.chargetrip.com/API-Reference/API/introduction)
| CommerceTools | e-commerce solutions | [Try it!](https://impex.commercetools.com/graphiql) | [Docs](https://docs.commercetools.com/graphql-api)
| Countries | Information about countries, continents, and languages, based on [Countries List](https://annexare.github.io/Countries/) | [Try it!](https://countries.trevorblades.com) | [Repo](https://github.com/trevorblades/countries)
| Countries v2 | Country related data like currencies, languages, flags, regions+subregions, bordering countries, distance to other countries and much more | [Try it!](https://countries-274616.ew.r.appspot.com/?query=query%20%7B%0A%09Country%20%7B%0A%20%20%20%20name%0A%20%20%20%20%23%20check%20the%20docs%20for%20more%20info%0A%20%20%7D%0A%7D%0A) | [Repo](https://github.com/lennertVanSever/graphcountries)
| EAN-Search | Search barcodes and products | [Try it!](https://api.ean-search.org/graphql) | [Docs](https://www.ean-search.org/blog/graphql-ean-api.html)
| EHRI | Holocaust-related archival materials | [Try it!](https://portal.ehri-project.eu/api/graphql/ui) | [Docs](https://portal.ehri-project.eu/api/graphql)
| FaunaDB | Serverless GraphQL Database | [Try it!](https://fauna.com/blog/try-faunadbs-graphql-api) | [Docs](https://docs.fauna.com/fauna/current/graphql)
| Gdom | DOM Traversing and Scraping using GraphQL | [Try it!](http://gdom.graphene-python.org/graphql?query=%7B%0A++page%28url%3A%22http%3A%2F%2Fnews.ycombinator.com%22%29+%7B%0A++++items%3A+query%28selector%3A%22tr.athing%22%29+%7B%0A++++++rank%3A+text%28selector%3A%22td+span.rank%22%29%0A++++++title%3A+text%28selector%3A%22td.title+a%22%29%0A++++++sitebit%3A+text%28selector%3A%22span.comhead+a%22%29%0A++++++url%3A+attr%28selector%3A%22td.title+a%22%2C+name%3A%22href%22%29%0A++++++attrs%3A+next+%7B%0A+++++++++score%3A+text%28selector%3A%22span.score%22%29%0A+++++++++user%3A+text%28selector%3A%22a%3Aeq%280%29%22%29%0A+++++++++comments%3A+text%28selector%3A%22a%3Aeq%282%29%22%29%0A++++++%7D%0A++++%7D%0A++%7D%0A%7D) | [Repo](https://github.com/syrusakbary/gdom)
| GitHub | Web-based Git repository hosting service | [Try it!](https://developer.github.com/v4/explorer/) | [Docs](https://docs.github.com/v4/)
| GitLab | Host-your-own Git repository hosting service | [Try it!](https://gitlab.com/-/graphql-explorer) | [Docs](https://docs.gitlab.com/ee/api/graphql/)
| GraphLoc  | Find a geolocation of an IP address including latitude, longitude, city, country, time zone and area code. Free to use, SSL supported | [Try it!](https://graphloc.com) | [Docs](https://www.graphloc.com)
| GraphQL Jobs | GraphQL jobs in modern startups | [Try it!](https://api.graphql.jobs) | [Docs](https://graphql.jobs/docs/api)|
| HIVDB | A curated database to represent, store and analyze HIV drug resistance data | [Try it!](https://hivdb.stanford.edu/page/graphiql/) | [Docs](https://hivdb.stanford.edu/page/webservice/)
| Idobata | Dedicated chat for team development. | [Try it!](https://idobata.io/api) | |
| leanIX | Tools for business strategy | | [Docs](https://dev.leanix.net/docs/graphql-api)
| Pipefy | The operations excellence platform. | [Try it!](https://app.pipefy.com/graphiql) | [Docs](https://developers.pipefy.com) |
| Mattermark | Business research and networking | | [Docs](https://developer.mattermark.com/docs/graphql)
| Memair | Quantified self / extended mind platform | [Try it!](https://memair.com/graphiql) | [Docs](https://docs.memair.com)
| React Finland | React Finland API is built with conferences and meetups in mind | [Try it!](https://api.react-finland.fi/graphql) | [Repo](https://github.com/ReactFinland/graphql-api)
| Saleor | Headless open-source E-commerce API for storefront and admin | [Try it!](https://demo.saleor.io/graphql/) | [Docs](https://docs.saleor.io/docs/3.x/developer/api-reference/)
| Shopify Storefront | The Storefront API gives you full creative control to build customized purchasing experiences for your customers. | [Try it!](https://help.shopify.com/api/storefront-graphiql) | [Docs](https://help.shopify.com/api/storefront-api)<br>[Examples](https://github.com/Shopify/storefront-api-examples)
| Shopify Admin | The Admin API is the primary way that apps and services interact with Shopify. | [Try it!](https://shopify-graphiql-app.shopifycloud.com/login) | [Docs](https://shopify.dev/docs/admin-api/graphql/reference)
| SWOP | GraphQL and REST foreign exchange rate API. Note: Required registration. | [Try it!](https://swop.cx/) | [Docs](https://swop.cx/documentation)
| Universe |  Check what your friends are doing & find unique events near you using our filter. | [Try it!](https://www.universe.com/graphiql) | [Docs](https://developers.universe.com/docs/graphql)
| Yelp  | User Reviews and Recommendations of Top Restaurants, Shopping, Nightlife, Entertainment, Services and More | [Try it!](https://www.yelp.com/developers/graphiql) | [Docs](https://www.yelp.com/developers/graphql/guides/intro)

## Unofficial API proxies

| API | Description | Graph*i*QL | Docs/Repo
| --- | ----------- | :--------: | :-: |
| Barcelona Urban Mobility API | Information about the different public transport / urban mobility services of Barcelona | [Try it!](https://barcelona-urban-mobility-graphql-api.netlify.app/graphql) | [Repo](https://github.com/aalises/barcelona-urban-mobility-graphql-api)
| Câmara dos deputados Brasil | "GraphQL api to grab the data from the brazilian deputies chamber" | [Try it!](https://graphql-camara-deputados.herokuapp.com/) | [Repo](https://github.com/matheusrocha89/graphql-camara-deputados)
| Ghibliql | "GhibliQL is a GraphQL wrapper to the Studio Ghibli REST API" | [Try it!](https://ghibliql.herokuapp.com/) | [Repo](https://github.com/kisscool-fr/ghibliql)
| Favware's GraphQL Pokémon | Query for all the Pokémon, and their abilities, moves, items, learnsets, and type matchups from generations 1 through 8. This API strives to always stay up-to-date with new Pokémon releases, and has multiple contributors to achieve this. | [Try it!](https://graphqlpokemon.favware.tech) | [Repo](https://github.com/favware/graphql-pokemon)|
| MetaMate | Semantic service bus example for HackerNews | [Try it!](https://metamate.io/blog/most-advanced-hackernews-api/) | [Repo](https://github.com/metamatex/metamate)<br>[Examples](https://showcase.metamate.io/hackernews-user-activity)
| MusicBrainz |  Open music encyclopedia that collects music metadata | [Try it!](https://graphbrainz.herokuapp.com/?query=query%20NirvanaAlbumSingles%20%7B%0A%20%20lookup%20%7B%0A%20%20%20%20artist(mbid%3A%20%225b11f4ce-a62d-471e-81fc-a69a8278c7da%22)%20%7B%0A%20%20%20%20%20%20name%0A%20%20%20%20%20%20releaseGroups(type%3A%20ALBUM)%20%7B%0A%20%20%20%20%20%20%20%20edges%20%7B%0A%20%20%20%20%20%20%20%20%20%20node%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20title%0A%20%20%20%20%20%20%20%20%20%20%20%20firstReleaseDate%0A%20%20%20%20%20%20%20%20%20%20%20%20relationships%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20releaseGroups(type%3A%20%22single%20from%22)%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20edges%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20node%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20target%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20...%20on%20ReleaseGroup%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20title%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20firstReleaseDate%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20%7D%0A%20%20%20%20%7D%0A%20%20%7D%0A%7D%0A&operationName=NirvanaAlbumSingles) | [Repo](https://github.com/exogen/graphbrainz)
| PokeAPI | Pokémon Data API | [Try it!](https://pokeapi-graphiql.herokuapp.com/) | [Repo](https://github.com/patrickshaughnessy/PokeAPI-GraphQL)
| Spacex Land | A non official platform for SpaceX's data! | [Try it!](https://api.spacex.land/graphql/) | [Docs](https://spacex.land/)
| Spotify | Spotify gives you instant access to millions of songs - from old favorites to the latest hits. | [Try it!](https://spotify-api-graphql-console.herokuapp.com/) | [Repo](https://github.com/thefrenchhouse/spotify-graphql)<br>[Examples](https://github.com/thefrenchhouse/spotify-graphql-examples)
| Stratz | Dota 2 Statistics Api | [Try it!](https://api.stratz.com/graphiql/) | [Site](https://stratz.com/welcome)
| SWAPI | Star Wars API | [Try it!](https://graphql.org/swapi-graphql/) | [Repo](https://github.com/graphql/swapi-graphql)
| Star-Wars-Api | A fully fledged Star Wars API. Using mostly the same data source as [swapi.dev](https://swapi.dev), but way faster (no Django overhead) and easier to query nested data. | [Try it!](https://swapi.skyra.pw) | [Repo](https://github.com/skyra-project/star-wars-api)
| TMDB | The Movie Database Wrapper | [Try it!](https://tmdb.apps.quintero.io/) | [Repo](https://github.com/nerdsupremacist/tmdb)


## Demonstration-only APIs

| API | Description | Graph*i*QL | Docs/Repo
| --- | ----------- | :--------: | :-: |
| A-Maze | [Enter the maze](https://maze.andreamazzarella.com), try to get out! | [Try it!](https://maze.andreamazzarella.com/graphiql) | [Repo](https://github.com/andreamazza89/amaze)|
| Lucas Bento's GraphQL Pokémon | Get information of a Pokémon with GraphQL! (**Note**: Only has data on Generation 1, and only has data on Pokémon!) | [Try it!](https://react-relay-pokemon.now.sh/#/) | [Repo](https://github.com/lucasbento/graphql-pokemon)<br>[ClientRepo](https://github.com/lucasbento/react-relay-pokemon)
| MongoDB Northwind demo | [Demo App](https://nodkz.github.io/relay-northwind/) build on top of [graphql-compose](https://github.com/nodkz/graphql-compose) and [mongoose](https://github.com/Automattic/mongoose) | [Try it!](https://graphql-compose.herokuapp.com/northwind/)<br>[Try Relay version!](https://nodkz.github.io/relay-northwind/) | [Docs](https://github.com/nodkz/graphql-compose)<br>[ServerRepo](https://github.com/nodkz/graphql-compose-examples)<br>[ClientRepo](https://github.com/nodkz/relay-northwind-app)
| MongoDB TODO-List | TODO List using GraphQL and MongoDb | [Try it!](https://todo-mongo-graphql-server.herokuapp.com/) | [Docs](https://www.compose.com/articles/using-graphql-with-mongodb/)<br>[Repo](https://github.com/igorlima/todo-mongo-graphql-server)
| Planets | Information about planets and exoplanets, including mass, radius, orbit, semimajor axis, and how it was discovered. | [Try it!](https://pristine-gadget-267405.appspot.com/graphql/) | [Repo](https://github.com/ZaneTurner/PlanetsAPI)
| Spotify GraphQL Server | This demonstrates how to build a GraphQL server which fetches data from an external API (Spotify) | [Try it!](https://spotify-graphql-server.herokuapp.com/) | [Repo](https://github.com/lowsky/spotify-graphql-server)
| UFC GraphQL Server | Public UFC API turned into a GraphQL server. It's hosted by [now.sh](https://now.sh/) then, sometimes, it gets freeze. | [Try it!](https://graphql-ufc-api.now.sh/) | [Repo](https://github.com/jgcmarins/graphql-ufc-api)
| Google directions API | GraphQL wrapper for google directions API. | [Try it!](https://directions-graphql.herokuapp.com/graphql) | [Repo](https://github.com/Arjun-sna/directions_graphql/)
| FakeQL | GraphQL API mocking as a service. | [Try it!](https://fakeql.com/) | [Docs](https://www.blowson.com/docs/)
| The Rick and Morty API | All the Rick and Morty information. | [Try it!](https://rickandmortyapi.com/graphql) | [Docs](https://rickandmortyapi.com/documentation/#graphql)
| UN SDG data series API | UN SDG statistical data served via GraphQL as JSON-LD objects mapped to RDF Data Cube Vocabulary | [Try it!](http://linkedsdg.apps.officialstatistics.org/graphql/) | [Code](https://code.officialstatistics.org/cslovell/sdg-docker-ontologies/tree/master/sdgapi)<br>[Docs](https://github.com/UNStats/LOD4Stats/wiki/SDG-series-as-RDF-Data-Cubes#querying-sdg-statistical-series-data-via-graphql)<br>[Blog post](https://medium.com/@sklarman/linked-open-statistical-data-served-simply-ead245bf715)
| Weather API | Retrieve the current weather for any given city | [Try it!](https://graphql-weather-api.herokuapp.com/) | [Repo](https://github.com/konstantinmuenster/graphql-weather-api)
| Fake GraphQL API | Mock user and to do data | [Try it!](https://mocki.io/graphql) | [Docs](https://mocki.io/docs)
| Fruits API | Information of fruit trees of the world | [Try it!](https://fruits-api.netlify.app/graphql) | [Docs](https://github.com/Franqsanz/fruits-api/blob/main/readme.md)
