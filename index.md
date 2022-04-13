<script type="text/javascript" async src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/MathJax.js?config=TeX-MML-AM_CHTML"></script>
<script type="text/x-mathjax-config">
 MathJax.Hub.Config({
 tex2jax: {
    inlineMath: [ ['$','$'], ["\\(","\\)"] ],
    displayMath: [ ['$$','$$'], ["\\[","\\]"] ]
 }
 });
</script>


## VAC (Variational approach for conformation dynamics) 

### Paper
   - [Noé, Frank, and Feliks Nuske. "A variational approach to modeling slow processes in stochastic dynamical systems." Multiscale Modeling & Simulation 11.2 (2013): 635-655.](https://epubs.siam.org/doi/abs/10.1137/110858616?casa_token=uwxuLpLlceIAAAAA:eJ-FwlnByXP_kLhUA_xAEbi_AGrejTzaEuaXW3wM8Uq_GAkPw_KK3w1gdPqVO3WWY6DnE-baFOQW) \[[BibTex](./bibtex/vac.bib)\]

### Code 
  - origin :  [markovmodel/variational](https://github.com/markovmodel/variational)
  - forked : [tanaka-hiroki1989/variational](https://github.com/tanaka-hiroki1989/variational)
  - package : [markovmodel/PyEMMA](https://github.com/markovmodel/PyEMMA/tree/devel/pyemma)

### [detail](./methods/vac)

----

## VAMP (Variational approach for Marokov process)

### Paper 
  - [Wu, Hao, and Frank Noé. "Variational approach for learning Markov processes from time series data." Journal of Nonlinear Science 30.1 (2020): 23-66.](https://link.springer.com/article/10.1007/s00332-019-09567-y)

### Code 
  - pacakge :[markovmodel/PyEMMA](https://github.com/markovmodel/PyEMMA/tree/devel/pyemma)

### [detail](./methods/vamp)

----

## VAMPnets

![vampnets](https://media.springernature.com/full/springer-static/image/art%3A10.1038%2Fs41467-017-02388-1/MediaObjects/41467_2017_2388_Fig1_HTML.gif?as=webp)
### Paper 
  - [Mardt, Andreas, et al. "VAMPnets for deep learning of molecular kinetics." Nature communications 9.1 (2018): 1-11.](https://www.nature.com/articles/s41467-017-02388-1)
  \[[BibTex](https://scholar.googleusercontent.com/scholar.bib?q=info:cdgg75wUJSYJ:scholar.google.com/&output=citation&scisdr=CgXkEEvhEJeMq7TsmrE:AAGBfm0AAAAAYknpgrFU35c_nqh1iymSeVHYftvRQCHg&scisig=AAGBfm0AAAAAYknpgiRKEcrSJWoNiwSJIN7WUzFMBlEo&scisf=4&ct=citation&cd=-1&hl=ja)\]

### Code 
  - origin [markovmodel/deeptime](https://github.com/markovmodel/deeptime)

### [detail](./methods/vampnets)

----
## SRV (state-free reversible

### Paper 
  - [Chen, Wei, Hythem Sidky, and Andrew L. Ferguson. "Nonlinear discovery of slow molecular modes using state-free reversible VAMPnets." The Journal of chemical physics 150.21 (2019): 214114.](https://aip.scitation.org/doi/abs/10.1063/1.5092521)\[[BibTex](https://scholar.googleusercontent.com/scholar.bib?q=info:E2D8TWgTxmoJ:scholar.google.com/&output=citation&scisdr=CgXkEEvhEJeMq7Ts20Q:AAGBfm0AAAAAYknpw0SMgn52dSDdQCWlFwEI3W4eUAu9&scisig=AAGBfm0AAAAAYknpw_SlbLByDIYPSNUuDtA27nePqo48&scisf=4&ct=citation&cd=-1&hl=ja)\]

### Code
  - origin [hsidky/srv](https://github.com/hsidky/srv)

### [detail](./methods/srv)
----
## Molecular latent space simulator

![LSS](https://pubs.rsc.org/image/article/2020/SC/d0sc03635h/d0sc03635h-f1_hi-res.gif)
### Paper
  - [Sidky, Hythem, Wei Chen, and Andrew L. Ferguson. "Molecular latent space simulators." Chemical Science 11.35 (2020): 9459-9467.](https://pubs.rsc.org/en/content/articlehtml/2020/sc/d0sc03635h)

### Code
  - [hsidky/srv/tree/newgen](https://github.com/hsidky/srv/tree/newgen/)

----
## GDynet (Graph dynamical netowrks)

### Paper
  - [Xie, T., France-Lanord, A., Wang, Y. et al. Graph dynamical networks for unsupervised learning of atomic scale dynamics in materials. Nat Commun 10, 2667 (2019)](https://www.nature.com/articles/s41467-019-10663-6))\[[BibTex]()\]

### Code
  - origin [txie-93/gdynet](https://github.com/txie-93/gdynet)

----
## RPnet (Reverse projection based neural network)
### Paper
  - [Gu, Hanlin, et al. "RPnet: a reverse-projection-based neural network for coarse-graining metastable conformational states for protein dynamics." Physical Chemistry Chemical Physics (2022).](https://pubs.rsc.org/en/content/articlelanding/2022/CP/D1CP03622J)\[[BibTex]()\]

### Code 
  - origin [ghl1995/BpNet-limping](https://github.com/ghl1995/BpNet-lumping)

----
## GraphVAMPnet
![GraphVAMPnet](https://github.com/ghorbanimahdi73/GraphVampNet/raw/main/figure_1.png)
### Results
  1. Trpcage
  2. Villin
  3. NTL9

### Paper
  - [GraphVAMPNet, using graph neural networks and variational approach to markov processes for dynamical modeling of biomolecules](https://arxiv.org/abs/2201.04609)
  \[[BibTex]()\]

### Code
  - origin [ghorbanimahdi73/GraphVampnet](https://github.com/ghorbanimahdi73/GraphVampNet)

----
## DeepGenMSM

### Paper
  - [Wu, Hao, et al. "Deep generative markov state models." Advances in Neural Information Processing Systems 31 (2018)](https://proceedings.neurips.cc/paper/2018/hash/deb54ffb41e085fd7f69a75b6359c989-Abstract.html)

### Code
  - [amardt/DeepGenMSM](https://github.com/amardt/DeepGenMSM)

### [detail](./methods/deepgenmsm)

----
## DeepRevMSM

### Paper
  - [Mardt, Andreas, et al. "Deep learning Markov and Koopman models with physical constraints." Mathematical and Scientific Machine Learning. PMLR, 2020.](https://proceedings.mlr.press/v107/mardt20a.html)

### Code
  - origin [markovmodel/deep_rev_msm](https://github.com/markovmodel/deep_rev_msm)
  - forked [tanaka-hiroki1989/deep_rev_msm](https://github.com/tanaka-hiroki1989/deep_rev_msm)

----
## iVAMPnets (independent Markov decomposition with VAMPnets)

### Paper
  - Preprint [Deep learning to decompose macromolecules into independent Markovian domains](https://www.biorxiv.org/content/10.1101/2022.03.30.486366v1)
### Code
  - origin [markovmodel/ivampnets](https://github.com/markovmodel/ivampnets)
  - forked [tanaka-hiroki1989/ivampnets](https://github.com/tanaka-hiroki1989/ivampnets)

## Galerkin approximation

# Paper
  - https://aip.scitation.org/doi/10.1063/1.5063730