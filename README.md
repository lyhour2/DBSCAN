# DBSCAN
## DBSCAN is a density-based algorithm.
- Density = number of points within a specified radius (Eps)

- A point is a core point if it has more than a specified number of points (MinPts) within Eps
- These are points that are at the interior of a cluster

- A border point has fewer than MinPts within Eps, but is in the neighborhood of a core point

- A noise point is any point that is not a core point or a border point.


- Minpts (minimun point): is threshold that has set in each circle
- Eps : R raduis in speacific circle (threshold: will set by it situation, speacific problem or it's concept)

**Sameple Data Point**
![Alt text](/sample-data-points.png.png)
**Applied DBSCAN**
![alt text](/DBSCAN/applied-DBSCAN.png)
