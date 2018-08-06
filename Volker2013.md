<!-- Required extensions: extra -->
## Volker Bromm 2013

### Cosmological Context

- minihalo: 
 - $\nu\sigma$-peak (to characterize perturbaions on a given mass scale, $\mathcal{P}_{\nu}\propto e^{-\nu/2}$)  
 - redshift evolution ( $k_{B}T_{vir}\sim m_{H}v_{vir}^{2},\quad v_{vir}^{2}\sim GM_{h}/R_{vir}$): 
$$ 1+z_{vir}\sim \nu \sigma_{0}(M)/\delta_{c},\quad \delta_{c}\sim 1.69 $$
$$R_{vir}\simeq 200\mathrm{pc}\left(\frac{M_{h}}{10^{6}M_{\odot}}\right)^{1/3}\left(\frac{1+z}{10}\right)^{-1}\left(\frac{\Delta_{c}}{200}\right)^{-1/3}$$
$$T_{vir}\simeq 2\times 10^{3}\mathrm{K}\left(\frac{M_{h}}{10^{6}M_{\odot}}\right)^{2/3}\left(\frac{1+z}{20}\right)$$
- cooling via $H_{2}$ (too cold for atomic cooling)
 - formation of $H_{2}$: $H^{-}$ channel (free electrons as catalysts) & $H_{2}^{+}$ channel (free protons, for $z\gt 100$)
 $$f_{H2}\propto T^{1.5}_{vir}$$
 - Rees–Ostriker–Silk criterion: $t_{cool}\lt t_{dyn}$
 - $H_{2}$ cooling function 
 - minimum collapse mass $M_{crit}\gtrsim 2\times 10^{5}M_{\odot}$ (from cosmological simulations: dynamical heating by merging)

- beyond the standard model
 - WDM: shift of sites to more massive halos
 - baryons-DM relative streaming $v_{s,i}\sim 30\mathrm{km\cdot s^{-1}}$: raises the minimum halo mass
 Jeans mass ($v_{eff}=\sqrt{c_{s}^{2}+v_{s}^{2}}$):
$$ M_{J}\simeq \frac{v^{3}_{eff}}{G^{3/2}\rho^{1/2}}$$

