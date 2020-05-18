# PCCR
Track Hub for Pairs of Conserved Complementery Regions

## How it works:
1. Copy the link https://raw.githubusercontent.com/kalmSveta/PCCR/master/hub.txt
2. Go to UCSC Genome Browser: https://genome.ucsc.edu/
3. Open My Data -> Track Hubs
4. Select My Hubs 
5. Paste the link into the bar and press Add Hub 

Data for two Human genomes is avaliable: Hg19 and Hg38.

The Hub includes the following tracks:

### PCCRs classified by the free energy dG, kcal/mol:
dG <= -15, -20, -25, -30\
The categories are CUMULATIVE. Additionaly, color of the structure indicates mutually exclusive categories:
- green - -20<ΔG<=-15
- yellow - -25<ΔG<=-20
- orange - -30<ΔG<=-25
- red - -35<ΔG<=-30
- magenta - ΔG<=-35

### PCCRs classified by the spread, nts:
spread <= 1000, 100\
The categories are CUMULATIVE. Additionaly, color of the structure indicates mutually exclusive categories:
- pink - 100<spread<=1000
- violet - spread<=100

### PCCRs classified by the evolutionary conservation e-value:
e-value <= 0.5, 0.05\
The categories are CUMULATIVE. Additionaly, color of the structure indicates mutually exclusive categories:
- light blue - 0.05<e-value<=0.5
- dark blue - e-value<=0.05

### PCCRs intersected with known long-range RNA structures
- black - known structures
- green/yellow/orange/red - PCCRs interscected with the known structures

### Probing data intersected with PCCRs:
- icSHAPe - red for plus strand and blue for minus strand. 
- PARIS
- LigRseq

### Experimental data of RNA pol II inhibition:
- a-amanitin 1 mcg/mL
- a-amanitin 2 mcg/mL 
- R749H mutation\
Color of exon indicate sign of delta PSI = PSIcase - PSIctr:
  - blue - dPSI < 0
  - red - dPSI > 0
