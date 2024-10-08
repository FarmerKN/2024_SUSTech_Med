# Protocols
## 1.Primer construction
The principle we need to follow:

1) For a single primer sequence: 5'-protected base + enzyme cutting sequence +20bp and template pairing sequence (CG base content is preferably 40-60%, the 3' end ends in G or C, and the difference in Tm values of the forward and reverse primers does not exceed 5℃)

2)Primers naming rules: h/m (human/mouse gene) + gene name + F/R (positive/reverse) + cleavage site

3)The fragment to be amplified must not contain the cleavage site of the endonuclease used.
 
## 2.PCR proving
1)Set up the following PCR reaction systems if using NEB Phusion DNA polymerase (note: Fidelity of Phusion seems not satisfactory, KOD DNApolymerase is better so should follow KOD's instruction to amplify)

Materials:

      ddH2O						X μl
      5X buffer				        10μl
      10m M dNTPs	          	  	        1μl
      Forward primer(10 μM)	   	                1.5 μl
      Reverse primer(10 μM)	   	                1.5 μl
      Template			               	50-100mg for plasmids and pure genomic DNA
      DMSO					 	1.5 μl
      Phusion DNA Polymerase	   	        0.5 μl
      Total					        50 μl
 
PCR program: always use hot lid

| Step | Temperature  |  Time  |
|:-------:|:-------:|:---------:|
| Initial Denaturation | 98℃ | 30s  |
| 32 Cycles | 98℃ | 15s   |
|  | 5-65℃ | 30s  |
|   | 72℃ | 30s/kb   |
| Final Extension | 72℃ |  2-5minutes    |
| Hold | 10℃| Infinite |

2)Run 5μl of PCR product on DNA gel to see if it's specific. If so, could directly purify the remaining PCR product. (Usually determine the concentration of PCR product after purification). If not specific, could use touchdown PCR to optimize.

(Supplementary: After PCR verification, if the gel image shows a single band, the product is purified and recovered. If the bands are not single, gel extraction is used for recovery. Refer to the kit instructions for specific operating procedures.)
 
## 3.Double enzyme digestion
1)Set up 20 μl digestions system and digest at 37C incubator.(Digestion can go from 2 hours to overnight depending on the enzyme efficiency.)

Materials:
 
      ddH20 			        X μl
      10x Buffer        			2 μl
	  Enzyme1           			1 μl
      Enzyme2           			1 μl
      Insert or vector                      1 μg
      Total         			20 μl
Note：

(but for vectors, don't use overnight digestions). For FA (Fse1 and Asc1) cloning, 5hoursshould be enough. To reduce potential self-ligation in later steps, add 1 μl of ClAP intothe vector digestion mixture and incubate for another 30min at 37℃ beforeharvesting. Inserts don't need ClAp treatment. For ligation of digested vectors and annealed oligoes with overhangsit's better to dephosphorylate digested vectors with ClAP and then add 0.5 μl T4 PNK in the 10 μl ligation system.
 
## 4.Ligation
1)Set up ligation system as follows and incubate at room temperature (RT) for 1 hr to overnight. When using the newly-digested vectors for the first time, always set up a no-insert ligation control.

Materials：

      ddH20           			4.5 μl
	  10x buffer	        		1 μl
	  Digested vector        		1 μl (0.5μl if vector has been proven good)
	  Digested insert
	  (or water for control)                3 μl (2.5μl if insert has been proven good)	
	  T4 Ligase		            	0.5 μl
	  Total			            	10 μl
 
## 5.Transformation into competent cells
1)Thaw competent cells on ice. Transform the 10μl ligation including the no-insert ligation control into competent cells, respectively. Recover for 1hr at 37℃ with shaking and then centrifuge bacteria down at ~8000rpm. Plate all pellets onto agar plates with correct antibiotics. Incubate plates upside-down in 37℃ incubator overnight.

2)The next morning, check colonies. If colonies from the no-insert control is significantly fewer than your construct of interest, you'll only need to pick up 2-3 colonies for each ligation.Inoculate colonies into 5ml 2YT media with appropriate antibiotics,shake at 37℃ (around 200rpm) for at least 8 hr.

3)Miniprep from 4 ml cultures. Roughly using 1 ug plasmids to be digested by the same set of restriction enzymes with lower amount (0.3μl of each enzyme is enough) and verify the presence of vector and insert of correct size. If correct, send 1 or 2 plasmids for each ligation to be sequenced. For difficult ligation, could also use colony or culture PCR to screen more colonies.

4)In the meantime, save the remaining culture at 4℃. lf the construct is designed to transfect mammalian cells, after the corresponding plasmid is sequenced/validated correct, inoculate the remaining culture to 100ml 2YT media with correct antibiotic and culture for 16-18 hr before harvesting. Bacterial pellets could be stored at -20℃ or lower before maxi-prep.
    
(Supplementary: After transformation, colony PCR and gel electrophoresis were performed to check for the target band with a specific bp value. If present, it indicates a successful transformation. If the results are accurate, plasmid extraction is conducted following the kit instructions, and 1-2 μl of the extract is sent for sequencing. )
 
