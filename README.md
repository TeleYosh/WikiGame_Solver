# WikiGame-Solver
This a mini project I coded to beat my friends at the Wikipedia game.
The goal of the Wikipedia game is to start form a given article page and reach another article by clicking only on links inside the page.
To do so, I created a graph from a wikipedia dump xml file using xml.sax for parsing the xml file and networkx to create the graph. The wiki graph is contructed as a unweighted directed graph, hence BFS is enought to find the shortest path between two nodes.
