# Cell and Molecular Biology

## Lab Activity: Characterization of a Plastid Genome

## 1. Purpose

In this activity, one plant genus with an available complete plastid genome was selected. A complete chloroplast genome was retrieved from a public database, uploaded to a personal UseGalaxy.org account, and analyzed to characterize its sequence and annotated genes. The complete workflow, results, and interpretation were documented in a GitHub repository.

## 2. Learning Outcomes

After completing this activity, the student should be able to:

- Locate and verify a complete plastid/chloroplast genome in NCBI.
- Explain basic plastid-genome terms such as LSC, SSC, IR, CDS, rRNA, tRNA, intron, pseudogene, and GC content.
- Describe the overall organization and gene content of a selected plastid genome.
- Use Galaxy to upload a plastid genome and obtain basic sequence statistics.
- Compare plastid genomes with mitochondrial and nuclear genomes.
- Evaluate the practical advantages and limitations of plastid genomes in biological studies.
- Document the data source, analysis steps, results, and interpretation in GitHub.

## 3. Choosing and Recording a Plant Genus

The selected plant genus for this activity is *Plumeria*. The species selected was *Plumeria rubra* cultivar *Acutifolia*, for which a complete chloroplast genome is available in the NCBI database.

| **Information** | Details |
|---|---|
| **Genus** | *Plumeria* |
| **Selected species** | *Plumeria rubra* cultivar *Acutifolia* |
| **Family** | Apocynaceae |
| **Organelle** | Chloroplast (plastid) |
| **Genome selected** | Complete chloroplast genome |
| **NCBI accession/version** | MN812495.1 |

  <img width="376" height="91" alt="image" src="https://github.com/user-attachments/assets/4a5cf0b4-e07f-4891-bad0-a7bdda28fc8a" />

  *Figure 1.* NCBI record for the complete chloroplast genome of *Plumeria rubra* cultivar *Acutifolia* (accession MN812495.1), showing the genome length of 153,912 bp and the available GenBank and FASTA sequence links.

  <img width="1071" height="613" alt="image" src="https://github.com/user-attachments/assets/06070d23-847f-42eb-847d-1d92a8911743" />

  *Figure 2.* NCBI GenBank record for the complete chloroplast genome of *Plumeria rubra* cv. *Acutifolia* (accession MN812495.1), showing a genome length of 153,912 bp and a circular chloroplast DNA molecule.


## 4. Data Source and Genome Selection

| **Information** | **Details** |
|---|---|
| **Genus** | *Plumeria* |
| **Species name** | *Plumeria rubra* cultivar *Acutifolia* |
| **Common name** | Frangipani |
| **Family** | Apocynaceae |
| **Organelle** | Chloroplast (plastid) |
| **Genome type** | Complete chloroplast genome |
| **NCBI accession/version** | **MN812495.1** |
| **Database** | NCBI GenBank / Nucleotide |
| **Genome length** | **153,912 bp** |
| **Topology** | Circular |
| **Sequence status** | Complete genome |
| **Source** | NCBI Nucleotide / GenBank |
| **Associated publication** | Wang, D.-L., Liu, Y.-Y., Tian, D., Yu, L.-Y., & Gui, L.-J. (2020). *Characterization of the complete chloroplast genome of Plumeria rubra cv. Acutifolia (Apocynaceae).* *Mitochondrial DNA Part B: Resources*. |
| **Publication link** | https://pmc.ncbi.nlm.nih.gov/articles/PMC7748865/ |
| **NCBI record** | https://www.ncbi.nlm.nih.gov/nuccore/MN812495.1 |

The selected genome is a complete chloroplast genome of *Plumeria rubra* cultivar *Acutifolia* from the NCBI database. The accession MN812495.1 provides a specific and traceable reference for the genome used in this activity. Its complete status and 153,912-bp length make it suitable for plastid genome characterization and further analysis in Galaxy.

<img width="1069" height="607" alt="image" src="https://github.com/user-attachments/assets/f6656cdd-036f-47b8-aff7-3b332ceda87c" />

*Figure 3.* FASTA sequence view of the complete chloroplast genome of *Plumeria rubra* cultivar *Acutifolia* (GenBank accession **MN812495.1**) obtained from the NCBI Nucleotide database.

