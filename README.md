# Toy PCR exercise

Open [index.html](index.html) in a browser to use the exercise. It is a standalone file with no other assets to upload. For GitHub Pages, place `index.html` in the directory published by the site.

## Student workflow

1. Examine both strands of the starting DNA. The green region is the target to amplify.
2. Optionally choose a new 27-base starting sequence and a primer length from 3 to 6 bases. The default is a 3-base primer and an 18-base starting sequence.
3. Enter the forward and reverse primer sequences **5′→3′**. The exercise checks whether they pair at the two ends of the green target. Incorrect primers produce an explanation.
4. Step through melting, primer annealing, and extension for three cycles. Every product made by extension is shown.
5. Enter the **total** number of cycles, including the three already shown, and select **Continue**. The final view shows the sequences and counts of all five product types. Select **Show log count bars** to compare their counts on a logarithmic axis.

## Teaching model

- The short primers are for teaching only. Real PCR primers are usually about 20 bases long; 3–6-base primers can bind at many genomic sites. This model shows binding only at the intended target ends.
- The longer starting DNA is 27 bases, exactly 50% longer than the 18-base default. Three bases on each side lie outside the green target.
- After cycle 1 there are 2 two-strand molecules; after cycle 2, 4; and after cycle 3, 8. The first two molecules with both strands exactly the target length appear after cycle 3.
- Final counts assume perfect primer binding and extension, with every available strand copied once per cycle and no loss of product. For a total of N cycles, the model gives 2^N two-strand molecules, of which 2^N − 2N have both strands exactly the target length. This idealized calculation does not model reagent depletion or reduced amplification efficiency.
- Some longer product types have a single-stranded flank or overhang. The final view counts each paired two-strand product as one molecule.

The exercise does not collect answers or grades. When browser storage is available, it remembers the current state locally.
