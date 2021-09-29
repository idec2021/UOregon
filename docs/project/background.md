
# <span style="color:royalblue"> **DiversiPhi29: an orthogonal replication system for the continuous directed evolution of genes *in vivo*** </span>

<img src="https://user-images.githubusercontent.com/59736592/135347873-8b7e1996-7f23-4342-9a72-a3dd3b4b8c49.png" alt = "DirectedEvolutionOverview" width = "900">

## <span style="color:royalblue"> **Motivation** </span>
Biological protein-based systems have diverse applications, from targeted drug delivery to sustainable textile manufacturing. A significant barrier to using proteins in medicine and industry is that proteins have evolved to function best in a living cell from their native organism, and frequently lose function in a different context. This necessitates innovative techniques to modify and optimize natural proteins for novel functions and conditions. 

Protein engineering involves mutating a protein's encoding DNA and observing the functional outcomes. However, the relationships between sequence and function are often unpredictable, and the mutational space for a given protein is virtually limitless. DiversiPhi29 is an approach to protein engineering which optimizes the scale and speed at which sequence space can be explored by limiting the necessity for manual mutation.

## <span style="color:royalblue"> **Directed Evolution** </span>
Directed evolution allows scientists to guide and accelerate the mutational path of a sequence, in a random or targeted manner, towards a certain functional or phenotypic ideal. Current approaches to directed evolution consist of rounds of mutation *in vitro* to develop a library of differentially mutated genes, followed by expression of the mutant library *in vivo* to assess phenotypic outcomes. Variants are screened for a select function, and the most suitable variants undergo further rounds of mutation, expression, and screening until a suitable phenotype is achieved.

This process is time-consuming and labor intensive, necessitating multiple transformation steps during which genes of interest are inserted in cells for replication and expression. Each transformation step also results in a loss of library diversity, or a “bottleneck,” as not all gene variants are successfully taken up by cells. As such, these approaches are limited in their ability to characterize many sequence-function relationships in parallel. 

## <span style="color:royalblue"> **Continuous Directed Evolution** </span>
Continuous methods for directed evolution circumvent many of these limitations, allowing multiple cycles of mutation to take place entirely *in vivo* without manual interference. Mutagenesis in continuous evolution relies on an increase in the mutational rate of the host cells above typical genomic error rates. This can be done through chemical mutagenesis, with alkylating agents, UV irradiation, or base analogues <span style="color:royalblue">(Packer & Liu, 2015)</span>. More recently, mutational frequency has been increased by deactivating host proofreading enzymes1 or mutating the host DNA Polymerase to reduce copying fidelity <span style="color:royalblue">(Greener et al, 1997)</span>. However, both of these methods generate unwanted mutations in the host genome. Over time, mutations accumulate in essential genes and kill the host, limiting the number of evolutionary generations possible. Such short experimental durations prevent access to certain adaptations of interest that require long mutational paths.

<img src="https://user-images.githubusercontent.com/59736592/131709454-e59d5383-8c9c-4552-b9df-8e40fe273717.png" alt = "DirectedEvolutionComparison" width = "900">

## <span style="color:royalblue"> **Orthogonal Replication for Directed Evolution** </span>
Orthogonal replication architectures are those in which replication of a gene of interest and host genomic replication occur by separate machinery and mechanism.
Orthogonal replication applied to directed evolution provides the advantages of continuous *in vivo* mutagenesis while maintaining stability of the host genome. Previously established systems have relied on an error-prone DNA polymerase which interacts specifically with an engineered DNA construct, and cannot interact with host genomic DNA <span style="color:royalblue">(Ravikumar et al, 2014)</span>. This allows high mutation rates on a gene of interest without damaging the host. The primary advantage of such a system is its ability to sustain long experimental durations, allowing a gene to evolve over hundreds of generations.

<img src="https://user-images.githubusercontent.com/59736592/131526537-c09be7cb-31ca-45fa-98b4-e056602ede60.png" alt = "GraphicalAbstract" width = "600">

