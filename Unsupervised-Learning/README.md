# Unsupervised Learning

Notes following STA 280 (Unsupervised Learning), Spring 2026.

The course is about finding structure in an unlabelled data matrix. Roughly two
halves: clustering (k-means, hierarchical, GMMs with EM, DBSCAN) and
dimensionality reduction (PCA, MDS). Along the way there's model selection for
choosing $k$, outlier detection, a note on what breaks in high dimensions, and
association rules at the end.

Most of the detail is in the derivations: where classical MDS comes from,
double centering, PCA as a regression.

Code is R, mentioned inline by function name (`prcomp`, `kmeans`, `hclust`,
`arules`) rather than written out.

The final section works through PCA and MDS on small numeric examples.
