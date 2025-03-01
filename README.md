# WikiGame-Solver
The goal of the Wikipedia game is to start from a given article page and reach another article by clicking only on links inside the page. The player who finds the shortest path wins.

To do so, I created a graph from a [wikipedia dump xml file](https://mirror.accum.se/mirror/wikimedia.org/dumps/) using `xml.sax` for parsing the xml file and `networkx` to create the graph. The wiki graph is contructed as a unweighted directed graph, hence BFS is enought to find the shortest path between two nodes.