## 6.Western-Blot (Note: make more gels than needed in case one leaks)
Check the SDS PAGE Preparation sheet for exact recipe for a certain % acrylamide gel or thickness of gel. In this case, 15% with a thickness of 1 mm gel is used this protocol.

1)Assemble the 2 glass plates in which the gel will be placed in between together, with the shorter plate facing the front. Make sure the bottom edges of the plates are aligned.

2)Place the glass plates into plate holders.

3)Place glass plates in holder onto the clear casting container with shorter glass facing forward- make sure all aspects of the bottom of the gel are touching the grey sponge.

4)1st make separating solution:
      
	  a. 4.4 mL of ddH2O – reuse serological pipette
	  b. 5.2 mL of 1.5 M Tris (pH 8.8) - reuse serological pipette  
	  c. 10 mL of Acrylamide/Bis-acrylamide – toxic to skin – put serological pipette back into paper casing before putting into sharps container
	  d. 200μl of 10% (w/v) ammonium persulfate (APS)
	  *Add following components only when ready to pour solution into gel casting.
	  e. 200μl of 10% (w/v) SDS
	  f. 20μl Of TEMED

5)Mix gently to avoid bubbles and carefully pour solution into the glass cast up until about top side of the green doors.

6)Add 100% isopropanol on top of the separating gel

7)Incubate at room temperature for ~30 mins.

8)When gel has polymerized, pour out isopropanol out.

9)Place entire casting apparatus on the side and place cut pieces of filter paper in between the two glass plates but without touching the gel

10)Make stacking gel

      a. 5.95 mL of ddH20
	  b. 2.5mL of 0.5 M Tris-HCL (pH 6.8)- can reuse serological pipette  
	  c. 1.34 mL of 30%/0.8% (w/v) acrylamide/Bis-acrylamide
	  d. 100μl of 10% (w/v) ammonium persulfaste (AP)
	  *Add following components only when ready to pour solution into gel casting.
	  e. 100μl of 10% SDS
	  f. 10μl of TEMED

11)Take out filter paper, turn casting apparatus upright

12)Using 1mL micropipette add stacking gel all the way to the very top of the glass cast. 
(\*Be gentle to avoid bubbles, but move quickly as the gel polymerizes quickly)

13)Place comb in from the sides, using a paper towel on top to put comb all the way in

14)Add some more stacking gel to the sides and upper edges of the comb

15)When the stacking gel has polymerized, remove gel in the glass plates with comb still intact from the green cast

16)Wrap each gel individually in paper towel and wet with towel with distilled H2O

17)Store gels at 4°C- can be stored for up to a week.

## 7.PVC Purification

This protocol details the steps involved in expressing and purifying PVC proteins from E.coli BL21 (DE3) cells. The procedure includes:

1)Transformation and Culture: PVC plasmids are introduced into E.coli cells, which are then cultured and induced to express the PVC protein.

2)Cell Harvest and Lysis: Cells are harvested and lysed to release the PVC protein.

3)Purification: The lysate is clarified and the PVC protein is purified using Ni-NTA affinity chromatography.

4)Concentration and Validation: The purified protein is concentrated and analyzed using SDS-PAGE to confirm purity and expression level.

## 8.PVC Loading Purification

1)Transformation and Culture: E.coli cells are transformed with the fusion protein plasmid and cultured under optimal conditions.

2)Cell Harvest and Lysis: Cells are harvested and lysed to release the fusion protein.

3)Purification: The lysate is clarified and the fusion protein is purified using Strep-Tactin affinity chromatography. The SUMO tag is then removed using SUMO protease to obtain the final protein.

4)Concentration and Validation: The purified protein is concentrated and analyzed using SDS-PAGE to confirm purity and expression level.

## 9.Cell Culture

This protocol outlines the maintenance of mammalian, insect, and primary spleen cells. Culture conditions and media formulations are provided for each cell type to ensure optimal growth and viability.

## 10.Immunofluorescence

1)Binding and Staining: Cells are incubated with Flag-tagged PVC particles and stained with anti-Flag antibodies and fluorescent dyes.

2)Cytoskeleton Observation**: Cells are incubated with PVC particles and stained with Rhodamine Phalloidin to visualize the cytoskeleton and assess the impact of PVC on cell structure.

## 11.Flow Cytometry

1)Cell Harvest: Cells are harvested and prepared for analysis.

2)Flow Cytometry Analysis: Samples are analyzed using a flow cytometer, and data is analyzed using specialized software to quantify delivery efficiency.

## 12.Deep Sequencing

1)PCR Amplification: Target regions are amplified using PCR.

2)Library Preparation: Libraries are prepared and sequenced on an Illumina MiSeq sequencer.

3)Data Analysis: Sequencing data is analyzed to identify indels and base substitutions.

## 13.Quantitative PCR (RT-qPCR)

1)RNA Extraction: RNA is extracted from E. coli cells.

2)cDNA Synthesis: RNA is converted to cDNA using reverse transcriptase.

3)qPCR Analysis: Gene expression levels are measured using qPCR and relative quantification is performed.

## 14.Mass Spectrometry Analysis

1)Protein Preparation: PVC proteins are prepared for digestion.

2)Digestion and Analysis: Proteins are digested into peptides using trypsin, which are then separated and analyzed using a mass spectrometer.
