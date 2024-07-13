# MoLD: Molecular Docking & Molecular Dynamics 

## Molecular docking of small molecules to HIV-1 proteins


### Workflow
Training data --> Train Chemprop model --> Predict/Screen new molecules --> Dock molecules to HIV-1 proteins --> Predict binding affinity  

## RNA of HIV-1 virus

<img width="1132" alt="image" src="https://github.com/satishgaurav/MoLD/assets/36672530/d5e059ce-6715-4028-b29b-2c5e09c8df5d">

It has 9 genes and encodes for 15 proteins
<img width="1435" alt="image" src="https://github.com/satishgaurav/MoLD/assets/36672530/8be246bf-d71c-4004-8ebe-8c95da96d19d">

Further, these 15 proteins can be classified into 4 types:

1. Structural --> 6 (gp120, gp41, Matrix p17, Capsid p24, Nucleocapsid p7)
2. Enzymes --> 3 (Protease, Reverse Transcriptase, Integrase)
3. Accessory --> 4 (Vif, Vpr, Vpu, Nef)
4. Regulatory --> 2 (Tat, Rev)

<img width="1404" alt="image" src="https://github.com/satishgaurav/MoLD/assets/36672530/3f884059-9e4a-435e-a6e9-aefcb4144303">

Also, protein length in the number of amino acids:

1. Reverse Transcriptase (p66 / p51 subunit) --> 1000 aa (560 aa/ 440 aa)
2. Env (gp120 / gp 41) --> 835 aa (560 aa/ 440 aa)
3. Integrase --> 288 aa
4. Capsid --> 231 aa
5. Nef --> 206 aa
6. Protease --> 198 aa
7. Vif --> 192 aa
8. Matrix --> 132 aa
9. Rev --> 116 aa
10. Vpr --> 96 aa
11. Tat --> (86 - 101) aa
12. Vpu --> 81 aa
13. Nucleocapsid --> 55 aa
14. p6 --> 52 aa

<img width="1341" alt="image" src="https://github.com/satishgaurav/MoLD/assets/36672530/5fe99c94-b43c-4934-b265-6233b02dcd8b">

More details of HIV Structural protein:
gp120 --> surface glycoprotein
gp41 --> transmembrane glycoprotein

<img width="537" alt="image" src="https://github.com/satishgaurav/MoLD/assets/36672530/1e1a0b23-93e3-453f-9fad-485eb45635fb">

Each pair of gp120 and gp41 proteins forms a trimer using a noncovalent bond. The envelope protein helps in the entry of the virus into the host cell. The gp120 protein has 2 regions namely the cd4 binding region and the v3 region. The gp120 subunit is also a key target for the host immune responses against HIV. As shown here, the outer surface of gp120 is heavily **glycosylated**. This **glycan shield** effectively cloaks many of the critical immune determinants that are on the surface of gp120, which helps HIV to evade host immune responses.

<img width="676" alt="image" src="https://github.com/satishgaurav/MoLD/assets/36672530/d953336f-547a-420e-b3d1-1c9edf8ef523">

<img width="344" alt="image" src="https://github.com/satishgaurav/MoLD/assets/36672530/bfc487ec-2b40-4f0d-97c0-aa30146f4cef">

<img width="1420" alt="image" src="https://github.com/satishgaurav/MoLD/assets/36672530/72f3134f-57b9-417f-a8f9-9ddc20001f90">

### HIV Enzyme

HIV has three enzymes namely protease, reverse transcriptase, and integrase. Each of these enzymes plays a critical role in HIV replication.

## HIV Virus Life Cycle:

<img width="1362" alt="image" src="https://github.com/satishgaurav/MoLD/assets/36672530/fb67efff-a66a-4687-9e49-351730657cb3">

--> Expression of the viral gene products
--> Production of virus particles  
--> Infection of a new cell
--> reintegration of the viral genome

### HIV Virus Life Cycle:

step 1: Viral transcripts are expressed from the promotor located in the 5' long terminal repeat (LTR), with **Tat** greatly enhancing the rate of transcription.

step 2: a set of spliced and genomic-length RNAs are transported from the nucleus to the cytoplasm, where they can be translated or packaged. This step is regulated by **Rev**.

step 3: viral mRNAs are translated in the cytoplasm, and the Gag and Gag-Pol polyproteins become localized to the cell membrane. the Env mRNA is the translated at the endoplasmic reticulum (ER).

step 4: the core

Tat: It is an essential protein that plays a crucial role in transcription factors. it increases the production of viral mRNAs ~ 100-fold and consequently is essential for viral replication.

Tat binds not to a DNA site but rather to an RNA hairpin known as TAR (trans-activating response element), which is present at the 5' end of the nascent viral transcripts.

86 amino acids Tat protein has suggested that a hydrophobic core region of about 10 amino acids adopts a defined structure but the rest of the molecule, including the arginine-rich RNA-binding domain, is relatively disordered.

It seems likely that Tat requires interactions with cellular proteins in addition to TAR to adopt a stable structure.

