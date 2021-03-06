Price Bond (Pure and Coupon-Paying)

Assume risk-neutral measure exists, the price of any security will be the expected present value of the future payoff under that measure

<a href="https://www.codecogs.com/eqnedit.php?latex=P_{t}&space;=&space;E^{*}_{t}(e^{-\int_{t}^{T}r_sds}V_T)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?P_{t}&space;=&space;E^{*}_{t}(e^{-\int_{t}^{T}r_sds}V_T)" title="P_{t} = E^{*}_{t}(e^{-\int_{t}^{T}r_sds}V_T)" /></a>


In this exercise, one-factor short-term rate model - Vasicek model is applied to simulate interest rate

<a href="https://www.codecogs.com/eqnedit.php?latex=dr_t&space;=&space;\kappa&space;(\bar{r}-r_t)dt&space;&plus;&space;\sigma&space;dW_t" target="_blank"><img src="https://latex.codecogs.com/gif.latex?dr_t&space;=&space;\kappa&space;(\bar{r}-r_t)dt&space;&plus;&space;\sigma&space;dW_t" title="dr_t = \kappa (\bar{r}-r_t)dt + \sigma dW_t" /></a>

Apply Euler's method of integral estimation

<a href="https://www.codecogs.com/eqnedit.php?latex=R&space;=&space;-\int_{0}^{T}r_sds&space;=&space;\Delta&space;(\sum_{j=1}^{n}r_t_j)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?R&space;=&space;-\int_{0}^{T}r_sds&space;=&space;\Delta&space;(\sum_{j=1}^{n}r_t_j)" title="R = -\int_{0}^{T}r_sds = \Delta (\sum_{j=1}^{n}r_t_j)" /></a>  
where <a href="https://www.codecogs.com/eqnedit.php?latex=\Delta&space;=&space;T/n,&space;t_j&space;=&space;j\Delta" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\Delta&space;=&space;T/n,&space;t_j&space;=&space;j\Delta" title="\Delta = T/n, t_j = j\Delta" /></a>


To simulate the Brownian Motion Process

<a href="https://www.codecogs.com/eqnedit.php?latex=dW_t&space;=&space;\sqrt{T/n}&space;\times&space;N(0,1)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?dW_t&space;=&space;\sqrt{T/n}&space;\times&space;N(0,1)" title="dW_t = \sqrt{T/n} \times N(0,1)" /></a>