## 5. Files to Obtain

| **File** | **Format** | **Purpose** | **File/Accession** |
|---|---|---|---|
| Genome sequence | FASTA | To upload the sequence to Galaxy and obtain sequence statistics. | *Plumeria rubra* chloroplast genome, **MN812495.1** |
| Annotated genome | GenBank / RefSeq | To examine genes, coordinates, introns, pseudogenes, and other annotated features. | *Plumeria rubra* chloroplast genome, **MN812495.1** |
| Source information | NCBI record link / accession | To document the original source of the genome used in the analysis. | [NCBI MN812495.1](https://www.ncbi.nlm.nih.gov/nuccore/MN812495.1) |

The FASTA file was used as the sequence input for Galaxy analysis, while the annotated GenBank record provided information about genes and other genome features. Using both sequence and annotated records allowed the analysis to examine the basic sequence properties as well as the organization and content of the chloroplast genome.

## 6. Galaxy Workflow

The downloaded *Plumeria rubra* chloroplast genome was uploaded to **UseGalaxy.org** as a FASTA file named **Plumeria_rubra_MN812495.1**. The **Fasta Statistics** tool was used to examine the sequence and obtain its basic statistics.

| **Statistic** | **Galaxy Result** |
|---|---:|
| **Genome length** | **153,912 bp** |
| **Number of sequence records** | **1** |
| **GC content** | **37.94%** |
| **Complete plastome represented by one sequence** | **Yes** |

The Galaxy analysis confirmed that the uploaded FASTA file contained one sequence representing the complete *Plumeria rubra* chloroplast genome.

<img width="1364" height="606" alt="image" src="https://github.com/user-attachments/assets/51448731-73ba-43b5-aa4c-b9aef0d13253" />

*Figure 4.* Fasta Statistics results in UseGalaxy.org for the uploaded *Plumeria rubra* chloroplast genome (MN812495.1), showing **153,912 bp**, **1 sequence record**, and a **GC content of 37.94%**.

## 7. Plastid Genome Terms to Understand

| **Term** | **Meaning** |
|---|---|
| **Plastid genome / plastome** | The DNA contained within a plastid, referring to the chloroplast genome in green plants. |
| **LSC** | Large Single-Copy region. One of the two single-copy regions that forms part of the typical circular structure of a plant plastid genome. |
| **SSC** | Small Single-Copy region. The smaller single-copy region located between the two inverted repeat regions. |
| **IR** | Inverted Repeat region. A pair of identical or nearly identical sequences, usually present as IRa and IRb in chloroplast genomes and oriented in opposite directions. |
| **CDS** | Protein-Coding Sequence. A DNA sequence that contains the information needed to produce a protein. |
| **tRNA gene** | A gene that produces transfer RNA, which helps deliver amino acids during protein synthesis. |
| **rRNA gene** | A gene that produces ribosomal RNA, an important component of ribosomes. |
| **Intron** | A non-coding portion of a gene that is removed from the RNA during processing. |
| **Pseudogene** | A DNA sequence that resembles a functional gene but has lost its original function. |
| **GC content** | The percentage of guanine (G) and cytosine (C) bases in a DNA sequence. |
| **Accession** | A unique identification number assigned to a sequence record in a biological database. |
| **Annotation** | Information identifying and describing genes and other features within a genome sequence. |

## 8. Required Plastid Genome Characterization

| **Characteristic** | *Plumeria rubra* cv. *Acutifolia* chloroplast genome |
|---|---|
| **Genus** | *Plumeria* |
| **Species** | *Plumeria rubra* cultivar *Acutifolia* |
| **Family** | Apocynaceae |
| **NCBI accession/version** | MN812495.1 |
| **Genome size** | 153,912 bp |
| **GC content** | 37.94% |
| **Topology** | Circular |
| **LSC size** | 84,852 bp |
| **SSC size** | 18,036 bp |
| **IR size** | 25,512 bp each |
| **Number of sequence records** | 1 |
| **Total annotated genes** | 130 genes |
| **Protein-coding genes** | 85 |
| **tRNA genes** | 37 |
| **rRNA genes** | 8 |
| **Introns** | Present in typical plastid genes, including *trnK*, *atpF*, and *rpoC1* |
| **Pseudogenes / gene fragments** | Degenerated features or truncated copies reported in the genome |
| **Gene duplications** | Genes located in the inverted repeat (IR) regions occur in two copies |
| **Overall organization** | LSC–IR–SSC–IR (quadripartite structure) |

### Gene Groups Identified

| **Gene group** | **Examples found in MN812495.1** | **Main function** |
|---|---|---|
| **Photosystem I (psa)** | *psaA, psaB, psaC, psaI, psaJ* | Involved in Photosystem I during photosynthesis |
| **Photosystem II (psb)** | *psbA, psbB, psbC, psbD, psbE, psbF, psbH, psbI, psbJ, psbK, psbL, psbM, psbN, psbT, psbZ* | Involved in Photosystem II during photosynthesis |
| **ATP synthase (atp)** | *atpA, atpB, atpE, atpF, atpH, atpI* | Helps produce ATP for energy |
| **Cytochrome b6f (pet)** | *petA, petB, petD, petG, petL, petN* | Involved in electron transfer during photosynthesis |
| **rbcL** | *rbcL* | Involved in carbon fixation |
| **RNA polymerase (rpo)** | *rpoA, rpoB, rpoC1, rpoC2* | Involved in transcription |
| **Ribosomal proteins (rpl)** | *rpl2, rpl14, rpl16, rpl20, rpl22, rpl23, rpl32, rpl33, rpl36* | Form part of the large ribosomal subunit |
| **Ribosomal proteins (rps)** | *rps2, rps3, rps4, rps7, rps8, rps11, rps12, rps14, rps15, rps16, rps18, rps19* | Form part of the small ribosomal subunit |
| **rRNA (rrn)** | *rrn16, rrn23, rrn4.5, rrn5* | Form part of the chloroplast ribosome |
| **tRNA (trn)** | *trnH-GUG, trnK-UUU, trnQ-UUG, trnS-GCU, trnG-UCC, trnM-CAU, trnI-GAU* | Carry amino acids during protein synthesis |
| **matK** | *matK* | Involved in RNA processing |
| **clpP** | *clpP* | Involved in protein degradation |
| **accD** | *accD* | Involved in fatty acid synthesis |
| **cemA** | *cemA* | Associated with the chloroplast envelope membrane |
| **ycf genes** | *ycf1, ycf2, ycf3, ycf4* | Conserved chloroplast genes with different functions |

The *Plumeria rubra* chloroplast genome is a circular plastome with the typical LSC–IR–SSC–IR organization. The LSC and SSC regions are separated by two inverted repeat regions. The genome contains protein-coding, tRNA, and rRNA genes, showing that the plastome carries genes involved in photosynthesis, protein synthesis, transcription, and other chloroplast functions. The Galaxy result also confirms that the complete sequence analyzed consists of one sequence record with a GC content of 37.94%.

<img width="878" height="602" alt="image" src="https://github.com/user-attachments/assets/f2fb7500-82a3-4c98-9db7-eeba10366cce" />

*Figure 5.* Annotated NCBI GenBank record of the complete chloroplast genome of *Plumeria rubra* cultivar Acutifolia (MN812495.1), showing annotated genomic features such as genes and coding sequences used in the plastid genome characterization.

## 9. Questions for the Student Report

### 1. Give the full scientific name, family, NCBI accession/version, database source, and complete plastid-genome size of your selected organism.

The selected organism is *Plumeria rubra* cultivar *Acutifolia*, which belongs to the family **Apocynaceae**. Its complete chloroplast genome is available in the NCBI GenBank database under accession **MN812495.1**. The genome has a total length of **153,912 bp**.

| **Information** | **Details** |
|---|---|
| **Scientific name** | *Plumeria rubra* cultivar *Acutifolia* |
| **Family** | Apocynaceae |
| **NCBI accession/version** | MN812495.1 |
| **Database source** | NCBI GenBank/Nucleotide |
| **Genome type** | Complete chloroplast genome |
| **Genome length** | 153,912 bp |

### 2. What evidence shows that the sequence is a complete plastid/chloroplast genome rather than a barcode marker, genome fragment, or nuclear sequence?

The NCBI record identifies MN812495.1 as a complete chloroplast genome of *Plumeria rubra* cultivar *Acutifolia*. The sequence is 153,912 bp long and contains the major structural regions and numerous annotated genes expected in a complete plant chloroplast genome. Therefore, it represents a complete plastid genome rather than a short barcode marker or a partial genomic fragment.

### 3. Describe the overall organization of the plastid genome. Does it contain the common LSC–IR–SSC–IR arrangement? Give the sizes of these regions when available.

The *Plumeria rubra* chloroplast genome has the typical **LSC–IR–SSC–IR** organization. It consists of a large single-copy region, a small single-copy region, and two inverted-repeat regions.

| **Region** | **Size** |
|---|---:|
| **LSC** | 84,852 bp |
| **SSC** | 18,036 bp |
| **IRa** | 25,512 bp |
| **IRb** | 25,512 bp |

The four regions together make up the complete chloroplast genome of 153,912 bp.

### 4. Summarize the annotated gene content: total genes, protein-coding genes, tRNA genes, rRNA genes, and pseudogenes. Explain why genes located in the inverted-repeat regions may appear in two copies.

The chloroplast genome contains **130 annotated genes**, consisting of **85 protein-coding genes, 37 tRNA genes, and 8 rRNA genes**.

| **Gene category** | **Number** |
|---|---:|
| **Total annotated genes** | 130 |
| **Protein-coding genes** | 85 |
| **tRNA genes** | 37 |
| **rRNA genes** | 8 |
| **Pseudogenes** | No separate number reported |

Some genes occur in two copies because the chloroplast genome has two inverted-repeat regions. A gene located in one IR can therefore have a corresponding copy in the other IR.

### 5. Choose at least eight protein-coding plastid genes from different functional groups. List each gene and briefly explain its biological function.

| **Gene** | **Functional group** | **Biological function** |
|---|---|---|
| *psaA* | Photosystem I | Encodes a major component of Photosystem I involved in photosynthesis. |
| *psbA* | Photosystem II | Encodes a core protein of Photosystem II involved in the light reactions. |
| *atpA* | ATP synthase | Encodes part of the ATP synthase complex involved in ATP production. |
| *petB* | Cytochrome b6f | Participates in electron transfer during photosynthesis. |
| *rbcL* | Carbon fixation | Encodes the large subunit of RuBisCO involved in carbon fixation. |
| *rpoB* | RNA polymerase | Encodes a subunit of the plastid RNA polymerase involved in transcription. |
| *rpl16* | Ribosomal protein | Encodes a component of the large ribosomal subunit. |
| *rps12* | Ribosomal protein | Encodes a component of the small ribosomal subunit. |
| *matK* | RNA processing | Encodes a maturase associated with RNA processing and intron splicing. |

These genes represent several important plastid functions, including photosynthesis, energy production, carbon fixation, transcription, protein synthesis, and RNA processing.

### 6. Identify important RNA and RNA-processing features. Include the rRNA genes, examples of tRNA genes, and at least two genes with introns if present in your genome.

The genome contains **8 rRNA genes**, including *rrn16, rrn23, rrn4.5,* and *rrn5*. These genes contribute to the structure and function of chloroplast ribosomes.

Examples of tRNA genes include *trnH-GUG, trnK-UUU, trnQ-UUG, trnS-GCU, trnG-UCC, trnM-CAU,* and *trnI-GAU*. These genes produce transfer RNAs involved in protein synthesis.

Examples of intron-containing genes include *trnK-UUU* and *atpF*. The *matK* gene is associated with the intron-containing *trnK* region and is involved in RNA processing.

### 7. Describe any pseudogenes, gene losses, duplications, rearrangements, or other unusual features reported for your plastid genome. If none are reported, state this clearly.

The available publication does not provide a specific number of pseudogenes for the *Plumeria rubra* chloroplast genome. It also does not identify a major gene loss or large-scale genome rearrangement as a major feature of the genome.

One important feature is the presence of two inverted-repeat regions. Genes located within these regions can occur as duplicated copies.

The genome also has the typical **LSC–IR–SSC–IR** structure of a plant chloroplast genome.

### 8. What is the GC content of your plastid genome? Based on your Galaxy results and annotation, describe two other notable sequence or structural observations.

The Galaxy Fasta Statistics analysis gave a **GC content of 37.94%**.

Two other observations from the analysis are:

1. The FASTA file contained **one sequence record** with a length of **153,912 bp**.
2. The genome has a quadripartite structure consisting of an **84,852-bp LSC, an 18,036-bp SSC, and two 25,512-bp IR regions**.

### 9. Compare plastid and mitochondrial genomes. Give at least five similarities and five differences, considering location, biological role, inheritance, genome organization, gene content, copy number, and evolutionary behavior.

#### Similarities

| **Feature** | **Similarity** |
|---|---|
| **Location** | Both are genomes found inside cellular organelles. |
| **DNA** | Both organelles contain their own DNA. |
| **Gene content** | Both contain genes that perform functions within their respective organelles. |
| **Copy number** | Multiple copies of organelle DNA may be present within a cell. |
| **Evolutionary origin** | Both organelles have evolutionary histories associated with ancient endosymbiotic events. |

#### Differences

| **Feature** | **Plastid genome** | **Mitochondrial genome** |
|---|---|---|
| **Location** | Found in chloroplasts or other plastids | Found in mitochondria |
| **Main function** | Mainly associated with photosynthesis and other plastid activities | Mainly associated with cellular respiration and energy metabolism |
| **Genome organization** | Commonly contains LSC, SSC, and two IR regions | Plant mitochondrial genomes have more variable structures |
| **Gene content** | Contains photosynthesis-related genes such as *psa, psb,* and *rbcL* | Contains genes mainly related to mitochondrial functions |
| **Genome structure** | Generally more conserved in many plant species | Plant mitochondrial genomes can undergo extensive structural changes |
| **Inheritance** | Often uniparental in plants, although this varies among species | Often uniparental in plants, although inheritance patterns vary |
| **Evolutionary behavior** | Usually relatively conserved in structure | Can show considerable rearrangement and structural variation in plants |

### 10. Explain the practical value of plastid genomes in research. List as many advantages as you can compared with the nuclear genome, including nuclear sex chromosomes where applicable, and also explain important limitations. Give one research question for which plastid data would be useful and one for which nuclear genomic data would be more appropriate.

Plastid genomes are useful in plant research because they provide a relatively compact source of genetic information that can be used for species identification, evolutionary studies, and comparisons among related plants.

#### Advantages of Plastid Genomes

- Relatively small compared with most nuclear genomes.
- Easier to assemble and analyze in many cases.
- Useful for plant species identification.
- Useful for DNA barcoding.
- Useful for phylogenetic studies.
- Useful for investigating evolutionary relationships.
- Provide conserved molecular markers.
- Useful for comparing closely related plant species.
- Contain genes involved in photosynthesis and other chloroplast functions.
- Complete plastomes provide more information than individual barcode regions.
- Useful for conservation and population studies.
- Generally have a relatively conserved organization in many flowering plants.
- Can be studied without sequencing the entire nuclear genome.

#### Limitations of Plastid Genomes

- Represent only one organelle and not the complete genetic information of the plant.
- Contain far fewer genes than the nuclear genome.
- Do not provide information about most nuclear genes.
- Do not contain nuclear sex chromosomes.
- May represent only one parental lineage when plastid inheritance is uniparental.
- May have insufficient variation for some population-level studies.
- Cannot fully explain complex traits controlled by nuclear genes.
- Plastid relationships may not always represent the complete evolutionary history of the species.
- Cannot replace nuclear genomic data when the research question concerns nuclear genes or chromosomes.

#### Research Question for Plastid Data

**How are different *Plumeria* species related based on their complete chloroplast genomes?**

Complete chloroplast genomes can be compared among *Plumeria* species to identify genetic differences and investigate their evolutionary relationships.

#### Research Question for Nuclear Genomic Data

**Which nuclear genes are associated with differences in flower color among *Plumeria* plants?**

Nuclear genomic data would be more suitable because flower color may involve multiple genes located throughout the nuclear chromosomes. Chloroplast data alone would not provide the complete genetic information needed to investigate this type of nuclear trait.
