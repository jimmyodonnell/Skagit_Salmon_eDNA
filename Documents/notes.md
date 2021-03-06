# Notes

_Add new items to the top_

[Sampling schedule](https://docs.google.com/spreadsheets/d/1rGF1CfOnSjiN8vHExiMQmoFGV8nV1kTJqkbsKRKS8jc/edit?ts=5887f21e#gid=0)

## 2018-03-06
- qPCR: note that the detector for the CKCO3 assay is named on the machine 'jimmy161209'

## 2018-03-02
- qPCR: used up the last of sample SKA-094 full strength
- more than 3uL were put into well 9b

## 2018-02-22
- Meeting: Ole, Jimmy, Linda. Jimmy's to-dos
  - All further work will focus on seine sites only
  - Put an aliquot of target samples into the fridge -- enough DNA for 3-6 qPCR reactions and 3-6 sequencing reactions
  - make sure we have enough volume of DNA for the remaining qPCR + seq replicates
  - ole will work on catch data next week
    - Jimmy will send Ole R code
  - qPCR:
    - check which samples have been run for CKCO3
    - which samples have been run for CYAG
    - increase DNA into qPCR for improved efficiency
  - sequencing
    - get Abi a list of templates to start PCR1
    - call Illumina, ask about cluster density on last run

## 2018-01-08
- Qubit of four samples:
  - post PCR1, 2 replicates of each sample were pooled
  - gel image IMG_4000 is of these
  - they were then cleaned up with Qiagen minelute PCR cleanup kit, eluted into 16 uL water
  - 1 uL from each of these was used for qubit
  - the remaining 15 uL went into PCR2 (illumina index PCR)
    - PCR2 details: 12 cycles, on machine bob, under user jimmy

## 2018-01-08
- Amplicon preparation:
  - The thermal cycler profile I have been using (Ford2016_PCR1) has lower denaturation temp; the mastermix I'm using should have higher denaturation temp. This might help improve success rate. Use protocol 'Prey16S-A_JD_2017' instead (see updated manuscript google doc).
- qPCR:
  - redo plate. Again. But use 6 replicates per dilution level.
  - compare SD ~ min(Ct) for each of standards, and controls.
  - check for similar limit of detection across assays/standards
  - volume of template into 10 uL qPCR can be upped from 2 uL to 3 uL

## 2018-01-02
- Abi caught an error:
  - *"The sample we have listed in our data sheets as 67 is actually sample 69. The label on the tube is hard to decipher so I went back and looked at the cleaning records, we never did 67, but we did do 69. I've changed it in the plate layout_updated sheet in the folder, and in my notes, but you'll want to change the sample to 69 in anything related to this qPCR (position I4-6), and in the Aug 30th 2017 qPCR (B22-24)."*

## 2017-09-08
  - Tapestation: samples, pooled amplicons: (27, 28, 92a, 94, 595); 595 failed.
  - PCR: PCR2 (index PCR); 
  - Cleanup: Ampure XP beads at 0.8 ratio
  - Tapestation: 

## 2017-09-07
  - PCR: PCR1 (16S-prey); samples, 3 replicates each: (27, 28, 92a, 92b, 92c, 94a, 94b, 94c, 595, 598)
  - Cleanup: Qiagen PCR cleanup kit

## 2017-08-03
- After PCR1, our samples had between 3 and 14 ng/uL
- Average expected fragment size after PCR1: 443bp
- SPRI size selection recommends sample volume should be ≥ 50 μL (but see illumina 16S metagenomic protocol)
- Sequalprep requires as input no more than 25uL of PCR product, containing at least 250 ng of amplicons.
- Thus, concentration after cleanup of PCR2 must be at least 10 ng/uL

## 2017-06-27
- For first round of sequencing, focus on beach seine index sites
- All sites visited at least 4 times
- Wylie Boat Ramp and Goat Island not sampled in summer 2016
- Sites sampled five times in 2017:
  - Turners, Strawberry, Lone Tree, Hoypus, Goat, Dugualla

## 2017-01-23
- Skagit River Systems Coop sampling schedule:
  - Seine: 12 index sites; 2x per month on NEAP tides
  - Fykes: 7 index sites;  2x per month on SPRING tides (high in AM)

- Total samples:
  - Fyke:   7 sites * 4 samples * 4 visits (original math was 7 * 4 * 5)
  - Seine: 12 sites * 4 samples * 4 visits (original math was 7 * 4 * 5)
- Crew needed:
  - Seines: 1 boat driver, 2 sample collectors
  - Fykes:  2 sample collectors

- Number of water samples per site:
  - optimal: 5; minimum: 4


- At two of the fyke sites, there is occasionally (when?) a mark-recapture study

- Personnel: *Ole's kid arrives ~ March 22, don't rely on him Feb 22 - April 22*
  - Boat drivers:
    - Wes, Ole, Kelly, Greg
  - Sample collectors:
    - Ole, Jimmy, Correigh, Josh, Jason, ?Kinsey?, Anna, Kelly, Ramon, Jono, Correigh, Katherine, Stu, Jenny, Raphael, ?Hollings Scholars?
  - Molecular (extractions, etc):
    - Jimmy, ?Abby?, ?Ask Jameal if there is money?

- Fish abundance in time:
  - __________: begin: early-Feb; peak: mid-March; end: mid-May
  - __________: begin early Feb and quickly peak; wind down through March, second slow peak in early May.


## 2017-01-11
- Specificity of chinook qPCR assay
  - Chinook and Coho may share some variation at COX3; we should test on DNA from tissue
  - Piper has tissue from these species and populations from which the variation is known. She offered to extract DNA alongside other extractions she's planning to do anyway.
  - We'll need to run the qPCR on these extractions

## 2016-04-21 Planning meeting
- Fish (smolts) come downstream as early as February
- Rearing continues until it gets warm, usually May or June
- both sampling techniques start in February, continue through about September
- With a 100 foot seine, entire ponds/estuaries can be effectively censused
  - About 20 every two weeks
- Fyke nets sample as tide sinks (with high confidence/efficiency)
  - 6 sites consistently, 3-4 rotating, every two weeks
- Belt transects conducted using trawl to sample water column
  - 500 meters long
  - Samples fish greater than about 100 millimeters
  - 36 per month
  - starts the week of May 16
  - low confidence
- We should only sequence samples taken at sites where methods/estimate is "good"
  - enclosed lagoons, etc
