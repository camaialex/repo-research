---
authors: Houghton
institution: Fred Hutch
version: 1.1
last_updated: 3/19/2023
aliases: 
type: SOP
project: [[]]
status: Verified
---

# Procedure Name
---
> [!SUMMARY]
> This protocol produces cDNA from isolated RNA in preparation for [[qPCR]]
> Using SuperScript II system ([Thermo](https://www.thermofisher.com/order/catalog/product/18064014))

# Materials
---
- RNA samples
-  Oligo-dT
-  dNTPs
-  SuperScript II, 10,000U
-  DTT
-  5x RT Buffer
-  Thermocycler

# Procedure
---
_Before start: turn on PCR machine, thaw reagents, prepare RNA dilutions_

# Anneal
1. In PCR tubes, pipet 11ul RNA mix. Make sure all liquid goes to bottom.
2.  Add 1ul oligo-dT. Put the lid on carefully and quick spin.
3.  Run “annealing” program in the PCR machine.
		
	_Annealing PCR Rxn:_
	1)  65C, 5 min
	2)  4C, hold

4.  While annealing proceeds, make enzyme mix for RT rxn.

# Enzyme mix, 1X (per sample):
---
- 1ul​dNTP
- 1ul​SSII
- 2ul​DTT
- 4ul ​5X buffer

5. Keep the samples on ice, then quick spin before opening tubes.
6. Add 8ul enzyme mix to each tube (20ul final volume). Close lids. Quick spin.
7. Run “SSIIRT” program in the PCR machine.

	_SSIIRT PCR Rxn:_
	1) 42C, 1 h
	2) 72C, 15 min
	3) 4C, hold
8. Quick spin. If multiple rxns ran for the same sample, pool together.
9. Proceed with qPCR, or store at -20C.. 

# Troubleshooting and Tips
---
- 

---
_Tags:_ #ref #dna #sop 