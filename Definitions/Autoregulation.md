202205172223
Status: #definition
Tags: #gene-expression #regulation 

# Autoregulation
## Genes

The process through which the product that results from gene expression somehow contributes in regulating the expression of this gene (or gene set). There is a variety of regulatory strategies. Having a combination of these regulatory strategies allows a relatively small number of inputs to regulate thousands of genes independently ([[Multiplex]]).

### Introduction
Every (somatic) cell contains all the genetic information available ([[Genome]]). Different cells express different genes. *How* does a cell know which to express to serve its purpose? Through regulatory mechanisms. *Why* is this the case? These mechanisms evolved very early in the timeline of life on earth, because single-celled organisms had an advantage if they only expressed the genes that code for proteins that are needed by the cell in a given moment.
```ad-example
collapse: open
If the resource the cell needs is plentiful nearby, it should stop self-producing it to save energy. If it is sparse, it needs to kickstart production in order to survive. This is self-regulating metabolic control.

```

### Categories
Negative and positive gene regulation are both methods by which signaling molecules interact with [[Operator]]s, [[Repressor]]s and [[Promoter]]s to regulate the frequency with which certain genes are expressed.

In negative gene regulation, signaling molecules **interact with repressor proteins** that dictate whether genes will be expressed. They do not interact directly with DNA.
```ad-example
collapse: open
Repressing gene expression, or deactivating a repressor.

```

In positive gene regulation, signaling molecules generate a complex that **interacts with DNA** (common in Eukaryotes!).
```ad-example
collapse: open
A signaling molecule like cAMP, will bind to a protein called an activator, which will then bind to DNA and directly stimulate gene expression by increasing the affinity that RNA polymerase has for the promoter.

```

#### Feedback Inhibition

The products of certain enzymatic pathway act as inhibitors for these pathways: if a certain compund accumulates in the cell, it slows down the pathway by which it was generated, inhibiting further production.

Bacterial cells utilize [[Operon]]s. Eukaryotes don't have these, but they're a good starting point (less complex).

A gene can be typically ON unless repressed:
```ad-example
collapse: open
A metabolic pathway present in *E. coli*.
Tryptophan is synthesized in 3 steps, with each step catalyzed by a different enzyme, and it takes a total of 5 genes to produces these enzymes. These genes are very close to one another; a single promoter serves them all, producing one huge mRNA that produces all of the five enzymes during translation, when ribosomes anneal at any of the various start codons on the chain.
These 5 genes are **coordinately controlled**; any influence on the transcription of these genes (of transcription at this site) will impact the production for all of these enzymes.

There is a segment of DNA in-between the promoter and the first gene which operates as an on-off switch. This is called an [[Operator]], and it controls whether RNA polymerase has access to transcribe or not.

The promoter, the operator, and all these genes, are all together called an [[Operon]].

Normally, the operon is at the ON state.
But something called a repressor can bind to the operator, which then blocks access to the promoter, so RNA polymerace can't do its job.
If the genes can't be transcribed, the enzymes can't be produced, and the cell can't build Tryptophan. This repressor is specific to this operator, so it doesn't do anything to other genes, and it is a protein, which is a product of a different gene somewhere else in the DNA.
This tryptophan-specific repressor is produced regularly but in an inactive state, which has little affinity for the operator. When tryptophan binds to the active site of the repressor, it changes shape to become an active form that has much more affinity for the operator, so it will bind and stay ON for quite some time, thus turning the operon OFF, inhibiting gene expression, and limiting further tryptophan production.
The more tryptophan there is in the cell, the more repressors that will be activated to inhibit gene expression. Repressor activation is concentration-dependent. The less tryptophan there is, the less inhibition there will be.

```

A gene can be that are typically OFF, or silenced, unless activated:
```ad-example
collapse: open
In *E. coli*, there are genes that when expresed, produce an enzyme that will metabolize lactose, a disaccharide, into individual monosaccharide units, glucose and galactose.

There is typically a repressor bound to the operator that corresponds to these genes but an isomer of lactose called allolactose will bind to the repressor and deactivate it, thus allowing for transcription of the gene, enzyme production, and higher levels of lactose metabolism.

```

#### Histones
An easy way to turn genes ON and OFF has to do with the way that DNA is wrapped around histones to form nucleosomes.
When bound to [[Histone]]s, genes can't be expressed.
In order to express a gene, the gene must become accessible. Genes become accessible if an enzyme modifies a histone through acetylation, methylation or phosphorylation thus decreasing its affinity for DNA.
When a gene is no longer coordinated to the histone, it is available for transcription.
In order for transcription to proceed, proteins called transcription factors are necessary.

In addition, there are other control elements farther away from the gene called enhancers, that interact with proteins called activators.
When activators bind to the enhancer, another protein can bend DNA back on itself to bring the activators closer to the promoter where the transcription factor can be found.
Other proteins mediate interacations that produce the complete transcription initation complex, which allows RNA polymerase to do its job.

Transcription is much more complex. There are many proteins involved when any gene is being transcribed, and so regulation of the levels of these proteins can regulate the expression of other genes.
Some genes can only be transcribed when specific activator proteins are present, and this may only occur at a specific time, like hormones carrying a message to promote the expression of genes whose products trigger development during puberty.
Combined with the acetylation and deacetylation of histones to either activate (euchromatin) or silence (heterochromatin) genes, proteins that bind to [[mRNA]] to prevent translation and other phenomena, the cell has several strategies at its disposal to regulate gene expression.


---
# References
https://www.wikiwand.com/en/Autoregulation#/Autoregulation_of_genes