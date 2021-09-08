# Lab notebook
## July 1st
Golden Gate Assembly (set link to GGA protocol file) of Phi29 Terminal protein (TP) ,Single stranded binding protein (SSBP) and Double Stranded binding protein (DSBP)+pGS21a backbone with Phi29 DNA Polymerase(DNAP) 

- PCR amplify fragments 
- rSAP digestion 
- PaqCI digestion of insert + backbone 

| Backbone | Insert |
| ----| ---- |
| 5.71 uL DNA | 2.32 uL DNA |
| 5 uL Cutsmart Buffer | 5 uL Cutsmart Buffer |
| 1 uL PaqCI | 1 uL PaqCI |
| 0.25 uL PaqCI activator | 0.25 uL PaqCI activator |
| 38.1 uL H2O | 41.43 uL H2O |

Total : 50 uL

Incubate 37C for 1 hour , Cleanup elute 10 uL

Conc. Insert : 12.75 ng/uL

Conc. Backbone : 22.7 ng/uL

Ligation (3 tubes of equal volume / components): 

| Tube 1 of 3 |
| ---- | 
| 3.13 uL TPBP (insert) | 
| 3.08 uL pGS21a (backbone) | 
| 10 uL T7 Buffer |
| 2.79 uL H2O | 
| 1 uL T7 Ligase | 

Incubate 25C for 1 hr

Cleanup elute 10uL

Cleanup Assembly:
| Concentration |
| ------------- |
|  11.65 ng/uL |


<img width="1019" alt="Screen Shot 2021-09-03 at 12 28 51 PM" src="https://user-images.githubusercontent.com/77999251/132057033-7c0e9d41-dbae-48c6-b8c0-fca727063a61.png">


Make Agar+LB plates with Carbenicillin 

## July 2nd
Transform Phi29-pGS21a into DH5alpha using electroporation protocol(link electroporation protocol) 

| Component   | Volume |
| ----| ---- |
| DNA | 2uL |
| DH5a | 25uL |

Plate 100uL on Carb 

## July 3rd 
Run Colony PCR (link protocol) on 15 colonies to ensure insert length using DH5a as control 
<img width="721" alt="Screen Shot 2021-08-05 at 11 36 10 AM" src="https://user-images.githubusercontent.com/77999251/128403234-d75b9962-cd51-46e3-a316-236d2c557678.png">

Create an overnight culture with 10mL LB+ scrape 1 colony with pipette tip and eject into test tube+ 10uL Carb 

Let shake in 37°C for 12-16 hours overnight 

## July 4th 
 Miniprep overnight culture
 Elute: 30 uL
 | Colony  | Qubit Concentration |
| ---- | ---- |
| 13 | 53.4 ng/uL |
| 17 | 65.6 ng/uL|

Digest with KpnI+NdeI to confirm length

How the gel shoud look:

<img width="529" alt="Screen Shot 2021-08-05 at 11 40 25 AM" src="https://user-images.githubusercontent.com/77999251/128403800-bee71f4d-a8e9-42be-bb92-280fb95fc921.png">

How the gel looked:

<img width="349" alt="Screen Shot 2021-08-05 at 11 40 38 AM" src="https://user-images.githubusercontent.com/77999251/128403860-79ce778c-58e1-4b81-9b30-4e5857afa15c.png">

Dilute down to 30 ng/uL to send for sequence validation by SNPsaurus using m1v1=m2v2 

send 10uL of diluted sample 

## July 5th 
Sequence validated by SNPsaurus

Colony 17 perfect alignment match on benchling 

## July 6th
Use miniprep Colony 17 from 7/4 for chemically competent transformation(link protocol) into T7

1 uL plasmid, 50 uL cells 

Serial Dilution using 1:10 ratio 3x 

Plate 100uL on Carb 

## July 7th 
Make an overnight culture with Colony plated on Carb and T7 cells with no colony (from stock) 

## July 8th
T7 OD600: 4.91

Col17 OD600: 4.62 

