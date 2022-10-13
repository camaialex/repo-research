#sop #facs

*For use with BD flow cytometers running FACSDiva software*
*Supporting protocol for [[sop_flow]]*

# FACSDiva SETUP:
1. Create a new experiment with the title firstinitial+lastname date description
2. Go to Cytometer Settings  :
		CHECK FSC H/W and SSC H/W
		DELETE all colors except FSC/SSC
		ADD needed colors.
3. Create samples  :
		Enter correct # of tubes  
4. Go to Experiment > Experiment Layout:
		Rename samples and colors
5. Go to Acquisition:
		Set events up to 50% of the cells you first plated.
6. Go to Experiment > Compensation Setup
		Create composition controls
		DELETE all “generic” compensation
7. Select first sample  

# COLLECTION
1. Set up Global Sheet:
		Enable Global Sheet  
2. Create dot plots:
		FSC vs. SSC (change to square dimensions)
		Time vs. FSC
	Create histograms:
		All marker channels  
3. Adjust FSC and SSC voltage:
		Acquire on excess pooled cells
		Adjust axes   
		Adjust FSC and SSC until majority of at ~250k max on both axes
	Adjust marker voltage:
		If possible, adjust on full stains or single stains of cells
		Center cells around 10e3 (log)
		Center beads at higher signal (≥10e4)
	Record all voltages used for troubleshooting.
5. Collect up to 75% of the cells initially plated. Be prepared to stop collection if flow rate drops.
