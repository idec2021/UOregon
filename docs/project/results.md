# <b>Results</b>
## <span style="color:royalblue"> **Validation of Parts: pɸ29** </span>
Restriction digest was used to validate successful assembly of a plasmid [pɸ29](https://benchling.com/calinplesa/f/lib_iPHSZtvU-phi29/seq_im7eHcq3-phi29_plasmid_real_cpfix/edit) carrying the Phi29 TP, DNAP, SSBP, and DSBP. Complete sequencing of our initial assembly revealed a 70 base-pair deletion. To fix the deletion, the plasmid was  PCR amplified with restriction sites, and the 70 base-pair segment was inserted by digest and ligation. Correct assembly was validated by gel electrophoresis of a MlyI digest on the original and fixed plasmid.

<img src="https://user-images.githubusercontent.com/59736592/134722281-fb970195-8d33-4ea1-a20c-257e4c466547.png" alt = "pPhi29_Gel_Validation" width = "300">

**Figure 1. Restriction Digest Validation of pɸ29**<br/> 
The final plasmid was validated by restriction digest with MlyI. Lane 1: 100 bp ladder, Lane 2: MlyI digest of pɸ29 plasmid, corrected with primers carrying missing sequence. Lane 3: MlyI digest of uncorrected pɸ29 plasmid. Lane 4: 1 kb ladder. 

## <span style="color:royalblue"> **Metabolic Burden of Phi29 Proteins** </span>

pɸ29, which expresses the Phi29 TP, DNAP, SSBP, and DSBP under control of a lac-inducible promoter was transformed into E. coli strain DH5α. Induction of these cells with variable concentration of the lactose analog IPTG showed the relative burden posed to host cells by the Phi29 proteins.

<img src="https://user-images.githubusercontent.com/59736592/134724297-9e997630-292a-4cfd-8386-7e53cbc5e1b4.png" alt = "Induction_DH5a" width = "600">

**Figure 2. Doubling Time of Cells Expressing pɸ29**<br/> 
Growth of pɸ29 cells (blue) when induced at 0, 0.05, 0.1, 0.5, and 1.0 mM IPTG compared to growth of DH5α cells (orange) at 0, 0.1, and 1.0 mM IPTG.

As IPTG induction level increased from 0 mM to 0.01 mM, doubling time slowed by 14.6%, from 144.4 ± 1.96 min to 165.6 ± 6.53 min. Increasing IPTG concentration to 0.05, 0.1, 0.5, and 1.0 mM slowed doubling time to 172.85 ± 3.11 min (19.7% slower), 174.84 ± 0.61 min (21.1% slower), 176.60 ± 6.55 min (22.3% slower) and 179.39 ± 0.94 min (24.2% slower). Successfully expressing Phi29 proteins may be complicated by their potential for toxicity to the host. Depending on a protein’s characteristics and function, overexpressing recombinant proteins in E. coli can interfere with cell survival and proliferation5. Increased doubling time indicates that Phi29 cells divert metabolic resources away from normal replication to make Phi29 proteins. The minor increase in doubling time from 0.1 to 1.0 mM suggests that pɸ29 expression reached saturation at 0.1 mM IPTG.

## <span style="color:royalblue"> **Replication of Linear Plasmid by Phi29 Proteins** </span>

Cells induced at varying levels of IPTG were then transformed with a linear plasmid (pL) carrying DHFR R67, a variant of dihydrofolate reductase which confers high levels of resistance to the antibiotic trimethoprim6. Cells both with (pL+) and without  pL (pL-), were plated on media with IPTG concentrations corresponding to induction level. A negative control not transformed with pL was also plated on each IPTG condition. As expected, pL+ and pL- cells plated on 10 ug/mL trimethoprim and without IPTG did not grow. Although growth was observed on one of four replica plates from the 10 ug/mL trimethoprim/1.0mM IPTG/ pL+ condition, no growth was seen on the other 3 plates.

Significant growth on all four replica plates was only observed on the 5 ug/mL trimethoprim and 0.1 mM IPTG condition, both with and without pL.

<img src="https://user-images.githubusercontent.com/59736592/134725362-e8cce6fe-1c5c-4e57-9ed3-69dbef4ec192.png" alt = "Plate_Growth_Table1" width = "600">. 

The 50% inhibitory concentration of DHFR R67 to trimethoprim is 5.8 g/L6. If pL replication by Phi29 proteins were successful, the expressed DHFR R67 would easily confer resistance of 10 ug/mL (0.01 g/L). The growth observed at lower trimethoprim resistance regardless of pL presence suggests a high frequency of escape mutations, in which the host naturally acquires resistance to the antibiotic through genomic mutations rather than expressing the plasmid carrying resistance. This was confirmed by running a colony PCR (Fig. 4) to assess the presence of pL in the surviving colonies. A colony from each of the conditions under which growth was observed was tested. The inverted terminal repeats in the Phi29 ORIs make PCR amplification of the entire pL impossible, so a PCR of the middle sequence, DHFR R67, was done and the product was visualized on a gel. Negative PCR results from all colonies verified that cells acquired resistance to trimethoprim through a separate mechanism independent of pL replication by Phi29 proteins. Colony PCR also verified that pL did not integrate into the genome, as DFHR R67 would have been amplified off the 0.1 mM IPTG -pL colonies.

<img src="https://user-images.githubusercontent.com/59736592/134725506-5b72b44d-7a55-430a-b908-e2cdf2cf6303.png" alt = "pL_GEL" width = "300">

**Figure 3. Colony PCR for DHFR R67**<br/>
Lane 1: 100 bp ladder. 
Lane 2: no template negative control. 
Lane 3: 0.1 mM IPTG/5ug/mL Tri /pL++. 
Lane 4: 1.0 mM IPTG/10 ug/mL/pL+. 
Lane 5: 0.1 mM IPTG/5 ug/mL/pL-. 
Lane 6: DHFR R67 template positive control

## <span style="color:royalblue"> **Validation of Parts: pGSɸ29** </span>

The Phi29 TP, DSBP, and SSBP were ligated into an alternative plasmid backbone, [pGS21a](https://benchling.com/s/seq-amYLb0fQvSCUsYLWSWoS), which carried the wildtype ɸ29 DNAP with 6XHis and GST tags to enable easier purification. In the resulting plasmid, [pGSɸ29](https://benchling.com/s/seq-pSqC9fjRFhvl5Rw8RFIG), expression of the Phi29 proteins is under control of a T7 promoter. pGS21a was transformed into *E. coli* strain T7 express (C2566H), which expresses T7 polymerase in the lac operon. T7 express is also optimized for protein expression.

<img width="247" alt="REMIX_pGS21a_phi29" src="https://user-images.githubusercontent.com/59736592/134743938-32fdc58b-6bdc-46a9-99cd-d754d94ca064.png">

**Figure 4. Restriction Digest Validation of pGSɸ29**<br/> 
The reconstructed pGSɸ29 plasmid was validated by restriction digest with KpnI and NdeI. Lane 1: 1 kb ladder, Lane 2: KpnI and NdeI digest of pɸ29 plasmid. Lane 3: KpnI/NdeI digest of pGSɸ29 plasmid. 

<img src="https://user-images.githubusercontent.com/59736592/134726581-389831e0-cee6-480e-9b91-3d6ac90432bd.png" alt = "T7_Induction" width = "600">

## <span style="color:royalblue"> **Metabolic Burden of Phi29 Proteins in T7** </span>

**Figure 5. Doubling Time of T7 Cells Expressing pGSɸ29**<br/> 
Growth of pɸ29 cells (blue) when induced at 0, 0.01, 0.05, 0.1, 0.5, and 1.0 mM IPTG compared to growth of DH5α cells (orange) at 0, 0.1, and 1.0 mM IPTG. 

T7 cells expressing pGSɸ29 were then induced at increasing concentrations of IPTG to express the Phi29 proteins. As IPTG induction level increased from 0 mM to 0.01 mM, doubling time slowed by 7.36%, from 106.1 ± 2.49 min to 113.9 ± 0.98 min. Increasing IPTG concentration to 0.05, 0.1, 0.5, and 1.0 mM slowed doubling time to 110.28 ± 5.08 min (3.92% slower), 111.94 ± 3.19 min (5.49% slower), 114.92 ± 3.50 min (8.30% slower) and 114.45 ± 3.00 min (7.85% slower).
Doubling time in T7 express was significantly faster than in DH5α. T7 cells induced at varying levels of IPTG were then transformed with pL. Cells both with (pL+) and without  pL (pL-), were plated on media with IPTG concentrations corresponding to induction level (0 mM, 0.1 mM, or 1 mM). A negative control not transformed with pL was also plated on each IPTG condition. To avoid escape mutations, trimethoprim concentration was increased to 0.5 mg/mL (a 50 fold increase from the first trial with DH5α). No growth was observed on any of the plates, indicating that replication of pL by the Phi29 proteins was unsuccessful.

<img src="https://user-images.githubusercontent.com/59736592/134737863-9f9fd6a4-86ab-4b67-8cda-436ca43398bf.png" alt = "Plate_growth_T7" width = "600">

To determine whether the Phi29 proteins were actually being expressed in T7, a protein gel was run on cells induced at 0, 0.1, and 1.0 mM IPTG. Proteins bands were only clear in the sample expressed at 0.1 mM IPTG. A distinct band at the molecular weight of the terminal protein (31 kD) was observed, but it was difficult to discern if bands at 95, 13, and 12 kD were distinct from bands in the T7 negative control.

<img src="https://user-images.githubusercontent.com/59736592/134738122-de577b82-02d7-4786-be31-b99fe76c35e1.png" alt = "T7_Protein_Gel" width = "600">

**Figure 6. Protein Gel of T7 Cells Expressing pGSɸ29**<br/> 
induced at 0, 0.1, and 1.0 mM IPTG. T7 cells not expressing pGSɸ29 was run as a control. Far left and right lanes are the Precision Plus Protein Ladder, and bands at the expected molecular weights are marked: DSBP: 12 kD, SSBP: 13 kD, TP: 31 kD, GST-tagged DNAP: 95 kD.  