Induce with 3 different concentrations of IPTG to test for protein toxicity on the cells by checking OD600 in a plate reader for 16 hours 

T7 no plasmid and only LB used as controls

| Type of Cells | Concentration of IPTG | Volume of cells | Volume of IPTG | Volume of LB |
| ---- | ---- | ---- | ---- | ---- |
| Col 17 | 0mM | 8.65 uL| 0uL | 791 uL |
| Col 17 | 0.01mM | 8.65 uL | 0.08uL | 791 uL |
| Col 17 | 0.05mM | 8.65 uL | 0.4uL | 790uL |
| Col 17 | 0.1mM |  8.65 uL | 0.8uL | 790uL |
| Col 17 | 0.5mM | 8.65 uL | 4 uL | 787uL |
| Col 17 | 1mM | 8.65 uL | 8uL | 783uL |
| T7 (-) | 0mM | 8.14 uL | 0uL | 791uL |
| T7 (-) | 0.1 mM | 8.14 uL | 0.8uL | 790uL |
| T7 (-) | 1mM | 8.14 uL  | 8uL | 783uL |
| LB (-) | 0mM | 0 uL | 0uL | 800uL |
| LB (-) | 0.1mM | 0uL | 0.8uL | 799uL |
| LB (-) | 1mM | 0uL | 8uL | 792uL |

## July 9th 
Induction Curve: 

Blue = pGS21a_Phi29_Colony17 in T7

Red = T7 no plasmid

<img width="807" alt="Screen Shot 2021-08-06 at 11 07 59 AM" src="https://user-images.githubusercontent.com/77999251/128553658-eff9d808-12df-4789-bb6f-4afdc2b315f9.png">

Made more Linear Plasmid using PCR, digestion and ligation of fragments (link protocol)

| Fragment | Concentration after PCR eluted into 20uL |
| ----| ---- |
| OriL | 83 ng/uL |
| Middle DHFR | 70.2 ng/uL|
| OriR | 85 ng/uL|

| Fragment | Concentration after Digest eluted into 12uL |
| ----| ---- |
| OriL | 54.6 ng/uL |
| Middle DHFR| 65.4 ng/uL|
| OriR | 45 ng/uL|

Used Biomath Calculator to figure out volume of each fragment to add to ligation, 2:1 outer:inner

OriL: 212 bp-> 0.6ug -> 3.13 pmol-> 8uL

Middle DHFR: 348 bp -> 0.72 ug-> 3.13 pmol-> 11 uL

OriR: 216 bp-> 0.49ug-> 3.13 pmol-> 10uL

| pL Final Concentration eluted into 11uL | 
| ----| 
| 58.8 ng/uL|

## July 12th
Made plates:

10 ug/mL Carb, 0.5 mg/mL Tri, 0mM IPTG

10 ug/mL Carb, 0.5 mg/mL Tri, 0.1 mM IPTG

10 ug/mL Carb, 0.5 mg/mL Tri, 1 mM IPTG 

Started 3 Large inductions in flasks using cells from overnight culture 

3 Concentrations of IPTG: 0mM , 0.1mM, 1.0 mM

OD600 start: 0.05

OD600 end: 0.7 

Make cells electrocompetent(link protocol)

Freeze some spun down cells in -80 

Transform pL into T7 cells with pGS21a_Phi29_Col17 by Electroporation (link protocol) 

Plate 100uL on compatible IPTG conc.  

## July 13th 
No colonies found on any pL + pGS21a_Phi29 plates 

Ran a protein gel using spun down cells from induction in -80

| Protein | Expected Size (kDa) |  
| ----| ---- |
| DNA Polymerase | 95 kDa | 
| Terminal Protein | 31 kDa| 
| Single Stranded Binding Protein | 13.3 kDa | 
| Double Stranded Binding Protein | 12 kDa | 

| Concentration of Supernatant| 0mM | 0.1mM | 1mM | T7 control |
| ----|  | 26.5 mg/mL | 13 mg/mL | 21.1 mg/mL | 1.8 mg/mL |

Ran 2 gels with  50 ug of each sample 

