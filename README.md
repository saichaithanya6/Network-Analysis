## Introduction and Goals
Wes Anderson writes and directs films with an instantly-recognizable style. From the powder blue uniforms in The Life Aquatic with Steve Zissou to the retro pastels in The Grand Budapest Hotel, as well as the recurrence 
of lead actors like Bill Murray and Owen Wilson, filmgoers instantly recognize continuities between the otherwise unrelated stories in his films.

With this summer’s release of his latest project, Asteroid City, this is a perfect time to explore the networks arising from these recurring casts and see what they can tell us about each films similarities and differences.
This report will contrast the Wes Anderson network with an equivalent network based on Steven Spielberg films, which serve as a sort of baseline representing a more a typical body of film (albeit an extremely successful one).
Throughout this report, wa_ and ss_ prefixes denote each director’s data sets.

Given the bimodal undirected nature of these networks, we focus on three types of analysis:

* Part A: Network-level metrics

* Part B: Centrality and node importance

* Part C: Communities and subgroups

### Data Sets
Please make sure that this RMD file is in a directory that contains data/clean_data.RData.

We used data from IMDB (the Internet Movie Database) to construct affiliate and adjacency matrices for 11 films and 25 lead actors and actresses among Wes Anderson films. These relationships represent when two actors lead in the same film together. We also retrieved additional metadata about each film such as date, awards, and ratings. This exercise was repeated for Steven Spielberg (34 actors, 13 films).

These data sets were retrieved using the imdb package (github.com/RMHogervorst/imdb) as well as the OMDB API. See clean_imdb_data.R for details on how we constructed our data sets using these APIs.
