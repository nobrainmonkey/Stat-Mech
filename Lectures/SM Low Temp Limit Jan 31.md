## Setup 
Box of atoms $m$
n = $\frac{N}{V} \rightarrow r_0 \approx  n^{-1/3}$ 
$\lambda_T = \frac{h}{\sqrt{2m\pi k_BT}}$ 
dimensionless quantity $n \lambda_T^3$ or $\lambda_t /r_0$   
if we fixed the density $n$, then there must exist low tempreture $T_{deg}$ when $\lambda_T \approx r_0$ .


## Analysis

* For $T> T_{deg}$ : Classical regime$\rightarrow U/N \propto \frac{3}{2} k_BT$, where Tempreature sets the energy scale.
* For SHO where $E_n = (n=\frac{1}{2}\hbar \omega_0)$: 
	* Occupancy up to high $n$ s.t. $E_n \approx n \hbar \omega_0 \approx k_B T$ 
	*  Average Occupancy of a particular level $<1$ where $n(E) \approx e^{-\beta (E-\mu)}$ 
	*  We then must have $\sum_i n(E_i)= N$, and $\mu (T) = k_B T \ln(n \lambda_T^3) = k_B T\ln(\frac{T_{deg}}{T})^{3/2}=-\frac{3}{2}k_BT\ln(\frac{T}{T_{deg}})$       
		
* For $T=0$, the overlap comes from **Quantum Statistics** instead of other physical potential interactions. Thus our Hamiltonian is still $H = \sum_i \frac{p_i^2}{2m}$ 
	* For SHO with Fermeions, we have $n_i = {0,1},$ $H =(N+1/2)\hbar \omega$ , and there is only one accessible microstate so $S=0$, and $\mu =\frac{E_{n+1}-E_{N}}{N+1-N}=(N+\frac{3}{2}) \hbar \omega_0 \approx N \hbar \omega_0$ 

* For $T< T_{deg}$, we will derive that
	* $n^F(E_i)=\frac{1}{e^{\beta (E_i - \mu)+1}}$ , and $\sum_i n^F(E_i) =N$ 

## Distribution function $n^{F,B}(E)$ 
Start with the Grand Paritition Function $T,V,\mu$ 
For a microstate, we must have $H= \sum_i E_j n_j$ and  $N = \sum_j n_j$ Where $n_j = {0,1}$ for Fermions, $n_j \in [0,\infty)$ for Bozons 
We then write our partition function
$Z= \sum_N \sum_{n_j} e^{-\beta[E-\mu N]}$, where $<N> = \frac{1}{\beta} \frac{1}{Z} (\frac{\partial Z}{\partial \mu})_{T,V}$     
Then, we can follow theese steps to solve for physical systems exactly:
* Simplify for noninteracting particles
* include Fermi or Bozon statistics

To be proven:
* $\langle N \rangle = \sum_i \frac{1}{e^{\beta(E_i - \mu)+1}}$ for Fermions
* $\langle N \rangle = \sum_i \frac{1}{e^{\beta(E_i - \mu)-1}}$ for Bozons