### Formation Physics: The Standard Model
#### Three Phases
- Atomic phase (below $n\sim 10^{8}\mathrm{cm^{-3}}$), asymptotic $H_{2}$ abundance $n[H_{2}]/n\sim 10^{-3}$
 - critical temperature & density for $H_{2}$ cooling transition (`loitering state'): $\sim 200\mathrm{K},\quad n\sim 10^{4}\mathrm{cm^{-3}}$
 $$M_{J}\simeq 500M_{\odot}\left(\frac{T}{200\mathrm{K}}\right)^{3/2}\left(\frac{n}{10^{4}\mathrm{cm^{-3}}}\right)^{-1/2}$$
 - $HD$ cooling (significant for lowest-mass minihalos, Pop III.2 stars from primordial gas after pre-ionization, $H_{2}+D^{+}\rightarrow HD+H^{+}$)

- Molecular phase ($n\sim 10^{8}\mathrm{cm^{-3}}$)
 -  increase of cooling $\sim 10^{3}$ **VS** heating by the release of binding energy of $H_{2}$ 4.48eV: near-isothermal collapse at $\sim 1000\mathrm{K}$
 - $n\gt 10^{12}\mathrm{cm^{-3}}$ (fully molecular): optically thick ro-vibrational lines of $H_{2}$
 - Sobolev approximation: $L_{char}\simeq v_{th}/|dV_{r}/dr|$
 escape probability:
$$\beta_{esc}=\frac{1-\exp(-\tau)}{\tau},\quad \tau=k_{lu}L_{char}$$

- Protostellar conditions ($n\gt 10^{14}\mathrm{cm^{-3}}$)
 - molecular lines are optically thick throught
 - $H_{2}-H_{2}$ supermolecule: continuous collision-induced emission (CIE) & CIA
 - $n\gt 10^{16}\mathrm{cm^{-3}}$: collisional dissociation of $H_{2}$ removing the binding energy, which limits the rise in central temperature driven by compressional heating $\sim 2000\mathrm{K}$
 - non-equilibrium chemistry, increasingly short reaction timescales at high $n$: equilibrium solver

#### Initial Collapse
- spherically symmetric Larson-Penston (LP) type similarity solutions: $\rho\propto r^{-n_{p}},\quad n_{p}=2/(2-\gamma)$ ($\gamma\simeq 1.1,\quad n_{p}\simeq 2.2$)
- definition of the extent of a protostar: photospheric: $\beta_{crit}=1-\exp(-1)\simeq 0.63$, hydrostatic: radial (infall) velocity $V_{r}\simeq 0$, $R_{hyd}>R_{pho}\sim 100-200 R_{\odot}$
- initial hydrostatic core: $M_{*}\sim 10^{-2}M_{\odot}$

#### Accretion and Disk Formation
- higher accretion rate due to higher temperature (compared with present-day star formation, of ratio $\sim(300/10)^{3/2}$)
$$ \dot{M}_{acc}\simeq\frac{M_{J}}{t_{ff}}\simeq\frac{c_{s}^{3}}{G}\propto T^{3/2} $$
- primordial protostellar disks are ubiquitously driven towards gravitational instability, due to the very high accretion rates
 - Toomre $Q$-criterion (stable): $Q=c_{s}\kappa/(\pi G\Sigma)>1$, $\kappa$ is the epicyclic frequency ($=\Omega$ for a Keplerian disk)
 - Gammie criterion (for a density perturbation to survive): $t_{cool}\lt 3\Omega^{-1}$
 Hotter disk may be stablized

#### Multiplicity
- 50% in binary, log-normal distribution of binary periods peaking at $\sim 900\mathrm{yr}$, from the disk fragmentation mode

#### Lower Mass Limit
- opacity-limited fragmentation (collapse stops when the gas is dense enough to be opaque and compressional heating can not be radiated away)
$$ M_{F}\simeq M_{Ch}f^{-1/2}\left(\frac{k_{B}T}{m_{H}c^{2}}\right)^{1/4} $$
(efficiency factor $f(Z)\lesssim 1$, Chandrasekhar mass $M_{Ch}$, $T\sim 10^{4}\mathrm{K},\quad f\sim 1\rightarrow M_{F}\simeq 10^{-2}M_{\odot}$)
- to survive the entire history of the Universe, $M_{*}\lesssim 0.8M_{\odot}$
- slow accretion of galactic ISM: low-mass Pop III can be identified as Pop II
> sink particles

#### Upper Mass Limit
- asymptotic growth:
$$ M_{*,up}=\int_{0}^{t_{*}}\dot{M}_{acc}dt\sim \dot{M}_{acc}t_{acc}$$
$\dot{M}_{acc}\sim 10^{-3}M_{\odot}\mathrm{yr^{-1}},\quad t_{acc}\sim t_{KH}\sim 10^{5}\mathrm{yr},\quad M_{*,up}\sim 100M_{\odot}$
- radiative feedback: a bipolar ultra-compact $HII$ region `boils away' the disk and thus quenches the accretion, $M_{*,up}\simeq 30-60M_{\odot}$

#### The Primordial IMF
- Initial Mass Function
$$\frac{dN}{dM_{*}}\propto M_{*}^{-x}$$
- present-day IMF: Salpeter slope $x=2.35$: 
$$\bar{M}_{*}\simeq \frac{1}{N_{*}}\int_{M_{*,low}}^{M_{*,up}}M_{*}\frac{dN}{dM_{*}}dM_{*}\sim 4\times M_{*,low}$$
- Pop III IMF: top-heavy

#### Stellar Rotation
- roughly solid-body rotation profile with surface velocities $\sim 80-100\%$ of the Keplerian velocity.
- little evidence of any correlation between the large-scale properties of each host minihalo?
- rotation could alter the protostars' life (e.g. stellar winds at $\Omega\Gamma$-limit)
- chemically-homogeneous evolution (CHE) due to sufficient rotational mixing
- observations of the pattern of chemical elements in the atmospheres of the metal-poor stars

### Beyond the Standard Model
#### Magnetic Fields
- for present-day star formation (dynamical effects)
 -  MHD turbulence in the molecular birth clouds
 -  transport of angular momentum
 -  limiting the efficiency of the star formation
- Seed fields
 - electro-weak or QCD phase transitions
 - inflation
 - Biermann battery in collapsed structures ($B\lesssim 10^{-17}\mathrm{G}$ on $\sim 100\mathrm{pc}$)
- kinematic dynamo by a velocity field endowed with net helicity (from small-scale turbulence during virialization and ongoing infall of material)
- MRI, MHD jets, ambipolar diffusion, suppression of fragmentation

#### Self-annihilating DM
- non-nuclear source of energy to stabilize proto-stellar disks
- very red, virtual absence of ionizing UV photons, possible very large masses, $M_{*}\gtrsim 10^{6}M_{\odot}$, extremely bright, prolonging lifetime
- stabilization frist or supression of DMA by inevitable mutiplicity 

#### Cosmic Rays
- Sources:
 - wake of magnetized SN explosions due to Fermi acceleration
 - dacay of exotic particles from the very early Universe (ultra-high energy CRs)
- Outcome:
 - giving rise to energetic, hydrogen and helium ionizing photons (interaction between CRs and the CMB)
 - bedrock (plateau) of $^{6}\mathrm{Li}$ abundance 
- Problem: unrealistically high IGM temperatures

### Second Generation Stars
#### Radiative Feedback (Pop III.2)
- ionization, over-abundance of free electrons, HD cooling (lowered temperatures set by CMB), smaller fragment masses
- pathways:
 - photo-ionization in the neighborhood of massive Pop III stars (relic $HII$ regions), cons: low density due to outflows by P-I heating
 - collisional ionization in strong virialization shocks (more massive halos with $T_{vir}\gtrsim 10^{4}\mathrm{K}$, `atomic cooling' through Lyman-$\alpha$ photons), cons: pre-enrichment

#### Chemical Feedback (Pop II)
- heavy elements produced and dispersed in energetic Pop III SN explosions
- critical metalicity for transition between the top-heavy Pop III and more normal Pop II
 - cooling due to fine-structure lines from atomic or ionic metal species, $Z_{crit}\simeq 10^{-3.5}Z_{\odot}$, identifies $C II$ and $O I$ as main coolant
 - cooling due to grains synthesized in the first SNe, critical dust-to-gas ratio $D_{crit}\simeq 4\times 10^{-9}$
 - Lyman-Wener radiation background

#### Turbulence & the First Clusters
- supersonic turbulence (at the scale of an atomic cooling halo), $Ma\sim v_{vir}/c_{s}\sim 10$
- density fluctuations, PDF:
- $$f(x)dx=\frac{1}{\sqrt{2\pi\sigma_{x}^{2}}}\exp\left[-\frac{(x-\mu_{x})^{2}}{2\sigma_{x}^{2}}\right]dx$$
$x\equiv\ln(\rho/\bar{\rho}),\quad\mu_{x}=-\sigma_{x}^{2}/2,\quad \sigma_{x}^{2}\simeq \ln(1+0.25Ma^{2})$
- velocity structure functions, $S_{2}\propto l^{\zeta(2)},\quad \zeta(2)\simeq 1.04$

### Empirical Signatures
- detection: in  massive clusters, explosive death (hypernovae, pair-instability SNe), Pop III survivors
- SNe
 -  PISN (very rare, from stars of $\sim 140-260M_{\odot}$): extended lightcurves with rest-frame plateaus lasting for one year; time-dependence in photometry towards increasingly redder colors; spectroscopy: lines of larger atomic mass number (by SN photosphere's receding into deeper layers of the exploding star)
 - core-collapse SN (much dimmer than PISN, unreachable for $z\lesssim 10$), 
 - metal-free regions which persist to lower redshifts

- GRB
 - emergence of BH remnants, enough angular momentum, the relativistic jet (lanched by the BH accretion torus) can escape from the stellar envelope
 - statistics:
 $$\frac{dN_{GRB}^{obs}}{dz}=\psi_{GRB}^{obs}(z)\frac{\Delta t_{obs}}{(1+z)}\frac{dV}{dz}$$
 $$\psi_{GRB}^{obs}(z)=\eta_{GRB}\psi_{*}(z)\int_{L_{lim}(z)}^{\infty}p(L)dL$$
 $\eta_{GRB}$: GRB formation efficiency, $\psi_{*}(z)$: star formation rate density (co-moving volume, rest-frame), $p(L)$: GRB luminosity function, $L_{lim}(z)$ minimum intrinsic luminosity for successful detection

- Nucleosynthesis, Cosmic Archaeology
 - Pop III SNe: core-collapse progenitors dominate, sign of PISN: elemental odd-even effect, complete absence of neutron-capture elements
 - carbon-enhanced extremely metal-poor (CEMP) abundance, from faint, BH-forming SNe (whose central regions with heavier elements are devoured by the BH)
 - C-enhanced & C-normal: fine-structure cooling & dust cooling

- BH Remnants
 - cumulative emission from accreting Pop III remnants at high redshifts: (soft) cosmic X-ray background (CXB)
 - reprocessed Lyman-$\alpha$ photons redshifted by a factor of 10 (which come from the strong ionizing UV radiation bottled up in the substantially neutral IGM): cosmic infrared background (CIB)
 - IMBH $\sim 100M_{\odot}$, power sources of ultraluminous X-ray sources (ULXs), possible strong feedback effects on the early IGM