| Volume ran on Gel | 0mM | 0.1mM | 1mM | T7 control |
| ----|  | 1.88 uL | 3.8 uL | 2.4 uL | 27 uL |

Stained one gel with Coomassie Blue, the other with Colloidal Overnight

## July 14th 
Imaged Both Gels, Gel stained with Colloidal was more clear 

Gel stained with Colloidal: 

<img width="338" alt="Screen Shot 2021-08-06 at 12 20 38 PM" src="https://user-images.githubusercontent.com/77999251/128561295-ca406fb3-a63e-478b-857d-407011127ee3.png">

Realized that DNAP size might be too hard to see on gel, ordered 7.5% Biorad protein gel to zoom in on 90 kDa

~Should have run only pGS21a backbone with no phi29 genes in as control~ 

## July 19th 
Make more pL (non-thiolated and thiolated) using different primers 

| Nonthio pL Conc. | Thio pL Conc. |
| ---- | ---- |
| 85.6 ng/uL | 68.8 ng/uL |

## July 20th
Control for homemade electrocompetent cells/electroporation transformation efficency 

Make more SEVA271 by transforming it into DH5a (link electrocomp protocol)
 
Plate 100 uL on Kan diluted once with 1:10 dilution in LB

## July 21st
Make overnight culture of SEVA271 colony 

Make overnight culture of T7 pGS21a_Phi29_Col17 cells 

Pour Kan+Carb plates  

Order protein 1 gblock and primers from IDT to incorporate it into pGS21a_Phi29_Col17 backbone

## July 23rd
Miniprep SEVA271 plasmid 

Nick SEVA271 plasmid with Nb.BtsI (link protocol)

Make T7 pGS21a_Phi29_Col17 cells electrocompetent and transform with SEVA271 

Plate 100 uL from serial dilution (3) onto Kan+Carb plates 

## July 26th 
Count Colonies on SEVA271 plate and calculate transformation efficiency 

Test for different concentrations of Trimethoprim using SEVA224+DHFR construct :

PCR amplify SEVA224 and DHFR using primers ordered off of IDT 

Cleanup elute : 20uL each 

| SEVA224 | DHFR  |
| ---- | ---- |
|  70.9 ng/uL | 104.8 ng/uL |

Resuspend p1 gblock gene fragment in elution buffer 

## July 27th
Made and ran gel of DHFR(2% gel) and SEVA24( 0.8% gel) PCR to ensure correct length 

SEVA224 (~4000 bp shown next to 1 kb ladder) :

<img width="249" alt="Screen Shot 2021-08-06 at 1 01 31 PM" src="https://user-images.githubusercontent.com/77999251/128565285-25c3f4e5-42f8-406e-8844-f5e8aef168b8.png">

DHFR (~300bp shown next to 100 bp ladder) :

<img width="265" alt="Screen Shot 2021-08-06 at 1 01 19 PM" src="https://user-images.githubusercontent.com/77999251/128565307-7cca5ddc-50f5-4b9a-9b69-1ce0ab963357.png">

## August 2nd  
DpnI digest of SEVA224 backbone

SEVA224 conc. elute 16 uL : 49.3

BsaI digest of SEVA224 and DHFR (link protocol)
 
 30 min. in add 1 uL rSAP to SEVA224
 
 elute into 10 uL
 
| SEVA224 | DHFR  |
| ---- | ---- |
|  37.9 ng/uL | 105.1 ng/uL |

Ligated fragments together with T4 link protocol)

## August 3rd 
Chemically competent transformation into T7 Express

Plated 100uL on Kan

Made plates with:

Kan + 0.5 mg/mL Tri

Kan + 0.25 mg/mL Tri

Kan + 0.1 mg/mL Tri 

## August 4th 
Saw growth on Kan only selection plates

Restreaked 4 Colonies on each different concentration of Tri + Kan plates 

## August 5th
Saw growth on all Tri + Kan selection plates which means the concentration of Tri is not killing the cells 

## August 9th 
PCR amplify P1 and pGS21a_Phi29 backbone 