References:
1. Mini-Lectures: Introduction to the Biology of HIV-1 https://www.youtube.com/watch?v=XP8tMBm8zbY
2. Mini-Lecture Series: Overview of the HIV Life Cycle https://www.youtube.com/watch?v=-sNjOZL_Sbg

AutoDock Vina documentation: 
https://autodock-vina.readthedocs.io/_/downloads/en/latest/pdf/


3D Printed Bioreactors Enable Cell Growth: 
https://www.youtube.com/watch?v=CmLvJ_Yxs9E

Molecular Docking | Autodock VINA Virtual Screening | VINA Docking tutorial | Bioinformatics: 
https://www.youtube.com/watch?v=tFFxNTvvoJI


Another video on Autodock: 
https://www.youtube.com/watch?v=2ewpDYW081Y

Autodock Docking of molecules: 
https://youtu.be/rrBsAzq0Fwg?si=d9jmJHKs_MA4zz1H
https://youtu.be/_1zSS1bnHFk?si=mx_NULYeSzJVPeDh
https://youtu.be/TyzjCUfPQj0?si=8ZV8E8nkIXlJpwVk
https://youtu.be/dhs0VOeCo_s?si=0yIdmrvb_0EdQxc8

https://www.csb.pitt.edu/people/faculty/david-koes/
https://en.wikipedia.org/wiki/Pharmacophore
https://pharmit.csb.pitt.edu/


Autodock Vina: 
https://github.com/ccsb-scripps/AutoDock-Vina

GNINA: 
​​https://www.youtube.com/watch?v=7w3SHcdn0gY

Another video on molecular docking: 
https://www.youtube.com/watch?v=UFuVL_0Tpi0

Part-2: 
https://www.youtube.com/watch?v=5SwSbb52PTU

More about protein can be read here: 
https://en.wikipedia.org/wiki/Structure_and_genome_of_HIV

https://www.ncbi.nlm.nih.gov/books/NBK513308/
https://github.com/gnina/gnina

https://github.com/deepchem/deepchem/tree/master?tab=readme-ov-file
https://deepchem.io/tutorials/modeling-protein-ligand-interactions/

https://colab.research.google.com/github/deepchem/deepchem/blob/master/examples/tutorials/An_Introduction_To_MoleculeNet.ipynb#scrollTo=ZElUmobLDLwq


https://colab.research.google.com/github/deepchem/deepchem/blob/master/examples/tutorials/Modeling_Protein_Ligand_Interactions_With_Atomic_Convolutions.ipynb#scrollTo=f7FPLsj4nB-6


https://colab.research.google.com/github/deepchem/deepchem/blob/master/examples/tutorials/Modeling_Protein_Ligand_Interactions.ipynb#scrollTo=cysXf_3bqTs0

https://www.youtube.com/watch?v=AHVJv5RNqKs&t=870s

https://moleculenet.org/datasets-1
https://github.com/deepchem/deepchem/blob/master/examples/tutorials/DeepChemXAlphafold.ipynb
https://github.com/chemprop/chemprop/tree/master
https://chemprop.readthedocs.io/en/latest/args.html#train-arguments


https://journals.lww.com/jaids/abstract/1999/09010/nitric_oxide_modulates_hiv_1_replication.1.aspx


https://en.wikipedia.org/wiki/Abacavir
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC102085/#:~:text=The%20increased%20production%20of%20cytokines,as%20the%20brain%20and%20lung.
https://en.wikipedia.org/wiki/Valinomycin
https://en.wikipedia.org/wiki/Chlorprothixene
https://en.wikipedia.org/wiki/Foscarnet


https://en.wikipedia.org/wiki/HIV
https://en.wikipedia.org/wiki/Antiviral_drug
https://go.drugbank.com/structures/small_molecule_drugs/DB04542
https://go.drugbank.com/drugs/DB03150
https://www.ebi.ac.uk/pdbe-srv/pdbechem/chemicalCompound/show/2DT
https://zinc15.docking.org/substances/ZINC000169289767/
https://www.drugs.com/promethazine.html


https://www.cell.com/cell/fulltext/S0092-8674(20)30102-1#secsectitle0060

https://www.youtube.com/watch?v=U8rHBrdHBDE&t=147s

Zinc 15: 
https://www.youtube.com/watch?v=YnLMG6MHoYE


https://alphafold.ebi.ac.uk/entry/A0A0M3KKW8


https://www.annualreviews.org/docserver/fulltext/biochem/67/1/annurev.biochem.67.1.1.pdf?expires=1711383569&id=id&accname=guest&checksum=258340F869493C1EDB811D3D86CBF73B

https://en.wikipedia.org/wiki/Enfuvirtide
https://en.wikipedia.org/wiki/Ritonavir
https://www.webmd.com/hiv-aids/aids-hiv-medication

https://zinc15.docking.org/tranches/home/

Hiv 1 gp 120 protein structure: 
https://www.uniprot.org/uniprotkb/A0A0M3KKW8/entry
https://alphafold.ebi.ac.uk/entry/A0A0M3KKW8
https://www.ebi.ac.uk/pdbe/entry/pdb/8F9Z



