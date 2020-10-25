

## Corrections to Original Version of Thesis


### Typos
* "[...] observations perfectly follow~~s~~ [...]"
* Eqns (3.27) and (3.29): added subscript index `i` to `ỹ` in Cost function
* Eqn (4.50): Corrected formula for width of confidence bands
* Fig 25: "[...] in ~~a~~ coordinate charts [...]"
* p. 71: "The geometric structure**s** on [...]"
* p. 85: "[...] is already known to lie **on** said boundary [...]"
* p. 85: "[...] can be used to parametrise **the level sets of** any smooth function [...]"
* p. 106: "[...] not defined for either α ≤ 0 or β ≤ 0 [...]" corrected to "[...] not differentiable for α = 0 or β = 0 [...]"
* p. 114: Corrected equation of state parameter for matter to w_m = 0.
* Bibliography: Deleted erroneous duplication of author name "Hall, Brian C." in references
* Bibliography: Corrected title of "Kullback: Information Theory and Statistics"


### Formatting
* Deleted erroneous duplication of sections 4.6 and 4.7
* Removed section numbering in appendix
* Changed section name in appendix from "[...] Program" to "[...] Programme" for consistent BE spelling
* Fig 34: Fixed bug which left central line incomplete
* p.131: Added link to associated github repository for "InformationGeometry.jl" (which had not yet been created at the time)


## Known mistakes which are not yet corrected
* There was a mistake in the implementation of a routine which draws the ellipsoidal confidence regions associated with a given covariance matrix. As a result, the ellipsoidal confidence regions obtained from the inverse Fisher metric at the MLE (i.e. via the Cramér-Rao lower bound) are drawn ≈ 30% too small. That is, while the overall shape is correct, the drawn ellipses depict confidence regions associated with lower confidence levels than was stated.
**This affects figures 31, 32 and 55**. These figures will be redone for the upcoming corrected version of the thesis.
* As a result of this error in the implementation, it was falsely stated (in several places throughout the thesis) that the estimate of covariance matrix via the Cramér-Rao lower bound underestimates the true uncertainties *even for linearly parametrised models with normal error distributions*, which, in fact, it does not. In that particular case, the CRLB provides an accurate reflection of the uncertainties in the best fit parameters.
