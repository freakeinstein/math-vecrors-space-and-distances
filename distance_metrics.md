## Closeness:
- two sets are close if they are arbitrarily near to each other.


## Topological Space:
- it is a geometrical space with [[closeness]] defined but cannot necessarily be measured by a numeric distance
- it is a set of points + set of neighborhoods for each point + axioms satisfied between points and neighborhoods
- Neighborhood [def]: 
	- Neighborhood (`N`) of a point (`x`) is a set of points (`N(x) s: x element of X`) which gets assigned by a function (called neighborhood topology `N`), then X is called a topological Space.


## Homeomorphism (topological isomorphism or bicontinuous function):
- continuous function between [[topological spaces]] that has a continuous inverse function.
- they are the mappings that preserve all the topological properties of a given space.
- Two spaces with a homeomorphism between them are called homeomorphic, and from a topological viewpoint they are the same.
- a topological space is a geometric object, and the homeomorphism is a continuous stretching and bending of the object into a new shape


## Topological property:
- a topological property or topological invariant is a property of a topological space which is invariant under [[homeomorphisms]]. 


## Metric Space:
- a metric space is a set together with a metric on the set.
- The metric is a function that defines a concept of distance between any two members of the set, which are usually called points.
- A metric on a space induces [[topological properties]] like open and closed sets
- Examples for metrics that can be used in Metric Spaces:
	- Euclidean metric -> Euclidean distance (length of the straight line segment connecting two points)
	- elliptic metric -> elliptic geometry (distance on a sphere measured by angle)
	- hyperbolic metric -> hyperbolic geometry (special relativity as a metric space of velocities)
	- finite sequences -> Hamming's or Levenshtein distance
	- probabilistic spaces -> Wasserstein metric
- A metric space is an ordered pair `(M,d)` where `M` is a set and `d` is a metric on `M`. 
- A function `d:M cartessian product M -> R` holds;
	- d(x,y) = 0 <=> x=y
	- d(x,y) = d(y,x)
	- d(x,z) <= d(x,y) + d(y,z)
- The function `d` is also called distance function or simply distance. Often, `d` is omitted and one just writes `M` for a metric space if it is clear from the context what metric is used. 
- Every metric space is a topological space in a natural manner, and therefore all definitions and theorems about general topological spaces also apply to all metric spaces.


## Euclidean distance
Euclidean distance between two points in Euclidean space is the length of a line segment between the two points.