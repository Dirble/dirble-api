# API v2
This is the second draft of the new API on Dirble.
See `:version` as v2 in the url.


#### GET /:version/stations

 Return a list of stations

**Parameters:** 


 - page : Page offset to fetch.

 - per_page : Number of results to return per page.

 - offset : Pad a number of results.


#### GET /:version/station/:id

 get one station by id

**Parameters:** 


 - id (required) : Station id.



#### GET /:version/song_history/:id

 Get song_history for station by station id

**Parameters:** 


 - id (required) : Station id.



#### GET /:version/categories

 Return a list of categories



#### GET /:version/categories/primary

 Return head categories, also known as Primaries.
 

#### GET /:version/categories/tree

 Get all categories as a tree.
 

#### GET /:version/category/:id/stations

 Get stations for a category (both primary and child categories)

**Parameters:** 


 - id (required) : Child and Primary Category id.

 - page : Page offset to fetch.

 - per_page : Number of results to return per page.

 - offset : Pad a number of results.



#### GET /:version/category/:id/childs

 Get child categories for head/primary categories

**Parameters:** 


 - id (required) : Primary category id.


#### GET /:version/countries

 Return a list of countries



#### GET /:version/continents

 Return a list of Continents



#### GET /:version/continents/:continent/countries

 Get child countries for continent

**Parameters:** 


 - continent (required) : Continent id.



#### GET /:version/country/:id/stations

 Get stations for a country

**Parameters:** 


 - id (required) : Country id.

 - page : Page offset to fetch.

 - per_page : Number of results to return per page.

 - offset : Pad a number of results.



#### GET /:version/search/:query

 

**Parameters:** 


 - query (required) : Search query.


## Revisions
* 19 march 2015: Fixed last fixes for release.
* 28 february 2015: Released the first draft of API v2.
