# Sprechtext zu den Folien

## Slide 1
Hi I am Thomas and my topic is:
“Exploring possibilities for 2-butanol production in A. woodii by exchange of the Adh4 promoter”.

Today I’ll show you how I tried to produce 2-butanol in A. woodii using a genetic approach – and why that matters.

## Slide 2 - A. woodii
First, let me tell you about the star of my project – Acetobacterium woodii!
It’s an anaerobic bacterium that can fix CO₂ through the Wood-Ljungdahl pathway.
It can also produe acetate and mek from 2,3-butanediol via acetyl-CoA.
However, it doesn't produce any 2-butanol.
it grows well without oxygen, it’s easy to genetically modify, and it's safe to handle because it doesn't produce toxic byproducts.


## Slide 3 - Background of the Project
Alright, now that’s clear — what’s my project actually about?

It’s simple: A. woodii can theoretically reduce 2,3-butanediol to 2-butanol — but it gets stuck at an intermediate called MEK.
So the goal is:
a) to understand why it stops there, and
b) to modify A. woodii so the full reduction works.

Why does that matter?
Because 2-butanol is a promising biofuel — it has more energy than ethanol and could replace fossil fuels.
And using the Wood-Ljungdahl pathway, we can couple its production directly to CO₂ fixation.

## Slide 4 - Crispr 
We want to modify the genom of a woodii and for this we used crispr and goldengate 
CRISPR stands for Clustered Regularly Interspaced Short Palindromic Repeats.
It’s part of the adaptive immune system in bacteria and archaea.
Cas proteins like Cas9 can cut DNA at specific sites, making it possible to edit genomes very precisely—either to knock out or insert genes.
The method was developed by Emmanuelle Charpentier and Jennifer Doudna and published in 2012.
They received the Nobel Prize in Chemistry in 2020—and honestly, it’s no surprise.
CRISPR has completely revolutionized molecular biology, medicine, and biotechnology.

## slide 5 . Crispr (genau erklären)

1.) Here you can see how we used the CRISPR/Cas system in our project.
First, we create a single guide RNA – the sgRNA – which acts as our spacer to target a specific DNA sequence.
The Cas protein binds to a nearby PAM sequence and cuts the DNA at the precise location.

2.)  This results in a double-strand break at the targeted site.
The cell detects this damage and tries to repair it.

3.)  To guide the repair, we provide a repair template – a piece of DNA with homologous arms.
These arms match the regions flanking the cut site, allowing the cell to use them for homologous recombination.
During this process, the new, stronger promoter is inserted.

4.)  As a result, the repaired DNA now contains exactly the genetic modification we intended –
a stronger promoter in place of the native one. 

## Slide 6 - Goldengate
to assembly the crispr editing vectors we used golden gate assembly
Golden Gate is a fast and efficient method for assembling DNA.
It uses Type IIS enzymes like Esp3I, which cut outside of their recognition sites.
This allows us to design custom overhangs— so the fragments fit together like puzzle pieces.
Because of that, we can ligate them seamlessly and in the right direction.
It’s super handy for building modular constructs.

## Slide 7 - Aim of the work

The goal of this project was to boost the expression of adh4 by replacing its native promoter with a stronger one.
Then we tested if the modified strain can produce 2-butanol when 2,3-butanediol or another diol is used as a cosubstrate.
And finally, we checked if adding hydrogen helps to shift the redox balance in favor of 2-butanol production.

## Slide 8 - workflow

Here we see the general workflow.
First, we assembled the plasmids: the spacers were annealed, and the promoter, left and right homology arms were amplified by PCR.
Then, we used Golden Gate cloning to build both the spacer and promoter plasmids, and transformed them into E. coli.
After isolating the promoter plasmid with a midiprep, we transformed it into A. woodii.
Finally, we tested if the modified strain is now able to produce 2-butanol.

## Slide 9 - promotor-plasmid

1.) I will only explain the construction of the promoter plasmid, since the other steps are very similar. We start by amplifying the DNA fragments — lha and rha from A. woodii and the pta promoter from Clostridium ljungdahlii — using PCR.

2.) These DNA fragments are then assembled into the plasmid using Golden Gate cloning.

3.) The plasmid is transformed into E. coli, and the bacteria are plated on agar plates containing chloramphenicol for selection.

4.) Colonies are screened by PCR to verify successful transformation and integration of the pta promoter. The PCR targets a DNA fragment containing the promoter sequence.

5.) One of the positive colonies is used to start an overnight culture.

6.) The plasmid DNA is extracted from this culture using a midiprep protocol.

