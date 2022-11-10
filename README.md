# Surrogate Source Model Learning for Determined Source Separation

Code to reproduce the results in the paper ["Surrogate Source Model Learning for Determined Source Separation"](https://ieeexplore.ieee.org/abstract/document/9414255)

:warning: **The code to train IVA models as described in this paper was shared in the [torchiva](https://github.com/fakufaku/torchiva) package.**
Please refer to its [documentation](https://torchiva.readthedocs.io/en/latest/) for more details.

## Abstract

SURROGATE SOURCE MODEL LEARNING FOR DETERMINED SOURCE SEPARATIONRobin Scheibler and Masahito TogamiLINE Corporation, Tokyo, JapanABSTRACTWe  propose  to  learn  surrogate  functions  of  universal  speech  pri-ors  for  determined  blind  speech  separation.    Deep  speech  priorsare highly desirable due to their superior modelling power, but arenot  compatible  with  state-of-the-art  independent  vector  analysisbased  on  majorization-minimization  (AuxIVA),  since  deriving  therequired  surrogate  function  is  not  easy,  nor  always  possible.   In-stead, we do away with exact majorization and directly approximatethe surrogate.   Taking advantage of iterative source steering (ISS)updates,  we  back  propagate  the  permutation  invariant  separationloss through multiple iterations of AuxIVA. ISS lends itself well tothis task due to its lower complexity and lack of matrix inversion.Experiments  show  large  improvements  in  terms  of  scale  invariantsignal-to-distortion  (SDR)  ratio  and  word  error  rate  compared  tobaseline methods.  Training is done on two speakers mixtures andwe experiment with two losses, SDR and coherence.  We find thatthe  learnt  approximate  surrogate  generalizes  well  on  mixtures  ofthree and four speakers without any modification.  We also demon-strate generalization to a different variation of the AuxIVA updateequations.  The SDR loss leads to fastest convergence in iterations,while  coherence  leads  to  the  lowest  word  error  rate  (WER).  Weobtain as much as36 %reduction in WER.

## Authors

* Robin Scheibler
* Masahito Togami
