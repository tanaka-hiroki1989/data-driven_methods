<script type="text/javascript" async src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/MathJax.js?config=TeX-MML-AM_CHTML"></script>
<script type="text/x-mathjax-config">
 MathJax.Hub.Config({
 tex2jax: {
 inlineMath: [['$', '$'] ],
 displayMath: [["$$","$$"]]
 }
 });
</script>


## VAC (Variational approach for conformation dynamics) 
### Concept
 Given a (classical) molecular dynamics trajectory with configurations $\{x_1, ..., x_T\}$, and a set of basis functions defined on the space of configurations $\{\chi_1(x), \dots, \chi_n(x)\}$, we compute the two correlation matrices:

$$c_{ij}(0) = \langle \chi_i(x_t) \chi_j(x_t) \rangle_t c_{ij} (\tau) = \langle \chi_i(x_t) \chi_j(x_t+\tau) \rangle_t$$

where < . >_t is average over time t. Of course this can be generalized to many trajectories. Then we solve the generalized eigenvalue problem

\\[C(tau) r = C(0) r l(tau)\\]

where the eigenvalues l(tau) approximate the dominant eigenvalues of the Markov propagator or Markov backward propagator of the underlying dynamics. The corresponding eigenfunction of the backward propagator is approximated by

\\[psi(x) = sum_i r_i chi_i(x)\\]
### Paper
   - [Noé, Frank, and Feliks Nuske. "A variational approach to modeling slow processes in stochastic dynamical systems." Multiscale Modeling & Simulation 11.2 (2013): 635-655.](https://epubs.siam.org/doi/abs/10.1137/110858616?casa_token=uwxuLpLlceIAAAAA:eJ-FwlnByXP_kLhUA_xAEbi_AGrejTzaEuaXW3wM8Uq_GAkPw_KK3w1gdPqVO3WWY6DnE-baFOQW) \[[BibTex](https://scholar.googleusercontent.com/scholar.bib?q=info:RhTGZVmWE7UJ:scholar.google.com/&output=citation&scisdr=CgXkEEvhEJeMq7TiUXU:AAGBfm0AAAAAYknnSXW1wyMGIRm2SR6LtN8sa2wE3PeX&scisig=AAGBfm0AAAAAYknnSRp2gIsftp0CyOjZTbgoVfIFyPxE&scisf=4&ct=citation&cd=-1&hl=ja)\]

### Code 
  - origin :  [markovmodel/variational](https://github.com/markovmodel/variational)
  - forked : [tanaka-hiroki1989/variational](https://github.com/tanaka-hiroki1989/variational)
  - [markovmodel/PyEMMA](https://github.com/markovmodel/PyEMMA/tree/devel/pyemma)
## VAMP (Variational approach for Marokov process)
### Paper 
  - [Wu, Hao, and Frank Noé. "Variational approach for learning Markov processes from time series data." Journal of Nonlinear Science 30.1 (2020): 23-66.](https://link.springer.com/article/10.1007/s00332-019-09567-y)\[[BibTex](https://scholar.googleusercontent.com/scholar.bib?q=info:lFqWUORfdYEJ:scholar.google.com/&output=citation&scisdr=CgXkEEvhEJeMq7TtHvg:AAGBfm0AAAAAYknoBvg9-0MnwBBYw8z-zyOyYvoUaX1h&scisig=AAGBfm0AAAAAYknoBr-8uwhO_ozQlTzTL2iO78giH7Y1&scisf=4&ct=citation&cd=-1&hl=ja)\]
### Code 
  - [markovmodel/PyEMMA](https://github.com/markovmodel/PyEMMA/tree/devel/pyemma)

## VAMPnets
### Paper 
  - [Mardt, Andreas, et al. "VAMPnets for deep learning of molecular kinetics." Nature communications 9.1 (2018): 1-11.](https://www.nature.com/articles/s41467-017-02388-1)
  \[[BibTex](https://scholar.googleusercontent.com/scholar.bib?q=info:cdgg75wUJSYJ:scholar.google.com/&output=citation&scisdr=CgXkEEvhEJeMq7TsmrE:AAGBfm0AAAAAYknpgrFU35c_nqh1iymSeVHYftvRQCHg&scisig=AAGBfm0AAAAAYknpgiRKEcrSJWoNiwSJIN7WUzFMBlEo&scisf=4&ct=citation&cd=-1&hl=ja)\]
### Code 
  - origin [markovmodel/deeptime](https://github.com/markovmodel/deeptime)

## SRV (state-free reversible VAMPnets)
### Paper 
  - [Chen, Wei, Hythem Sidky, and Andrew L. Ferguson. "Nonlinear discovery of slow molecular modes using state-free reversible VAMPnets." The Journal of chemical physics 150.21 (2019): 214114.](https://aip.scitation.org/doi/abs/10.1063/1.5092521)\[[BibTex](https://scholar.googleusercontent.com/scholar.bib?q=info:E2D8TWgTxmoJ:scholar.google.com/&output=citation&scisdr=CgXkEEvhEJeMq7Ts20Q:AAGBfm0AAAAAYknpw0SMgn52dSDdQCWlFwEI3W4eUAu9&scisig=AAGBfm0AAAAAYknpw_SlbLByDIYPSNUuDtA27nePqo48&scisf=4&ct=citation&cd=-1&hl=ja)\]
### Code
  - origin [hsidky/srv](https://github.com/hsidky/srv)

## GDynet
### Paper
  -\[[BibTex]()\]
### Code
  - origin [txie-93/gdynet](https://github.com/txie-93/gdynet)

## RPnet
### Paper
  - \[[BibTex]()\]
### Code 
  - origin [ghl1995/BpNet-limping](https://github.com/ghl1995/BpNet-lumping)

## GraphVAMPnets
### Paper
  - (https://arxiv.org/abs/2201.04609)
  \[[BibTex]()\]
### Code
  - origin [ghorbanimahdi73/GraphVampnet](https://github.com/ghorbanimahdi73/GraphVampNet)

## DeepGenMSM
### Paper
### Code
