# <b>Results</b>

## <span style="color:royalblue"> **Objective** </span>

The objective of our work was to establish orthogonal replication of a linear plasmid (pL) in *E. coli* using a minimal set of replication proteins from bacteriopage ɸ29. We first built a vector plasmid, [pɸ29](https://benchling.com/calinplesa/f/lib_iPHSZtvU-phi29/seq_im7eHcq3-phi29_plasmid_real_cpfix/edit),  carrying the genes encoding each of these proteins, and expressed it in *E. coli.*

## <span style="color:royalblue"> **ɸ29 Toxicity** </span>

We screened for toxicity of the ɸ29 proteins in *E. coli* by performing an induction assay. Expression of the ɸ29 proteins only occurs in the presence of the inducer Isopropyl β-d-1-thiogalactopyranoside (IPTG). Any detrimental effects posed to the host by the ɸ29 proteins would be indicated by slowed growth in the cells expressing the ɸ29 proteins in the presence of IPTG. 

Cells carrying pɸ29 were induced at 0, 0.05, 0.1, 0.5, and 1.0 mM IPTG and compared to the growth of DH5α cells (orange) at 0, 0.1, and 1.0 mM IPTG.  

<img src="https://user-images.githubusercontent.com/59736592/134724297-9e997630-292a-4cfd-8386-7e53cbc5e1b4.png" alt = "Induction_DH5a" width = "600">

**Figure 1. Doubling Time of Cells Expressing pɸ29**<br/>  
Growth of pɸ29 cells (blue) when induced at 0, 0.05, 0.1, and 1.0 mM IPTG compared to growth of DH5a cells (orange) at 0, 0.1, and 1.0 mM IPTG. 

As IPTG induction level increased from 0 mM to 1.0 mM, doubling time slowed by 24.2%, which suggests that successfully expressing Phi29 proteins may be complicated by their potential for toxicity to the host. Depending on a protein’s characteristics and function, overexpressing recombinant proteins in *E. coli* can interfere with cell survival and proliferation (Rosano and Ceccarelli, 2014). Increased doubling time indicates that Phi29 cells divert metabolic resources away from normal replication to make Phi29 proteins. The minor increase in doubling time from 0.1 to 1.0 mM suggests that pɸ29 expression reached saturation at 0.1 mM IPTG.

## <span style="color:royalblue"> **Replication of Linear Plasmid by Phi29 Proteins** </span>

Cells induced at varying levels of IPTG were then transformed with a linear plasmid (pL) carrying DHFR R67, a variant of dihydrofolate reductase which confers high levels of resistance to the antibiotic trimethoprim6. Cells both with (pL+) and without  pL (pL-), were plated on media with IPTG concentrations corresponding to induction level. A negative control not transformed with pL was also plated on each IPTG condition. As expected, pL+ and pL- cells plated on 10 ug/mL trimethoprim and without IPTG did not grow. Although growth was observed on one of four replica plates from the 10 ug/mL trimethoprim/1.0mM IPTG/ pL+ condition, no growth was seen on the other 3 plates. Significant growth on all four replica plates was only observed on the 5 ug/mL trimethoprim and 0.1 mM IPTG condition, both with and without pL.

<img src="https://user-images.githubusercontent.com/59736592/134725362-e8cce6fe-1c5c-4e57-9ed3-69dbef4ec192.png" alt = "Plate_Growth_Table1" width = "600">. 

The 50% inhibitory concentration of DHFR R67 to trimethoprim is 5.8 g/L6. If pL replication by Phi29 proteins were successful, the expressed DHFR R67 would easily confer resistance of 10 ug/mL (0.01 g/L). The growth observed at lower trimethoprim resistance regardless of pL presence suggests a high frequency of escape mutations, in which the host naturally acquires resistance to the antibiotic through genomic mutations rather than expressing the plasmid carrying resistance. This was confirmed by running a colony PCR (Fig. 3) to assess the presence of pL in the surviving colonies. A colony from each of the conditions under which growth was observed was tested. The inverted terminal repeats in the Phi29 ORIs make PCR amplification of the entire pL impossible, so a PCR of the middle sequence, DHFR R67, was done and the product was visualized on a gel. Negative PCR results from all colonies verified that cells acquired resistance to trimethoprim through a separate mechanism independent of pL replication by Phi29 proteins. Colony PCR also verified that pL did not integrate into the genome, as DFHR R67 would have been amplified off the 0.1 mM IPTG -pL colonies.

<img src="https://user-images.githubusercontent.com/59736592/134725506-5b72b44d-7a55-430a-b908-e2cdf2cf6303.png" alt = "pL_GEL" width = "300">

**Figure 2. Colony PCR for DHFR R67**<br/>
Lane 1: 100 bp ladder. 
Lane 2: no template negative control. 
Lane 3: 0.1 mM IPTG/5ug/mL Tri /pL++. 
Lane 4: 1.0 mM IPTG/10 ug/mL/pL+. 
Lane 5: 0.1 mM IPTG/5 ug/mL/pL-. 
Lane 6: DHFR R67 template positive control

## <span style="color:royalblue"> **Transitioning Expression to pGSɸ29 and T7 Express** </span>

The Phi29 TP, DSBP, and SSBP were ligated into an alternative plasmid backbone, [pGS21a](https://benchling.com/s/seq-amYLb0fQvSCUsYLWSWoS), which carried the wildtype ɸ29 DNAP with 6XHis and GST tags to enable easier purification. In the resulting plasmid, [pGSɸ29](https://benchling.com/s/seq-pSqC9fjRFhvl5Rw8RFIG), expression of the Phi29 proteins is under control of a T7 promoter. pGS21a was transformed into *E. coli* strain T7 express (C2566H), which expresses T7 polymerase in the lac operon. T7 express is also optimized for protein expression.

## <span style="color:royalblue"> **Metabolic Burden of Phi29 Proteins in T7** </span>

We screened for toxicity of the ɸ29 proteins in T7 by performing an induction assay identical to the induction performed on DH5a cells expresing pɸ29. We anticipated that, because T7 was an strain better suited for protein expression than DH5a, the growth time would be less severely impeded by expresion of the ɸ29 proteins. 

<img src="https://user-images.githubusercontent.com/59736592/134726581-389831e0-cee6-480e-9b91-3d6ac90432bd.png" alt = "T7_Induction" width = "600">


**Figure 3. Doubling Time of T7 Cells Expressing pGSɸ29**<br/> 
Growth of T7 cells expressing pɸ29 (blue) when induced at 0, 0.01, 0.05, 0.1, 0.5, and 1.0 mM IPTG compared to growth of DH5α cells (orange) at 0, 0.1, and 1.0 mM IPTG. 

T7 cells expressing pGSɸ29 were induced at increasing concentrations of IPTG to express the Phi29 proteins. As IPTG induction level increased from 0 mM to 1.0 mM, doubling time slowed by 7.85%, from 106.1 ± 2.49 min to 114.45 ± 3.00 min. Consistent with our expectation, doubling time in T7 express was significantly faster than in DH5α. 

T7 cells induced at varying levels of IPTG were then transformed with pL. Cells both with (pL+) and without  pL (pL-), were plated on media with IPTG concentrations corresponding to induction level (0 mM, 0.1 mM, or 1 mM). A negative control not transformed with pL was also plated on each IPTG condition. To avoid escape mutations, trimethoprim concentration was increased to 0.5 mg/mL (a 50 fold increase from the first trial with DH5α). No growth was observed on any of the plates, indicating that replication of pL by the Phi29 proteins was unsuccessful.

<img src="https://user-images.githubusercontent.com/59736592/134737863-9f9fd6a4-86ab-4b67-8cda-436ca43398bf.png" alt = "Plate_growth_T7" width = "600">

To determine whether the Phi29 proteins were actually being expressed in T7, a protein gel was run on cells induced at 0, 0.1, and 1.0 mM IPTG. Proteins bands were only clear in the sample expressed at 0.1 mM IPTG. A distinct band at the molecular weight of the terminal protein (31 kD) was observed, but it was difficult to discern if bands at 95, 13, and 12 kD were distinct from bands in the T7 negative control.

<img src="https://user-images.githubusercontent.com/59736592/134738122-de577b82-02d7-4786-be31-b99fe76c35e1.png" alt = "T7_Protein_Gel" width = "600">

**Figure 4. Protein Gel of T7 Cells Expressing pGSɸ29**<br/> 
induced at 0, 0.1, and 1.0 mM IPTG. T7 cells not expressing pGSɸ29 was run as a control. Far left and right lanes are the Precision Plus Protein Ladder, and bands at the expected molecular weights are marked: DSBP: 12 kD, SSBP: 13 kD, TP: 31 kD, GST-tagged DNAP: 95 kD.  

Given the change in doubling time of cells expressing pGSɸ29 (Fig. 3), and the protein gel (Fig. 7) which indicted potential expression of the ɸ29 proteins, it was hypothesized that the ɸ29 proteins, it was hypothesized that the ɸ29 proteins likely were expressed but were not interating successfully wih pL, potentially as the result of deleterious interactions with heterolosou host proteins. To study the protein-protein interactions between *E. coli* and ɸ29, and rationally design the ɸ29 proteins to avoid the would not have been feasible, so we proceeded with randomized mutagenesis. 

THe pGSɸ29 backbone was amplified normally with PCR, and different sets of the replication proteins were amplified with error-prone PCR (EP PCR) to introduce base substitutions at a rate of ~10⁻⁴ substitutions per replicated base (Packer and Liu, 2015).  Successful amplification was validated with gel electrophoresis (Fig 5). All amplicons were the expected length. In future work, mutations will be evaluated using Sanger sequencing. 

<img src="https://user-images.githubusercontent.com/59736592/137065714-07c08898-f7a4-4e68-baef-dd55e2ef02d0.png" alt = "Validation_of_PCR_mutagenesis" width = "600">


# <span style="color:royalblue"> **References** </span>
(1) Rosano GL and Ceccarelli EA (2014) Recombinant protein expression in Escherichia coli: advances and challenges. Front. Microbiol. 5:172. doi: 10.3389/fmicb.2014.00172

(2) Packer, M. S.; Liu, D. R. Methods for the Directed Evolution of Proteins. Nature Reviews Genetics 2015, 16 (7), 379–394. https://doi.org/10.1038/nrg3927

