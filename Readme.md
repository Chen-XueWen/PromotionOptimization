# Promotion Optimization for UK Online Retailer

Code for the following paper:
https://www.researchgate.net/publication/357300031_Promotion_Optimization_for_UK_Online_Retailer

Dataset:
https://www.kaggle.com/carrie1/ecommerce-data)

Presentation Video:
https://www.youtube.com/watch?v=qTBaXGC5xkM

### Linear Programming formulation
$$
begin{equation}\n",
begin{split}\n",
max~ & \\sum_{j=1}^9\\sum_{i=1}^n p_{ij}x_{ij}d_{ij} + \\sum_{i=1}^n y_{i} \\bar{p}_{i} \\bar{d}_{i} \\\\\n",
s.t. ~& \\sum_{j=1}^9x_{ij}\\leq 1, ~ i = 1,...,n\\\\\n",
& \\sum _{j=1}^{9}\\sum _{i=1}^{n} p_{ij} x_{ij} \\leq c\\\\\n",
& y_{i}= 1-\\sum_{j=1}^9 x_{ij}, ~ i = 1,...,n \\\\\n",
& x_{ij} \\in \\{0,1\\}\n",
end{split}\n",
end{equation}\n",
"\n",
$$
