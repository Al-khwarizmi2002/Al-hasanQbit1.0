# 10.2.1 Nonholomonic Process:
a system that does not return to its original state when transported around a closed loop
![nonholonomic.png](../../Desktop/Graduation Prodject/Quantum/nonholonomic.png)
area of this portion $A=(\frac{1}{2})(\frac{\Theta}{2\pi})4\pi R^2=\Theta R^2$
So the solid angel $\Omega=\frac{A}{R^2}=\Theta$
this answer is independent of the shape of the path.
	For a pendulum of latitude line $\theta_0$  the solid angle $\Omega=\int Sin\theta d\theta d\phi=2\pi(1-cos\theta_0)$

## 10.2.2 Geometric Phase__
$\gamma _n (t)=i \int_{0}^{t}{\large{\lang}}\psi _n (t')|\frac{\partial}{\partial t'}\psi _n (t'){\large{\rang} }dt'$
	$\psi$ depends on t because there is some parameter R(t) in the Hamiltonian that is changing with time.
$\gamma _n (t)=i \int_{R_i}^{R_f}{\large{\lang}}\psi _n (t')|\frac{\partial}{\partial R}\psi _n (t'){\large{\rang} }dR$ 				10.42
if the hamiltonian returns to its original form after time T, then $R_f =R_i$
So $\gamma_n (T)=0$ 
for a more interisting view suppose there are N parameters that depend on time.
equ(10.43) $\frac{\partial \psi_n}{\partial t}=\frac{\partial \psi_n}{\partial R_1}\frac{\partial R_1}{\partial t}+\frac{\partial \psi_n}{\partial R_1}\frac{\partial R_2}{\partial t}+.....=(\nabla_R \psi_n).\frac{dR}{dt}$
$\gamma _n (t)=i \int_{R_i}^{R_f}{\large{\lang}}\psi _n (t')|\nabla _R\psi _n (t'){\large{\rang} }. dR$
for a hamiltonian that returns to its original form after a Time T
$\gamma _n (T)=i \oint{\large{\lang}}\psi _n (t')|\nabla _R\psi _n (t'){\large{\rang} }.dR$  equ(10.45)
$\theta _n (T)=-\frac{1}{\hbar}\int_{0}^{T} e_n (t')dt'$.
a line integral around a closed loop 
$\gamma _n (T)$ Berry's phase : depends on path taken, [not how fast] 
$\phi _n (T)$ dynamic Phase : depends on elapsed time.
- suppose a beam of particles is split into 2:
    - one pass in an adiabatically changing potential, the other not.
    - $\psi = \frac{1}{2}\psi_0 +\frac{1}{2}\psi_0 e^{i\Gamma}$.
- $\Gamma$is the extra phase acquired by the beam.
- $|\psi|^2=\frac{1}{4}|\psi _0|^2(1+e^{i\Gamma})(1+e^{-i\Gamma})$
- $|\psi|^2=|\psi _0|^2 cos^2 (\frac{\Gamma}{2})$.
$\Phi=\int_S B . da$
$B=\nabla\times A$ sub the apply stokes' theorem:
$\Phi=\oint _c A.dr$
- **thus the Berry's phase can be thought as the flux of a magnetic field**
$"B”=i\nabla _R \times \lang \psi _n |\nabla _R \psi _n\rang$,

$\gamma _n (t)=i \int_{R_i}^{R_f}{\large{\lang}}\psi _n (t')|\nabla _R\psi _n (t'){\large{\rang} }. dR$
can be written as 
$\gamma _n (t)=i \int[ \nabla _R \times{\large{\lang}}\psi _n (t')|\nabla _R\psi _n (t'){\large{\rang} }]. da$         10.51
we chose R as the Parameter that changed
i.e increasing the width of the square well then $R=w$

Examble 10.2
let the magnetic field swipe an area of a sphere
when solving the berry phase 
$\gamma _+ (T)=-\frac{1}{2}\Omega$
where $\Omega$ is the Solid angle susbended by the origin


## The Aharonov-Bohm Effect
in classical electrodynamics  $E=-\nabla\phi-\frac{\partial A}{\partial t}$

in quantum mechanics the  hamiltonian is expressed by $\phi$ and A not __E__ and B
$H=\frac{1}{2m}(\frac{\hbar}{i}\nabla-qA)^2+q\phi$
Aharonov and bohm showed that vector potential can affect the quantum behavior of a charged particle even when moving through a region where field is zero.

- imagine a particle moving in a circle of radius b (in a wire ring)
- along the axis runs a solenoid of radius a<b (carrying a steady current I)
- let the magnetic field inside is uniform  and out side is zero
- the vector potential outside is non-zero A
- adopting to $\nabla.A=0$
    - $A=\frac{\Phi}{2\pi r}\hat{\phi}$      for r>a
- $\Phi$ is the magnetic flux $\Phi=\pi a^2 B$
- is this case the Hamiltonian become
$H=\frac{1}{2m}(\frac{\hbar}{i}\nabla-qA)^2+q\phi$
$H=\frac{1}{2m}[-\hbar^2 \nabla ^2 -2\frac{\hbar}{i}qA\nabla + (qA)^2 +q\phi]$
let$\phi=0$
the wave function depends only on azimuthal angel $\phi$
$\nabla \rightarrow (\frac{\hat{\phi}}{b})\frac{d}{d\phi}$
so $H=\frac{1}{2m}[-\frac{\hbar^2}{b^2}\frac{d^2}{d\phi ^2}+\cancel{2}i\hbar q (\frac{\Phi}{\cancel{2}\pi r}).\frac{1}{b}\frac{d}{d\phi}+q^2 (\frac{\Phi}{2\pi r})^2]$
applying the hamiltonian on the wave function
$\frac{d^2 \psi}{d \phi ^2}-2i\beta\frac{d\psi}{d\phi}+\epsilon\psi=0$
        $\beta=\frac{q\Phi}{2\pi \hbar}$  ,          $\epsilon =\frac{2mb^2 E}{\hbar ^2}-\beta^2$
  this equation have a solution in the form $\psi =A e^{i\lambda \phi}$
  $\lambda=\beta \pm \sqrt{\beta ^2 +\epsilon}$ =n             10.72
“**[ continuity of $\psi$ requires that $\lambda$ be an integer n]**”
$E_n =\frac{\hbar ^2}{2mb^2}(n-\frac{q\Phi}{2\pi\hbar})^2$
$n=0,\pm 1,\pm 2,\dots$
positive n represents particles moving in the same direction as the current.(has lower energy)
negative n particles travel in the opposite direction .
__**allowed energies depend on the field inside the solenoid even though the field at the location of the particle is zero**__

assuming A is static and generalizing the method to time-dependent potentials.
$i\hbar\frac{\partial\psi}{\partial t}=[\frac{1}{2m}(\frac{\hbar}{i}\nabla-qA)^2+V]\psi$     __10.75__
→→ →    [this can be simplified by $\psi=e^{ig}\psi'$] __10.76__
$g(r)=\frac{q}{\hbar}\int_{\mathcal{O}}^{r}A(r').dr'$
$\mathcal{O}$ is an arbitrary reference point
**the definition makes sense only when $\nabla\times A$ or the line integral would depend on the path**
$\psi=e^{ig}\psi'$
so $\nabla \psi = e^{ig}\nabla \psi ' +\psi ' i e^{ig}\nabla g$ 				,$\nabla g =\frac{q}{\hbar}A$
$-i\hbar\nabla =\frac{\hbar}{i}e^{ig}\nabla \psi '+\frac{\hbar}{i}i\psi\frac{q}{\hbar}A$

→ → → $(\frac{\hbar}{i}\nabla-qA)\psi=\frac{\hbar}{i}e^{ig}\nabla\psi'$
-->>  $(\frac{\hbar}{i}\nabla-qA)^2\psi=-\hbar ^2 \ \ \ \underline{e^{ig}}\ \ \ \nabla ^2 \psi'$      __10.79__
$i\hbar\frac{\partial\psi}{\partial t}=[\frac{1}{2m}(\frac{\hbar}{i}\nabla-qA)^2+V]\psi=i\hbar\frac{\partial\psi}{\partial t}$     __10.75__
sub 79 in 75.

$-\frac{\hbar^2}{2m}\nabla ^2 \psi ' +V \psi ' =i\hbar\frac{\partial\psi '}{\partial t}$
- $\psi '$ satisfies the $schr\"{o}dinger$ equation without $A$
**if we can solve equ 10.80 correcting for the presence of a vector potential will be trivial :just tack on the phase factor $e^{ig}$.**
- Aharonov and Bohm proposed as experiment
    - the beam is split to bath on each side of a solenoid.
    - the region is $B=0$ but $A\neq 0$
        - $A=\frac{\Phi}{2\pi r}\hat{\phi}$      ,      $g(r)=\frac{q}{\hbar}\int_{\mathcal{O}}^{r}A(r').dr'$
- $g=\pm\frac{q\Phi}{2\hbar}$
-  
![655*384](/home/al-khwarizmi/Desktop/Graduation Prodject/Quantum/ahonov.png "655*384")
- plus for electrons traveling with $A$ , so the beam arrives out of phase by and amount proportional to the magnetic flux the path encircle.
- the phase shift leads to measurable interference.
- this effect van be regarded as an example of geometric phase
### Berry's point of view  

let  a box  confine charges with potential$V(r-R)$
transport the box adiabatically around the solenoid.
- R will become a function of time.
- write the Hamiltonian
- and calculate g
- we find that $\psi '$ satisfies the same eigenvalue equation for $A$ → 0
- **Why does this process don't have to be adiabatic?????**    equ 10.86
- $\gamma _n (T)=i \oint{\large{\lang}}\psi _n (t')|\nabla _R\psi _n (t'){\large{\rang} }.dR$
- to determine the Berry's Phase we evaluate $\lang\psi _n |\nabla _R \psi _n\rang$
- **redo 10.87**
- Aharonov-Bohm effect is a particular instance of geometric phase.
- 
