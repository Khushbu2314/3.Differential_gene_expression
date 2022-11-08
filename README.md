# Differential_gene_expression
In the Differential gene expression the NDB1,NDB2,NDB3,NDB4 are assumed to be tumor and DCB1,DCB2,DCB3,DCB4,DCB5 are assumed to be control

Basic syntax:

vec1= gene[i,tumor]
vec2= gene[i,control]

Log2fc=
mean(vec1) - mean(vec2)

Interpretation: A enhanced volcano plot is generated ,where positive are upregulated and negative are downregulated genes.
