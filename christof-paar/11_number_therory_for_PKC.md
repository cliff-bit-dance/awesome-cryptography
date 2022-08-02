# lecture 11

## The Euclidean Algorithm

the Greatest Common Divisor (GCD) of two integers A and B is the largest integer that divides both A and B.

The Euclidean Algorithm for finding GCD(A,B) is as follows:
- If A = 0 then GCD(A,B)=B, since the GCD(0,B)=B, and we can stop.  
- If B = 0 then GCD(A,B)=A, since the GCD(A,0)=A, and we can stop.  
- Write A in quotient remainder form (A = B⋅Q + R)
- Find GCD(B,R) using the Euclidean Algorithm since GCD(A,B) = GCD(B,R)

To prove that GCD(A,B)=GCD(B,R) we first need to show that GCD(A,B)=GCD(B,A-B).

![proof](https://www.khanacademy.org/computing/computer-science/cryptography/modarithmetic/a/the-euclidean-algorithm#:~:text=The%20Algorithm,%3D%20B%E2%8B%85Q%20%2B%20R))

## Extended Euclidean Algorithm (EEA)

Given r_{0}, r_{1}
find s & t such that gcd(r_{0}, r_{1}) =  s \cdot r_{0} + t \cdot r_{1}

## computing inverse mod n using EEA

Problem: a^{-1} \cdot a = 1 mod n
what is a^{-1}

if there is inverse, the gcd(n,a) must be 1.

EEA gives gcd(n,a) = s \cdot n + t \cdot a = 1
gcd(n,a) mod n = 0 + t \cdot a = 1 mod n
so a^{-1} = t

## Euler's Phi Function
Z_{m} = {0,1,..., m-1}
the number of integers in Z_{m} relatively prime to m is denoted by \phi(m)

## Fermat's Little Theorem

## Euler's Theorem
a^{\phi(m)} = 1 (mod m)





