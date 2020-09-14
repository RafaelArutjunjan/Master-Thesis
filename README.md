# Master-Thesis
Collection of materials related to my master's thesis on the topic of information geometry.


Summary
-------
In essence, my thesis discusses ways to generalise simultaneous confidence regions to so-called parameter manifolds in the context of information geometry. In addition, given a dataset and candidate model for its description, an efficient method for determining exact confidence regions irrespective of the chosen parametrisation of a model is developed.

A handout of the slides of a talk aimed at introducing and defending the results of said thesis is also provided.


Corrections
-----------
In addition to the original version that was handed in officially, I will retain the right to also publish updated revisions of my thesis, where typos and formatting errors are incrementally corrected as I find them. In general, I recommend using the newest version.

Changes so far:
* Deleted erroneous duplication of sections 4.6 and 4.7
* Removed section numbering in Appendix


## Numerical Implementation
An implementation of the methods which were developed and discussed in my thesis have been published as the [InformationGeometry.jl](https://github.com/RafaelArutjunjan/InformationGeometry.jl) package for the [Julia](https://github.com/JuliaLang/julia) programming language. A detailed guide explaining its use will follow soon.


Contact
-------
If you should have any questions regarding the provided materials or contents of the thesis, feel free to [message me at arutjunjan.r@gmail.com](mailto:arutjunjan.r@gmail.com?subject=[GitHub]%20Master-Thesis).


Citation
--------
```
@mastersthesis{GeometricParameterInference,
  author       = {Rafael Arutjunjan},
  title        = {On the Geometric Foundation of Parameter Inference},
  school       = {Friedrich-Alexander University Erlangen-Nürnberg},
  year         = {2020},
  month        = {August},
	type				 = {Master's thesis},
  url          = {https://github.com/RafaelArutjunjan/Master-Thesis},
}
```
