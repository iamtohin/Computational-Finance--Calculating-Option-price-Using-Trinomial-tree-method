# Computational-Finance--Calculating-Option-price-Using-Trinomial-tree-method Trinomial Tree

P1: Trinomial Tree
In the problem we mentioned that a binomial model can be generalized to a trinomial model. In a trinomial model we need to consider three stock price developments: in one period the price increases by a factor of  𝑢
  with the probability  𝑝𝑢
 , descreases by a factor of  𝑑
  with the probability  𝑝𝑑
 , or remains unchanged with the probability  1−𝑝𝑢−𝑝𝑑
 . The trinomial model can be built in a similar way to the binomial model, e.g., by matching the expectation and the variance and using  𝑢𝑑=1
  we obtain:
𝑢=𝑒𝜎2Δ𝑡√,𝑑=𝑒−𝜎2Δ𝑡√,𝑝𝑑=𝑒𝜎Δ𝑡2√−𝑒𝑟Δ𝑡2𝑒𝜎Δ𝑡2√−𝑒−𝜎Δ𝑡2√2,𝑝𝑢=𝑒𝑟Δ𝑡2−𝑒−𝜎Δ𝑡2√𝑒𝜎Δ𝑡2√−𝑒−𝜎Δ𝑡2√2.
 
For the programming task I write the corresponding Python functions that are asked in each section below.
