# HW2
## 刘博远  物理32  2013012221
### 1.7
- a. detailed balance:  
$$\frac{dn_{2}}{dt}=n_{1}B_{12}\bar{J}-A_{21}n_{2}=0$$
since $n_{1}/n_{2}=\exp[h\nu_{0}/(kT)]g_{1}/g_{2}$, $g_{1}B_{12}=g_{2}B_{21}$, $A_{21}=2h\nu^{3}B_{21}/c^{2}$, we have  
$$\bar{J}=\frac{A_{12}n_{2}}{B_{12}n_{1}}=\frac{A_{21}}{B_{12}}\frac{g_{2}}{g_{1}}\exp[-h\nu_{0}/(kT)]=\frac{2h\nu^{3}}{c^{2}}\exp[-h\nu_{0}/(kT)]$$

- b. $$\frac{dn_{2}}{dt}=n_{1}B_{12}\bar{J}-n_{2}B_{21}\bar{J}-A_{21}n_{2}=0$$
$$ \bar{J}=\frac{A_{21}/B_{21}}{[(g_{1}B_{12})/(g_{2}B_{21})]\exp[h\nu_{0}/(kT)]-1} $$
equilibrium:
$$ \bar{J}_{\nu}=I_{\nu}=\frac{2h\nu^{3}/c^{2}}{\exp[h\nu/(kT)]+1} $$
we have
$$ \frac{A_{21}}{B_{21}}=-\frac{2h\nu^{3}}{c^{2}},\quad g_{1}B_{12}=-g_{2}B_{21} $$
(which is equivalent to setting $B_{21}\rightarrow -B_{21}$ in the ordinary derivation for the boson case)

### 1.9
recall (1.30) for an constant source $S_{\nu}$ 
$$ I_{\nu}(\tau_{\nu})=S_{\nu}+e^{-\tau_{\nu}}(I_{\nu}(0)-S_{\nu}) $$
i.e. 
$$ I_{\nu}(\tau_{\nu})-I_{\nu}(0)=(1-e^{-\tau_{\nu}})(S_{\nu}-I_{\nu}(0)) $$
In our case, $I_{\nu}(0)=B_{\nu}(T_{c})$ seen along A, $I_{\nu}(0)=0$ seen along B, $S_{\nu}=B_{\nu}(T_{s})$, and $\tau_{\nu_{1}}\ll\tau_{\nu_{0}}$.
If $B_{\nu}(T)\approx B_{\nu_{0}}(T)\sim B(T)$, $I_{\nu_{1}}(0)\approx I_{\nu_{0}}(0)=I(0)$
we have  
$\Delta_{10}= I_{\nu_{1}}(\tau_{\nu_{1}})-I_{\nu_{0}}(\tau_{\nu_{0}})=(e^{-\tau_{\nu_{0}}}-e^{-\tau_{\nu_{1}}})(B(T_{s})-I(0))$

- a. along A: $\Delta_{10}^{A}=(e^{-\tau_{\nu_{0}}}-e^{-\tau_{\nu_{1}}})(B(T_{s})-B(T_{c}))>0$, since $e^{-\tau_{\nu_{0}}}<e^{-\tau_{\nu_{1}}}$, and $B(T_{s})<B(T_{c})$ for $T_{s}<T_{c}$  
along B: $\Delta_{10}^{B}=(e^{-\tau_{\nu_{0}}}-e^{-\tau_{\nu_{1}}})B(T_{s})<0$

- b. along A: similar to a., $\Delta^{A}_{10}<0$, as $B(T_{s})>B(T_{c})$ for $T_{s}>T_{c}$  
along B: the same with a., $\Delta_{10}^{B}=(e^{-\tau_{\nu_{0}}}-e^{-\tau_{\nu_{1}}})B(T_{s})<0$


### 1.10
- a.  
$$ \frac{1}{3}\frac{\partial^{2}J}{\partial \tau^{2}}=\epsilon(J-B) $$
If $\epsilon$, $B$ are constant, we have
$$ J(\tau)=c_{1}e^{\sqrt{3\epsilon}\tau}+c_{2}e^{-\sqrt{3\epsilon}\tau}+B $$  
boundary condition:
$$I^{+}=\left(J+\frac{1}{\sqrt{3}}\frac{\partial J}{\partial \tau}\right)|_{\tau=+\infty},\quad I^{-}=\left(J-\frac{1}{\sqrt{3}}\frac{\partial J}{\partial \tau}\right)|_{\tau=0}$$
which leads to
$$ c_{1}=0,\quad B=I^{+},\quad c_{2}=\frac{I^{-}-I^{+}}{1+\sqrt{\epsilon}} $$
therefore  
$$ J(\tau)=\frac{I^{-}-B}{1+\sqrt{\epsilon}}e^{-\sqrt{3\epsilon}\tau} +B $$  
$$ F(0)= \int I\cos\theta d\Omega=2\pi \int_{-1}^{+1}\mu Id\mu=\frac{4\pi}{3}\frac{\partial J}{\partial\tau}|_{\tau=0}=\frac{4\pi(B-I^{-})\sqrt{\epsilon}}{3+\sqrt{3}}$$

- b. apparently, when $\tau\gg 1/\sqrt{3\epsilon}$, i.e. $\tau_{*}\equiv\sqrt{3\epsilon}\tau=\sqrt{3\tau_{a}(\tau_{a}+\tau_{s})}\gg 1$, we have $e^{-\sqrt{3\epsilon}\tau}\ll 1$ and $J(\tau)\approx B$




### Eddinton Approximation
- expansion of the intensity to the first order with respect to $\mu=\cos\theta$ results in the Eddinton Approximation:
$$ I_{\nu}(\tau,\mu)=a_{\nu}(\tau)+b_{\nu}(\tau)\mu\ ,\quad K=\frac{1}{2}\int_{-1}^{+1}\mu^{2}Id\mu=\frac{a_{\nu}}{3} $$
- radiation transfer equation
$$ \mu\frac{\partial I_{\nu}}{\partial \tau}=I_{\nu}-S_{\nu} $$
where $d\tau(z)=-(\alpha_{\nu}+\sigma_{\nu})dz$, and $S_{\nu}=(\alpha_{\nu}B_{\nu}+\sigma_{\nu}J_{\nu})/(\alpha_{\nu}+\sigma_{\nu})$ is isotropic.
- from integration of the radiation transfer equation multiplied by $1$ or $\mu$, we can derive
$$ \frac{1}{3}\frac{\partial^{2}J_{\nu}}{\partial \tau^{2}}=\epsilon_{\nu}(J_{\nu}-B_{\nu})$$
from which we can solve $J_{\nu}$, $S_{\nu}$ and thus $I_{\nu}$, given $\epsilon_{\nu}=\alpha_{\nu}/(\alpha_{\nu}+\sigma_{\nu})$, and $B_{\nu}$ as the thermal emission of the medium
