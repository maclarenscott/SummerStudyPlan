# Answers

## MATH 235 (Algebra 1)

1. A ∪ B = {1, 2, 3, 4, 5, 6, 7, 8}, A ∩ B = {4, 5}.
2. Proof: Let x ∈ (A ∪ B) - B. Then x ∈ A ∪ B and x ∉ B. If x ∈ A, then x ∈ A - B. If x ∈ B, then x ∉ B, which is a contradiction. Therefore, x ∈ A - B. This shows that (A ∪ B) - B ⊆ A - B. The reverse inclusion A - B ⊆ (A ∪ B) - B is obvious.
3. The function f is not injective because f(-1) = f(1) = 1. The function f is not surjective because there is no x ∈ R such that f(x) = -1.
4. Proof: Let r be a rational number and i be an irrational number. Suppose r + i is rational. Then r + i - r = i is rational, which is a contradiction.
5. Proof by contradiction: Suppose there are only finitely many prime numbers p_1, p_2, ..., p_n. Consider the number N = p_1p_2...p_n + 1. The number N is not divisible by any of the primes p_1, p_2, ..., p_n, so N is either prime or has a prime divisor not in the list p_1, p_2, ..., p_n. This is a contradiction.
6. Proof: |z|^2 = (a + bi)(a - bi) = a^2 + b^2 = z * conjugate(z).
7. Proof: |zw| = |z||w|.
8. Proof: A - λI = [[a - λ, b], [c, d - λ]], so det(A - λI) = (a - λ)(d - λ) - bc = λ^2 - (a + d)λ + ad - bc = λ^2 - tr(A)λ + det(A).

## MATH 222 (Calculus 3)

1. The Taylor series expansion of sin(x) at x = 0 up to the x^4 term is x - x^3/6.
2. ∂f/∂x = 2xy, ∂f/∂y = x^2 - 3y^2.
3. ∫∫_R (2x - y) dA = ∫ from 1 to 2 ∫ from 0 to 1 (2x - y) dy dx = 1.
4. ∫_C F · dr = ∫ from 0 to 1 (t^2, t^2) · (1, 1) dt = ∫ from 0 to 1 2t^2 dt = 2/3.
5. ∇f = (2x, 2y, 2z).
6. curl F = (∂F3/∂y - ∂F2/∂z, ∂F1/∂z - ∂F3/∂x, ∂F2/∂x - ∂F1/∂y) = (1 - 1, 1 - 1, 1 - 1) = (0, 0, 0).
7. div F = ∂F1/∂x + ∂F2/∂y + ∂F3/∂z = 0 + 0 + 0 = 0.
8. ∫∫_S F · dS = ∫ from 0 to 2π ∫ from 0 to π (sinφ cosθ, sinφ sinθ, cosφ) · (sinφ cosθ, sinφ sinθ, cosφ) sinφ dφ dθ = 4π.

## MATH 242 (Analysis 1)

1. Proof: For any ε > 0, choose N such that N > 1/ε. Then for all n > N, |1/n - 0| = 1/n < 1/N < ε. Therefore, the sequence {1/n} converges to 0.
2. Proof: Observe that a_(n+1) - a_n = (1/2)(a_n + 2/a_n) - a_n = 1 - a_n^2/2 ≤ 0 for all n ≥ 1, so the sequence {a_n} is decreasing. Also, a_n ≥ 0 for all n ≥ 1, so the sequence {a_n} is bounded below. Therefore, by the Monotone Convergence Theorem, the sequence {a_n} converges.
3. Proof: The series ∑_(n=1)^∞ 1/n^2 is a p-series with p = 2 > 1, so by the p-Series Test, the series converges.
4. Proof: For any ε > 0, choose δ = ε. Then for all x such that |x - 1| < δ, |f(x) - f(1)| = |x^2 - 1| = |x - 1||x + 1| < ε|x + 1|. Since x is close to 1, |x + 1| is close to 2, so |f(x) - f(1)| < 2ε. Therefore, f is continuous at x = 1.
5. Proof by contradiction: Suppose f is uniformly continuous on (0, 1). Then for any ε > 0, there exists δ > 0 such that for all x, y ∈ (0, 1) with |x - y| < δ, |f(x) - f(y)| < ε. Choose ε = 1 and x = 1/2 and y = 1/2 + δ/2. Then |x - y| = δ/2 < δ, but |f(x) - f(y)| = |1/2 - 1/(2 + δ)| = δ/(2(2 + δ)) > δ/8, which can be made larger than 1 by choosing δ large enough. This is a contradiction, so f is not uniformly continuous on (0, 1).
6. Proof: The limit as h approaches 0 of (f(1 + h) - f(1))/h = ((1 + h)^2 - 1)/h = 2 + h exists and is equal to 2, so f is differentiable at x = 1.
7. Proof: The limit as h approaches 0 of (f(0 + h) - f(0))/h = h/h = 1 and the limit as h approaches 0 of (f(0 - h) - f(0))/h = -h/h = -1 are not equal, so f is not differentiable at x = 0.
8. Proof: For any ε > 0, choose δ = ε. Then for all```markdown
## MATH 242 (Analysis 1) Continued

8. (Continued) Then for all x, y ∈ R with |x - y| < δ, |f(x) - f(y)| = |x^3 - y^3| = |(x - y)(x^2 + xy + y^2)| ≤ |x - y|(x^2 + xy + y^2) < δ(3 + 3δ + δ^2) = ε(3 + 3ε + ε^2), which can be made smaller than ε by choosing ε small enough. Therefore, f is uniformly continuous on R.

## COMP 273 (Introduction to Computer Systems)

1. The binary number 101101 is 45 in decimal.
2. The hexadecimal number A3 is 10100011 in binary.
3. A simple combinational circuit with two inputs, A and B, and one output, F, such that F = 1 if and only if exactly one of A and B is 1 is an XOR gate.
4. A MIPS assembly program that computes the factorial of a non-negative integer n is as follows:
5. A direct-mapped cache is a cache where each cache line corresponds to exactly one location in main memory. This location is determined by the address of the data.
6. Virtual memory is a technique that allows a computer to use more memory than it physically has. It does this by swapping data between main memory and a disk.
7. Pipelining improves the performance of a computer by allowing multiple instructions to be executed at the same time. Each instruction is divided into stages, and each stage is executed in a different pipeline stage.
8. An interrupt is a signal to the processor to stop what it is doing and do something else. This can be caused by various events, such as an I/O device needing attention or a user pressing a key.

## COMP 206 (Introduction to Software Systems)

1. A C program that prints "Hello, world!" to the console is as follows:
```c
#include <stdio.h>

int main() {
    printf("Hello, world!\n");
    return 0;
}```