Cleanup elute: 20uL 

| P1 | pGS21a_Phi29 (Remix) |
| ---- | ---- |
| 101.45 ng/uL | 102.35 ng/uL |

Run a gel to confirm lengths before digesting 

P1 : 2% gel, 100 bp ladder 
Remix : 0.8% gel, 1 kb ladder 

P1 gel (~300 bp ): 

<img width="271" alt="Screen Shot 2021-08-10 at 12 01 11 PM" src="https://user-images.githubusercontent.com/77999251/128919550-e14a941f-71e8-4024-9c51-e72ab140584b.png">

Remix gel ( ~ 9370 bp) : 

<img width="259" alt="Screen Shot 2021-08-11 at 10 26 01 AM" src="https://user-images.githubusercontent.com/77999251/129075188-112be313-f721-487b-9a4f-50df5ca6aa7e.png">

- Primer dimerization shown at the bottom of the gel

## August 10th
Make Overnight Culture of T7+remix cells for induction/ transformation 

## August 11th
OD600 of Overnight Culture : 3.17

Make Plates with 500 mL LB+Agar: 

| 0 mM IPTG | 0.1 mM IPTG | 1 mM IPTG |
| ---- | ---- | ---- |
| 500 uL Carb| 500 uL Carb | 500 uL Carb |
| 0 uL IPTG | 500 uL IPTG | 5 mL IPTG |
| 5 mL Tri | 5 mL Tri | 5 mL Tri |

3 Induction Flasks:

| 0 mM IPTG | 0.1 mM IPTG | 1 mM IPTG |
| ---- | ---- | ---- |
| 50 mL LB | 50 mL LB | 50 mL LB |
| 0 uL IPTG | 50 uL IPTG | 500 uL IPTG |
| 789 uL cells | 789 uL Cells | 789 uL Cells |

Start : 0.05 OD600

End : 0.7 OD600

Make Induced Cells Electrocompetent 

- 45 mL cells per tube (x uL H20 by 9)

- Aliquot into 9 tubes

| 0 mM IPTG | 0.1 mM IPTG | 1 mM IPTG |
| ---- | ---- | ---- |
| no pL | no pL | no pL |
| pL | pL | pL |
| thiolated pL | thiolated pL | thiolated pL |

- Put 3 tubes in -80 to run protein gel on in the future 

Transform with :

pL conc. : 85.6 ng/uL -> 0.4 uL 

Thio pL conc. : 68.8 ng/uL -> 0.58 uL

Plated 100 uL on each conc. 

## August 12th
- No growth on any plate 

Run gel on thiolated and non-thiolated pL to ensure ligated correctly 

ran 300 ng DNA

| Ladder | Non-Thio pL | Thio pL |
| ---- | ---- | ---- |
| 3 uL dye | 3 uL dye | 3 uL dye |
| 1 uL 100 bp | 3.5 uL DNA | 4.4 uL DNA |
| 8 uL H2O  | 5.5 uL H2O | 4.6 uL H2O |


1% gel , 125 V, 35 min.: 

<img width="328" alt="Screen Shot 2021-08-12 at 12 56 43 PM" src="https://user-images.githubusercontent.com/77999251/129261246-4e677bee-64b6-4b8c-b8f0-4695e3d7f0ff.png">

Correct length = 776 bp

## August 13th 

- To prevent primer self dimerization use smaller concentration : 100 nmole


| Q5 | H2O | DNA | FWD Primer | REV Primer |
| ---- | ---- | ---- | ---- | ---- | 
| 25 uL | 23.5 uL | 0.5 uL | 0.5 uL | 0.5 uL |

0.8% gel 130 V 35 min. :

<img width="278" alt="Screen Shot 2021-08-13 at 2 25 15 PM" src="https://user-images.githubusercontent.com/77999251/129430902-47af6295-1edc-4761-95be-172e2819615c.png">

- Still primer dimers 

## August 16th 
Run protein gel on induced/ electrocompetent cells in -80 

- use T7 cells as neg. control 
- run on any kD gel and 7.5% gel to see DNAP

