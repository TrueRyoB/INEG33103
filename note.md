## Discrete Random Variables and Probability Disribution
A target is referred to as a random variable if its measured value can change from one replicate of the experiment to another; it is either discrete or continuous.
Probability is the likelihood that particular values occur; it's usually expressed in terms of a random variable.
Event is defined by a collection of categorical outcomes, instead of measured values; there always exists its complement(denoted as $A'$); it can be either inclusive or mutually exclusive.

### Expression
$$P(X \in{[a, b]}) = p$$ or $$P(a \leq X \leq b) = p$$

### Discrete random variables
Measures a value for discrete domains(like the number of particles of containment of a silicon wafer); probability mass function (=discrete probability density function) is the means of defining a discrete probability distribution and is denoted as $f(x)$; cumulative distribution function takes a value less than or equal to a specific number; mean(= expected value) of the discrete random variable X is denoted as E(X) while variance is denotes as V(X).
$ V(X) = \frac{\sum{(X-E(X))^2}}{N} $

### Binomial distribution
Bernoulli trial is a building block of a random experiment that is indenepdent from each other (=thereby the probability of a success is constant) and yields only TWO possible outcomes; a binomial distribution describes the # of successes in a FIXED number of Bernoulli trials; its mean is always at the median point for its ubiquitous distribution.
$ P(X = k) = (n, k)p^k(1-p)^(n-k) $
$ E(X) = np $ 

### Poisson Distribution
Models the # of events occuring within a FIXED interval duration, given a known average rate of occurence (λ) more than 0. A formula below represents the probability of a given number of events occuring i a fixed interval of time.
$ P(X = k) = (e^(-λ))\frac{λ^k}{k!} $
$ λ = E(X) $
$ V(X) = λ $


- Discrete RV
- Bernoulli RV
- Binomial RV
- Poisson Distribution

## Histogram Chart
Deal with quantitative data; determins a bin first: a range of intervals to separate data; it's often by taking either sqrt(N) or 1+logN.

### Other diagrams
- Pareto Chart (nonincreasing to right)
- Box plot (describes a trend of a data set; used for scatter diagrams)
- time series (continuous yet discrete)
- scatter diagrams (visualizes a correlation)