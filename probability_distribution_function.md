A probability distribution function (PDF) describes the likelihood of a random variable taking on a particular value within a given range. It gives the probability of different outcomes in a probability space. The PDF is often denoted by \( f(x) \), where \( x \) represents the variable.

Mathematically, for a continuous random variable, the probability that the variable falls within a specific interval \([a, b]\) is given by the integral of the PDF over that interval:

\[ P(a \leq X \leq b) = \int_{a}^{b} f(x) \,dx \]

For a discrete random variable, the probability distribution function is typically represented by a probability mass function (PMF), which gives the probability of each specific outcome.

Let's consider an example of a continuous random variable with a normal distribution (bell-shaped curve) as the probability distribution function. The standard normal distribution has a PDF given by the probability density function for a normal distribution:

\[ f(x) = \frac{1}{\sqrt{2\pi}} e^{-\frac{x^2}{2}} \]

In this example, \( x \) represents the random variable, and \( e \) is the base of the natural logarithm. The standard normal distribution has a mean of 0 and a standard deviation of 1.

Now, if you want to find the probability that \( X \) falls between -1 and 1, you would integrate the PDF from -1 to 1:

\[ P(-1 \leq X \leq 1) = \int_{-1}^{1} \frac{1}{\sqrt{2\pi}} e^{-\frac{x^2}{2}} \,dx \]

The result of this integration would give you the probability of \( X \) being between -1 and 1 in a standard normal distribution. The exact value would be calculated using numerical methods or tables for the standard normal distribution.
