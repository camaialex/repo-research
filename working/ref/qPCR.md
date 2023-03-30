---
author: T Pisarenko
lab: Houghton
---

#ref #sop #dna 

> [!NOTE]
> cDNA concentration (RNA concentration): 2ug/20ul = 100ng/ul

# Standard Taqman real time PCR set up:
---
- **10ul** ​2X TaqMan Enzyme Mix
- **1ul​** Primer-probe
- **9ul**​ cDNA plus H2O
- **20ul**​ Total reaction volume


# Setup:
---
1. Work quickly and on ice. Minimize pipetting error to ensure consistency between replicates.
2. Make a master mix of your cDNA samples diluted in H2O (9ul per rxn). Pipette into wells.
	1. Add 1-100ng of cDNA per rxn
	2. Ideally, make enough to run each cDNA sample in triplicate per target
	3. It may be necessary to titrate the cDNA concentration
3. Make a master mix of your primers (1uL/rxn) diluted in 2X TaqMan Enzyme Mix(10uL per rxn) and add to appropriate wells 
	1.  1ul primer-probe plus 10ul 2X TaqMan Enzyme Mix
	2. Again, make enough to run each target in triplicate per cDNA sample

> [!MATH]
> (9uL sample + 11uL TaqMan/primer = 20ul final volume)
	
4. Once finished pipetting, seal the plate with a plate cover and spin down at 1200 rpm for 2 min


# Example: Run on the StepOnePlus:
---
1. Turn on the StepOne Plus
	1. Main power switch is located on the back right next to the black power cord plug
2. Load PCR plate into StepOne Plus
3. Open StepOne Software v2.2.2 on the desktop
4. “Experiment” > “New Experiment”
5. “Set Up” > “Advanced Setup”
6. Experiment Properties
	1. Enter “Experiment Name”
	2. Instrument: “StepOne”
	3. Experiment Type: “Quantitation – Comparative CT (DDCT)
	4. Reagents: “TaqMan”
	5. Ramp Speed: “Standard (~2h to complete a run)
7. Plate setup (click on “Plate Setup” on the left-hand side)
	1. Define “Targets” and “Samples”
		1. Add “Target” or add “Saved Target” aka genes
		2. Add “Samples” or add “Saved Samples” aka cDNA
	2. Assign “Targets” and “Samples” (the tab next to “Define Targets and Samples”
		1. Click on the “Target” or “Sample” on the left-hand side and then assign that into the plate layout on the right-hand side
		2. Click on multiple wells corresponding to the same target or sample
8. Run
9. Analyze
	1. Once the run is finished, the screen will show amp curves on the left-hand side and “View Wells” on the right-hand side
	2. Go to the top next to the green box “Analyze” and click on the grey rectangular box “Analysis Setting”
		1. Keep Automatic Threshold
			1. Undo Automatic Baseline
				1. Set Baseline: Start cycle -3/ end cycle -10
		2. Click “Apply Analysis Setting” on the bottom
	3. Export
		1. Go to the top and click “Export” (blue round icon with yellow arrow)
		2. Select data to export: “Results”
		3. Select “One File” or “Separate Files”
		4. Export file name: leave as it appears
		5. Export file location: browse to find your folder under “Experiment” folder
	4. Transfer your data to J-Drive from D:\\Applied Biosystems\\StepOne Software v2.2.2\\Experiments
		1. J-Drive icon is on the desktop