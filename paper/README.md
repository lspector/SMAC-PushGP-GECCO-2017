# An experience report on using SMAC to optimize PushGP parameters

The basic outline is something like:

* Introduction that sets up what SMAC is and what we were doing with it
* Background: What is SMAC. (Or should that just be in the introduction?)
* What Morris folks did with SMAC in August
* What @thelmuth did applying those parameters to 5 problems
* Some discussion of what we learned and what this means
* Future work:
  * Use SMAC to tune parameters on the other four problems one at a time, and
    see how that works on the other problems.
  * Use SMAC to tune on (sub)sets of the problems, like all 5, or on subsets
    that seem similar (or different) based on the individual tuning.

## Notes

Cite Fast Bayesian Optimization of Machine Learning Hyperparameters on Large Datasets http://arxiv.org/abs/1605.07079

More generally, we'll need to have at least some lit review that highlights
the huge amount of work that's been done on trying to optimize parameters,
from early work on things like population size and mutation rates in GAs to
more modern things like SMAC (which can't be the only thing out there that does
this kind of thing).
