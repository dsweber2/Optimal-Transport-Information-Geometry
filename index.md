# Course Outline

We are doing a reading course on optimal transport in the context of graphs and its ties with information geometry. A list of possible papers can be found [here.](https://www.math.ucdavis.edu/~saito/data/acha.read.s19/) What follows are a list of relevant papers beyond these. When it is your week to present, please add any relevant papers to the list. To add your references, [edit here](https://github.com/dsweber2/optimalTransportInfoGeo/edit/master/index.md).

### Meeting time: Fridays at 1:30pm, 2240 MSB

## [April 12th, and 19th](https://doi.org/10.1109/MSP.2017.2695801): Optimal Mass Transport: Signal processing and machine-learning applications
*Presenter*: Yiqun Shao
### Relevant Papers: 
[38, Otto, 2001](https://doi.org/10.1081/PDE-100002243): the paper that presented the 2-Wasserstein space as a Riemannian metric derived from a Variational problem.

[40, Park et al, 2018](https://doi.org/10.1016/j.acha.2017.02.002)([Arxiv](https://arxiv.org/abs/1507.05936]): The paper that transforms optimal transport into a Euclidian space in 1D via preserving distances to a reference distribution. It makes density functions separable after the transform.

[Santambrogio 2015](https://doi.org/10.1007/978-3-319-20828-2): Optimal transport for the applied mathematician. Good reference book for further reading.

[50, W. Wang, D. Slepcev, S. Basu, J. A. Ozolek, and G. K. Rohde](https://link.springer.com/content/pdf/10.1007%2Fs11263-012-0566-z.pdf) “A linear opti- mal transportation framework for quantifying and visualizing variations in sets of images,” The original LOT.

[14, M. Cuturi](https://arxiv.org/pdf/1306.0895.pdf) “Sinkhorn distances: Lightspeed computation of optimal trans- port” Using the entropy penalty term to compute optimal transport map fast.

[26, S. Kolouri and G. K. Rohde](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Kolouri_Transport-Based_Single_Frame_2015_CVPR_paper.pdf) “Transport-based single frame super resolution of very low resolution face images”. Single frame superresolution using PCA on transport map.

## [April 26th](https://doi.org/10.1137/17M1132665): Quadratically-Regularized Optimal Transport on Graphs
*Presenter*: Shaofeng Deng
### Relevant Papers:
[D. Knowles](https://cs.stanford.edu/people/davidknowles/lagrangian_duality.pdf) Lagrangian Duality for Dummies!

[Davis, T.A., 2011](https://pdfs.semanticscholar.org/e560/62bcea9184bebf26cfe4c46d72022198e6e6.pdf) This paper shows how to update the pseudo inverse of a graph Laplacian given a rank-1 change via Cholesky factorization.

[Graph Laplacian](http://www.cis.upenn.edu/~cis515/cis515-14-graphlap.pdf) A good tutorial on graph laplacian.

## [May 3rd](https://papers.nips.cc/paper/4927-sinkhorn-distances-lightspeed-computation-of-optimal-transport): Sinkhorn Distances: Lightspeed Computation of Optimal Transportation Distances
*Presenter*: Dong Min Roh
### Relevant Papers:
[T. Cover, J. Thomas; CH.2](http://www.cs-114.org/wp-content/uploads/2015/01/Elements_of_Information_Theory_Elements.pdf) Introduction to Entropy

[P. Knight](http://www.cerfacs.fr/algor/reports/2006/TR_PA_06_42.pdf) Sinkhorn-Knopp Algorithm


## [May 17th](https://doi.org/10.1007/s41884-018-0002-8): Information geometry connecting Wasserstein distance and Kullback–Leibler divergence via the entropy-relaxed transportation problem
*Presenter*: Haolin Chen
### Relevant Papers:
[Amari 2016](https://link.springer.com/content/pdf/10.1007/978-4-431-55978-8.pdf): Information geometry and its applications

[Cuturi 2013](https://papers.nips.cc/paper/4927-sinkhorn-distances-lightspeed-computation-of-optimal-transport.pdf): Sinkhorn distances: Lightspeed computation of optimal transport


## [May 24th](https://doi.org/10.1007/s41884-018-0002-8): Information Geometry for Regularized Optimal Transport and Barycenters of Patterns
*Presenter*: David Weber
### Relevant Papers:
[Amari 2016](https://doi.org/10.1007/978-4-431-55978-8) Recent reference on information geometry for machine learning by Amari.

[Determinant of Block Matrices](https://en.wikipedia.org/wiki/Determinant#Block_matrices) used in the proof of convexity of $D_\lambda$

[Sherman-Morrison formula](https://en.wikipedia.org/wiki/Sherman%E2%80%93Morrison_formula) used in the proof of convexity of $D_\lambda$

[Agueh & CarlieEnr, 2011](https://doi.org/10.1137/100805741) ([preprint](https://www.ceremade.dauphine.fr/~carlier/AC_bary_Aug11_10.pdf)): Demonstration that the Barycenters of the Wasserstein metric are translation invariant.


[Cuturi & Doucet, 2014](http://proceedings.mlr.press/v32/cuturi14.html): uses the C-function to compute Barycenters.

## [May 31st](https://arxiv.org/abs/1806.01364): The data-driven Schroedinger bridge
*Presenter*: Haotian Li
### Relevant Papers:


## [June 19th](https://arxiv.org/abs/1311.4581): Application of the Wasserstein metric to seismic signals
*Presenter*: Bohan Zhou
### Relevant Papers:
[Engquist_2018_Seismic_Inversion](https://arxiv.org/pdf/1810.08686.pdf): Data normalization techs for pre-processing seismic data.

[Engquist_2018_Seismic_Imaging](https://arxiv.org/pdf/1808.04801.pdf): A review for seismic inversion problem and the application of optimal transport.

[Plessix_2006_Review](https://watermark.silverchair.com/167-2-495.pdf?token=AQECAHi208BE49Ooan9kkhW_Ercy7Dm3ZL_9Cf3qfKAc485ysgAAAkowggJGBgkqhkiG9w0BBwagggI3MIICMwIBADCCAiwGCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQMtwH_Y5dwf_sJaqarAgEQgIIB_U4AnZraIx-MqYfoRxHLqKFnXYV7KbCZ7riV5RDiHwzzVlYzMUjMNt3twlIbb2gCpnAcA9QUvWbndDlyO9hx8lq45M3Lpj9tRGNMnidH99aUCfcPrGuWomy7PgNMIGEC1Zhz4QV9rs01X6u5VDJSnVqR7lN_UJQdgaK50EOZ_wKpW2WYu4MXbiLT6puT3DxMT53gue7Z1Ox7N1L8cPJuwhwjFgHK4ARot2sO5ep1yHDH8W1cD6as3Tbv2151Yg_K_quiMCTJWbDUIQsLti3ZOy5mFhS2o-f0PkUDn3fxeg-ueWEZ0mi10kHt7ButRwiTPF1zocd1dYDxmCunu9IcfGdi3jBBqq_1TZT4aVNlxnm4V42adUvpcBIDVz6U5emlgLHflDe4IATZDdV7iL-WEiiA52HdnRHVUyPMaYW-5Vemw_BcokiQcLfLiPTJXOzfDa82m5ZdTJwB8XQc9YrrMFgUwSKhGDZwyhYsauOQ8NV2_Fh6oE3yj_3FiYuh8cMHgO4LtFABxAOuZJULH2ufq1ZzL8hOZhZ550zpaUatfF6iDXGFm-bNLWLUjGq4kCbEbI_f8YV0EWEo2ydRNaPdbyuHtQXfnY7stzycgN_XgXmh68S8rS5vOIuAEBJRUTH6opRdE0V1pUZk8kOrqYBhEeNbmfASkuRMTElZiDCm): A review of the adjoint-state method for computing the gradient
of a functional with geophysical applications.

[Yang_2017_Analysis](https://www.researchgate.net/profile/Yunan_Yang/publication/316883585_Analysis_of_optimal_transport_and_related_misfit_functions_in_FWI/links/59dcbb40458515e9ab4d6b1e/Analysis-of-optimal-transport-and-related-misfit-functions-in-FWI.pdf): Analysis of misfit functions.

[Engquist_2013_Application](https://www.math.ucdavis.edu/~saito/data/acha.read.s19/engquist-froese_wasserstein-metric-for-seismic-signals.pdf): Basic property to be satisfied before applying Wasserstein distance.

[Bradley_2013_adjoint method](https://cs.stanford.edu/~ambrad/adjoint_tutorial.pdf): A manual for PDE-constrained optimization and the adjoint method from the beginning.



## [The Future](https://doi.org/10.1007/s00205-017-1192-2): Optimal Micropatterns in 2D Transport Networks and Their Relation to Image Inpainting
*Presenter*: Theodore Eberts
### Relevant Papers:
