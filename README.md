# About me

I am a physicist by training, with a PhD in astrophysics. My main research interest for the past several years has been the application of machine learning techniques to science, particularly astronomy.

## Interpretable machine learning for scientific research
In 2014 -back when I was at Yonsei University, Korea- I started taking part in Kaggle competitions and I was hooked. I realized that machine learning would forever change the way we do science, as much and more than the arrival of the ability to do computer simulations had already done compared to the days of pen-and-paper calculations. But would it do so for the better? Was it going to be a positive or negative development?

After securing two Marie Curie grants to apply machine learning to astronomy and publishing about twenty papers on the subject, I understood that the kind of tools we need in scientific research do not fully overlap with those that are being developed by and for industry. Cynthia Rudin famously argued that we should [stop explaining black box machine learning models for high stakes decisions and use interpretable models instead](https://www.nature.com/articles/s42256-019-0048-x). But why stop at high stakes decisions? While many decisions we take in science are low stakes in that they do not directly affect people in the way the now infamous COMPAS software did, we still need transparent models for different reasons. The _point_ of research is to understand what is going on, so a black-box prediction simply won't cut it. Explaining it a posteriori with [XAI tools](https://christophm.github.io/interpretable-ml-book) is like looking at one of those intuitive explanations of a theorem, where at the end you feel cheated of the confidence that comes from rigorously established results.

But how are you going to set up a fully interpretable classifier for a problem where the decision boundary is a fractal, like in [some gravitational dynamics situations](https://gitlab.com/mariomario/3bodyclassifierxai)? That's the kind of questions I am pondering these days.

## Causality and the social sciences

Thanks to [my wife](https://nadiiamatsiuk.com) I had the opportunity to learn about many topics in statistics that are often overlooked by physicists. [As Cosma Shalizi puts it](http://bactra.org/weblog/517.html) statistical physicists do not learn any statistics. While things have definitely changed from 2006, we certainly still do not get to learn a bunch of beautifully clever and [subtly controversial](https://mungowitzend.blogspot.com/2015/09/friends-dont-let-friends-do-iv.html) methods for teasing out causal information from observational data, such as [regression discontinuity](https://en.wikipedia.org/wiki/Regression_discontinuity_design), [instrumental variables](https://en.wikipedia.org/wiki/Instrumental_variables_estimation), or [matching](https://en.wikipedia.org/wiki/Propensity_score_matching). But economists do.

Of course experiments are better than quasi experiments if you can afford to run one, but we are not going to experimentally set off supernovas in the Collinder 135 star cluster anytime soon, so behold the first ever application of regression discontinuity to astronomy in Fig. 9. of [this paper of mine](https://arxiv.org/abs/2106.07658).
