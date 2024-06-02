# Riskless Assets
By mean of "Rickless", It mean safest assets. In other word, asset with negligible risk and a promise payback.

Examples: 
- Banks: Savings deposits
- Municipal bonds

Riskless assets could trade at different prices bause of:
1. Maturity
2. Liquidity (As it is easy to resell in secondary market)


# Interest Rate

Suppose the annual interest rate be r, wealth $W_T$ and starting with $P_0$ in t years.

- Annual compunding: $W_T=P_0(1+r)^{t}$
- Semi-annual compunding: $W_T=P_0(1+\frac{r}{2})^{2t}$
- Compunding n-times per year: $W_T=P_0(1+\frac{r}{n})^{nt}$
- Continuous compunding: $W_T=P_0e^{rt}$
![Example banner](.\01-AnnualCompundComparison.png)

Although the order of difference are negligible, but with a higher compunding frequency, high wealth in shorter time.

Examples:

Suppose r be the annual interest rate, n be the number of compunding period per years.

- The annual percentage rate (APR)=$r$
- The annual percentage yield (APY) [Compute the commulative return in a year]=$(1+\frac{r}{n})^{n}-1$

We claim APY>APR.

Consider 
$$
(1+\frac{r}{n})^n-1\implies 1+r+C^n_2 (\frac{r}{n})^2+\dots-1=r+C^n_2(\frac{r}{n})^2+\dots>r
$$

Therefore, $(1+\frac{r}{n})^n-1>r\implies APY>APR$

# Discounting

Suppose we want to end up with $P_f$ after t years, what $P_0$ we need?

From n-compunding wealth, $P_0(1+\frac{r}{n})^{nt}=P_f$, we have
$$
P_0=\frac{P_f}{(1+\frac{r}{n})^{nt}}
$$

# Zero-Coupon Bond

Zero coupon bonds are bonds that do not pay interest during the life of the bonds. Instead, investors buy zero coupon bonds at a deep discount from their face value, which is the amount the investor will receive when the bond "matures" or comes due.

For a t-year zero-coupon bond pays $P_f$ in year t. With t be maturity, P be price, $r$ be yield to maturity/annual interest rate,

$$
P(t)=\frac{P_f}{(1+r)^t}
$$
Yeild has an interpretation of a quote of a price, in this case has an economic interpretation as the average return if held to maturity.

# Return

Return (R) is define as a change in price from one period to another.
$$
R=\frac{P_t}{P_0}-1
$$
Where $P_t$ be the changed price while $P_0$ be the initial price.
-Continuously compunded return:$e^{r_1}=\frac{P_1}{P_0}$