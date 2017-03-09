# Understanding AGN Accretion Disks based on 3D Global Radiation MHD Simulations with Realistic Opacity
## Yanfei Jiang

### Basics
- Super-Eddington
Optically thick, geometric thick
ULX, TDEs
- Sub-Eddington
OP thick, GEO thin
Soft state XRBs, Quasars
- Very low accretion rate
OP thin, GEO thin
galactic center

- alpha disk model
$ \tau_{r\phi}=\alpha P $, viscos heating is balanced by local radiative cooling (optically thick)
- time scale
$ t_{\phi}=1/\Omega=0.51 \text{day}\left(\frac{M_{BH}}{10^{8}M_{\odot}}\right) $, $t_{th}=\alpha^{-1}t_{\phi}$, $t_{\nu}=(R/H)^{2}t_{th}$

- MRI: angular momentum transfer

### puzzles
- AGN disks are too large (**the inner edge**, compared with the prediction of the thin disk model)
- AGN spectrum, short wavelength cut-off
dust? cloud?
- Change look AGNs
$ t=1300\text{yr}(\alpha/0.1)^{-1}(\lambda_{\text{Edd}}/0.005)^{-2}(\eta/0.1)^{2}(r/10r_{g})^{7/2}(M_{8}/2.0) $

### Simulation
- ideal MHD with accretion radiation (photon) momentum and energy source terms
- radiation pressure is a tensor
- opacity, He, irons..., solar mass BH mainly free-free
- Radiation pressure dominated thin disks with electron scattering opacity are thermally unstable
$ Q^{+}\propto\frac{R^{2}_{r}}{\Sigma} $, while $ Q^{-}\propto\frac{P_{r}}{\Sigma} $
- **metalicity leads to stability**

- initial conditions: configuration of magnetic fields and mass distribution at the outer region
- boundary conditions: horizon: inflow only, outher shell: outflow only 
- logarithmic scaled grid with fixed size in spherical coordinates

- density waves & AM transfer
- radiation contributes a lot to AM transfer
- thin disks (sub-Edd): perpendicular outflows (photons)

- other methods? 
Not suitable for high-precison MHD simulation