| T7 | 0 mM IPTG | 0.1 mM IPTG | 1.0 mM IPTG | 
| ---- | ---- | ---- | ---- |
| 4.67 mg/mL | 56.6 mg/mL | 39.97 mg/mL | 31.15 mg/mL |

- dilute down to 5 mg/mL with Bugbuster 
- added Laemli+BME to denature proteins 
- ran 50 ug of each sample ( 10 uL)

200 V 50mA 

initial voltage : 100V 

rinse gel with DI H2O

stain overnight in colloidal coomassie stain

## August 17th 
Gel stained for 20 hours, broke in container and some slipped into aqueous waste

Rerun the any kD gel 

| Protein | Expected Size (kDa) |  
| ----| ---- |
| DNA Polymerase | 95 kDa | 
| Terminal Protein | 31 kDa| 
| Single Stranded Binding Protein | 13.3 kDa | 
| Double Stranded Binding Protein | 12 kDa | 

Imaged both gels : 

7.5% :

Ladder: 

<img width="68" alt="Screen Shot 2021-08-17 at 1 13 29 PM" src="https://user-images.githubusercontent.com/77999251/129794227-903aba45-9f42-4758-b0dd-c5fdacc2ffa9.png">


<img width="363" alt="Screen Shot 2021-08-17 at 1 07 31 PM" src="https://user-images.githubusercontent.com/77999251/129794097-6fbe8c83-9351-4f02-8450-18b552459d40.png">

any kD : 

Ladder : 

<img width="49" alt="Screen Shot 2021-08-17 at 1 27 47 PM" src="https://user-images.githubusercontent.com/77999251/129795866-df6a04d1-ea0a-4f9d-8b34-a46f19d213ff.png">

<img width="446" alt="Screen Shot 2021-08-17 at 1 07 38 PM" src="https://user-images.githubusercontent.com/77999251/129795819-753f6960-ff5e-4144-8170-9a7f46a6811d.png">

- diluted original samples again with bugbuster 
- ran new any kD and 7.5% gel 
- 50 ug of each sample  ( 10 uL of each sample ) 
- stained overnight with Coomassie Colloidal Stain for 18 hours 

## August 18th 
- Try to use Betaine to remove primer dimer secondary structures from pGS21a_Remix_Backbone PCR reaction for adding P1

1M Betaine : 

| Q5 | H2O | DNA | FWD Primer | REV Primer | Betaine |
| ---- | ---- | ---- | ---- | ---- | ---- | 
| 25 uL | 11.5 uL | 0.5 uL | 1.5 uL | 1.5 uL | 10 uL |


1.35M Betaine :

| Q5 | H2O | DNA | FWD Primer | REV Primer | Betaine |
| ---- | ---- | ---- | ---- | ---- | ---- | 
| 25 uL | 8 uL | 0.5 uL | 1.5 uL | 1.5 uL | 13.5 uL |

1.7M Betaine : 

| Q5 | H2O | DNA | FWD Primer | REV Primer | Betaine |
| ---- | ---- | ---- | ---- | ---- | ---- | 
| 25 uL | 4.5 uL | 0.5 uL | 1.5 uL | 1.5 uL | 17 uL |

Cleanup Elute 20 uL 

Concentrations : 

| 1M | 1.35 M | 1.7 M|
| ---- | ---- | ---- |
| 55.5 ng/uL | 34.1 ng/uL | 15.7 ng/uL |


0.8% gel, 140V,  30 min. 

300 ng of each, 6 ng of miniprep product 

<img width="256" alt="Screen Shot 2021-09-03 at 12 03 52 PM" src="https://user-images.githubusercontent.com/77999251/132054769-87d98497-aab7-4e43-b9fe-99ee8ad86cf4.png">

Make overnight culture of T7+remix 
-10 mL LB
-10uL Carb
- scrape colony 

## August 19th 
- Try using 1,2 propane-diol to get rid of dimers 
- Try linearizing DNA (BsaI digest)

Miniprep T7+Remix overnight culture 