Different drugs for HIV 1: 
https://www.webmd.com/hiv-aids/aids-hiv-medication



6 types of drugs are used for HIV therapy. It primarily works by stopping viral multiplication. 
https://www.ncbi.nlm.nih.gov/books/NBK513308/


HIV type 1: 
Protein list: 

Mechanism of HIV1: 

https://www.annualreviews.org/doi/pdf/10.1146/annurev.biochem.67.1.1

https://en.wikipedia.org/wiki/HIV-1_protease
https://en.wikipedia.org/wiki/Ritonavir

HIV1 protease protein structure: 
https://alphafold.ebi.ac.uk/entry/A0A0M3KKW8

About ZINC dataset: https://www.youtube.com/watch?v=YnLMG6MHoYE
About AlphaFold: https://www.ebi.ac.uk/training/online/courses/alphafold/

From the zinc dataset, I selected two compounds, one is new: 
https://zinc15.docking.org/substances/ZINC000013597823/

Today, I was able to work with the model. So, Firstly I train model on HIV dataset to check model’s ability to classify molecules against HIV replication inhibition. I started with classic HIV dataset from the moleculeent. The dataset contains around 40 thousand molecules tested against the HIV virus (more can be found about that). Now, first time i trained on the whole dataset however, the result I got was not great. I certainly can’t say whether it was because of skewed dataset (Most of the molecules was not effective with 0 value in the dataset) or either it could be because of bad parameter choice. 

However to keep things simple, I, first separated molecules that was active against the virus which is around <1450 molecules. Similarly, I separated non active molecules. Now, to make the dataset balanced I randomly selected 1500 molecules and trained the model on that. 

I think the model worked surprisingly well against classifying the molecules against the virus. 
I found certain molecules that was approved drug for the HIV therapy, the molecules was not included in the training dataset. (I just matched the molecules, however, I didn’t match different representation of smiles in the training dataset).


Interesting find: Out of five times training with different dataset (remember randomly choosing inactive 1500 molecules). N2O nitrous-oxide being as effective against the HIV as 
Stavudine and Zidovudine! crazy!  Right? Later I found a paper on effect of it on the HIV replication [ Tilted: Nitric Oxide Modulates HIV-1 Replication ] I haven’t gone through the study let’s see what they find, although, study was done in 1999! 







https://drugs.ncats.io/drug/776E09GMHQ
https://www.google.com/search?q=cefuroxime&sourceid=chrome&ie=UTF-8

Learning parameters: 
https://www.cell.com/cell/fulltext/S0092-8674(20)30102-1?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS0092867420301021%3Fshowall%3Dtrue#secsectitle0030

Smiles representation of molecules: 
https://archive.epa.gov/med/med_archive_03/web/html/smiles.html


HIV list of antiviral therapy (List of drugs): 
https://www.ncbi.nlm.nih.gov/books/NBK513308/


All predicted drug active against HIV inhibition with probability with more than > 0.9 
https://go.drugbank.com/drugs/DB00552
https://en.wikipedia.org/wiki/Nitrous_oxide
https://moleculenet.org/datasets-1
https://en.wikipedia.org/wiki/Zidovudine
https://en.wikipedia.org/wiki/Stavudine

https://zinc15.docking.org/substances/ZINC000169289767/
https://en.wikipedia.org/wiki/Trypan_blue
https://en.wikipedia.org/wiki/Floxuridine


https://en.wikipedia.org/wiki/Sulfasalazine
https://en.wikipedia.org/wiki/Zidovudine

https://pubchem.ncbi.nlm.nih.gov/compound/Rolitetracycline


https://www.google.com/search?q=Zalcitabine&oq=Zalcitabine&gs_lcrp=EgZjaHJvbWUyBggAEEUYOTIGCAEQLhhA0gEHNTk0ajBqMagCALACAA&sourceid=chrome&ie=UTF-8

Effect of NO (Nitrous Oxide) on HIV replication: 
https://journals.lww.com/jaids/abstract/1999/09010/nitric_oxide_modulates_hiv_1_replication.1.aspx#:~:text=Summary%3A,NO%20on%20HIV%2D1%20replication.


https://www.google.com/search?q=Retrovir&sca_esv=9aead19d0345d1c5&ei=uxjuZaq5KNKNnesPloGW6As&ved=0ahUKEwjqgpaHxeqEAxXSRmcHHZaABb0Q4dUDCBE&oq=Retrovir&gs_lp=Egxnd3Mtd2l6LXNlcnAiCFJldHJvdmlySABQAFgAcAB4AZABAJgBAKABAKoBALgBDMgBAJgCAKACAJgDAJIHAKAHAA&sclient=gws-wiz-serp


https://zinc15.docking.org/substances/ZINC000169289767/

https://en.wikipedia.org/wiki/HIV


https://www.science.org/doi/10.1126/science.adl2528
https://github.com/baker-laboratory/RoseTTAFold-All-Atom


(It was predicted by the model)
https://en.wikipedia.org/wiki/Abacavir


Message Passing Neural Network: 
https://www.youtube.com/watch?v=ZgEMv-t1B_g













