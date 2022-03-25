# Complex modeling using ColabFold

This page is prepared to model the complex of phage G3P and E. Coli TolA coreceptor using ColabFold.
![image](https://user-images.githubusercontent.com/64282221/160193476-7575c1be-33f6-4d4e-a082-41a564c6e132.png)

## Biological Investigation:
- **Monomer 1:** Attachment protein G3P, Escherichia phage If1 (Bacteriophage If1)

Uniprot ID: O80297 https://www.uniprot.org/uniprot/O80297 

- **Monomer 2:** Cell envelope integrity inner membrane protein TolA, E. Coli

Uniprot ID: Q8X965 https://www.uniprot.org/uniprot/Q8X965 

![image](https://user-images.githubusercontent.com/64282221/160192504-4f68bf1b-e5d6-4091-b0bc-a472bbd3f584.png)

- It is known that N1 domain of G3P (17-81 res.) binds to CT domain of TolA (268-394 res.), so we will use these domains to model the complex structure. You can read the [relevant paper](https://reader.elsevier.com/reader/sd/pii/S002228361001260X?token=DB99DA48FE133670DABFD590C40756BE90D947E4CA2B329B42FF134E7FFB0BE337C2564EC5BDDC81D801D603AC2F793E&originRegion=us-east-1&originCreation=20220325214322).


## ColabFold
Website Link: https://colab.research.google.com/github/sokrypton/ColabFold/blob/main/AlphaFold2.ipynb 

![image](https://user-images.githubusercontent.com/64282221/160191598-fb622958-7d70-4f60-8875-625fe5c134c9.png)


## Preparing input fasta files
- Input file should be provided as one line.
- There should be **:** sign between sequences.

![image](https://user-images.githubusercontent.com/64282221/160193197-08090698-e9b3-4538-abcd-3e33d3306222.png)

- **Final input sequence in ColabFold format:** Let's select the interacted domains from the input sequences and prepare the input file for ColabFold as below:

TTDAECLSKPAFDGTLSNVWKEGDSRYANFENCIYELSGIGIGYDNDTSWNGHWTPVRAAD:SGADINNYAGQIKSAIESKFYDASSYAGKTCTLRIKLAPDGMLLDIKPEGGDPALCQAALAAAKLAKIPKPPSQAVYEVFKNAPLDFKPA

- Please copy and paste the above sequence to the **_query_sequence_** section, give a job name and please run all.

![image](https://user-images.githubusercontent.com/64282221/160193033-37a8a55f-904a-4cf0-b43b-db9525f004fe.png)

- You can follow the progression of your run in **_Run Prediction_** section.

-  When the run is completed you see the results in **_Display 3D structure_** section.

- The results are ranked according to pLDDT score between 0-100; higher score means better confidence. You read more on it from [here](https://alphafold.ebi.ac.uk/faq#faq-5).

- If you are using Chrome, the results are automatically downloaded to your computer as zip file. Otherwise you can download manually from the left section as zip file.

- Now, you can download the result file from [here](https://github.com/BurcuOzden/CSB-WS/blob/main/Workshop-run-sample.result.zip).

## Comparison of the generated models with the experimental structure

- Download the experimental structure from Protein Data Bank (PDB): https://www.rcsb.org/
- Name of complex: crystal structure of g3p from phage IF1 in complex with its coreceptor, the C-terminal domain of TolA
- PDB ID: **[2X9A](https://www.rcsb.org/structure/2X9A)**

![image](https://user-images.githubusercontent.com/64282221/160195620-9a6da885-0754-4c78-8a26-5c745d14241e.png)

- Open both the crystal structure and the generated models in PyMOL.
- Let's go deeper in PyMOL!

