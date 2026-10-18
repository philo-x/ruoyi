# Arithmetic contract
Arith.div must calculate the quotient using HALF_UP and the requested nonnegative scale. Every zero denominator, including 0/0, must throw ArithmeticException. Zero divided by a nonzero denominator remains zero. Preserve add/sub/mul/round behavior.