## <span style="color:royalblue"> **Bacteriophage Phi29** </span>
The initiation of DNA synthesis conventionally relies on priming by a short sequence of DNA or RNA, which provides a 3’ hydroxyl group for DNA Polymerase to extend from. In several phages, a terminal protein serves as a primer for genomic replication <span style="color:royalblue">(Salas, 1991)</span>. Bacteriophage Phi29, a virus which infects *Bacillus subtilis*, represents the most extensively studied example of terminal protein-primed replication. Critical to this mechanism are the Phi29 Origins of Replication (ORIs) which flank the genome and allow cooperative binding of the Phi29 DNA Polymerase and Terminal Protein <span style="color:royalblue">(Mencia et al, 2011)</span>. 

DiversiPhi29 repurposes the transcriptional machinery of bacteriophage Phi29 for orthogonal replication, using *E. coli* as a cellular chassis. Our protein-primed replication mechanism differs from the mechanism used by the *E. coli* DNA polymerase to replicate the *E. coli* genome, which enables isolation of an error-prone Phi29 DNA Polymerase (DNAP) from the host genome. In DiversiPhi29, the Phi29 ORIs flank a gene of interest on a linear plasmid so that the Phi29 DNA Polymerase and priming Terminal Protein replicate the gene of interest as they would replicate the Phi29 genome.

<img src="https://user-images.githubusercontent.com/59736592/131540707-04b9f432-e0b8-47f5-83f6-0e03f48d9ae8.png" alt = "Phi29 Cycle" width = "600">

 ## <span style="color:royalblue"> **DiversiPhi29** </span>
Once we have established replication of a linear plasmid carrying a gene of interest, we will modify the Phi29 DNA Polymerase to reduce its copying fidelity. The low-fidelity Phi29 polymerase will perform error-prone replication of the linear plasmid while the host polymerase carries out normal replication of the genome.

<img src="https://user-images.githubusercontent.com/59736592/135347873-8b7e1996-7f23-4342-9a72-a3dd3b4b8c49.png" alt = "DirectedEvolutionOverview" width = "900">

 ## <span style="color:royalblue"> **Tunable Mutagenesis** </span>
In future work we plan to create a system to tune and control the rate of mutagenesis on a linear plasmid by alternating expression of a low and high-fidelity polymerase. Expression of each will be under control of a different inducer or repressor, such that high expression of one coincides with low expression of the other. Over several generations, a linear plasmid will alternate expression between the low and high-fidelity polymerase, such that the cumulative error rate can be controlled.

<img src="https://user-images.githubusercontent.com/59736592/135354398-b9d377f7-fe24-4858-9319-24b110e9dbd1.png" alt = "PolymeraseErrorRate" width = "900">


# <span style="color:royalblue"> **References** </span>
(1) 	Packer, M. S.; Liu, D. R. Methods for the Directed Evolution of Proteins. Nat. Rev. Genet. 2015, 16 (7), 379–394. https://doi.org/10.1038/nrg3927.<br/> 
(2) 	Greener, A.; Callahan, M.; Jerpseth, B. An Efficient Random Mutagenesis Technique Using AnE.Coli Mutator Strain. Mol. Biotechnol. 1997, 7 (2), 189–195. https://doi.org/10.1007/BF02761755.<br/> 
(3) 	Ravikumar, A.; Arrieta, A.; Liu, C. C. An Orthogonal DNA Replication System in Yeast. Nat. Chem. Biol. 2014, 10 (3), 175–177. https://doi.org/10.1038/nchembio.1439.<br/> 
(4) 	Salas, M. Protein-Priming of Dna Replication. Annu. Rev. Biochem. 1991, 60 (1), 39–71. https://doi.org/10.1146/annurev.bi.60.070191.000351.<br/> 
(5) 	Mencia, M.; Gella, P.; Camacho, A.; de Vega, M.; Salas, M. Terminal Protein-Primed Amplification of Heterologous DNA with a Minimal Replication System Based on Phage 29. Proc. Natl. Acad. Sci. 2011, 108 (46), 18655–18660. https://doi.org/10.1073/pnas.1114397108.






