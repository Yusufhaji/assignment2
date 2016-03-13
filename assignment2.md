Seminar Growth and regional development
=======
## Assignment Empirics: Cross-section and panel-data analysis of national growth experiences in the world.  

## Use the Solow model and our dataset to do the following:
### Question 1:  Derive the convergence equation.

$lny(t)=lny^* + e^{-λt}  [ lny(0)-lny^*]…………………………………(E.1)$
Where y ≡ Y/AL  is the output per effective worker

Since  y^* is the steady state level of income per effective worker and ; y(t) is the actual value of output per effective worker at time t.
Convergence in the Solow model is arrived at by taking a first order Taylor expansion of output around the steady state level gives : 

$(d[lny(t)-lny^*])/dt=-λ[lny(t)-lny^*]$

The Solow model suggests a natural regression to study the rate of convergence;
	
$lny(t)= (1-e^(-λt) )  lny^*+ e^(-λt)  lny(0)$

To Show that (E.1( is equivalent to (E.2) and (E.3) , we take  from (E.1) and show that output converges to its steady state and the time path of output is given by subtracting  lny(0) from both sides . y(0) is income per effective worker at some initial data (year);

$lny(t)- lny(0)  = lny^*- (e^(-λt) )  lny^*+ e^(-λt)  lny(0) - lny(0)$

$lny(t)- lny(0)  = (1-e^(-λt) )  lny^*+ e^(-λt)  lny(0) -   lny(0)$

$lny(t)- lny(0)= (1-e^(-λt) )  lny^* - (1-e^(-λt) )   lny(0)$

Equation (E.2) can also be derived as above by subtracting lny(t-T) from both sides. T is an arbitrary log in order to get income per effective worker at some initial year.

Equation (E.1) can therefore become;

$lny(t)- lny(t-T) = lny^* - (e^(-λt) )  lny^*- lny(t-T)+ e^(-λt)  lny(t-T)$

$lny(t)- lny(t-T)=(1-e^(-λt) )  lny^* - (1-e^(-λt)) lny(t-T)$

and T is a lag of one year.
Equation (E.3) can be written as above by multiplying both sides by capital letter T and it cancels out and we remain with :

$(lny(t)- lny(t-T))/T=((1-e^(-λt) )  lny^* )/T* T- ((1-e^(-λt) ) lny(t-T))/T * T$

$lny(t)- lny(t-T) = (1-e^(-λt) )  lny^* - (1-e^(-λt) ) lny(t-T)$

In this regard, we consider a time span of just one year which is technically feasible given that the underlying dataset provides annual data.
The left hand side shows what convergence of income per capita depends on and provides a model. Thus the growth of income is a function of the determinants of ultimate steady state and the initial level of income .
The coefficient in front of lagged income which is    $- (1-e^(-λt))$ is the coefficient of the initial level of income. This coefficient is used to determine whether there is a significant tendency towards convergence.
Since the Solow model makes quantitative predictions about the speed of convergence to steady state and requiring that $y≈y^*$ to hold close in a steady state , we find that this would require the following value of $λ∶ λ = (1-α)(δ+n+g)$
Therefore , the parameter governing the speed of convergence is  $λ$ .


### Question 2:  Derive the regression equation.

The Solow model takes the rates of savings, population growth and technological progress as exogenous.
A Cobb-Douglas production function is assumed , so production at time t is given by;

$Y(t) = K(t)^α (A(t)L(t))^(1-α)  ,0<α<1$

L and A are assumed to be exogenous at rates n and g∶ $L(t) = L(0)  e^nt$
$A(t)= A(0)  e^gt$

Defining variables in intensive form: y ≡ Y/AL  , k ≡ K/AL  

Therefore ;$ y = K^α(AL)^(1-α) = k^α = (K/AL)^α  $
$y = k^α$

Capital accumulates and the evolution of capital is governed by:

$k ̇(t) = sy(t)- (n+g+δ)k(t)$

$= k ̇(t) = sy(t)- (n+g+δ)k(t)$

In steady state k ̇=0  and so; 

$sk(t)^∝  = (n+g+δ)k(t)$

$sk(t)^(∝+1)  = (n+g+δ)$

$k^(∝-1) = ((δ+n+g)/s)^(1/(∝-1))$

And so the steady state capital per effective worker is : 
$k^*=(s/(δ+n+g))^(1/(1-∝))$

But the central-predictions of the Solow model concern the impact of saving and population growth on real income and so we can derive the steady state output per effective worker : y*
Since :                   
y = k^α
And so : 
$y^* = (s/(δ+n+g))^(∝/(1-∝))$

And by taking the log of $lny^*$

So we have the steady-state income per capita as:

$((Y(t))/(L(t)))^*=A(t).y^*=A_0 e^gt  (s/(δ+n+g))^(∝/(1-∝))$

By taking logarithms in order to “linearize” the above equation, we get 

$ln(Y/L) = lnA(0) + gt +∝/(1-∝) lns -  ∝/(1-∝) ln(n+g+δ)$

Mankiw Romer and Weil (1992) assume that:
lnA(0) = a + ε  where a is a constant and ε  is a country-specific shock (e.g., climate, social capital and property rights). The constant a is assumed to be identical across countries.

Using  lnA(0) = a + ε   and normalizing t=0 and thus taking log of income per capita we get the basic regression equation: 

$ln(Y/L) = lnA(0) + gt+∝/(1-∝) lns-  ∝/(1-∝)  ln(n+g+δ) + ε$

We assume that s and n are independent of ε and therefore we can estimate the above equation with OLS.
Augmented Solow model: Adding Human-Capital Accumulation to the Solow model
The production function becomes extended :

$Y(t) = K(t)^∝ H(t)^β (A(t)L(t)^(1-α-β)$

The evolution of the economy is now determined by :

$k ̇(t) = s_k y(t)- (n+g+δ)k(t)$

$h ̇(t) = s_h y(t)- (n+g+δ)h(t)$

Where ; y ≡ Y/AL  , k ≡ K/AL  and h ≡ H/AL 

The production function in intensive form is :
$y= k^∝ h^β $ 

Savings:  $s ≡ s_K+s_H $

In steady state k ̇= 0 and k ̇= h= 0 and so 

$k^* = ((s_K^(1-β) s_H^β)/(δ+n+g))^(1/(1-∝-β))$      and     

$h^* = ((s_K^∝ s_H〗^(1-∝))/(δ+n+g))^(1/(1-∝-β))$

So    $y = k^∝ h^β$  becomes;    $y^*=((s_K^(1-β) s_H^β)/(δ+n+g))^(∝/(1-∝-β)) ((s_K^∝ s_H^(1-∝))/(δ+n+g))^(β/(1-∝-β))$

And simplifies to be:

$((Y(t))/(L(t)))^*=A(0).e^gt=A_0 e^gt  (((s_K^α s_H^β ))/(δ+n+g)^(1/(∝+β)) )^((α+β)/(1-∝-β))$

Taking logs on both sides of the equation gives the linear specification:
$ln(Y/L)^*=lnA(0) + gt-(∝+β)/(1-∝-β) ln(n+g+δ) +  ∝/(1-∝-β)  lns_K + β/(1-∝-β)  lns_H $

MRW(1992) assume $lnA(0)= η_0 + ε $   and normalizing  t=o we get the extended regression equation with human capital as follows:

$ln(Y/L)^*=η_0-(∝+β)/(1-∝-β) ln(n+g+δ)+  ∝/(1-∝-β)  lns_K + β/(1-∝-β)  lns_H + ε$

We assume that the rates of saving and population growth are independent of country-specific growth factors shifting the production function. That is, we assume that s and n are independent of ε (the error term). This assumption implies that we can estimate the above equation with Ordinary Least Squares (OLS).
