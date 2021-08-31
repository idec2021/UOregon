
# <span style="color:royalblue"> **DiversiPhi29: an orthogonal replication system for the continuous directed evolution of genes in vivo** </span>
## <span style="color:royalblue"> **Motivation** </span>
Biological protein-based systems have diverse applications, from targeted drug delivery to sustainable textile manufacturing. A significant barrier to using proteins in medicine and industry is that proteins have evolved to function best in a living cell from their native organism, and frequently lose function in a different context. This necessitates innovative techniques to modify and optimize natural proteins for novel functions and conditions. 

## <span style="color:royalblue"> **Directed Evolution** </span>
Directed evolution allows scientists to guide and accelerate the mutational path of a sequence, in a random or targeted manner, towards a certain functional or phenotypic ideal. Current approaches to directed evolution consist of rounds of mutation in vitro to develop a library of differentially mutated genes, followed by expression of the mutant library in vivo to assess phenotypic outcomes. Variants are screened for a select function, and the most suitable variants undergo further rounds of mutation, expression, and screening until a suitable phenotype is achieved.

This process is time-consuming and labor intensive, necessitating multiple transformation steps during which genes of interest are inserted in cells for replication and expression. Each transformation step also results in a loss of library diversity, or a “bottleneck,” as not all gene variants are successfully taken up by cells. As such, these approaches are limited in their ability to characterize many sequence-function relationships in parallel. 

## <span style="color:royalblue"> **Continuous Directed Evolution** </span>
Continuous methods for directed evolution circumvent many of these limitations, allowing multiple cycles of mutation to take place entirely *in vivo* without manual interference. Mutagenesis in continuous evolution relies on an increase in the mutational rate of the host cells above typical genomic error rates. This can be done through chemical mutagenesis, with alkylating agents, UV irradiation, or base analogues (2). More recently, mutational frequency has been increased by deactivating host proofreading enzymes1 or mutating the host DNA Polymerase to reduce copying fidelity (3). However, both of these methods generate unwanted mutations in the host genome. Over time, mutations accumulate in essential genes and kill the host, limiting the number of evolutionary generations possible. Such short experimental durations prevent access to certain adaptations of interest that require long mutational paths.

## <span style="color:royalblue"> **Orthogonal Replication for Directed Evolution** </span>
Orthogonal replication architectures are those in which replication of a gene of interest and host genomic replication occur by separate machinery and mechanism.
Orthogonal replication applied to directed evolution provide the advantages of continuous *in vivo* mutagenesis while maintaining stability of the host genome. Previously established systems have relied on an error-prone DNA polymerase which interacts specifically with an engineered DNA construct, and cannot interact with host genomic DNA (4). This allows high mutation rates on a gene of interest without damaging the host. The primary advantage of such a system is its ability to sustain long experimental durations, allowing a gene to evolve over hundreds of generations.

<img src="https://user-images.githubusercontent.com/59736592/131526537-c09be7cb-31ca-45fa-98b4-e056602ede60.png" alt = "GraphicalAbstract" width = "600">


## <span style="color:royalblue"> **Bacteriophage Phi29** </span>
The initiation of DNA synthesis conventionally relies on priming by a short sequence of DNA or RNA, which provides a 3’ hydroxyl group for DNA Polymerase to extend from. In several phages, a terminal protein serves as a primer for genomic replication (28). Bacteriophage Phi29, a virus which infects *Bacillus subtilis*, represents the most extensively studied example of terminal protein-primed replication. Critical to this mechanism are the Phi29 Origins of Replication (ORIs) which flank the genome and allow cooperative binding of the Phi29 DNA Polymerase and Terminal Protein. 

DiversiPhi29 repurposes the transcriptional machinery of bacteriophage Phi29 for orthogonal replication, using *E. coli* as a cellular chassis. Our protein-primed replication mechanism differs from the mechanism used by the *E. coli* DNA polymerase to replicate the *E. coli* genome, which enables isolation of an error-prone Phi29 DNA Polymerase (DNAP) from the host genome. In DiversiPhi29, the Phi29 ORIs flank the gene of interest so that the Phi29 DNA Polymerase and priming Terminal Protein replicate the gene of interest as they would replicate the Phi29 genome.


 