7.) The extracted DNA is further purified with a specialized cleanup kit.

8.) Finally, the DNA concentration is measured using a Nanodrop to ensure there is enough plasmid for the subsequent transformation into A. woodii.

9.) Here we have the finished plasmid at sufficient concentration, ready for transformation into A. woodii.

## Folie 10 - transformation in a woodii 

1.) Now that we have our purified promoter plasmid, the next step is to transform it into A. woodii using electroporation.
This was done according to an established protocol, and since A. woodii is an anaerobic organism, all steps were carried out in an anaerobic chamber under nitrogen atmosphere.

2.) After the transformation, the CRISPR system starts its work:
Cas9 cuts the A. woodii genome exactly at the target site specified by the sgRNA.

3.) The cell then repairs the break via homologous recombination — using the template DNA we provided — and integrates the new, stronger promoter.

4.) Now we have our modified A. woodii strains!
We transformed A. woodii with the modified promoter plasmid

5.) The transformed cells were plated, and colonies were allowed to grow.
This took about two weeks, since A. woodii grows relatively slowly — one reason why we built the plasmid in E. coli first.
Here, thiamphenicol was used as the selection marker.

6.) To ensure the colonies would lose their antibiotic resistance, they were incubated for several days in well plates without antibiotics.
Without selective pressure, the resistance is typically lost within a few generations.

7.) Finally, a PCR was performed to check whether any wild-type DNA was still present.
Only when that could be ruled out...

8.) ...were the confirmed strains transferred to serum bottles for cultivation.

## Folie 11 - serum bottle experiments

Now in the serum bottle experiments,
we studied the growth of A. woodii and its 2-butanol production on different substrates.

The wild-type strains were tested on:

   - 2,3-butanediol alone

   - 2,3-butanediol with methanol

   - 2,3-butanediol with 1,2-propanediol

   - and 2,3-butanediol with ethylene glycol.

The modified strains were tested only on:

   - 2,3-butanediol alone

   - and 2,3-butanediol with methanol.

Additionally, cultures were grown on:

   - 2,3-butanediol alone

   - 2,3-butanediol with methanol

   - and directly with MEK and 1,2-propanediol,

but here the nitrogen atmosphere was replaced by hydrogen
to shift the redox balance toward 2-butanol production.

From all cultures,
we measured optical density at 600 and 660 nm to monitor cell growth — 660 nm was used because of the indicator dye —
and performed HPLC analysis to quantify the metabolites produced.

## Slide 12 

So, now we come to the HPLC measurements

## Slide 13
Here we see
 Here we see both A. woodii strains grown on 2,3-butanediol as the sole carbon source. The curves are very similar, although the strain with the pta promoter seems to react slightly faster. Both strains produce Mek and acetate as expected. we could detect traces of 2-butanol, but the stronger promoter doesn't have any effect of production.

## Slide 14
Next we used propandiol additionaly to butandiol 
 This diagram shows the same basic trend for 2,3-butanediol, but now we’ve added 1,2-propanediol. It’s converted into propionate and 1-propanol in nearly equal ratios. What stands out is that the presence of 1,2-propanediol significantly increases 2-butanol production, as expected. The difference between the two conditions is clear and consistent, indicating that 1,2-propanediol enhances reductive conversion.

## Slide 15

 In this final experiment, we directly added MEK and used hydrogen instead of nitrogen. The reaction proceeded much more slowly, and we consistently detected propanal over several timepoints – a known intermediate that can be further reduced to 1-propanol and propionate. Interestingly, this intermediate was never observed in the nitrogen condition. Also, contrary to expectations, the MEK concentration remained unchanged. Instead, we saw a sharp increase in formate and acetate levels, most likely due to carbonate in the medium being metabolized – possibly because it's the energetically most favorable option for A. woodii.

(## Slide 16 fliegt raus)

## Slide 17

Alright – so, what worked and what didn’t?
We successfully replaced the native adh4 promoter with the pta promoter from C. ljungdahlii.
This led to increased adh4 expression, which was also inducible by 1,2-propanediol.
However, a redox shift towards 2-butanol by hydrogen could not be confirmed.
2-butanol was produced – but not in higher amounts than with the native promoter.

## Slide 18

So, what could we do differently to improve 2-butanol production?

First, instead of focusing on promoter strength, it might be more effective to increase NADH availability.
We could also consider replacing Adh4 with a more selective alcohol dehydrogenase.
Another strategy would be to boost NADH regeneration, for example by introducing formate dehydrogenase.
And finally, testing alternative redox conditions – like formate or CO – could help shift the balance more towards 2-butanol.