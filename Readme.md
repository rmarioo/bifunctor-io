#Bifunctor IO in Kotlin - Mario Russo

This is a _work in progress_ implementation of bifunctor IO.  
The bifunctor io ```BIO[E, A]``` is an immutable data type that models an effectful program that
 runs forever, fails with an E, or computes an A.  

BIO values are pure, immutable values and thus preserves referential transparency, being usable in functional programming.   
BIO

  - represents just a description of a side effectful computation
  - preserves referential transparency
  - allow the composition also of side effectful 
