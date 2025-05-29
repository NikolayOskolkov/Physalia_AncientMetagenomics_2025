![](images/logo.png)

# Ancient Metagenomics

## Instructor

- Dr. Nikolay Oskolkov, Lund University, NBIS SciLifeLab

## Course overview
The study of ancient microbial, animal, and plant DNA from archaeological samples is a rapidly expanding field with significant potential for uncovering insights into past environments, lifestyles, and diseases. However, the limited quantity and degraded quality of ancient DNA pose significant challenges to computational analysis. In this course, we will explore the key challenges and analytical methods in ancient metagenomics, focusing on a comprehensive understanding and practical implementation of the ancient metagenomic workflow, aMeta.

## Target audience and assumed background
We assume some basic awareness of UNIX environment, as well as at least beginner level of R and / or Python programming.

## Learning outcomes
By completing this course, you will:

- Understand the basics of ancient microbial and environmental metagenomic analysis
- Have an overview of bioinformatic tools and best practices for ancient metagenomic analysis
- Be able to apply aMeta workflow to your ancient metagenomic samples
- Know key challenges, approaches and solutions in the ancient metagenomics research field
- Be able to choose the right tools and approaches to answer your specific research question 

---

# Schedule

## Before the course

| Time   | Activity                                                                                           | Link                                                                                                                                     |
|--------|----------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------|
| ~ 1 h  | Recorded talk: aMeta presented at the Microbiome Virtual International Forum (MVIF) 2024           | [Video](https://www.youtube.com/watch?v=nIWpmUWAapM&t=39s)                                                                               |
| ~ 1 h  | Recorded talk: False-positives in ancient metagenomics, aMeta approach, SPAAMtish 2023             | [Video](https://www.youtube.com/watch?v=KUf0auYHjrc&t=405s)                                                                              |
| ~ 2 h  | aMeta method article in Genome Biology 2023                                                        | [PDF](https://github.com/NikolayOskolkov/Physalia_AncientMetagenomics_2025/raw/master/articles/aMeta_GenomeBiology_2023.pdf)             |
| ~ 1 h  | Useful reading: Fungal DNA in the gut of Tyrolean Iceman (Ötzi)                                    | [PDF](https://github.com/NikolayOskolkov/Physalia_AncientMetagenomics_2025/raw/master/articles/Oskolkov_BMC_Genomics_2025.pdf)            |
| ~ 1 h  | In case needed: Recap on Unix                                                                      | [Lab](command-line-basics.md)                                                                                                            |
| ~ 1 h  | Useful reading: Detecting microbial contaminamination in eukaryotic reference genomes              | [Blog](https://www.biorxiv.org/content/10.1101/2025.03.19.644176v1)                                                                      |
| ~ 1 h  | Useful reading: Refining filtering criteria for taxonomic profiling of ancient metagenomics data   | [Blog](https://www.biorxiv.org/content/10.1101/2025.03.31.646431v1)                                                                      |


## Day 1: 2 pm - 8 pm Berlin time

| Time           | Activity                                                                                   | Link                                                                                                                                     |
|----------------|--------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------|
| 14.00 - 14.30  | Course outline and practical information                                                   | [Slides](https://github.com/NikolayOskolkov/Physalia_AncientMetagenomics_2025/raw/master/slides/course-outline-and-practical-info.pdf)   |
| 14.30 - 15.30  | Introduction: challenges in ancient microbial and environmental metagenomics               | [Slides](https://github.com/NikolayOskolkov/Physalia_AncientMetagenomics_2025/raw/master/slides/Lecture_IntroAncientMetagenomics.pdf)    |
| 15.30 - 15.45  | Break                                                                                      |                                                                                                                                          |
| 15.45 - 16.30  | Quality control, adapter and host removal                                                  | [Slides](https://github.com/NikolayOskolkov/Physalia_AncientMetagenomics_2025/raw/master/slides/Lecture_QC_AdapterRemoval.pdf)           |
| 16.30 - 16.45  | Break                                                                                      |                                                                                                                                          |
| 16.45 - 17.30  | Practical: quality control, adapter and host removal                                       | [Lab](exercises.md#getting-the-raw-data)                                                                                                 |
| 17.30 - 17.45  | Break                                                                                      |                                                                                                                                          |
| 17.45 - 18.45  | Taxonomic profiling and filtering criteria                                                 | [Slides](https://github.com/NikolayOskolkov/Physalia_AncientMetagenomics_2025/raw/master/slides/Lecture_TaxonomicProfiling.pdf)          |
| 18.45 - 19.00  | Break                                                                                      |                                                                                                                                          |
| 19.00 - 20.00  | Practical: taxonomic profiling in microbial and environmental ancient metagenomics         | [Lab](exercises.md#read-based-taxonomic-profiling)                                                                                       |


## Day 2: 2 pm - 8 pm Berlin time

| Time           | Activity                                                                                   | Link                                                                                                                                     |
|----------------|--------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------|
| 14.00 - 15.00  | Authentication analysis: genomic hit confirmation and ancient status                       | [Slides](https://github.com/NikolayOskolkov/Physalia_AncientMetagenomics_2025/raw/master/slides/Lecture_Authentication.pdf)              |
| 15.00 - 15.15  | Break                                                                                      |                                                                                                                                          |
| 15.15 - 16.45  | Practical: genomic hit confirmation by evenness of coverage and damage pattern             | [Lab](exercises.md#genomic-hit-confirmation)                                                                                             |
| 16.45 - 17.00  | Break                                                                                      |                                                                                                                                          |
| 17.00 - 18.00  | Decontamination analysis of metegenomic data and eukaryotic reference genomes              | [Slides](https://github.com/NikolayOskolkov/Physalia_AncientMetagenomics_2025/raw/master/slides/Lecture_Decontamination.pdf)             |
| 18.00 - 18.15  | Break                                                                                      |                                                                                                                                          |
| 18.15 - 20.00  | Practical: microbial contamination correction and source tracking                          | [Lab](exercises.md#microbiome-contamination-correction)                                                                                  |


## Day 3: 2 pm - 8 pm Berlin time

| Time           | Activity                                                                                   | Link                                                                                                                                     |
|----------------|--------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------|
| 14.00 - 14.15  | Bonus lecture: UMAP vs. PCA for population genomics and ancient metagenomics               | [Slides](https://github.com/NikolayOskolkov/Physalia_AncientMetagenomics_2025/raw/master/slides/UMAP_NBIS_AI_IO_2025_Oskolkov.pdf)       |
| 14.15 - 15.00  | aMeta: an accurate and memory-efficient ancient metagenomic profiling workflow             | [Slides](https://github.com/NikolayOskolkov/Physalia_AncientMetagenomics_2025/raw/master/slides/Lecture_aMeta.pdf)                       |
| 15.00 - 15.15  | Break                                                                                      |                                                                                                                                          |
| 15.15 - 16.45  | Practical: aMeta ancient metagenomic workflow                                              | [Lab](exercises.md#ameta-introduction-and-installation)                                                                                  |
| 16.45 - 17.00  | Break                                                                                      |                                                                                                                                          |
| 17.00 - 18.00  | Metagenome de-novo assembly, quality control, authentication of assembled contigs          | [Slides](https://github.com/NikolayOskolkov/Physalia_AncientMetagenomics_2025/raw/master/slides/Lecture_Assembly.pdf)                    |
| 18.00 - 18.15  | Break                                                                                      |                                                                                                                                          |
| 18.15 - 19.30  | Practical: de-novo assembly, quality control, authentication                               | [Lab](exercises.md#metagenome-assembly)                                                                                                  |
| 19.30 - 20.00  | Questions an discussion                                                                    |                                                                                                                                          |


