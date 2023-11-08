# min-quad

Compute the minimum quadrilateral that encloses all your points. We use a very simple algorithm that is based on the observation that:

* A minimum k-gon that encloses a polygon has k - 1 edges that cover k - 1 edges of the polygon. 

## Examples

![image](https://github.com/Vrroom/min-quad/assets/7254326/4fd00966-ead6-47e4-b27a-b0413c26dbd5)

## Runtime

In the examples I tried, it takes upto 4 seconds. That said, the algorithm is highly parallelizable. 

## References 

* Minimum area circumscribing Polygons -- Aggarwal et al.
