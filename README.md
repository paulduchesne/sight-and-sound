# Sight and Sound 2012
Linked Open Data experiment with data from the 2012 Sight and Sound Film Poll.

- 1-scrape: scrape sight and sound film/voter/votes data (from https://www.bfi.org.uk/films-tv-people/sightandsoundpoll2012/).

- 2-link: link data to Wikidata via IMDB.

- 3-ontology: minimal ontology constructed in Protégé (https://protege.stanford.edu/).

- 4-rdf: N-triples produced in Karma (https://usc-isi-i2.github.io/karma/).

- 5-inject: create wikibase instance using wikibase-docker image (https://github.com/wmde/wikibase-docker) and wikibase-api (https://github.com/samuelmeuli/wikibase-api).

- 6-sparql: query wikibase via SPARQL, notebook intended to be run in Voila (https://github.com/voila-dashboards)

- 7-federation: match data between wikibase and wikidata to submit a joint query.
