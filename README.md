# Concurrency-of-Delaunay-Triangulation-and-MST
Led a team of 2, Developed a parallelized sequential program in Java that constructed a Euclidean minimum spanning tree (MST) for a collection of points in a plane. Utilized fork-join thread pool to parallelize Dwyer’s Delaunay triangulation algorithm, created several helper threads to parallelize MST that allowed the algorithm to specify various start-up parameters. Achieved 870% speedup compared to original one when starts with 32 threads (in node2x18a machine)
