# Promotion Optimization for UK Online Retailer

Code for the following paper:
https://www.researchgate.net/publication/357300031_Promotion_Optimization_for_UK_Online_Retailer

Dataset:
https://www.kaggle.com/carrie1/ecommerce-data)

Presentation Video:
https://www.youtube.com/watch?v=qTBaXGC5xkM

### Formulation of a promotion optimization problem

$$
\begin{align}
\sum_{j=1}^9 \\
\end{align+}
$$

\\max~ & \\sum_{j=1}^9\\sum_{i=1}^n p_{ij}x_{ij}d_{ij} + \\sum_{i=1}^n y_{i} \\bar{p}_{i} \\bar{d}_{i} \\\\\n
"s.t. ~& \\sum_{j=1}^9x_{ij}\\leq 1, ~ i = 1,...,n\\\\\n",
"& \\sum _{j=1}^{9}\\sum _{i=1}^{n} p_{ij} x_{ij} \\leq c\\\\\n",
"& y_{i}= 1-\\sum_{j=1}^9 x_{ij}, ~ i = 1,...,n \\\\\n",
"& x_{ij} \\in \\{0,1\\}\n",

    "\n",
    "\n",
    "c = User defined constant to limit number of promotion <br>\n",
    "n = number of products <br>\n",
    "j = different prices for each product <br>\n",
    "\n",
    "d<sub>ij</sub> = Demand for product i at j price <br>\n",
    "x<sub>ij</sub> = Binary Selection, if x<sup>ij</sup> = 1 means select at product i and price j, 0 if otherwise  <br>\n",
    "p<sub>ij</sub> = j<sup>th</sup> Price for product i "
   ]