Elute 35 uL 

Conc. 1 : 11.95 ng/uL

Conc. 2 : 9.45 ng/uL 

BsaI digest: 
- cut all of mp 1 

 | Cutsmart | BsaI-Hfv2 | H2O | DNA |
| ---- | ---- | ---- | ---- | 
| 5 uL | 0.4 uL | 11.6 uL | 33 uL (400 ng) |

incubate 37C for 1 hour, heat inactivate enzymes 80C for 20 min

Cleanup elute 20 uL 

Conc. 11.5 ng/uL 

Remix PCR 1,2 Propane-diol ( not linearized ) :

| Q5 | H2O | DNA | FWD Primer | REV Primer | 1,2 Propane-diol|
| ---- | ---- | ---- | ---- | ---- | ---- | 
| 25 uL | 18.5 uL | 0.5 uL | 1.5 uL | 1.5 uL | 3 uL |

BsaI cut Remix PCR 1,2 Propane-diol :

| Q5 | H2O | DNA | FWD Primer | REV Primer | 1,2 Propane-diol|
| ---- | ---- | ---- | ---- | ---- | ---- | 
| 25 uL | 18.5 uL | 0.5 uL | 1.5 uL | 1.5 uL | 3 uL |

BsaI cut Remix PCR 1.35M Betaine :

| Q5 | H2O | DNA | FWD Primer | REV Primer | Betaine |
| ---- | ---- | ---- | ---- | ---- | ---- | 
| 25 uL | 8 uL | 0.5 uL | 1.5 uL | 1.5 uL | 13.5 uL |

## August 20th 
Concentrations : 

Remix PCR 1,2 Propane-diol ( not linearized ): 57.9 ng/uL

BsaI cut Remix PCR 1,2 Propane-diol : 84.6 ng/uL

BsaI cut Remix PCR 1.35M Betaine : 40.5 ng/uL

## August 24th 
How gel was oriented: 

| PD remix PCR | BsaI cut Betaine remix PCR | BsaI cut PD remix PCR |
| ---- | ---- | ---- | 
| 200 ng | 200 ng | 200 ng | 

<img width="239" alt="Screen Shot 2021-09-03 at 12 21 49 PM" src="https://user-images.githubusercontent.com/77999251/132056324-caf12f8f-0697-4f63-adf3-c3bde57570ac.png">

## August 25th
- Make new assembly on Benchling where P1 is inserted after TP stop codon before DSBP RBS
- Make another new assembly on Benchling where P1 is inserted after DSBP stop codon before SSBP RBS 
- Make new assembly on benchling for PCR mutagenesis of entire insert 
- Make new assembly on benchling for PCR mutagenesis of TP+DNAP
- Make new assembly on benchling for PCR mutagenesis of TP

- Order all primers 

## September 1st 
Make more non-Thio and Thio pL 

Cleanup Elute 20 uL

Conc. : 

| OriL | Middle | OriR |
| ---- | ---- | ---- | 
| 120.45 ng/uL | 111.5 ng/uL | 138.9 ng/uL | 

| Thio-OriL | Middle | Thio-OriR |
| ---- | ---- | ---- | 
| 96.2 ng/uL | 124.05 ng/uL | 109.6 ng/uL | 

## September 2nd 

BspQI digest w/ 19 uL DNA

| OriL | Middle | OriR |
| ---- | ---- | ---- | 
| 19 uL DNA | 19 uL DNA | 19 uL DNA| 
| 5 uL NEB 3.1 Buffer| 5 uL NEB 3.1 Buffer| 5 uL NEB 3.1 Buffer|
| 2.2 uL BspQI | 2.1 uL BspQI | 2.6 uL BspQI |
| 23.8 uL H2O | 23.9 uL H2O | 23.4 uL H2O |

| Thio-OriL | Middle | Thio-OriR |
| ---- | ---- | ---- | 
| 19 uL DNA | 19 uL DNA | 19 uL DNA| 
| 5 uL NEB 3.1 Buffer| 5 uL NEB 3.1 Buffer| 5 uL NEB 3.1 Buffer|
| 1.8 uL BspQI | 2.3 uL BspQI | 2 uL BspQI |
| 24.2 uL H2O | 23.7 uL H2O | 24 uL H2O |

