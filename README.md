# Welcome! Fungal Investigator

Greetings Doctor! Thank you for coming to help us diagnose these patients. 

We know you are a **world-renowned fungal geneticist**, and we greatly appreciate your help. 

As you know, fungal infections are serious and impact many people and animals around the world. 

Many types of fungi, like the mushrooms you get on pizza, are harmless. However, some fungi are microscopic and can infect people! 

With your help, we can **diagnose the infections** at our clinic. 

<img width="400" alt="image" src="https://github.com/user-attachments/assets/c6cc27e1-b211-4114-b41e-529707ec1603" />


&nbsp;
&nbsp;

# Step 1 - Choose a patient

Below are the patients that our clinic has seen with fungal infections. 

We have cultured the fungi from the patients and sequenced a specific region of their DNA called the ITS. 

Please report all of your findings here: _INCLUDE LINK_

<img width="1000" alt="patient_history" src="https://github.com/user-attachments/assets/462d2e73-51ae-4ef2-9665-eb23412dc360" />


&nbsp;
&nbsp;

# Step 2 - How to identify a microscopic fungus

Identifying fungi in patients can be done by looking at the cells. It is important, however, that we know exactly which species each patient is infected with. That can provide valuable information about how to treat the infection. To identify our fungal species, we will use DNA Sequencing.

&nbsp;

## DNA - the genetic instructions

DNA, or deoxyribonucleic acid, is the molecule that carries the genetic instructions for the development, functioning, growth, and reproduction of all known organisms. 

<img width="750" alt="image" src="https://github.com/user-attachments/assets/6baa950e-ac53-49ca-a67f-d117063dc829" />

&nbsp;
&nbsp;

## DNA differs between individuals and species

You and your siblings and/or cousins have similar DNA because you share ancestors (parents or grandparents).

Similarly, species share similar DNA because they are descended from a common ancestor. 

<img width="500" alt="image" src="https://github.com/user-attachments/assets/c65b0807-a1b6-4e6c-8522-862ff11cd540" />

&nbsp;
&nbsp;


## DNA Barcoding 

Fungal species differ from each other in ways we can use to identify them. 

This is called a **DNA Barcode** - this is a region of DNA that can be matched to a reference database for species identification. 

If we visualize DNA such that each base in the sequence is a different color - we can see the differences between the barcodes. 

<img width="500" alt="image" src="https://github.com/user-attachments/assets/205758d2-eeb7-40cc-af68-fd632d75eaf2" />

&nbsp;
&nbsp;

# Step 3 - Analyze your patient's fungal sequence

The clinic has sequenced the barcode region of the fungus infecting your patient. 

This sequence will help you identify what species of fungus is causing the illness. 

## Examine your sequence

The DNA sequences for the barcode region are here:
- alex_c https://github.com/The-Lab-LaBella/fungal_investigator/blob/main/alex_c.fasta 
- casey_m https://github.com/The-Lab-LaBella/fungal_investigator/blob/main/casey_m.fasta
- pepper_a https://github.com/The-Lab-LaBella/fungal_investigator/blob/main/pepper_a.fasta
- blake_c https://github.com/The-Lab-LaBella/fungal_investigator/blob/main/blake_c.fasta 
- nellie_c https://github.com/The-Lab-LaBella/fungal_investigator/blob/main/nellie_c.fasta

&nbsp;
&nbsp;

## Copy the sequence into the NCBI BLAST search 

Open this link - https://blast.ncbi.nlm.nih.gov/Blast.cgi?PROGRAM=blastn&PAGE_TYPE=BlastSearch&LINK_LOC=blasthome 

Paste your DNA Sequence into the box labeled **Enter Query Sequence** and hit the **BLAST** button 

<img width="1500" alt="image" src="https://github.com/user-attachments/assets/91a208a6-a571-49bc-b0f1-a3c4ade6bb19" />

&nbsp;
&nbsp;


## Examine the results and report the species infecting your patient

What fungus is causing your patient to get sick?

&nbsp;
&nbsp;

# Antifungal Resistance 

To treat our patient, we need to identify which antifungal compound can be used to kill the fungus. 

However, some fungi are resistant to antifungals 

&nbsp;

<img width="500" alt="image" src="https://github.com/user-attachments/assets/f251b8cb-bcac-4528-88cd-90e79f174a71" />

&nbsp;


One of the most common antifungals is Fluconazole - which is an azole that inhibits the enzyme **ERG11** also known as **CYP51**

Without active ERG11, the cell's membrane is weakened and toxic compounds start to accumulate. 

&nbsp;

<img width="500" height="565" alt="image" src="https://github.com/user-attachments/assets/5939477f-9aad-4826-8381-6f8e0d014069" />

&nbsp;

Some fungi have mutations in their CYP51 gene that allow them to survive in the presence of Fluconazole. 

This is called antifungal resistance, and it means we need to seek a different treatment plan for this patient. 

&nbsp;
&nbsp;


## View the structure of your species' ERG11 (or CYP51) gene

The ERG11 protein binds to iron, and this is essential to its function. This binding occurs at a "binding site." Mutations at this binding site can lead the fungus to be resistant to treatment with fluconazole. 

We need to figure out what position in the amino acid sequence of the protein does the iron binding occur. 

To do that, we need to examine the structure of the protein. Alphafold, a computer program that predicts protein structure, has been used to generate information about the binding site for our fungal pathogens. 

Select your fungal pathogen and go to the **Features** section to identify the "Position" of the binding site. 

- Aspergillus fumigatus https://www.uniprot.org/uniprotkb/A0A890DMZ9/entry 
- Candida albicans https://www.uniprot.org/uniprotkb/P10613/entry 
- Coccidiodes posadasii https://www.uniprot.org/uniprotkb/Q68HC6/entry 
- Cryptococcus neoformans https://www.uniprot.org/uniprotkb/A0A0G3F905/entry 
- Rhizopus oryzae https://www.uniprot.org/uniprotkb/A0A367JF20/entry 

**What position is the binding site? What amino acid (letter) is at that site?**

&nbsp;
&nbsp;

## Treatment plan

Does your patient's fungal pathogen have the resistance mutation? You hypothesize that if a species has a Serine (S) instead of a Cysteine (C) at the binding site, this can lead to resistance to fluconazole. 

To check this, we will compare the ERG11 gene from your patient's fungal infection with a reference. 

- Alex ERG11 https://github.com/The-Lab-LaBella/fungal_investigator/blob/main/alex_c_ERG11.fasta
- Casey ERG11 https://github.com/The-Lab-LaBella/fungal_investigator/blob/main/casey_m_ERG11.fasta
- Pepper ERG11 https://github.com/The-Lab-LaBella/fungal_investigator/blob/main/pepper_a_ERG11.fasta
- Blake ERG11 https://github.com/The-Lab-LaBella/fungal_investigator/blob/main/blake_c_ERG11.fasta
- Nellie ERG11 https://github.com/The-Lab-LaBella/fungal_investigator/blob/main/nellie_c_ERG11.fasta

&nbsp;

Copy the protein sequences below into the **Upload Data** website by selecting **Text**

<img width="400" alt="image" src="https://github.com/user-attachments/assets/345f5e54-9c76-44f7-9f55-4edf96733ba9" />

Scroll to the position of the binding site. Does your sequence have a C (susceptible to the fluconazole) or an S (resistant to fluconazole?

&nbsp;


**Would you treat your patient with fluconazole?**

# Thanks!


