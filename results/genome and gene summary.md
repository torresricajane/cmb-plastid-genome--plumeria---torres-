## 4. Data Source and Genome Selection

The selected genome for this analysis is the complete chloroplast genome of *Plumeria rubra* cultivar *Acutifolia*. The genome was obtained from the NCBI GenBank/Nucleotide database using accession **MN812495.1**.

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

## 5. Files to Obtain

The following files and sources were used for the *Plumeria rubra* cultivar *Acutifolia* chloroplast genome analysis.

| **File** | **Format** | **Purpose** | **File/Accession** |
|---|---|---|---|
| Genome sequence | FASTA | To upload the sequence to Galaxy and obtain sequence statistics. | *Plumeria rubra* chloroplast genome, **MN812495.1** |
| Annotated genome | GenBank / RefSeq | To examine genes, coordinates, introns, pseudogenes, and other annotated features. | *Plumeria rubra* chloroplast genome, **MN812495.1** |
| Source information | NCBI record link / accession | To document the original source of the genome used in the analysis. | [NCBI MN812495.1](https://www.ncbi.nlm.nih.gov/nuccore/MN812495.1) |

## 6. Galaxy Workflow

The downloaded *Plumeria rubra* chloroplast genome was uploaded to **UseGalaxy.org** as a FASTA file named **Plumeria_rubra_MN812495.1**. The **Fasta Statistics** tool was used to examine the sequence and obtain its basic statistics.

| **Statistic** | **Galaxy Result** |
|---|---:|
| **Genome length** | **153,912 bp** |
| **Number of sequence records** | **1** |
| **GC content** | **37.94%** |
| **Complete plastome represented by one sequence** | **Yes** |

The Galaxy analysis confirmed that the uploaded FASTA file contained one sequence representing the complete *Plumeria rubra* chloroplast genome.

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