Total: 50 uL

Incubate 50C for 1 hour 

Cleanup elute 12 uL 

Conc. : 

| OriL | Middle | OriR |
| ---- | ---- | ---- | 
| 99.3 ng/uL | 84.6 ng/uL | 85.3 ng/uL | 

| Thio-OriL | Middle | Thio-OriR |
| ---- | ---- | ---- | 
| 84.3 ng/uL | 106.5 ng/uL | 86.7 ng/uL | 

1:2 backbone: Ori's ratio for ligation 

3 PCR tubes all with same volume :

| T7 Ligase Buffer | OriL | Middle | OriR | H2O | T7 Ligase | 
| ---- | ---- | ---- | ---- | ---- | ---- | 
| 15 uL | 2.08 uL | 4 uL | 2.46 uL | 5.46 uL | 1 uL | 

| T7 Ligase Buffer | Thio-OriL | Middle | Thio-OriR | H2O | T7 Ligase | 
| ---- | ---- | ---- | ---- | ---- | ---- | 
| 15 uL | 3.08 uL | 4 uL | 3.03 uL | 3.89 uL | 1 uL | 

Total : 30 uL 

Incubate 25C for 1 hour in thermocycler 

Cleanup Elute 12 uL

Conc. : 

pL : 55.75 ng/uL

Thio-pL : 47.1 ng/uL 

## September 3rd 
- Amplify pGS21a_Remix backbone for p1 using 2 different sets of new primers ( one after DSBP stop codon the other after TP stop codon) but with same overhang as original assembly 
- Add Betaine to ensure no primer dimers

| Q5 | H2O | DNA | FWD Primer | REV Primer | Betaine |
| ---- | ---- | ---- | ---- | ---- | ---- | 
| 25 uL | 8 uL | 0.5 uL | 1.5 uL | 1.5 uL | 13.5 uL |

Cleanup Elute 20 uL 

Concentration after TP : 30.8 ng/uL

Concentration after DSBP : 23.6 ng/uL

## September 7th 
Run gel: 0/8% gel, 130 V 30 min.

| Ladder | After DS | After Tp |
| ---- | ---- | ---- |
|1 uL 1 kb Ladder | 6 uL DNA | 8.5 uL DNA |
| 3 uL dye | 3 uL dye | 3 uL dye |
| 10 uL H2O | 5 uL H2O | 2.5 uL H2O |

Gel ( want band around 9kb) : 

<img width="275" alt="Screen Shot 2021-09-07 at 11 35 06 AM" src="https://user-images.githubusercontent.com/77999251/132394204-191a04ea-279f-46b2-8507-ebfb94725b31.png">

- Run PCR on backbones of fragments that are going to be mutated :
- backbone for entire insert
- backbone for TPDNAP 
- backbone for TP

How PCR was set up:

| Q5 | H2O | DNA | FWD Primer | REV Primer | Betaine |
| ---- | ---- | ---- | ---- | ---- | ---- | 
| 25 uL | 8 uL | 0.5 uL | 1.5 uL | 1.5 uL | 13.5 uL |

## September 8th 
Cleanup elute 20 uL

Conc. :

Backbone for entire insert : 28.15 ng/uL

Backbone for TPDNAP : 76.2 ng/uL

Backbone for TP : 65.75 ng/uL

Run 300 ng on gel, 130 V, 30 min. 

| Ladder | insert backbone | TPDNAP backbone | TP backbone |
| ---- | ---- | ---- | ---- |
|1 uL 1 kb Ladder | 10.6 uL DNA | 3.93 uL DNA | 4.56 uL DNA |
| 3 uL dye | 3 uL dye | 3 uL dye | 3 uL dye |
| 10 uL H2O | 0.4 uL H2O | 7.1 uL H2O | 6.4 uL H2O |

Gel : 


























