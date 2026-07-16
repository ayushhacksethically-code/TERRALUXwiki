## Logarithms and Anti-Logarithms

### General Definition and System

- Logarithms are used to change the form of numbers that are either too large or too small to make long, tedious, and confusing calculations simple.
- The changed number can be returned to its original form by using an anti-logarithm (antilog).
- Logarithms and anti-logarithms are the inverses of each other.
- A logarithm of a number is the power (or exponent) to which a given base must be raised to obtain that number.
- Mathematically, if $b^y = x$, then $y$ is the logarithm of $x$ to base $b$.
- Example: If $2^4 = 16$, then 4 is the logarithm of 16 with the base as 2, written as $4 = \log_2 16$.
- Mathematical representations of the system:
  $$\begin{aligned} b^x &= y \\ x \log b &= \log y \\ \text{or, } x &= \log_{b}y \end{aligned}$$
  Here, $y > 0$, $b > 0$, and $b \neq 1$.

### Logarithmic Laws and Theorems

#### Theorem 1 (Product Rule)
- The logarithm of the product of two numbers (say $x$ and $y$) is equal to the sum of the logarithms of the numbers, provided the base is the same for both numbers.
- Formula: $\log_b(xy) = \log_b x + \log_b y$.
- Proof steps:
  - Let $\log_b x = p$ such that $b^p = x \dots (i)$.
  - Let $\log_b y = q$ such that $b^q = y \dots (ii)$.
  - Multiplying $(i)$ and $(ii)$ gives: $b^p \times b^q = x \times y = b^{(p+q)}$.
  - Taking the logarithm on both sides yields: $\log_b xy = p + q = \log_b x + \log_b y$.

#### Theorem 2 (Quotient Rule)
- The division of two numbers is the antilog of the difference of the logarithms of the two numbers, provided the base is the same for both.
- Formula: $\log(x/y) = \log x - \log y$.
- Proof steps:
  - Let $\log_b x = p$ such that $b^p = x \dots (i)$.
  - Let $\log_b y = q$ such that $b^q = y \dots (ii)$.
  - Dividing $(i)$ by $(ii)$ gives: $x/y = b^p / b^q = b^{(p-q)}$.
  - Taking the logarithm on both sides yields: $\log(x/y) = p - q = \log x - \log y$.

#### Theorem 3 (Base Change Rule)
- The logarithm of a number to any other base can be determined by the relation: $\log_a x = \log_b x \times \log_a b \Rightarrow \log_b x = \log_a x / \log_a b$.
- Proof steps:
  - Let $\log_a x = p$, $\log_b x = q$, and $\log_a b = r$.
  - From the definition of logarithms: $a^p = x = b^q$ and $a^r = b$.
  - The equation $b^q = x$ can be written as $(a^r)^q = a^{rq} = x$.
  - Since $a^p = b^q = a^{rq} = x$, comparing the powers yields: $p = rq$.
  - This translates back to: $\log_a x = \log_a b \times \log_b x$ or $\log_b x = \log_a x / \log_a b$.

#### Theorem 4 (Power Rule)
- The logarithm of a number raised to a power is equal to the index of the power multiplied by the logarithm of the number, with the base remaining the same.
- Formula: $\log_b x^n = n \log_b x$.
- Proof steps:
  - Let $\log_b x = p$ so that $b^p = x$.
  - Raising both sides to the power $n$ yields: $(b^p)^n = x^n \Rightarrow b^{pn} = x^n$.
  - Taking the logarithm on both sides yields: $\log_b x^n = pn$ or $\log_b x^n = n \log_b x$.

#### Additional Structural Identities
- $\log_b(x+y) = \log_b x + \log_b(1+y/x)$
- $\log_b(x-y) = \log_b x + \log_b(1-y/x)$

### Characteristic and Mantissa Typologies

#### Positive Characteristic
- The whole part or the integral part of a log number is the characteristic.
- The characteristic of the logarithm of any number greater than 1 is positive and is one less than the number of digits to the left of the decimal point in the given number.
- If the number is less than one, the characteristic is negative and is one more than the number of zeros to the right of the decimal point.
- Data examples from the text:
| **Number** | **Characteristic** | **Reason Provided in Text** |
|---|---|---|
| 4 | 0 | One less than the number of digits to the left of the decimal point |
| 21 | 1 | Follows the rule for numbers greater than 1 |
| 111 | 2 | Follows the rule for numbers greater than 1 |
| 0.1 | 1 | One more than the number of zeros on the right immediately after the decimal point [Note: text states 1, conventionally represented as $\bar{1}$] |
| 0.025 | 2 | Follows the rule for numbers less than 1 [Conventionally $\bar{2}$] |
| 0.000010 | 5 | Follows the rule for numbers less than 1 [Conventionally $\bar{5}$] |

#### Negative Characteristic
- The logarithm of a number having '$n$' zeros immediately after the decimal is $-(n+1) + \text{the decimal}$.

#### Mantissa
- The decimal part of the logarithm of a number is the mantissa.
- A mantissa is always a positive quantity.
- A negative mantissa should always be converted into a positive one.
- Example conversion: $-5.2592 = -6 + (1 - 0.2592) = \bar{6} + 0.7428$.

### Anti-Logarithms Mechanics
- The anti-logarithm of a number is the inverse process of finding the logarithm of that number.
- If $x$ is the logarithm of a number $y$ with a given base $b$, then $y$ is the anti-logarithm of $x$ to the base $b$.
- Identity: If $\log_b y = x$, then $y = \text{antilog } x$.
- Natural Logarithms and Anti-Logarithms have their base as 2.7183.
- Logarithms and Anti-Logarithms with base 10 can be converted into natural Logarithms and Anti-Logarithms by multiplying by 2.303.
- An anti-logarithmic table is used to find the anti-logarithm of a number through the following operational steps:
  1. Separate the characteristic and the mantissa parts of the number.
  2. Use the antilog table to find a corresponding value for the mantissa, where the first two digits of the mantissa work as the row number and the third digit equals the column number. Note this value.
  3. Locate the mean difference in the antilog table; for the same row of the mantissa, the column number in the mean difference is equal to the fourth digit. Note this value.
  4. Add the values obtained from the row/column intersection and the mean difference column together.
  5. Add one to the characteristic; this final value indicates the place to insert the decimal point, counting that many digits from the left.

### Evaluative Problem Solutions
- **Problem 1:** Find the value of $\log 2.8726$.
  - _Solution:_ The number of digits to the left of the decimal is 1, so the value of the characteristic will be one less than one, which is 0. From the log table, the value of 2.8726 is 0.45827. Adding the mantissa and characteristic values gives the final value of the logarithm: $\log 2.8726 = 0 + 0.45827 = 0.45827$ [Note: text textually writes $\log 2.8725$ in the final summation line].
- **Problem 2:** Calculate the antilog of 3.6552.
  - _Solution:_ Find the number whose logarithm is 3.6552. From the antilog table, the value corresponding to row 65 and column 5 is 4508. The mean difference column for the value 2 is 2. Adding these two values gives $4518 + 2 = 4520$ [Note: text states $4518+2$ instead of $4508+2$ due to a typo in the source graphics]. The decimal point is placed $3 + 1 = 4$ digits from the left. Thus, $\text{antilog } 3.6552 = 4520.0$.