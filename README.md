# Missingno-Tutorial-
Missingno Tutorial 

quickstart

Matrix
The msno.matrix nullity matrix is a data-dense display which lets you quickly visually pick out patterns in data completion.

Bar
msno.bar is a simple visualization of nullity by column: 
You can switch to a logarithmic scale by specifying log=True. bar provides the same information as matrix, but in a simpler format.

Heatmap
The missingno correlation heatmap measures nullity correlation: how strongly the presence or absence of one variable affects the presence of another:
Nullity correlation ranges from -1 (if one variable appears the other definitely does not) to 0 (variables appearing or not appearing have no effect on one another) to 1 (if one variable appears the other definitely also does).

Dendrogram
The dendrogram allows you to more fully correlate variable completion, revealing trends deeper than the pairwise ones visible in the correlation heatmap:
