### qPCR: quantitative real-time PCR

**REAGENTS**
Per N samples, where N = 3 * (number of samples + 8 dilution steps inclusive of NTC)
- primer 1 @ 10uM
- primer 2 @ 10uM
- probe @ 10uM
- PCR Master Mix @ 2x
- PCR grade water
- DNA templates
- Dilution series (3 replicates each), 

**CONSUMABLES** (per N samples)
- 1.5mL tubes (1 per primer set)
- PCR plate (96 or 384 wells)
- 1000uL filter tips (4N)
- 10uL filter tips (1)

**EQUIPMENT**
- centrifuge for plates
- pipettes (including a repeater pipette and a multichannel pipette capable of loading 96 and/or 384 well plates)
- vortexer
- frozen block for 384 well plates

#### PREPARING THE REACTIONS
- **FIRST: Qubit the full-strength dilution step**
- Get out all reagents and DNA samples
- While these are coming to room temperature, arrange samples in the exact way you will load them on the plate.
- **Vortex** the master mix, primers, and probe.
- Make PCR soup by adding appropriate amounts of the following to a 1.5 mL tube:
  - **master mix**, **water**, **primer 1**, **primer 2**, and **probe**.
- Pipette up and down to mix.
- Get out a plate and set it on a frozen block. _Note that dust and lint will affect the ability of the laser to get good readings._
- Mark conspicuously the top left corner (well A1)
- Mark the top of the plate to indicate where blocks of samples and controls go.
- Using a repeater pipette, add the appropriate amount of PCR soup to each well. Consider first loading this into one strip, and then using a multichannel to distribute to the rest of the plate.
- Using fresh tips each time, add samples to each of the wells of the plate.
- Cover the plate with a clear seal, and wipe with a rubber spatula to seal it tightly.
- Keeping a Kimwipe underneath, load the plate and centrifuge it briefly.

<div style="page-break-after: always;"></div>

#### RUNNING THE MACHINE (Applied Biosystems 7900HT)
- Open the software SDS. (Login as admin; no password needed)
- `File` > `New`, `OK`
- Assay: Standard Curve.
- Tab `Setup`:
  - Add detector (bottom left):
    - `New` > `Name`, reporter = `FAM`
  - select the new row and then click `copy to plate document`
  - highlight all wells you're using (if you are using all wells, select all), and click `use`.
  - highlight wells for NTC and select `NTC` under column `task`
  - highlight wells for dilution series, set `task` to `standard` and set quantity
  - highlight all wells and check the `Use` box in `detector` on the right side
- Tab `Instrument`:
  - Tab `Thermal Cycler`:
    - **IMPORTANT! Set the reaction volume!** (top right corner)
    - Set thermal cycler conditions
  - Tab `Real Time`:
    - `Connect to instrument`
    - Select `Open/Close`
    - Load plate with first well (A1) in the correct position
- Click `Start Run`, and when asked if you'd like to save changes, click `Yes`.
- Create a new directory using the plate ID (e.g. `CKCO3-20160317`) and save your file there.
- Bob's your uncle!

#### AFTER THE RUN
- Close the run (and the software?)
- Reopen the run
- Click `Analysis` > `Analyze` (or bright green triangle button)
- Click `File` > `Save`
- Click `File` > `Export` > and one by one, export data in plain text format named by the file type (e.g. `results_table.txt`).
