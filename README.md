# Assignment2-Kunta

# Pooja Kunta

##### Mehfil

My favourite food is **mehfil biryani**, in hyderabad.Hyderabad is among the global centres of IT in the world with the evolution of IT Hub commonly called **Cyberabad**. The area was primarily created for the promotion of **IT Infrastructure** in the city with several IT zones. ... Microsoft's largest R&D campus outside the US is in Hyderabad.

<hr>
# Nearest Airport and Address

## RGIA Airport

1. Take a cab outside the airport
2. option 2- Take a metro oustide the airport
3. Step down at mehfil biryani Point



### Recommended Food Items

* Chicken Corn Soup
* Thali
* soft drinks and Icecreams

[Goto AboutMe] (Aboutme.md)

<hr>

## Recomended Games


Below table gives a breif intro about gaming activites and the location of gaming arena along with amount payable for any additional equipment opted.


|Sport | Location | Money Payable|
|  ---  |   ---   | :--- |
|Four square| Kansas | $ 1500|
|Skydiving| New York | $ 3470|
|Surfing| Dallas | $ 1355|
|Skating| Minnesota | $ 650|

<hr>

# Pithy Quotes

> “Believe you can and you are halfway there.”<br>

>***- Theodore Roosevelt***

>“Today is the opportunity to build the tomorrow you want.”<br>

>***- Ken Poirot***



<hr>

# Code Fencing

# Computational geometry



>Computational geometry is a branch of computer science devoted to the study of algorithms which can be stated in terms of geometry. Some purely geometrical problems arise out of the study of computational geometric algorithms, and such problems are also considered to be part of computational geometry. While modern computational geometry is a recent development, it is one of the oldest fields of computing with a history stretching back to antiquity.[-Goto Source](https://en.wikipedia.org/wiki/Computational_geometry).


we can implement `Computational geometry` as follows <https://cp-algorithms.com/geometry/basic-geometry.html>


```
point3d intersect(point3d a1, point3d n1, point3d a2, point3d n2, point3d a3, point3d n3) {
    point3d x(n1.x, n2.x, n3.x);
    point3d y(n1.y, n2.y, n3.y);
    point3d z(n1.z, n2.z, n3.z); 
    point3d d(dot(a1, n1), dot(a2, n2), dot(a3, n3));
    return point3d(triple(d, y, z),
                   triple(x, d, z),
                   triple(x, y, d)) / triple(n1, n2, n3);
}
```